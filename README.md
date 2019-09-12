# Mecab-ko-for-GoogleColab

## install_mecab-ko_on_colab190912.sh은 
## Google Colab에 은전한닢 프로젝트 Mecab-ko라이브러리 install을 도와주는 Shell Script입니다.
### 영구적인 설치가 아닙니다.
### 라이브러리는 새 노트를 만들때마다 다시 설치해주어야합니다.

### 은전한닢 프로젝트
### https://bitbucket.org/eunjeon/mecab-ko-dic/src/master/


##1. 설치되는 mecab 버전
> mecab-0.996-ko-0.9.2

> mecab-ko-dic-2.1.1-20180720

##2. 사용법
1. ! git clone https://github.com/SOMJANG/Mecab-ko-for-Google-Colab.git

2. git clone 명령어를 통하여 저장소를 복사해옵니다.

3. cd Mecab-ko-for-Google-Colab

4. Mecab-ko-for-Google-Colab  directory로 이동합니다.

5. ! bash install_mecab-ko_on_colab190912.sh

6. 명령어로 실행합니다.

7. from konlpy.tag import Mecab

8. mecab = Mecab()

9. nouns와 같은 다양한 형태소 분석 method를 사용할 수 있습니다.
