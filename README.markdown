# Park Adv website

## Criando novo artigo

Abrir programa Terminal (dentro de "Other")

Digitar e enter para:
```
cd Public/park.adv.br
```

```
rake new_post['titulo']
```

```
mate arquivo_criado
```
Vai abrir o textmate: colar a notícia (sem título e com fonte e link) e save

## (voltar no terminal) Testando localmente

```
rake generate

rake preview
```
Acessar: [http://localhost:4000/](http://localhost:4000/)

dar Ctrl + c no terminal para sair da notícia

## Publicando o site

```
rake gen_deploy
```

## Enviando para o GitHub

```
git add .
```

```
git commit -m "Novo post"
```

```
git push origin master
```
