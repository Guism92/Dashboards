# Clonar o repositório
git clone <repositorio> <meu-projeto-clone>
* Só se faz uma vez

## Clona a partir de uma branch
git clone -branch new_feature <repositorio>


# Atualizar o repositório
git pull https://github.com/Guism92/Dashboards.git


# Verificar o log
git log
## Log resumido
git log -- oneline
## Log por autoro
git log --author="user_name"
## Log por data
git log --since=1.month.ago --until=1.day.ago
# Log formatado 
git log --pretty="format:%h %s"

# Status
git status

# Commit
git commit arquivo.formato -m "Mensagem"

# Push
git push origin main 
git push origin desenvolvimento

# Restore
git restore --source a0c893b app.js
## Restore de tudo
git restore --source a0c893b .

# Adiciona uma página NOVA
git add contato.html
# Adiciona todas as NOVAS páginas criadas
git add .

# Criar uma branch de desenvolvimento
git checkout -b desenvolvimento 

# Trocar para outra branch
git switch main
git switch desenvolvimento