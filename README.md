
# cara-git-local-to-github
Cara Menghapus .git/git ulang
<br>
<pre>
#> rm -rf .git
</pre>
<br>
Cara Upload Project Local ke Github menggunakan Terminal
<br>
1. Pertama buat repository terlebih dahulu di github anda
<br>
2. Buak Folder project anda yang ada di local menggunakan terminal
<br>
3. Inisialisa local folder sebagai Git Repository
<br>
<pre>
    #> git init
    </pre>
    <br>
4. Menambahkan file di local repository
<br>
<pre>
    #> git add .
    </pre>
    <br>
5. Commit file di local repository
<br>
<pre>
    #> git commit -m "initial commit"
    </pre>
    <br>
6. Copy https url di repository yang baru dibuat di terminal untuk me-remote repository
<br>
<pre>
    #> git remote add origin repositoryURL
    #> git remote -v
    </pre><br>
7. Upload local repository ke Github
<br>
<pre>
    #> git push -f origin master
</pre>
    
Mohon maaf jika kurang jelas, Ini dibuat hanya sebagai catatan saya saja
