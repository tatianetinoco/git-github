# Introdução ao Git e GitHub

### Introdução ao Git e GitHub básico, indicado para quem está dando os primeiros passos em programação. 





- **O que é Git** <br />
Criado em 2005 por *Linus Torvalds*, O **Git** é um sistema de controle de versionamento distribuído *(Version Control System, VCS)*. Ajuda a gerenciar alterações em código fonte ao longo do tempo pois a ferramenta mantém um registro de todas as versões do código. Podendo voltar para qualquer versão anterior ou compará-las, ajudando a descobrir e corrigir erros.

- **Instalando e configurando o Git** <br />
  1 - Instalando a Partir do Fonte: Baixe o arquivo exe do instalador a partir da página e execute-o. Link https://git-scm.com/download <br />
  2 - Após a instalação defina o seu nome de usuário e endereço de email. <br />

  Comandos:
  <code> git config --global user.name "NOME" </code> <br />
  <code> git config --global user.email EMAIL@EXEMPLO.COM </code> <br />

- **Primeiros comandos no Git (Iniciantes)** <br />
<code>git help</code> : Ajuda  <br />
<code>git init </code>: Cria um repositório <br />
<code>git add *</code>: Adiciona arquivos <br />
<code>git status </code>: Verifica status dos arquivos <br />
<code>git commit </code>: Comitar arquivos <br />
<code>git commit -m "MENSAGEM" </code>: Comitar arquivos com mensagem <br />
<code>git rm </code>: Remove arquivos <br />
<code>git mv</code> : Move arquivos <br />
<code>git log </code>: Visualizar logs <br />
<code>git remote -v </code>: lista o link dos seus repositórios remotos <br />
<code>git remote add origin LINK DO GITHUB </code>: Vincular repositório local com um repositório remoto <br />
<code>git remote show origin </code>: Mostra informações dos repositórios remotos <br />
<code>git push origin master </code>- "empurrar" o código para Github <br />
<code>git pull origin master </code>- "puxar" o código do Github <br />
<code>git clone URL </code>:  Clonar um repositório <br />
<code>ls</code>: Listar <br />
<code>ls -a </code>: Listar arquivos ocultos <br />
<code>cd NOME-DA-PASTA </code>: Navegar na pasta <br />
<code>cd .. </code>: Retroceder um nível <br />
<code>mkdir NOME-ARQUIVO </code>: Criar pasta <br />
<code>ctrl + l </code>: Limpar tela do terminal  <br />

- **Iniciando o Git e criando um commit** <br />
1 - Abra o Git Bash no local onde deseja criar o repositório <br />
2 - Crie uma pasta <code>mkdir NOME-DA-PASTA</code>, entre nela <code>cd NOME-DA-PASTA</code> e inicie o repositório <code>git init</code> <br />
3 - Crie um arquivo de texto dentro do repositório e salve-o em .md (nomedoarquivo.md) <br />
4 - Use os comandos para comitar:  <code>git add *</code> enter  e depois <code>git commit -m "MENSAGEM"</code> enter <br />

- **O que é GitHub** <br />
Plataforma de hospedagem de código-fonte e arquivos com controle de versão (VCS) usando o Git.  <br />

- **Criando conta no GitHub** <br />
1 - Acesse o site do GitHub https://github.com/ <br />
2 - Clique em Sign up <br />
3 - Coloque seus dados nome de usuário, endereço de email e senha <br />
4 - Siga as instruções e verifique sua conta <br />

- **Subindo primeiro repositório** <br />
1 - Acesse o GitHub e clique em novo repositório <br />
2 - Coloque o nome do repositório e descrição <br />
3 - Copie endereço/url gerado na opção “push an existing repository from the command line” <br />
4 - Abra o Git Bash na pasta onde está o seu projeto <br />
5 - Use o comando <code>git remote add origin LINK DO GITHUB</code> <br />
6 - Use o comando <code>git remote -v</code> <br /> 
7 - Use o comando <code>git push origin master</code>  <br />
8 - Será solicitado o usuário e senha para autenticar no GitHub <br />
9 - Repositório local enviado para repositório remoto/Github <br />

- **Clonando repositório** <br />
1 - No GitHub.com, vá até a página principal do repositório <br />
2 - Clique em Código (Code) <br />
3 - Copie a URL do repositório <br />
4 - Abra Git Bash <br />
5 - Escolha o local onde deseja ter o diretório clonado <br />
6 - Digite <code>git clone</code> e cole a URL copiada <br />
Comando:  <code>git clone https://github.com/USUARIO/REPOSITORIO</code> <br />
7 - Pressione ENTER para criar seu clone local <br />

- **Resolvendo Conflitos** <br />
Resolvendo conflitos de mesclagem causado por alterações de linha <br />
1 - Abra o arquivo com o conflito <br />
2 - A linha ======= divide suas alterações das alterações na outra ramificação.  <br />
3 - Faça as modificações necessárias e exclua os marcadores de conflito <<<<<<<, =======, >>>>>>> <br />
4 - Use o comando <code>git add *</code> <br />
5 - Use o comando <code>git commit -m "Mensagem"</code> <br />
6 - Use o comando <code>git push origin master</code> <br />
