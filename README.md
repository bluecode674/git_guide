###### 마크다운사용법 찾아보면서 편집하기

# git_guide

#### 사용자 정보 설정 (초기 1회)
  ```
  git config --global user.name <깃이름>
  git config --global user.email <이메일>
  ```

#### 이름과 이메일 확인
  ```
  git config user.name                
  git config user.email
  ```

1. 레포지토리 생성 (readme, ignore 파일 생성 x)

#### file upload (처음 파일 올리기)
  ```
  git init
  git add .
  git remote add origin <깃주소>
  git commmit -m <메세지>
  git push origin <브렌치 이름>
  ```

#### file download (처음 파일 다운받기)
```
  git init
  git clone <깃주소>
```

#### git push
```
git add .
git commit -m <커밋문>
git push origin <브렌치 이름>
```


### git pull
```
git add .
git pull
```
