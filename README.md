# Exercício 2
Teste de uso do **Git** com **Git Bash**

Etapas usadas:
1. Criar repositório no GitHub
2. Copiar a URL do *repo*
3. Comandos:
 * `git clone URL` - copia o repositório especificado no URL para a pasta local
 * `git commit -a` ou `git commit -a -m "Mensagem do commit"` - atualiza o repositório e prepara para o *push*
 * `git status` - informa a situação do repos *repo*
 * `git log` ou `git log -N` - mostra o log dos commits, N é número das últimas atualizações
 * `git remote` ou `git remote -v` - mostra o nome e endereço do local de origem da instância duplicada do *repo*
4. Para subir (*push*) um novo projeto criado localmente usando o Git Bash:
 * `git init` - criar na pasta do projeto os arquivos do *.git*
 * `git remote add nomeDaOrigem URLdaOrigem` - adiciona o endereço da origem. Para obter a URL da origem, precisa criar uma *repo* no GitHub
 * `git add nomeDoArquivo` ou `git add .`- adiciona o arquivo ou todos os arquivos com o ´.´ para ser processado pelo *commit*
 * `git commit nomeDoArquivo -m "Mensagem do commit"` - faz o *commit* do arquivo ou dos arqivos se usar o atributo `-a`
  * `git push remote branch` - sobe ou faz upload dos arquivos do *repo* para a *origem* (o *remote*) no *branch* especificado
  * `git pull remote branche` - baixa os arquivos que foram *commitados* no GitHub (na web) para a *origem* (o *remote*) no *branch* especificado
