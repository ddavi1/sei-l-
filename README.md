#Curso de git e github


#git init = inicia o git nos arquivos
#git status = mostra os status dos arquivos a serem commitados 
#git add (nome do arquivo) ou git add . para adicionar tudo
#git commit -m "mensagem aqui" = commita os arquivos
#git remote add origin (link do repositorio)
#git push -u origin master ou main 

quando o repositorio já existir?

#push = enviar/empurrar
#pull = serve para atualizar o seu repositorio na maquina com o que está remoto se houver alterações

#git clone (link do repositorio) =  clona o repositorio 
#git clone (link do repositorio) . =  clona 
#git log = mostra os logs de quem deu commit

#git restore (nome do arquivo) = volta para o estado anterior com base no repositorio remoto
#git restore (nome do arquivo) ou git checkout (nome do arquivo) = 
        # git restore = Restaurar arquivos/desfazer mudanças.
        # git restore --staged (nome do arquivo) = tira o arquivo da fila de commit ou seja do git add . ou git add (nome do arquivo)
        # git checkout = Navegar entre branches ou restaurar arquivos.

#git reset --hard origin/master ou sua branch = ele força o projeto local a ficar igual o projeto remoto, descartando qualquer anteração que você fez sem o commit, qualquer codigo preparado para commit será apagado também, pois ele apagará de todos os locais 

#git branch = lista as branch criadas
#git branch (nome da branch) = cria uma nova branch
#git checkout (nome da branch) = vai para a branch informada
#git branch -d (nome da branch) = deleta a branch


#git stash = Guarda tudo o que foi modificado (mas que já é rastreado pelo Git) para você usar depois
#git stash -u = Guarda tudo, inclusive arquivos novos que você ainda não deu git add (untracked)
git stash list = Mostra tudo o que você tem guardado no "baú"
git stash apply e passar (indice do stash) = Recupera as mudanças, mas mantém uma cópia delas no baú.
git stash pop = Recupera as mudanças e as deleta do baú (é o mais usado).