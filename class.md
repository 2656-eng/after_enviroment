## 에디터 부가 기능 사용
1. Extensions -> git graph 검색 후 설치
2. 완전히 껏다가 켜기
3. 왼쪽 git 메뉴 클릭-> view git graph 활성화 확인

## 복습
1. ch03 -> git init
1. readme.md 파일생성(##main에서 init)
1. add -> commit
1. branch 생성/변경 후 readme.md 파일 수정(###새로운 branch에서 수정)
1. main branch 변경 후 readme.md 파일 수정(###main에서 수정)
1. merge 후 git graph로 확인

## github와 연결
* `git config --global user.name "이름"`
* `git config --global user.email "이메일"`
* `git config --list`
1. git hub 레파지토리에서 'enviroment' 생성(리드미 추가X)
1. 다시 로컬로 돌아와서
1. `git branch -M main`
1. `git remote add origin URL주소복붙`
1. `git push -u origin main`