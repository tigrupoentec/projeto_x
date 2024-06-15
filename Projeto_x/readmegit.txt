git init
ls -al --pra ver arquivos ocultos do git
git add main.py
git commit -m "meu primeiro commit"  --vai dar erro pq antes tem que criar usuario git
git config --global user.email "ti@grupoentec.com.br"
git config --global user.name "tigrupoentec"
git log

--se vc deleta algum arquivo
git status --mostra o que houve
git restore nomearquivo --restora o arquivo

--se vc deleta algum arquivo e da commit pra deletar real
git add nomearquivo
git commit -m "removendo arquivo"
git status --não vai ter mais a opçao de restore
git log --pra ver a chavehash commit
git checkout chavehash nomearquivo
git add nomearquivo
git commit -m "restaurando o arquivo"

--depois disso vc cria a conta no github e cria o ssh
--ver video youtube do luciano https://www.youtube.com/watch?v=-M4pMd2yQOM minuto 27:00

git remote add origin https://github.com/tigrupoentec/projeto_x.git
git push -u origin main


