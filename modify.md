# Modify
**Nota:**
Para realizar as etapas abaixo, é necessário que tenha o conhecimento básico de [Git](https://git-scm.com/book/pt-br/v2) juntamente com as ferramentas do [Github](https://github.com).

* [Get fork](#fork)
* [Clone repository](#clone)
* [Modify files](#modify)
	- [authors.csv file](#authors.csv)
* [Add files](#add-files)
* [Make commit](#commit)
* [Make push](#push)
* [Request](#pull-request)

## Fork
**Criando o fork do projeto**

* Clicando na imagem abaixo você poderá criar um fork do projeto! 

	[![Get fork](get-fork.png)](https://github.com/Leran-Ins/Pixel/fork)

## Clone
Vá ao terminal(prompt de comando) e digite o comando abaixo! 
```bash
 git clone git@github.com:Leran-Ins/Pixel.git
```
 
## Modify
Agora que clonou o repositório poderá fazer quaisquer modificações que quiser dentro das pastas [Arts](https://www.github.com/Leran-Ins/Pixel/tree/arts) e [Animations](https://github.com/Leran-Ins/Pixel/tree/animations), é claro, seguindo as [regras](rules.md).

### 	Authors.csv
Esse aquivo é destinado para deixar os créditos para a pessoa que criou alguma arte, para entender como ele funciona, leia abaixo.

* Leia sobre os aquivos com extensão [csv](https://fileinfo.com/extension/csv) para não se perder
* Seu padrão `author,art-name,contributors`
* Contributors, merece um cuidado especial, afinal seu padrão não é como todos, sempre que modificar uma arte, lembre-se de colocar seu nome nela e usando como separador `/`

## Add files
Use os comando abaixo para adicionar os aquivos ao seu repositório remoto.
```bash
git status -s
git add <file_name> 
or
git add .
```


## Commit
Para modificar ou adicionar um arquivo, use:
```bash
git commit -m "Add: <nickname> <file_name>"
git commit -m "Modify: <nickname>"
```

## Push
O comando abaixo enviar seus arquivos para o repositório do github.
```bash
git push origin main
```

## Pull request
Essa é a parte que integra suas modificações ou adições no repositório [Pixel](https://github.com/Leran-Ins/Pixel).
Clique [aqui](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) para saber como se faz um pull request.