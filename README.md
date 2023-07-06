# softservedata


PS C:\Users\Taras\softservedata> git add example.txt
PS C:\Users\Taras\softservedata> git commit -m"New commit"
[develop (root-commit) 099bb72] New commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 example.txt
PS C:\Users\Taras\softservedata> git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Pokroveckiy/softservedata.git'
PS C:\Users\Taras\softservedata> git branch -M main
PS C:\Users\Taras\softservedata> git remote add origin https://github.com/Pokroveckiy/softservedata.git
error: remote origin already exists.
PS C:\Users\Taras\softservedata> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 231 bytes | 115.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Pokroveckiy/softservedata.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\Taras\softservedata>
