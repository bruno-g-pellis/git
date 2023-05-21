**Git comandos**

 - Primeiro, **git init** para inserir pasta .git ao diretório local;
 - Depois, adicionar arquivo(s) com **git add nome-arquivo ou git add * (adiciona todos)**;
 - Arquivo passa para staged;
 - Para verificar status - untracked (quando não tem pasta .git ainda), unmodified (falta git add e git commit), staged (falta git commit) - usar **git status**;
 - Depois de adicionar arquivo(s), fazer **git commit -m "mensagem"**;
 - Após o git commit, o arquivo volta para unmodified;
 - Encaminhar para repositório remoto: **GitHub**;
 - Para encaminhar para GitHub: **git remote add origin https...(copia do GitHub)**;
 - Depois, **git push origin main/master**.

 Outros comandos:

 Em vez de criar um novo repositório local, pode-se criar um clonando um repositório remoto com **git clone https..**.

 - **git pull origin main/master:** cópia do repositório remoto. Atualiza automaticamente com a branch no PC;
 - **git fetch:** cópia do repositório remoto. Mas **NÃO** atualiza automaticamente com 
 a branch no PC;

 - **git log:** histórico de commits;
 - **git diff nome-arquivo:** apresenta alterações no prompt;
 **Em staged (já add) usar:**  git diff --staged nome-arquivo.

 - **git restore: nome-arquivo** remove modificação.
 **Em staged (já add) usar:**  git restore --staged nome-arquivo

 - **git branch:** cria brach ou lista branches;
 - **git checkout nome-branch:** muda para nova branch;
 - **git merge nome-branch-que-receberá-arquivos:** união de branches;
 
