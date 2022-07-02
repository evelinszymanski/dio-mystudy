### 🌸 Objetos Fundamentais do Git

- Blobs
- Trees
- Commit

### 🌸 Configurações do Git
    git config --list
⬆️ Para verificar as configurações. 
    
    git config —global —unset 
⬆️ Para apagar alguma configuração

    git config --global user.name " "
⬆️ Para criar um novo nome de usuário

    git config --global user.email " "
⬆️ Para criar um novo e-mail de usuário

### 🌸 Chave SSH
###### A chave SSH estabelece uma conexão segura entra as máquinas.
##### Criando uma chave SSH através do Git Bash:

1️⃣ Digite: 

    ssh-keygen -t ed25519 -C <e-mail>
- substitua pelo seu e-mail.</ul> 

2️⃣ Defina uma senha para a chave.

3️⃣ Para encontrar sua chave na pasta, digite: 

    cd /c/Users/<usuário>/.ssh 
- substitua pelo nome de usuário da sua máquina.

Existem duas chaves, pública e privada. Você irá buscar a pública (que termina com .pub).
    
4️⃣ Digite: 

    cat id_ed25519.pub
    
5️⃣ Copie sua chave e cole no campo SSH do GitHub.
  
 ### 🌸 Comandos do Git 
 
- git init -> Cria um repositório
- git status -> Mostra informações importantes dos arquivos
- git add -A -> Inclui todas as atualizações dos arquivos para o próximo commit
- git commit -> Salva alterações e define um ponto de verificação
- git push -> Envia as alterações para o servidor remoto
- git pull -> Obtém atualizações de um repositório remoto

### 🌸 Ciclo de Vida dos arquivos Git
##### untracked > staged > commit > unmodified > modified > staged > commit > unmodified ...
###### Quando acabamos de criar um arquivo e o Git ainda não sabe de sua existencia, ele é untracked.
###### Arquivos que podem ser rastreados se apresentam como unmodified, modified e staged. 
