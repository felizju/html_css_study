
## vscode 초기 설치 플로그인 목록
1. korean language pack - 한글패치
2. live server - 실시간 코드 변동 확인
3. material theme - 테마
4. auto rename tag - tag name 자동 변경 <></>
5. material icon theme - 아이콘테마
6. beautify - 자동 줄 맞춤 

## 폰트 글꼴 확대 단축키 설정법
1. 파일 -> 기본설정 -> 바로가기 키 -> 글꼴 검색 -> 단축키 지정

## Beautify 단축키 설정법
1. 파일 -> 기본설정 -> 바로가기키 -> hooky 검색 -> beautify file 단축키 설정

## html 설정
1. ! tab키

## git
git log
git log --stat
git log -p
git log --oneline
git log --oneline --all

git status

1. git add
	** git add . 모든 폴더 추가
2. git commit -m "메시지"

3. git push origin master --> git hub까지 커밋됨
	** head -> master, origin/master 전부 올라가야함

git clone https://github.com/felizju/git_study.git .

학원과 집 동일하게 만들기 : 
git pull origin master

git pull request : pull 하기 전에 미리 확인 후 pull

git rm -rf 파일명 : rkdwp tkrwp
git rm -r 파일명

git checkout  버전일련번호 (git log --oneline에서 나온 축약 버전번호 복붙)
git checkout master : 복구

mkdir 폴더명 : 폴더 생성
touch 파일 파일 : 파일 추가

로컬상태에서만 가능 reset
git reset --soft 전버전일련번호 : add 전 상태로 돌림
git reset --hard 전버전일련번호 : add 후 상태로 돌림 (파일 진짜 없어짐)

원격관리되고 있는지 확인
git remote -v

git remote add origin https://github.com/felizju/html_css_study.git

git remote -v로 다시 확인

