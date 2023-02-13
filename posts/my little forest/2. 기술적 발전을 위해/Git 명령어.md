### git checkout  
git branch 명령에 의해 생성 된 지점 사이를 이동하는 명령. 내가 사용할 브랜치를 지정하는 것.

### remote repository의 폴더 삭제 방법 
(ignore 부분이 한번 복사된 경우):
##### 기초작업
1. git bash open
2. git folder로 이동 (예: $ cd e:/home/obsidian/repo)
4. git init
5. git config --list로 현재 상태 확인
6. 필요하면 사용자 설정 입력 (예: $  git config --global user.name "username")
7. 연결상태 확인 : git remote -v
##### 삭제작업
7. $ git rm -r --cached "first_directory_under_repo_root/second_director/dir_to_be_removed"
   (여기서 첫번째 디렉토리란 repo 이름은 빼고 그 다음에 나오는 디렉토리를 의미. 
   예를들면.. $ git rm --cached -r "posts/my little forest/0. 인생 지도"
   -r option은 recursive, --cached는 remote.  --cached가 없으면 local에서 삭제됨)
8. $ git commit -am 'dir_to_be_removed removed from the repo'
9. $ git push

