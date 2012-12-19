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
Vai abrir o textmate: colar a notícia (sem título e com fonte e link)

## (voltar no terminal) Testando localmente

```
rake preview
```
dar Ctrl + c no terminal para sair da notícia

Acessar: [http://localhost:4000/](http://localhost:4000/)

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
