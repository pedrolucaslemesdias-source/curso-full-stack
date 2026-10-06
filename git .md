
# git para iniciante

📁 Configuração
git config --global user.name "Seu Nome" — define seu nome.

git config --global user.email "email@exemplo.com" — define seu e-mail.

git config --list — mostra as configurações atuais.

🚀 Criar ou obter um repositório
git init — cria um novo repositório Git na pasta atual.

git clone URL — baixa/clona um repositório existente.

📌 Verificar o estado
git status — mostra arquivos modificados, adicionados e pendentes.

git log — mostra o histórico de commits.

git log --oneline — mostra o histórico de forma resumida.

git diff — mostra alterações que ainda não foram adicionadas ao stage.

➕ Adicionar alterações
git add arquivo.txt — adiciona um arquivo ao stage.

git add . — adiciona todas as alterações ao stage.

git add -A — adiciona todas as alterações do repositório.

💾 Commits
git commit -m "mensagem" — cria um commit.

git commit -am "mensagem" — adiciona e faz commit de arquivos já rastreados.

git commit --amend — altera o último commit.

🌿 Branches
git branch — lista as branches.

git branch nome-da-branch — cria uma branch.

git switch nome-da-branch — muda para uma branch.

git switch -c nome-da-branch — cria e muda para uma nova branch.

git branch -d nome-da-branch — exclui uma branch local.

git merge nome-da-branch — incorpora uma branch à branch atual.

Em versões antigas do Git, você também verá git checkout sendo usado para trocar/criar branches.

☁️ Repositório remoto
git remote -v — mostra os repositórios remotos configurados.

git remote add origin URL — adiciona um repositório remoto.

git push — envia commits para o remoto.

git push origin main — envia a branch main.

git push -u origin main — envia e configura a branch upstream.

git pull — baixa alterações e tenta integrá-las à branch atual.

git fetch — baixa informações do remoto sem integrar as alterações.

↩️ Desfazer alterações
git restore arquivo.txt — descarta alterações não commitadas de um arquivo.

git restore --staged arquivo.txt — remove um arquivo do stage.

git reset --soft HEAD~1 — desfaz o último commit mantendo as alterações no stage.

git reset --mixed HEAD~1 — desfaz o último commit mantendo as alterações nos arquivos.

git reset --hard HEAD~1 — desfaz o último commit e também descarta as alterações.

⚠️ Cuidado com git reset --hard, pois ele pode apagar alterações definitivamente.

🏷️ Tags
git tag — lista as tags.

git tag v1.0.0 — cria uma tag.

git push origin v1.0.0 — envia uma tag para o remoto.

git push origin --tags — envia todas as tags.

🔎 Outros comandos úteis
git show COMMIT — mostra detalhes de um commit.

git diff branch1..branch2 — compara duas branches.

git blame arquivo.txt — mostra quem alterou cada linha.

git stash — guarda temporariamente alterações não commitadas.

git stash pop — recupera as alterações guardadas.

git clean -n — mostra arquivos não rastreados que poderiam ser removidos.

git clean -f — remove arquivos não rastreados.