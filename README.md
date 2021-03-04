"#server_dev django"

## 우분투 서버에서 가동하기

### 파이썬 및 pip설치    
sudo apt update를 먼저 해야됨   
sudo apt install python3 설치   
sudo apt install python3-pip 설치 

### 가상환경 설치   
pip3 install virtualenv 

### 가상환경 생성 후 접속   
virtualenv venv --python=python3   
source venv/bin/activate 

### requirets파일에 정의된 장고 및 라이브러리 설치   
pip install -r requirements.txt 

### 장고 서버 실행   
python manage.py runserver
