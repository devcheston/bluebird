# bluebird
django 서버

### python 관련 패키지 버전
joe@Eunsungui-MacBook-Pro-2 ~ % pyenv --version
pyenv 2.3.18

joe@Eunsungui-MacBook-Pro-2 ~ % pyenv version
3.10.4 (set by /Users/joe/.pyenv/version)


## 환경세팅 명령어
  385  python --version
  386  python -m venv venv_bluebird

  390  source venv_bluebird/bin/activate
  391  which python

  396  python -m pip install "django~=4.0.0"

## django 버전
(venv_bluebird) joe@Eunsungui-MacBook-Pro-2 bluebird % python -m django --version
**4.0.10**

  422  python -m django startproject backbone .


## 개발 DB 세팅

hombrew 설치

brew install mysql@5.7

brew services start mysql@5.7

/usr/local/opt/mysql@5.7/bin/mysql_secure_installation

→ 비밀번호 세팅

echo 'export PATH="/usr/local/opt/mysql@5.7/bin:$PATH"' >> ~/.zshrc

→ 환경변수 세팅

mysql -uroot -p

mysql -u [your_username] -p

→ mysql 접속
