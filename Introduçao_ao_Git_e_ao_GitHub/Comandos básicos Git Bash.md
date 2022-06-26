 ## **Comandos básicos no Git Bash (com explicações simplificadas):**
 
 ##### _Obs: Clicar com o botão direito dentro de um diretório e abrir o Git Bash, já inicia o Git Bash no diretório selecionado._
 
 - **pwd**: Mostra o caminho do diretório. 
 - **cd nome_do_diretorio**: Entra no diretório _**nome_do_diretorio**_
 - **cd ..**: Volta 1 nivel.
- **ls**: Lista os arquivos e diretórios.
- **ls -a** : Lista arquivos ocultos (os: diretórios com "." na frente, são ocultos).
- **mv nome_do_arquivo.formato ./ diretorio/**: Move o arquivo _**"nome_do_arquivo.formato"**_ para o diretorio _**"diretorio"**_.
- **git ini**t: Cria um repositorio Git no diretorio.
- **git add nome_do_arquivo.formato**: Transfere o arquivo _**"nome_do_arquivo.formato"**_ para _Staged_
- __git add *__ _ou_  **git add .** : Transfere todos os arquivos para _Staged_.
-  **git commit -m  "exemplo de comentario"**: Empacota todos os arquivos em _Staged_ e cria um commit com o comentário _**"exemplo de comentario"**_.
- **git status**: Status do commit.
- **git config --list**: Lista as configurações do commit.
- **git config --global user.email "exemplo@gmail.com"** : Registra o e-mail _**exemplo@gmail.com no commit**_.
- **git config --global -- unset user.email**: Retira o e-mail registrado no commit.
- **git config --global user.name NickName**: Registra no nome _**"NickName"**_ no commit.
- **git config --global -- unset user.name**: Retira o nome registrado no commit.
- **git remote add origin https://github.com/GaPinheiro/dio-desafio-github-primeiro-repositorio.git**: Adiciona o repositório remoto _**"dio-desafio-github-primeiro-repositorio"**_.
- **git remote -v**: Lista os repositorios remotos.
- **git pull origin master**: Puxa o commit do github.
- **git push origin master**: Empurra o commit para o Github
- **git clone https://github.com/GaPinheiro/dio-desafio-github-primeiro-repositorio.git**: Clona o repositório _**"dio-desafio-github-primeiro-repositorio" do GitHub**_








