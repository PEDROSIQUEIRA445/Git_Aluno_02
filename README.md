🚀 Como enviar arquivos locais para o GitHub
Este guia apresenta o passo a passo para enviar arquivos e projetos que estão no computador local para um repositório no GitHub utilizando o Git.

📋 Pré-requisitos
Antes de começar, você precisa ter:

Git instalado no computador.
Uma conta no GitHub.
Um repositório criado no GitHub.
1. Verificar se o Git está instalado
Abra o terminal (CMD, PowerShell ou Git Bash) e execute:


bash
git --version
Se o Git estiver instalado, será exibida a versão instalada.

2. Configurar o Git (primeiro uso)
Configure seu nome e e-mail:


bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"
3. Acessar a pasta do projeto
No terminal, navegue até a pasta onde estão os arquivos que deseja enviar:


bash
cd caminho/da/sua/pasta
Exemplo:


bash
cd C:/Users/Usuario/Documents/meu-projeto
4. Inicializar o repositório Git
Dentro da pasta do projeto, execute:


bash
git init
Esse comando inicializa o Git na pasta local.

5. Adicionar os arquivos
Para adicionar todos os arquivos ao controle de versão:


bash
git add .
Para adicionar um arquivo específico:


bash
git add nome-do-arquivo
6. Criar um commit
Registre as alterações com uma mensagem:


bash
git commit -m "Primeiro commit"
7. Conectar ao repositório do GitHub
Copie a URL do seu repositório no GitHub e execute:


bash
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
Verifique se o repositório remoto foi configurado corretamente:


bash
git remote -v
8. Enviar os arquivos para o GitHub
Defina a branch principal como main:


bash
git branch -M main
Agora envie os arquivos:


bash
git push -u origin main
Pronto! 🎉 Seus arquivos locais foram enviados para o GitHub.

🔄 Como enviar novas alterações?
Depois de modificar ou adicionar arquivos ao projeto, utilize os seguintes comandos:


bash
git add .
git commit -m "Descrição das alterações"
git push
Esses três comandos permitem atualizar seu repositório no GitHub sempre que necessário.

📌 Resumo dos principais comandos

Comando	Descrição
git init	Inicializa um repositório Git
git add .	Adiciona todos os arquivos
git commit -m "mensagem"	Registra as alterações
git remote add origin URL	Conecta ao GitHub
git branch -M main	Define a branch principal
git push -u origin main	Envia os arquivos ao GitHub
git pull	Baixa atualizações do GitHub
git status	Verifica o estado dos arquivos
git log	Exibe o histórico de commits
⚠️ Dicas importantes
Nunca envie senhas, tokens ou chaves de API para o GitHub.
Utilize um arquivo .gitignore para ignorar arquivos desnecessários.
Escreva mensagens de commit claras e objetivas.
Antes de enviar alterações, verifique o status com git status.
📚 Referências
Documentação oficial do Git
GitHub Docs
GitHub Skills
⭐ Gostou deste guia? Deixe uma estrela no repositório!

Autor: PEDRO
Tecnologias: Git | GitHub

Dica: Salve esse conteúdo com o nome README.md na raiz do seu repositório. Assim, ele será exibido automaticamente na página inicial do seu projeto no GitHub.


