# Praticando-Git
Repositório apenas para praticar git.

# O que é git?
- É um sistema de controle de versão, sendo uma ferramenta de registro de alterações feitas em arquivos de um projeto. Muito usado para programar e principalmente para projetos que envolvem várias pessoas ou precisam de um histórico organizado.

# Para que serve? 
- Guardar histórico do seu projeto: Cada mudança que você faz, poderá ser registrada com um "commit". E para ver o histórico, através do log.
- Voltar no tempo: Com git, é permitido voltar para qualquer versão anterior.
- Trabalho em equipe: Como mencionado a cima, podemos criar branches para desenvolver partes diferentes do projeto sem interferir no código principal.

# Principais comandos
- git init -> cria um repositório git.
- gid add . -> adiciona arquivos para serem commitados.
- git commit -m "mensagem" -> salva as mudanças, podendo definir qual mudança em específico através da mensagem.
- git status -> mostra o que mudou.
- git push -> envia para o GitHub.
- git pull -> baixa as novidades do GitHub.
- git remote add origin url -> linka seu repositório local com o GitHub.
- git branch -M main -> Cria uma branch main.
- git pull -u origin main -> Puxa atualizações.
- git revert -> Desfaz alterações em um commit.
- git log -> Mostra o histórico de quem mexeu no código e commits.
- git reset --hard id_do_commit -> Resetar para um id de commit antes da falha.
- git clone -> Clona arquivos de respositórios através de url de outros repositórios.
- git remote -v -> Verifica se os repositórios estão configurados corretamente.
