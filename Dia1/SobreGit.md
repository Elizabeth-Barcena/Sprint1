# Como utilizar o git primeiros passos:
- Para iniciar abra a pasta que você quer salvar no git e abra com git dash
- De um git init
- Logo, utilize o git add (nome do arquivo)
- Para ver o arquivo que você add digite: git status
- Para fazer o commit: git commit -m "mensagem"
- Para mudar o nome da branch master para main: git branch -M "main"
- Conectar ao github nuvem: git remote add origin (SSH- link fornecido pelo github)
- Para enviar arquivos para o git: git push -u origin main

# Após fazer modificações no projeto segue os passos:
- git add .
- git commit -m "(nome do commit)"
- Enviar novas atualizações pra nuvem: git push origin main

# Como utilizar branchs:
Para criar uma nova branch utilize:
- git checkout -b "(nome da branch)"
## E salve na nuvem:
- git add .
- git commit -m "(nome do commit)" 
- git push origin nome-da-branch

# Mudar a branch:
- git checkout nome-da-branch

# Juntar as branchs:
- git merge nome-da-branch-que-quer-juntar

# Autor
Elizabeth-barcena
