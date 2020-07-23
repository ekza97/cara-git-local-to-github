
# cara-git-local-to-github
cara menghapus .git/git ulang
#> rm -rf .git
Cara Upload Project Local ke Github menggunakan Terminal
1. Pertama buat repository terlebih dahulu di github anda
2. Buak Folder project anda yang ada di local menggunakan terminal
3. Inisialisa local folder sebagai Git Repository
    #> git init
4. Menambahkan file di local repository
    #> git add .
5. Commit file di local repository
    #> git commit -m "initial commit"
6. Copy https url di repository yang baru dibuat di terminal untuk me-remote repository
    #> git remote add origin repositoryURL
    #> git remote -v
7. Upload local repository ke Github
    #> git push -f origin master
    
Mohon maaf jika kurang jelas, Ini dibuat hanya sebagai catatan saya saja
