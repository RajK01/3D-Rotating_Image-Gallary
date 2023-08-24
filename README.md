## 3D Gallery 


####  ✨ Steps used to upload folder in git for future issues in  main branch ✨

1. git init
2. git remote add origin https://github.com/RajK01/3D-Rotating_Image-Gallary.git
3. git status
4. git branch -M main
5. git add img/
6. git push -u origin main
7. Error: ! [rejected]        main -> main (fetch first)
         error: failed to push some refs to 'https://github.com/RajK01/3D-Rotating_Image-Gallary.git'
          hint: Updates were rejected because the remote contains work that you do
          hint: to the same ref. You may want to first integrate the remote changes
          hint: (e.g., 'git pull ...') before pushing again.
          hint: See the 'Note about fast-forwards' in 'git push --help' for details.
8. git fetch origin main:tmp
9. git rebase tmp
10. git push origin HEAD:main
11. Error: ! [rejected]        HEAD -> main (non-fast-forward)
          error: failed to push some refs to 'https://github.com/RajK01/3D-Rotating_Image-Gallary.git'
          hint: Updates were rejected because the tip of your current branch is behind
          hint: its remote counterpart. Integrate the remote changes (e.g.
          hint: 'git pull ...') before pushing again.
          hint: See the 'Note about fast-forwards' in 'git push --help' for details.
12. git push -f -u origin main
  🎇✨ Successful🎇✨
    
