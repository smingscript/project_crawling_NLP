# 인테리어 사이트 웹 크롤링 및 자연어 처리
이 프로젝트 인테리어 사이트 Homify에서 게재하는 매거진의 이미지와 텍스트를 크롤링한 후 자연어 처리를 통해 인테리어 카테고리 별로 유사성이 높은 단어를 분석할 수 있습니다.
이 프로젝트의 최종목표는 이미지 분류 딥러닝을 통해 사용자가 입력한 사진을 바탕으로 유사한 컨셉의 사진을 텍스트 기반으로 검색해주는 웹 서비스를 만드는 것입니다.

## 개발환경
- Python 설치 버전: Python 3
- Python library
  - pandas(0.20.2)
  - requests(2.18.1) / BeautifulSoap 4
  - KoNLPy(Twitter, 0.4.4) / NLTK(3.2.5)
  - gensim(Word2Vec, 2.1.0)

## 참고
Mobile phone reviews NLP by dreamgonfly: [github](https://github.com/dreamgonfly/phone-reviews-nlp)

## 라이선스
This project is licensed under the MIT License
