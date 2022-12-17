# Introdução ao Git e GitHub

### Introdução ao Git e GitHub básico, indicado para quem está dando os primeiros passos em programação. 





- **O que é Git**
Criado em 2005 por *Linus Torvalds*, O **Git** é um sistema de controle de versionamento distribuído *(Version Control System, VCS)*. Ajuda a gerenciar alterações em código fonte ao longo do tempo pois a ferramenta mantém um registro de todas as versões do código. Podendo voltar para qualquer versão anterior ou compará-las, ajudando a descobrir e corrigir erros.

- **Instalando e configurando o Git**
  1 - Instalando a Partir do Fonte: Baixe o arquivo exe do instalador a partir da página e execute-o. Link https://git-scm.com/download 
  2 - Após a instalação defina o seu nome de usuário e endereço de email. 

  Comandos:
  <code> git config --global user.name "NOME" </code>
  <code> git config --global user.email EMAIL@EXEMPLO.COM </code>

- **Primeiros comandos no Git (Iniciantes)**
<code>git help</code> : Ajuda 
<code>git init </code>: Cria um repositório
<code>git add *</code>: Adiciona arquivos
<code>git status </code>: Verifica status dos arquivos
<code>git commit </code>: Comitar arquivos
<code>git commit -m "MENSAGEM" </code>: Comitar arquivos com mensagem
<code>git rm </code>: Remove arquivos
<code>git mv</code> : Move arquivos
<code>git log </code>: Visualizar logs
<code>git remote -v </code>: lista o link dos seus repositórios remotos
<code>git remote add origin LINK DO GITHUB </code>: Vincular repositório local com um repositório remoto
<code>git remote show origin </code>: Mostra informações dos repositórios remotos
<code>git push origin master </code>- "empurrar" o código para Github
<code>git pull origin master </code>- "puxar" o código do Github
<code>git clone URL </code>:  Clonar um repositório
<code>ls</code>: Listar
<code>ls -a </code>: Listar arquivos ocultos
<code>cd NOME-DA-PASTA </code>: Navegar na pasta
<code>cd .. </code>: Retroceder um nível
<code>mkdir NOME-ARQUIVO </code>: Criar pasta
<code>ctrl + l </code>: Limpar tela do terminal 

- **Iniciando o Git e criando um commit**
1 - Abra o Git Bash no local onde deseja criar o repositório
2 - Crie uma pasta <code>mkdir NOME-DA-PASTA</code>, entre nela <code>cd NOME-DA-PASTA</code> e inicie o repositório <code>git init</code>
3 - Crie um arquivo de texto dentro do repositório e salve-o em .md (nomedoarquivo.md)
4 - Use os comandos para comitar:  <code>git add *</code> enter  e depois <code>git commit -m "MENSAGEM"</code> enter

- **O que é GitHub**
Plataforma de hospedagem de código-fonte e arquivos com controle de versão (VCS) usando o Git. 

- **Criando conta no GitHub**
1 - Acesse o site do GitHub https://github.com/
2 - Clique em Sign up
3 - Coloque seus dados nome de usuário, endereço de email e senha
4 - Siga as instruções e verifique sua conta

- **Subindo primeiro repositório**
1 - Acesse o GitHub e clique em novo repositório
2 - Coloque o nome do repositório e descrição
3 - Copie endereço/url gerado na opção “push an existing repository from the command line”
4 - Abra o Git Bash na pasta onde está o seu projeto
5 - Use o comando <code>git remote add origin LINK DO GITHUB</code>
6 - Use o comando <code>git remote -v</code>
7 - Use o comando <code>git push origin master</code> 
8 - Será solicitado o usuário e senha para autenticar no GitHub
9 - Repositório local enviado para repositório remoto/Github

- **Clonando repositório**
1 - No GitHub.com, vá até a página principal do repositório
2 - Clique em Código (Code)
3 - Copie a URL do repositório
4 - Abra Git Bash
5 - Escolha o local onde deseja ter o diretório clonado
6 - Digite <code>git clone</code> e cole a URL copiada
Comando:  <code>git clone https://github.com/USUARIO/REPOSITORIO</code>
7 - Pressione ENTER para criar seu clone local

- **Resolvendo Conflitos**
Resolvendo conflitos de mesclagem causado por alterações de linha
1 - Abra o arquivo com o conflito
2 - A linha ======= divide suas alterações das alterações na outra ramificação. 
3 - Faça as modificações necessárias e exclua os marcadores de conflito <<<<<<<, =======, >>>>>>>
4 - Use o comando <code>git add *</code>
5 - Use o comando <code>git commit -m "Mensagem"</code> 
6 - Use o comando <code>git push origin master</code> 