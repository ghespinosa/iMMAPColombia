## This explains how to clone, push, pull, etc a GitHub repository using the terminal in Jupyter

Introduction to Data Science Part 1.2: A Dose of Data (Boring Mix): https://www.youtube.com/watch?v=DrCW6JefWMk

Introduction to Data Science Part 2.2 : Gitting Data: https://www.youtube.com/watch?v=RGVfCidAs_Y


`jovyan@jupyter-ghespinosa:~$ ls`

`jovyan@jupyter-ghespinosa:~$ git clone https://github.com/ghespinosa/iMMAPFellowship.git`

` Cloning into 'iMMAPFellowship'...`

`Username for 'https://github.com': ghespinosa
Password for 'https://ghespinosa@github.com': `

` 
 remote: Enumerating objects: 9, done.
 remote: Counting objects: 100% (9/9), done.
 remote: Compressing objects: 100% (7/7), done.
 remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
 Unpacking objects: 100% (9/9), 64.39 KiB | 8.05 MiB/s, done.`

`jovyan@jupyter-ghespinosa:~$ ls`

` DATA146ReasoningUnderUncertainty  DATA490Venezuela  iMMAPColombia  iMMAPFellowship  lost+found  Misc`

`jovyan@jupyter-ghespinosa:~$ cd iMMAPFellowship/`
`jovyan@jupyter-ghespinosa:~/iMMAPFellowship$ ls`
`GusanitoLogo.001.jpeg  README.md  TrialRun.ipynb`

`jovyan@jupyter-ghespinosa:~/iMMAPFellowship$ git add -A .`

`jovyan@jupyter-ghespinosa:~/iMMAPFellowship$ git commit -m "Test"`

`[master 126fb8f] Test
 2 files changed, 116 insertions(+)
 create mode 100644 .ipynb_checkpoints/TrialRun-checkpoint.ipynb
 create mode 100644 TrialRun.ipynb`
 
`jovyan@jupyter-ghespinosa:~/iMMAPFellowship$ ls`

` GusanitoLogo.001.jpeg  README.md  TrialRun.ipynb`

`jovyan@jupyter-ghespinosa:~/iMMAPFellowship$ git push
Username for 'https://github.com': ghespinosa
Password for 'https://ghespinosa@github.com':`

` Enumerating objects: 9, done.
 Counting objects: 100% (9/9), done.
 Delta compression using up to 2 threads
 Compressing objects: 100% (8/8), done.
 Writing objects: 100% (8/8), 1.37 KiB | 1.37 MiB/s, done.
 Total 8 (delta 1), reused 0 (delta 0)
 remote: Resolving deltas: 100% (1/1), done.
 To https://github.com/ghespinosa/iMMAPFellowship.git/
   e3a8297..fa07c69  master -> master`

`jovyan@jupyter-ghespinosa:~/iMMAPFellowship$`