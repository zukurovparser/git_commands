 ------- creating a new local repository with git -------
git init
							
git add	file.ext			envia files para to stand
git add.					envia all files to stand

git status
git branch -M "main"		renomear branch
git commit -m "criando repositorio"

git remote add origin https://github.com/owns_repository/name_repository.git
git push -u origin main

 ------- changing files git -------
git add.					envia all files to stand
git status
git commit -m "alterando files"
git push origin main

 ------- changing a new branch -------
git checkout -b "new-branch"
git add.					envia all files to stand
git commit -m "new-branch"
git push origin new-branch

 ------- get to main branch -------
git checkout main

 ------- get to new-branch -------
git checkout new-branch

 ------- merging new-branch -------
git checkout main			voltar para a main
git merge new-branch
git push origin main

 ------- git clone -------
git clone https://github.com/owns_repository/name_repository.git

 ------- get changes into local repository -------
git pull