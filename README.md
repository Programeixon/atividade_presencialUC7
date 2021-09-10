# atividade_presencialUC7

Colaborador 1 - Felipe



felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.txt

no changes added to commit (use "git add" and/or "git commit -a")

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git add .

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.txt


felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git push -u origin main
Everything up-to-date
Branch 'main' set up to track remote branch 'main' from 'origin'.

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git push -u origin
Everything up-to-date
Branch 'main' set up to track remote branch 'main' from 'origin'.

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git push
Everything up-to-date

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.txt


felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git add .

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.txt


felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git commit -m "Fazendo alteração e segunda parte"
[main 36b4954] Fazendo alteração e segunda parte
 1 file changed, 3 insertions(+), 1 deletion(-)

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 338 bytes | 169.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Programeixon/atividade_presencialUC7.git
   efd2783..36b4954  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

felip@DESKTOP-GOCROBK MINGW64 ~/OneDrive/Documentos/atividade_presencialUC7 (main)
$ git log
commit 36b495402ee3252fc52df224464b94e3c8741501 (HEAD -> main, origin/main)
Author: Programeixon <felipeavisos@gmail.com>
Date:   Fri Sep 10 09:16:49 2021 -0300

    Fazendo alteração e segunda parte

commit efd278329a67e8dfde112fe88676e25ca2578b54
Author: Diego Miranda <diego_smiranda@hotmail.com>
Date:   Fri Sep 10 08:16:53 2021 -0300

    Descrição dos comandos no README

commit bfee91b377f81556a8c7a53ec94d48d77756fff3
Author: Diego Miranda <diego_smiranda@hotmail.com>
Date:   Fri Sep 10 08:08:15 2021 -0300

    Alterações do colaborador 2

commit f823c2546952fdbbb055af8cbb8678526844863f
Author: Felipe Casetta Caldeira <89617233+Programeixon@users.noreply.github.com>
Date:   Thu Sep 9 22:45:59 2021 -0300

    Create README.md

commit 6a98771a3ea1ca21e0d3ee722be8ea3cf06e31c1
Author: Programeixon <felipeavisos@gmail.com>
Date:   Thu Sep 9 22:43:56 2021 -0300

    iniciando atividade







Colaborador 2 - Diego
  
  

DIEGO@DESKTOP-G8LFJR5 MINGW64 /b/Senai/atividade_presencialUC7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contatos.txt

nothing added to commit but untracked files present (use "git add" to track)

DIEGO@DESKTOP-G8LFJR5 MINGW64 /b/Senai/atividade_presencialUC7 (main)
$ git add .

DIEGO@DESKTOP-G8LFJR5 MINGW64 /b/Senai/atividade_presencialUC7 (main)
$ git commit -m "Alterações do colaborador 2"
[main bfee91b] Alterações do colaborador 2
 1 file changed, 6 insertions(+)
 create mode 100644 contatos.txt

DIEGO@DESKTOP-G8LFJR5 MINGW64 /b/Senai/atividade_presencialUC7 (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

DIEGO@DESKTOP-G8LFJR5 MINGW64 /b/Senai/atividade_presencialUC7 (main)
$ git log
commit bfee91b377f81556a8c7a53ec94d48d77756fff3 (HEAD -> main)
Author: Diego Miranda <diego_smiranda@hotmail.com>
Date:   Fri Sep 10 08:08:15 2021 -0300

    Alterações do colaborador 2

commit f823c2546952fdbbb055af8cbb8678526844863f (origin/main, origin/HEAD)
Author: Felipe Casetta Caldeira <89617233+Programeixon@users.noreply.github.com>
Date:   Thu Sep 9 22:45:59 2021 -0300

    Create README.md

commit 6a98771a3ea1ca21e0d3ee722be8ea3cf06e31c1
Author: Programeixon <felipeavisos@gmail.com>
Date:   Thu Sep 9 22:43:56 2021 -0300

    iniciando atividade




