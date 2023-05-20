##**Git comandos**

 - Primeiro **git init** para inserir pasta git ao diretório local;
 - Depois adicionar arquivo(s) com **git add nome-arquivo ou git add * (adiciona todos)**;
 - Para verificar status - untracked (quando não tem pasta git ainda), unmodified (falta add e commit), staged (falta commit) - usar **git status**;
 - Depois de adicionar arquivo(s), fazer **git commit -m "mensagem"**;
 - Após o git commit, o arquivo volta para unmodified;
 - Encaminhar para repositório remoto: **GitHub**;
 - Para encaminhar: **git remote add origin https...(copia do GitHub)**;
 - Depois, **git push origin main/master**.


 ##Em vez de criar um novo repositório local com **git init**, pode-se criar um clonando um repositório remoto com **git clone https..**.

 ##Outros comandos:

 - **git diff:** apresenta alterações no prompt do arquivo.
 **Em staged (já add) usar:**  git diff --staged nome-arquivo

 - **git restore:** remove modificação.
 **Em staged (já add) usar:**  git restore --staged nome-arquivo

 - **git branch:** cria brach ou lista branches
 - **git checkout nome-branch:** muda para nova branch
 
