# Repository for Activity 9.1
## Description!
sverma@DOH-DHNX273:~/code_pcde$ echo "# GitHubMiniLesson" >> README.md
sverma@DOH-DHNX273:~/code_pcde$ git init
Reinitialized existing Git repository in /home/sverma/code_pcde/.git/
sverma@DOH-DHNX273:~/code_pcde$ git add .
sverma@DOH-DHNX273:~/code_pcde$ git commit -m "first commit"
    [master (root-commit) 604ab3d] first commit
     4 files changed, 10 insertions(+)
     create mode 160000 PCDE-Activity-9.1
     create mode 100644 README.md
     create mode 100644 test3
     create mode 100644 test3.pub
sverma@DOH-DHNX273:~/code_pcde$ git branch -M main
sverma@DOH-DHNX273:~/code_pcde$ git remote add origin git@github.com:shivkumarcdri/GitHubMiniLesson.git
sverma@DOH-DHNX273:~/code_pcde$ git push -u origin main
    Warning: Permanently added the ECDSA host key for IP address '140.82.113.3' to the list of known hosts.
    Enumerating objects: 5, done.
    Counting objects: 100% (5/5), done.
    Delta compression using up to 8 threads
    Compressing objects: 100% (4/4), done.
    Writing objects: 100% (5/5), 729 bytes | 243.00 KiB/s, done.
    Total 5 (delta 0), reused 0 (delta 0)
    To github.com:shivkumarcdri/GitHubMiniLesson.git
     * [new branch]      main -> main
    Branch 'main' set up to track remote branch 'main' from 'origin'.
sverma@DOH-DHNX273:~/code_pcde$ cd PCDE-Activity-9.1
sverma@DOH-DHNX273:~/code_pcde/PCDE-Activity-9.1$ echo "# GitHubMiniLesson" >> README.md
sverma@DOH-DHNX273:~/code_pcde/PCDE-Activity-9.1$ git init
  Reinitialized existing Git repository in /home/sverma/code_pcde/PCDE-Activity-9.1/.git/
sverma@DOH-DHNX273:~/code_pcde/PCDE-Activity-9.1$ git add README.md
sverma@DOH-DHNX273:~/code_pcde/PCDE-Activity-9.1$ git commit -m "first commit"
    [main e7836bf] first commit
     1 file changed, 1 insertion(+)
     create mode 100644 README.md
sverma@DOH-DHNX273:~/code_pcde/PCDE-Activity-9.1$ git remote add origin git@github.com:shivkumarcdri/PCDE-Activity-9.1.git
    fatal: remote origin already exists.
sverma@DOH-DHNX273:~/code_pcde/PCDE-Activity-9.1$ git push -u origin main
    Warning: Permanently added the ECDSA host key for IP address '140.82.112.4' to the list of known hosts.
    ERROR: We're doing an SSH key audit.
    Reason: unverified automatically (private key found in a public repository)
    Please visit https://github.com/settings/keys/81004259
    to approve this key so we know it's safe.

    Fingerprint:
    SHA256:q6eQ8W9sumzscDl1JWdEnkA6Q37rmg/Hl3sjnUm/z2w

    fatal: Could not read from remote repository.

    Please make sure you have the correct access rights
    and the repository exists.
sverma@DOH-DHNX273:~/code_pcde/PCDE-Activity-9.1$ git push -u origin main
    Warning: Permanently added the ECDSA host key for IP address '140.82.114.3' to the list of known hosts.
    Enumerating objects: 4, done.
    Counting objects: 100% (4/4), done.
    Delta compression using up to 8 threads
    Compressing objects: 100% (2/2), done.
    Writing objects: 100% (3/3), 295 bytes | 147.00 KiB/s, done.
    Total 3 (delta 0), reused 0 (delta 0)
    To github.com:shivkumarcdri/PCDE-Activity-9.1.git
       55c8482..e7836bf  main -> main
    Branch 'main' set up to track remote branch 'main' from 'origin'.
sverma@DOH-DHNX273:~/code_pcde/PCDE-Activity-9.1$
