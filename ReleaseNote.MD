# Quick Start Guide


(1) 먼저 구글에 로그인 해준다. 그리고 아래의 코랩 링크에 들어간다. 아래 링크의 코드는 이 레퍼로터지의 3-LSTM 폴더의 mbti_LSTM.ipynb와 동일하다.

https://colab.research.google.com/drive/1OhXjgmXnt5RcVw5A2LZ65Za0fS4S1LkK#scrollTo=n4SGJk_oF36x

(2) 링크에 접속했다면 페이지 상단에 있는 메뉴의 '런타임>모두실행'을 통해 코랩코드를 실행한다.

(3) 필요한 패키지가 import 되고, 데이터가 load 된 후 전처리와 4가지 지표의 이진 분류에 대한 학습이 진행된다.
    그리고 마지막 부분에는 직접 텍스트를 받아 MBTI 성격 유형을 분류하는 것도 가능한 것을 확인할 수 있다.

(5) 직접 텍스트를 넣어 MBTI를 분류하길 원한다면, text 변수에 분류하길 원하는 텍스트를 넣고 셀을 실행해 준다.

![image](https://user-images.githubusercontent.com/90343909/172702978-07c9c758-bc2a-4dc5-a80c-4a1390388b20.png)



(6) 다음 셀을 실행해 준다. (text 변수를 input으로 넣은 코드)

![image](https://user-images.githubusercontent.com/90343909/172702621-d27bb530-d7d7-452b-a491-72cccd4d6849.png)




(5) 그러면 그 텍스트에서 드러나는 MBTI를 예측하는 것을 볼 수 있다.

![image](https://user-images.githubusercontent.com/90343909/172703093-f070cabe-e4a0-4b0a-88fb-4c8742b97b42.png)



# Other method

혹시 Quick Start Guide의 방법으로 했을 때 문제가 있다면 직접 소스 코드 파일을 다운받아 구글 드라이브에 업로드 해 코랩으로 파일을 돌리는 방법이 있다.

그 방법은 아래와 같다.

[mbti_LSTM.zip](https://github.com/parkjimin00-a11y/1839_gross/files/8864295/mbti_LSTM.zip)

(1) 위 zip파일을 다운 받고 압축을 푼다. 위 zip파일에 담긴 파일은 코드 파일로, 이 레퍼로터지의 3-LSTM 폴더의 mbti_LSTM.ipynb와 동일하다.

(2) 압축을 푼 폴더 안의 mbti_LSTM.ipynb(코드 파일)을 구글 드라이브에 저장해준다.

(3) 위의 (2)에서 구글 드라이브에서 저장한 mbti_LSTM.ipynb(코드 파일)를 열면 코랩으로 코드 파일이 열린다.

(4) 링크에 접속했다면 페이지 상단에 있는 메뉴의 '런타임>모두실행'을 통해 코랩코드를 실행한다.

(3) 필요한 패키지가 import 되고, 데이터가 load 된 후 전처리와 4가지 지표의 이진 분류에 대한 학습이 진행된다.
    그리고 마지막 부분에는 직접 텍스트를 받아 MBTI 성격 유형을 분류하는 것도 가능한 것을 확인할 수 있다.

(5) 직접 텍스트를 넣어 MBTI를 분류하길 원한다면, text 변수에 분류하길 원하는 텍스트를 넣고 셀을 실행해 준다.

![image](https://user-images.githubusercontent.com/90343909/172702978-07c9c758-bc2a-4dc5-a80c-4a1390388b20.png)

(6) 다음 셀을 실행해 준다. (text 변수를 input으로 넣은 코드)

![image](https://user-images.githubusercontent.com/90343909/172702621-d27bb530-d7d7-452b-a491-72cccd4d6849.png)


(5) 그러면 그 텍스트에서 드러나는 MBTI를 예측하는 것을 볼 수 있다.

![image](https://user-images.githubusercontent.com/90343909/172703093-f070cabe-e4a0-4b0a-88fb-4c8742b97b42.png)



# 논문

다음은 이 코드를 이용해 '딥러닝을 이용한 MBTI 분류 연구' 라는 주제로 쓴 논문의 url이다.

https://github.com/parkjimin00-a11y/1839_gross/blob/main/%EB%94%A5%EB%9F%AC%EB%8B%9D%20%EA%B8%B0%EB%B0%98%20MBTI%20%EC%84%B1%EA%B2%A9%20%EC%9C%A0%ED%98%95%20%EB%B6%84%EB%A5%98%20%EC%97%B0%EA%B5%AC.pdf
