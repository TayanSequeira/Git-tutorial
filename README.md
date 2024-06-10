# Curso digital: Git

# Navegue até a pasta
cd caminho/para/sua/pasta/Git-tutorial

# Inicialize o repositório Git
git init

# Crie o arquivo README.md com o conteúdo do tutorial
echo "# Tutorial de Git/GitHub
## Introdução
Git é um sistema de controle de versão distribuído, enquanto GitHub é uma plataforma de hospedagem de código-fonte que usa o Git. Este tutorial irá guiá-lo pelos conceitos básicos e pelos comandos essenciais para começar a usar Git e GitHub.

### 1. Instalação do Git no Windows
- Baixe o instalador do Git no site oficial: [git-scm.com](https://git-scm.com)
- Execute o instalador e siga as instruções na tela.

### 2. Configurando Git
Após a instalação, configure seu nome de usuário e e-mail, que serão usados em seus commits.
```bash
git config --global user.name \"Seu Nome\"
git config --global user.email seuemail@example.com
```
```bash
### 3. Principais comandos
git init # Inicializa um repositório
git clone URL_DO_REPOSITORIO # Clonar um repositório existente
git status # Verificar o status do repositório
git add NOME_DO_ARQUIVO # Adicionar arquivos ao índice
git commit -m "Mensagem do commit" # Comitar mudanças
git log # Ver o histórico de commits
git restore File # Retornar modificacoes no arquivo
git restore --staged File # Retornar um arquivo do staged antes do commit
git push origin NOME_DA_BRANCH # Enviar commits para o GitHub
git pull origin NOME_DA_BRANCH # Atualizar o repositório local com mudanças do GitHub
