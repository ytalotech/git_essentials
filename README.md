git init

git branch -a

git status

git branch

git checkout -b mensagem

git checkout master

git remote add origin git@github.com:ytalotech/git_essentials.git
git branch -M main
git push -u origin main


==================================== 3 ============================================

O ponto diz que é para baixar no contexto atual, na pasta atual
git clone link_para_clonar .

Desfazer todas as mudanças:
git checkout .

Esse arquivo ignora todas as pastas que não quero subir:
.gitignore

Baixar aquivos do repositorio
git pull


==================================== 4 ============================================

Merge operacao direta, pegando os commits de uma branch para outra
git merge

git log

Abrir esse processo de merge no github e alguem vai precisar validar
pull request

Deletar branch
git branch -D master

faz um novo commit para tirar o que já tem. HARD rrevert o que tem na cabeça do commit
git revert HEAD

HEAD~1 desfaz 1 commit acima
git reset --hard HEAD~1


==================================== 5 ============================================

buscar as ultimas 7 caracteres do id do meu commit
git log --pretty=format:%h -n 1

guardar as informações em uma area temçporaria e depois pode pegar devolta. Pois as vezes é preciso resolvr algum problema, e preciso que as informações modificadas não esteje no momento da alteração.
git stash

Para voltar as alterações, posso dar
git stash apply