# Web using Apache



### 아파치 

* 웹서버 소프트웨어
* C:\Bitnami\wampstack-8.0.6-0\apache2\htdocs 에 html 파일을 넣으면 서버에 파일이 들어감.
* bitnami 를 사용해서 서버를 키고 끌 수 있다.
* 내 컴퓨터의 포트는 81이다. 안 바꾸는 걸 추천!! &#40;만약 바꾸고 싶다면 
아파치의 포트 관련 환경설정 파일 열기
&#36; sudo nano /etc/apache2/ports.conf

80이라고 되어 있는 Listen 포트를 아래와 같이 원하는 포트로 변경한 후 수정한 파일을 저장하고 에디터 모드에서 빠져나옵니다.

아파치의 가상호스트 환경설정 파일 열기
&#36; sudo nano /etc/apache2/sites-available/000-default.conf

&lt;VirtualHost *:80&gt; 라인을 찾고 아래와 같이 수정한 후 저장하고 나옵니다.
&lt;VirtualHost *:8081&gt;

아파치 서비스 재시작하기
&#36; sudo /etc/init.d/apache2 restart&#41;

* http://127.0.0.1:81  : http 뒤 숫자는 내 컴퓨터 로컬 ip 주소이다. 

* 만약 같은 와이파이를 사용한다면 내 컴퓨터 IPv4 주소를 치고 포트번호 친 다음에 파일명을 치고 들어가면됨 ex)  http://127.0.0.1:81/index.html 이런 식으로 

* IPv4주소를 얻기 위해서는 네트워크와 공유센터에서 연결 항목에서 확인가능. IP는 각자 다름
