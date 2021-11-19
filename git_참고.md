1. git push origin HEAD:[remoteBranch]  
https://stackoverflow.com/questions/4181861/git-message-src-refspec-master-does-not-match-any-when-pushing-commits-in-git
2. git ignore 적용 할 때  
$ git rm -r --cached . // cache에 기록된 tracking 중인 파일리스트 삭제  
$ git add .  
$ git commit -m 'remove ignored file'  
$ git push {remote} {branch}  
