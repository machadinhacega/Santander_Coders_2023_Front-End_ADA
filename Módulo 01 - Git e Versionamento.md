## Módulo 01 - Git e Versionamento 
Conteúdo das aulas

_______________________________________________________________
_______________________________________________________________

### Aula 01 - O que é Git? 
https://www.youtube.com/watch?v=tcUsdj8CNEI


_______________________________________________________________


### Aula 02 - Instalando e configurando o Git
https://www.youtube.com/watch?v=ZXJPth6zteQ

Conf inicial
usuário que está editando:
git config --global user.name "nome"
git config --global user.email "email" 

_______________________________________________________________


### Aula 03 - Repositórios do Git 
https://www.youtube.com/watch?v=0EyaRrKH3xw

• prompt
(para entrar na pasta)
cd [colar local]
(para clonar o projeto)
git clone [colar link do github]


_______________________________________________________________


### Aula 04 - Gravando mudanças no repositório | Aula 04
https://www.youtube.com/watch?v=79YlA2bcfsI

• git status:
Untracked
Unmodified
Modified
Staged


_______________________________________________________________


### Aula 05 - Git diff e commit
https://www.youtube.com/watch?v=4MxLs7mYc54

Git add .arquivo (manda pra Staged)
git diff .arquivo (mostra o que foi alterado no arquivo)
aperta "q" para sair do git diff
Git commit -m "mensagem" (comita)


_______________________________________________________________


### Aula 06 - Git log e restore
https://www.youtube.com/watch?v=NrW_UPAr83Q

Git log (mostra todos os commits feitos)
git restore .arquivo (volta para a versao anterior)
git restore --staged ()


_______________________________________________________________


### Aula 07 - Repositórios remotos
https://www.youtube.com/watch?v=0th6FUR2EN4

git push

git remote (mostra os repositorios remotos)
ex: git remote
(retorno: origin)
git push origin main
(origin: o repositorio remoto)
(main: a branch q esta sendo trabalhada)

git pull
(puxa tudo do repositório e sobreescreve no nosso código)

git fetch
(baixa tudo que tem no repositório, mas não sobreescreve. Assim da pra verificar com o git diff oq foi alterado )


_______________________________________________________________


### Aula 08 - GitHub
https://www.youtube.com/watch?v=y9ziXFBmV5o

Git serie de comandaos no software para versionar o projeto
GitHub uma plataforma para armazenar os projetos


_______________________________________________________________


### Aula 09 - Git branch
https://www.youtube.com/watch?v=EAJl34f0fYw

git branch dev
(criou uma nova branch chamada "dev")

git checkout dev
(leva a gente pra brand dev)

git log --oneline --decorate
(indica uma série de commmits, e também em qual branch nós estamos)
(lembrar de apertar "q" para sair)


_______________________________________________________________


### Aula 10 - Merging branches
https://www.youtube.com/watch?v=TFBWfHw7ohs

git merge

na branch principal:
git merge dev

resolve os conflitos. FIM