<h1 align="center">🎯 Sobre o Tutorial</h1>

O tutorial vai servir para os devs que estão aprendendo sobre versionamento git e querem colaborar com seu time de forma que criem suas branchs e após terminar suas features possam pedir para realizar a MR(Merge Request).

<h1 align="center">🎯 Branchs</h1>

O repositório terá três branchs e cada um terá um readme sobre como fazer.

### Comandos em ordem

1- git checkout -b "nome da branch" 
(esse comando vai criar uma branch no diretório)

2- git status
(poderá verificar o funcionamento de files)

3- git add .
(vai adicionar todos os arquivos)

4- git commit -m "mensagem do commit""

5- git push origin (nome da branch nova)



Após isso vai ter subido para a branch nova seus files.
Então agora a intenção é aplicar o merge.

## Merge

1- git checkout master
Vamos mudar para a master.

2- git merge (branch que quer dar merge)
Ainda esta localmente, vamos subir.

3- git add .

4- git commit -m "mensagem da merge"

5- git push origin master
(estamos na branch master)


## Comandos 

Existem muitos comandos para trabalhar com versionamento de git. Esses são os principais para trabalhar com essa operação.
No caso se houver impedimento de conseguir setar o remoto que precisa trabalhar use:

1- git remote -v
(Diz qual é o repositório)

2- git remote add origin REPOLINK

Caso já tenha um e precise mudar:

3- git remote set-url origin NOVO_REPO_LINK
 <h1 align="center">✒️  Desenvolvedor </h1>

E dar prosseguimento com o git commit, push origin ou

4- git push -u origin master 


[<img src="https://avatars.githubusercontent.com/u/59845047?v=4" width=115><br><sub>Valdeir Camargo</sub>](https://github.com/Camargovf)
| :---: | :---: | :---: | :---: | :---: | :---: | 
