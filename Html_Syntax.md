# HTML Syntax

- &lt;strong&gt;&lt;/strong&gt;: tag 안의 텍스트를 진하게 표시해준다. 
- &lt;u&gt;&lt;/u&gt;: tag 안의 텍스트 아래에 밑줄을 그어준다. 
- &lt;br&gt;: tag는 줄바꿈을 의미하므로 닫을 필요가 없다. 
- &lt;p&gt;&lt;/p&gt;: tag는 어디서부터 어디까지가 단락인지 표현함. 


- 태그로만은 정보가 부족할 수 있다.
- &lt;img src="허찬용.png" width= 100&gt; 이런 식으로 사진을 가지고 올수도 있고 크기도 지정 가능
- &lt;li&gt;: 띄워쓰기 가능
- &lt;ul&gt;: &lt;li&gt; 태그의 부모태그이다.  
- &lt;ol&gt;&lt;/ol&gt;: 태그를 사용하면 자동으로 번호가 매겨진다. ul과 ol은 list의 약자이다. o는 Ordered u는 UnOrdered임.
- &lt;table&gt;&lt;/table&gt;:은 3대가 같이 다녀야함
- &lt;tr&gt;&lt;/tr&gt; &lt;td&gt;&lt;/td&gt;: tr은 table row(가로줄을 만드는 역할) td는 table data 약자임 셀을 만드는 역할
- &lt;parent&gt;  &lt;child&gt;&lt;/child&gt; &lt;/parent&gt;


- meta: 메타는 문서 그 자체를 설명하는 태그임.
- &lt;!DOCTYPE html&gt;: 그냥 적어줘야함. 
- &lt;meta charset="utf-8"&gt;: 한국어가 깨질 수도 있으므로 utf-8사용
- &lt;a href="http://www.w3.org/TR/html/" target="_blank" title="html speicification"&gt;&lt;/a&gt;: href 의 의미는 hyper text reference의 의미이다. 누르면 해당 링크로 이동함 태그 사이의 글이 하이퍼 텍스트가 되고 target="_blank"하게 되면 새창에서 열림 title 사용하면 추가적인 내용 나옴.

- &lt;input type="checkbox"&gt;: check box를 만드는 명령어.
- &lt;asub&gt;: 아래 첨자로 태그 안의 문자열을 아래 첨자로 보냄.
- &lt;asup&gt;: 위 첨자로 태그 안의 문자열을 위 첨자로 보냄.
- \<

- &lt;input type="text"&gt;: 텍스트 박스 생성
- &lt;input type="password"&gt;: 패스워드 박스 생성
- &lt;input type="date"&gt;: 연도/월/일 박스 생성
- &lt;input type="time"&gt;: 시간 박스 생성
- &lt;input type="range"&gt;: 범위 박스 생성
- &lt;input type="color"&gt;: 색 박스 생성
- &lt;input type="radio"&gt;: 하나를 선택할 때 radio를 사용
- &lt;input type="checkbox"&gt;: 여러개를 선택하게 만들 때는 checkbox 사용
- &lt;input type="file"&gt;: 파일선택 박스 생성
- &lt;textarea name="" id="" cols="30" rows="10"&gt;: 메모장 같은 텍스트 공간 생성

- ctrl + /: 하면 주석 처리됨

* header nav section article aside footer로 파일은 이루어져 있음 모두 있을 필요는 없음.
* 블락 요소는 자기가 한 줄 다 차지함 
* 인라인 요소는 다른 요소들하고 같이 위치함. 
