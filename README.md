# Softcon_Blind-Student-s-Helper(Softcon 시각장애인 학습도우미 ㅅ스템)
공개SW 개발자 대회

시각장애인들이 수업을 들을 때, 전공서적을 보는 것, 칠판과 빔 프로젝트의 내용을 보는 것에 대해서 제약을 받는다. 
그런 시각장애인들을 위해, 수업시간에 보이지 않는 글자들을 소리로써 들을 수 있게 하는 시각장애인들의 눈의 역할을 하는 시스템을 개발하게 되었다. 
시각장애인 학습도우미는 칠판, PPT내용 혹은 전공서적에 대한 이미지를 받아서 이미지의 텍스트를 추출한 후, 텍스트를 소리로 변환 후 귀로 들을 수 있는 기능을 가졌다. 또한, 변환된 소리는 mp3파일로써 저장되는 기능을 가진다.
‘시각장애인 학습도우미’는 Tesseract-OCR으로 이미지의 Text를 추출하고, 추출한 Text는 GTTS(Google-Text-To-Speech)를 사용하여 mp3파일로 변환된 후 변환된 음성을 출력하는 기능을 가진다.



