# git&github

---

git: 버전 관리 시스템

github: git을 지원하는 클라우드 서비스

github 홈페이지: [https://github.com/](https://github.com/)

git 설치: [https://git-scm.com/downloads](https://git-scm.com/downloads)

### 프로젝트 생성 , 미완성

---

프로젝트 파일 생성후 git bash로 파일 들어가기

```bash
cd ..
ls
cd <파일경로>
```

### git 사용자 정보 설정 (초기세팅)

---

이름과 이메일, github 프로젝트 주소는  자신의 것으로 설정

```bash
git init
git config --global user.name ""
git config --global user.email 
git remote add origin 
```

이름과 이메일 설정 확인하기

```bash
git config user.name                
git config user.email
```

### README.md 생성 (초기세팅)

---

```bash
echo "test" >> README.md 
git add README.md
git commit -m "first commit"
git push origin master
```

### push 과정

---

파일 수정 후 push해주기 

```bash
git add .
git commit -m "second commit"
git push origin master
```

### git 명령어 정리

---

| 명령어 |  | 기능 |
| --- | --- | --- |
| git init |  | 로컬 저장소 만들기 |
| git status |  | 작업 디렉터리 상태 확인하기 |
| git add | git add <스테이지에 추가할 대상> | <스테이지에 추가할 대상>을 스테이지에 올리기 |
|  | git add . | 모든 변경 사항을 스테이지에 올리기 |
| git commit |  | 자세한 커밋 제시지와 함께 커밋하기 |
|  | git commit --message “<커밋 메시지>”               git commit -m “<커밋 메시지>” | <커밋 메시지>로 커밋하기 |
| git log |  | 커밋 목록 조회하기 |
|  | git log --oneline | 커밋 목록을 한 줄로 조회하기 |
|  | git log --patch                                                        git log -p | 커밋별 변경 사항 목록 조회하기 |
|  | git log --graph | 커밋 목록을 그래프로 조회하기 |
|  | git log --branches | 모든 브랜치의 커밋 목록 조회하기 |
| git tag |  | <태그> 추가하기 |
|  | git tag <태그> <커밋> | <커밋>에 <태그> 추가하  |
|  | git tag                                                                     git tag --list                                                              git tag -I | 태그 목록 조회하기 |
|  | git tag --delete <태그>                                         git tag -d <태그> | <태그> 삭제하 |

```bash
mkdir 
cd
pwd
ls
```