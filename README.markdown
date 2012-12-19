# Park Adv website

## Criando novo artigo

Abrir Terminal

```
cd Public/park.adv.br
```

```
rake new_post['<titulo>']
```

```
mate <arquivo_criado>
```

## Testando localmente

```
rake preview
```

Acessar: http://localhost:9292/

## Publicando o site

```
rake generate
```

```
rake deploy
```

## Enviando para o GitHub

```
git add .
```

```
git commit -am "Novo post: <titulo>"
```

```
git push origin master
```
