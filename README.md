# git_guide

## git 파일 올리기 (생성된 파일 올리는 방법)
  1. git init
  2. git add .
  3. git config --global user.name <깃이름>
  4. git config --global user.email <이메일>
  5. git remote add origin <깃주소>
  6. git commmit -m <메세지>
  7. git push origin <브렌치 이름>
     
# 이름과 이메일 확인
  git config user.name                
  git config user.email

## git 파일 받기 (생성된 파일 받는 방법)
  git init
  git clone <깃주소>
