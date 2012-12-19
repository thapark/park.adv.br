# Park Adv website

## Criando novo artigo

Abrir Terminal (dentro de "Other")

```
cd Public/park.adv.br
```

```
rake new_post['titulo']
```

```
mate arquivo_criado
```
Vai abrir o textmate: colar a notícia (sem título e com fonte e link)

## (voltar no terminal) Testando localmente

```
rake preview
```

Acessar: http://localhost:9292/

## Publicando o site

```
rake gen_deploy
```

## Enviando para o GitHub

```
git add arquivo_criado
```

```
git commit -m "Novo post: titulo"
```

```
git push origin master
```
