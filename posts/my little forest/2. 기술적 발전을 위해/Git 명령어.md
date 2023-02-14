
### remote repository의 폴더 삭제 방법 
(ignore 부분이 한번 복사된 경우 리모트만 삭제하기):

##### 기초작업
1. git bash open
2. git folder로 이동 (예: $ cd e:/home/obsidian/repo)
3. git init
4. git config --list로 현재 상태 확인
5. 필요하면 사용자 설정 입력 (예: $  git config --global user.name "username")
6. 연결상태 확인 : git remote -v

##### 삭제작업
7. $ git rm -r --cached "first_directory_under_repo_root/second_director/dir_to_be_removed"  
   (여기서 첫번째 디렉토리란 repo 이름은 빼고 그 다음에 나오는 디렉토리를 의미. 
   예를들면..  
   내 Vault가 my_vault이고 일기/비밀일기 라는 폴더가 잘못 올라갔다면..  
   $ git rm -r --cached  "posts/my_vault/일기/비밀일기" 로 지운다는 뜻이다.  
   -r option은 recursive,  하위폴더의 내용도 모두 지운다는 뜻  
   --cached는 remote.  --cached가 없으면 local에서 삭제됨)  
8. $ git commit -am 'dir_to_be_removed removed from the repo'  
9. $ git push 



### git checkout  
git branch 명령에 의해 생성 된 지점 사이를 이동하는 명령. 내가 사용할 브랜치를 지정하는 것.

#테크니컬팁