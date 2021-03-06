<p align="center">**컴퓨터시스템기초설계**
---------------------------------------------------
<p align="center">- 최종 설계 보고서

<p align="center">
![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142217778.png?raw=true)

<p align="end"> 6조
<p align="end">2013136007 권기범 
<p align="end">2013136008 권진우
<p align="end">2015136029 김영진
<p align="end">제출일 : 2016. 06. 08


#<p align="center">**목 차**

**1. 필요성, 문제 ......................................................................................................................3**

   문제 인식.........................................................................................................................3
 
   문제 정의.........................................................................................................................3
 
   진짜 문제 정의....................................................................................................................4
 
   필요성	...........................................................................................................................4

**2. 요구사항 정의......................................................................................................................5**

**3. 요구 상황을 충족하기 위한 해결책에 대한 아이디어	........................................6**

**4. 유사한 문제 해결을 위한 기존의 방법/아이디어	............................................7**

**5. 기존 방법 대비 우리 조의 차별성 및 장점..................................................9**

**6. 전체 시스템 구조 설계	..................................................................11**

  1) 시스템 구조................................................................................11

  2) 시스템의 기능..............................................................................13

  3) 시스템의 구성 요소 및 각 구성 요소의 기능, 입출력 데이터...................................14

  4) 각 시스템 기능 별 시스템 구성 요소 간의 동작 흐름..........................................16

**7. 핵심 구성 요소 상세 설계...............................................17**

  1) 구성 요소 1 상세 설계 – class E-board......................................................17

  2) 구성 요소 2 상세 설계 – lecture PC.........................................................17

**8. 구현에 필요한 기술 및 개발 환경에 대한 조사	..........................25**

**9. 과제 수행 내용에 대한 각자 의견 및 소감................................27**

#1. 필요성, 문제#
 1) 문제 인식
  컴퓨터공학부에 재학 중인 학생 A는 수학을 공부하는데 많은 어려움이 있다. 그래서 A는   대학교에서 배우고 있는 미적분학 수업을 통해서 수학실력을 더 키우고 싶었다. 그런데     미적분학 수업에 들어가 보니 교수님이 칠판에 많은 내용을 빠른 속도로 적으시면서 설명   을 하시는데 A가 이 내용을 다 적어가면서 강의를 따라가는 데에는 많은 어려움이 발생했   다. 교수님이 칠판을 다 쓰셔서 내용을 지우면 그 내용을 다 적지도 못하는 문제도 발생했   다. 복습을 하려고 노트를 펼쳐 봐도 노트에는 본인이 필기를 하다가 놓쳐서 부족한 부분   들이 너무 많았다. 수업을 따라가는 게 어려워지자 이해하는 내용도 갈수록 없어져 갔다.    결국 A는 수업을 따라갈 수가 없어져서 결국 수업을 듣는 것이 의미가 없어졌다. A는 어   떻게 하면 수업을 잘 따라 갈 수 있을까? 교수님의 수업에 집중하면서도 필기의 내용까지   한 번에 습득할 수 있는 방법은 없을까?



 2) 문제 정의
 어떻게 하면은 필기의 내용도 챙기고 수업하는 내용도 챙길 수가 있을까?
 사람이 동시에 여러 가지 일을 한 번에 하는 데에는 어려움이 따른다.
 필기를 하면서 수업을 듣기에는 집중력이 많이 떨어지게 된다.
 수업만 들으면 필기 등의 자료가 부족해져서 시험 대비에 많은 어려움이 따르게 되고, 필   기만 하면 수업 내용에 대해서 잘 모르기 때문에 노트를 다시 보게 되더라도 이것이 무슨   내용인지에 대해서 잘 모르게 된다.
 교수님들은 보통 학생들이 필기를 해서 그 내용을 가지고 있기를 원하신다.

<p align="center">
![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142224086.png?raw=true)

3) 진짜 문제 정의
 ● 필기를 하면서 수업을 들으면 수업 이해도가 많이 떨어지기 때문에 수업 중에 필기를    하느라고 집중력이 떨어지고 분산되는 문제를 교수님이 하시는 수업에 집중할 수 있도록    유도해야 한다.   

<p align="center">
![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142227853.png?raw=true)
                                              

 4) 필요성
  수학 수업을 들을 때 교수님께서 말씀하시는 내용을 따라가는 것도 어려운데 필기까지 하   면서 수업을 이해하는 것은 더욱 어렵다. 예를 들면, 수학이나 과학 같은 과목에서 교수님   이 문제를 풀어나가는 과정을 적어가면서 풀어주시는데 이것을 단순히 이해하기에는 어려   움이 있어서 필기를 해놓고서 복습을 해봐야 할 필요성이 있다. 또한 교수님의 강의 설명   내용을 듣는 것이 중요한데 필기를 하게 되면 이 점을 놓치게 되는 경우가 많이 발생하게   된다. 그래서 강의 시간에는 강의에 집중할 수 있도록 해주고 강의 이후 복습 시간에는 강   의 시간에 사용된 필기나 강의자료 등을 볼 수 있는 환경이 필요하다.  

#2. 요구사항#
 
 ● 교수님의 수업 진행에 있어서 방해가 되지 않아야 한다.

 ● 수업을 듣는 과정에 교수님의 설명을 듣고 이해할 수 있어야 한다.

 ● 필기 내용을 수업 이후에도 볼 수 있는 방법이 요구된다.

 ● 복습 과정에서 교수님의 강의 내용이 연상될 수 있는 자료가 필요하다.

 ● 교수님의 문제 풀이 과정을 순서대로 볼 수 있는 방법이 필요하다.
 
#3. 요구 상황을 충족하기 위한 해결책에 대한 아이디어#

  칠판에 있는 내용을 순간순간 캡처할 수 있는 기능을 칠판에 적용시킨다. 칠판에서 교수   님의 펜이 어느 정도의 거리를 두고 떨어지게 되면 칠판은 그림을 캡처하는 것이다. 이렇   게 캡처된 사진들은 칠판과 선으로 연결되어 있는 각 강의실의 컴퓨터로 바로바로 전송되   어 컴퓨터에 캡처 폴더에 자동으로 저장되게 된다. 사진을 받기 시작하면 컴퓨터는 받은    사진을 바로 이전에 받은 사진과 비교하는 작업을 진행한다. 이 때 이전 사진과 방금 받은   사진이 동일할 경우에는 사진을 제거하는 작업을 진행한다. 이렇게 비교작업까지 완료된    사진들은 구글 드라이브 같은 공유 서버에 실시간으로 업로드 되도록 한다. 또한 동시에    사진에 쓰여 있는 내용을 프로그램을 통해서 Microsoft words 같은 프로그램에 글씨로 쓸   수 있도록 하는 작업을 진행한다.
  칠판에서는 글씨를 쓸 때, 컴퓨터의 인식만을 필요로 하므로 과거 마커 또는 분필을 사용   하던 칠판은 필요로 하지 않는다. 특수 제작된 펜을 이용해서 전자칠판에 작성한다. 전자칠   판에서 사용하고 싶은 색깔도 선택을 할 수 있게 하고 지우개를 선택하면 부분 지우기 또   는 전체 지우기 같은 기능도 가능하도록 한다.
  또한 교수님께서 과거 필기했던 내용도 쉽게 불러올 수 있도록 하는 기능을 필요로 한다.   컴퓨터에 사진이 저장되어 있으므로 교수님이 그 사진들을 다시 열람하여 선택해서 칠판으   로 보내기 기능을 사용하면 칠판에 기존에 기록되었던 내용과 똑같은 내용이 다시 표출되   도록 한다.
  이렇게 저장된 사진은 학기가 종료가 되면 서버에서 자동으로 파일이 삭제되도록 만들어 준다.
  
<p align="center">
![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142233460.png?raw=true)

#**4. 유사한 문제 해결을 위한 기존의 방법/아이디어**#

 조사해본 결과 이러한 문제를 해결하기 위한 사례들은 전 세계에 존재하지 않았다. 이에   우리의 문제 해결을 위한 여러 가지 아이디어 중에 기존의 아이디어와 비슷했던 아이디어   를 가지고 와보았다.

**⑴ 칠판에 마커를 쓰지 않고 인식 펜을 사용하는 것**

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142237694.png?raw=true)
 [그림1] plumones inteligentes

 위 그림은 mimio 사에서 나온 plumones inteligentes 이라는 펜이다. 이 펜은 페루에서 제작된 것으로 보이는 펜이다. 칠판에 마커를 사용하는 것이 아니라 왼쪽의 도구와 색깔별로 구성되어있는 펜을 연결하여 칠판에 쓰면 칠판에 그 색깔의 글씨가 표출되도록 하는 것이다. 이것을 이용하면 마커를 다 사용하면 계속해서 구매하는 것이 아니라 배터리가 다 되었을 경우에 충전을 하기만 하면 반영구적으로 사용하는 것이 가능해진다.

**⑵ 현재 많이 사용되고 있는 전자칠판**

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142240415.png?raw=true)
 [그림2] 전자칠판 표출 모습

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142245047.png?raw=true)
[그림3] 전자칠판의 작성 모습

 현재 우리학교에서도 담헌실학관 등지에 설치되어있는 전자칠판이라는 것의 모습입니다. 이 칠판의 경우에는 아래 사진에서 보이는 조그마한 모니터에 터치스크린이 적용되어 있어 교수님이 모니터에 무언가를 적을 경우에 TV로 표출되는 시스템이 적용되어 있습니다. 

#5. 기존 방법 대비 우리 조의 차별성 및 장점

 우리 조에서 새롭게 설계한 전자 칠판은 위의 기존 방법의 불편했던 점을 크게 보완하였다. 


**⑴ 펜**
<p align="center">
![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142251140.png?raw=true)
[그림4] 삼성 갤럭시 s노트

요즘 삼성 갤럭시 노트에서 s노트라는 애플리케이션을 들어가 보면 우리가 원하는 펜을 설정하여 사용할 수 있다. 펜의 종류, 펜의 색깔, 펜의 두께 등 모든 것들을 설정하여 입력하는 것이 가능하다. 이를 이용해서 우리의 칠판에도 이러한 기능을 적용한다. 기존의 칠판에 펜을 인식하여 쓰는 경우 색깔 등을 바꾸려면 펜을 일일이 바꾸어가면서 사용을 했어야 했지만 이제는 하나의 펜으로 칠판에서 원하는 펜의 종류를 선택하면 그 내용을 적을 수 있도록 해준다. 

**⑵ 칠판에 내용을 작성하는 것**
<p align="center">
![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142254167.png?raw=true)
[그림5] 칠판에 내용을 작성하는 모습

 이미 앞에서도 소개했던 바와 같이 컴퓨터 모니터에 기록하고, 삼성 갤럭시 s노트 등을 이용해서 칠판을 대신해 사용할 수 있는 대체품이 많이 나와 있음에도 교수님들이 칠판에 판서를 하는 데에는 여러 가지 이유가 존재한다. 판서하는 것이 그만큼 더 편리하기 때문이다. 그래서 우리는 다른 도구를 거쳐 나와서 칠판에 판서가 표기되는 것이 아닌 칠판에 직접 판서를 해서 학생들이 볼 수 있도록 하는 시스템이 적용되어야 한다고 생각했다.
 
위 두 가지의 기존 전자 칠판과의 차별성이 우리가 새롭게 설계한 전자 칠판이 훨씬 더 편리하게 사용될 수 있도록 만들어준다.


#6. 전체 시스템 구조 설계
**1) 시스템 구조**

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142259475.png?raw=true)
[그림6] 전체 시스템 메카니즘

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142302135.png?raw=true)
[그림7] 수업 중의 시스템 구조

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142305346.png?raw=true)
[그림8] 수업 중의 시스템 구조

 <p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142308249.png?raw=true)
[그림9] 수업이 종료된 후의 시스템 구조

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142311604.png?raw=true)
[그림10] 전체 시스템 구조

**2) 시스템의 기능**

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142315397.png?raw=true)
[그림11] 시스템의 상호작용 및 기능


**3) 시스템의 구성 요소 및 각 구성 요소의 기능, 입출력 데이터**

 ➀ 전자 칠판
<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142320662.png?raw=true)

 ➁ 강의실 PC

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142330577.png?raw=true)

 ➂ 서버

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142341058.png?raw=true)

 ➃ 개인 PC

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142343387.png?raw=true)

**4) 각 시스템 기능 별 시스템 구성 요소 간의 동작 흐름**

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160610_142347216.png?raw=true)

<p align="center">![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160601_202230103.png?raw=true)

#7. 핵심 구성 요소 상세 설계#

|	E_Board	|	Lecture_PC	|	Server	|	PC	|
|---------|---------|---------|---------|
|	scr_img[][] : Mat	|	scr_img[][][] : Mat	|		|		|
|	lettercolor : Mat	|		|		|		|
|	sleep_time : Int	|	img_compar[][][] : Mat	|		|		|
|	distance : Int	|		|		|		|
|	distance_state : Int	|	compare_state : Int	|		|		|
|---------|---------|---------|---------|
|	letter_recognition	|	img_receive	|	file_receive	|	file_download	|
|	letter_color	|	img_save	|		|		|
|	letter_erase	|	img_compare	|		|		|
|	letter_print	|	img_delete	|		|		|
|	img_save	|	img_save_final	|	file_upload	|	contact	|
|	img_save_time(sleep)	|	img_file	|		|		|
|	img_save_distance	|	img_to_text	|		|		|
|	img_send	|	img_upload_server	|		|		|
|		|	img_call	|		|		|
|		|	img_send_Board	|	file_save	|		|

**변수**

**클래스 E_Board**

scr_img[1900][1200] : 칠판에 쓰는 모든 글씨, 문자, 그림들을 저장하는 가로1900 x 세로1200 해상도로 구성되어 있는 image matrix

lettercolor : 검정, 빨강, 초록, 파랑색을 선택 할 수 있게 저장하는 matrix

sleep_time : sleep함수에 들어갈 시간을 저장하는 변수

distance : 어느 정도 거리가 떨어졌을 때 저장할지를 정하는 변수

distance_state : 거리의 상태를 표기한다. 예를 들어 거리를 5m로 지정했다고 하자. 그러면 5m안일 때 상태는 0, 5m밖일 때 저장하기 전 상태는 1, 5m밖이어서 저장을 한 후에는 2로 표기한다.  

**클래스 Lecture_PC**
scr_img[100][1900][1200] : 전자칠판에서 받은 최종 이미지들을 저장하는 image matrix

img_compare[2][1900][1200] : 전자칠판에서 받은 이미지들을 비교할 수 있게 저장하는 image_matrix

compare_state : 두 이미지들을 비교해서 조금이라도 다르면 뒤에 들어온 이미지를 저장한다. 100%다르면 앞에 있는 이미지를 최종 저장하고 새로 들어온 이미지를 비교대상에 넣는다.

**함수**

**클래스 E_Board**

letter_recognition : 전자펜과 전자지우개를 칠판에 쓰면 그것을 인식하는 함수이다.

letter_color : lettercolor[4]에 저장된 검정, 빨강, 초록, 파랑색중 하나를 선택해 쓸 수 있게 해주는 함수이다.

letter_erase : 전자지우개를 쓰면 그 부분을 지우게 하고, 전자칠판에 있는 지우기 버튼을 누르면 칠판 전체를 지우개 한다.

letter_print : 전자펜을 인식해 그것을 쓰는 대로 출력하는 함수이다.

img_save : 칠판에 인식된 것들을 저장하는 함수이다.

img_save_time : sleep함수를 이용해 sleep_time변수에 저장되어 있는 시간에 따라 img_save함수를 이용해 이미지를 저장하는 함수이다.

img_save_distance : distance변수에 저장되어 있는 거리에 따라 distance_state변수에 저장되어있는 상태가 변한다. 그 상태에 따라 img_save함수를 이용해 이미지를 저장하는 함수이다.

img_send : 저장된 이미지를 Lecture_PC에 보내는 함수이다.

클래스 Lecture_PC
img_receive : E_Board에서 보낸 이미지를 받는 함수이다.

img_save : E_Board에서 받은 이미지를 img_compare[2][1900][1200]배열에 저장을 한다. 비교당할 이미지는 img_compare[0][1900][1200]배열에 저장하고 비교할 이미지는 img_compare[1][1900][1200]배열에 저장한다.

img_compare : img_compare[][][]에 저장되어있는 두 이미지를 비교하여 compare_state변수에 그 차이를 저장한다.

img_delete : 두 이미지를 비교해 0%<compare_state<100%이면 뒤에 있는 이미지를 앞에 저장을 한다. compare_state=0%이면 아무것도 하지 않는다. compare_state=100%이면 img_save_final함수를 실행시키고 img_compare[][][]를 0으로 초기화 시킨다.

img_save_final : img_delet함수에서 이 함수를 실행시키면 scr_img[][][]에 차례대로 이미지들을 저장한다.

img_file : sccr_img[][][]에 저장되어 있는 이미지를 파일로 저장한다.
img_to_text : scr_img[][][]에 저장되어 있는 이미지를 텍스트파일(docx)로 변환시켜 저장한다.

img_upload_server : 이미지 파일이랑 텍스트파일을 서버로 업로드 시킨다.

img_call : 서버에 있는 이미지 파일이랑 텍스트파일을 불러온다.

img_send_Board : 서버에서 불러온 이미지 파일, 텍스트파일을 전자칠판에 보낸다.

**수도코드**

**class E-Board**

char scr_img[1900][1200];

char lettercolor[4] = {“red”, “black”, “green”, “blue”};

int sleep_time;

int distance;

int distance_state;
 
//칠판에 쓰면 그것을 인식
void letter_recognition(){}

//색을 선택 할 수 있는 함수
void letter_color(){}

//letter_recognition에서 전자지우개로 인식된 것이 있으면 그것을 지움
void letter_erase(){}

//letter_recognition에서 전자펜으로 인식된 것이 있으면 그것을 출력
void letter_print(){}

//칠판에 인식된 것들을 저장
void img_save(){}

//칠판에 인식된 것들을 시간에 맞추어 저장
void img_save_time(int sleep_time=5)

{

   sleep(sleep_time);

   void img_save();

}

//칠판에 인식된 것들을 거리에 맞추어 저장
void img_save_distance(int space, int distance = 5, int distancestate = 0)
{

   if(space>=distance)
 
   {

      distancestate=1;

      if(distancestate==1)

      void img_save();
 
      distancestate=2;
 
   }
 
   If(space<distance)
 
   {
 
      distancestate=0;
 
   }

}

//Lecture_PC로 저장된 이미지를 전송
void img_send(){}

**class Lecture_PC**

char scr_img[100][1900][1200]=NULL;

char img_compare[2][1900][1200]=NULL;

int compare_state;

// E-Board에서 보낸 이미지를 받는 함수
void img_receive(char img[1900][1200]){}

//받은 이미지를 저장하는 함수
void img_save(char img[1900][1200])
{

   if(img_compare[0][1900][1200] == NULL)

      img_compare[0][1900][1200] = img[1900][1200];

   else

      img_compare[1][1900][12000] = img[1900][1200]; 

}

//img_compare[][][]에 저장되어있는 두 이미지를 비교한다.
void img_compare(char img_compare[2][1900][1200])
{
   비교코드;
   compare_state = compare결과
}

//두 이미지를 비교해 필요없는 것은 삭제한다
void img_delete(int compare_state, char img_compare[2][1900][1200])

{

   if(compare_state<100 || compare_state>0)

      img_compare[0][1900][1200] = img_compare[1][1900][1200];

   if(compare_state=0)

   {

      img_save_final();’

      img_compare[0][1900][1200]=NULL’

   }   

}

//최종 이미지를 저장한다.
img_save_final

(char scr_img[100][1900][1200], char img_final[1900][1200])

{

int i = 0;

scr_img[i][1900][1200] = img_final[1900][1200];

++;

}

//scr_img[][][]에 저장되어 있는 이미지를 파일로 저장
void img_file(char scr_img[][][]){}

//scr_img[][][]에 저장되어 잇는 이미지를 텍스트 파일(docx)로 변환
void img_to_text(char scr_img[][][]){}

//이미지 파일, 텍스트파일을 서버로 업로드
void img_upload_server(){}

//서버에 있는 이미지 파일, 텍스트파일 호출
void img_call(){}

// 서버에서 불러온 이미지파일, 텍스트파일을 전자칠판에 전송
void img_send_Board(){}


#8. 구현에 필요한 기술 및 개발 환경에 대한 조사

**1) 구현에 필요한 기술**

 1. 칠판 내용 캡쳐하는 기술
   -- Windows Media API for capturing the screen
    Windows Media 9.0은 Windows Media Encoder 9 API로 스크린 캡쳐를 지원한다. Windows Media Encoder API는 스크린 내용을 보다 효율적으로 캡쳐하는데 사용되는 인터페이스 IWMEncoder2를 제공한다.

 2. 칠판 내용(글씨) 인식 기술 - 그림 글씨 인식
   - MSER(Maximally stable extremal) regions 기술 사용
    1. Bin sort를 수행하여 Intensity 값이 낮은 순으로 정렬.
    2. 트리를 생성한다.
    3. Extermal Region 후보를 찾는다.
    4. 강건한 Extermal Region을 골라낸다.
    5. 크기 등의 조건을 통해, 불필요한 Extermal Region은 제거한다.

![](https://github.com/YJ-koreatech/FinalReport/blob/master/Final%20Report/KakaoTalk_20160601_202229576.png?raw=true)
3. S펜 같은 도구를 인식하는 기술
   - Wacom Dual Digitizer
    Wacom Dual Digitizer란, 정밀한 EMR 디지털 펜과 스크린 아래의 digitizer 층으로 부      터 전기 용량적 멀티-터치와 액티브 펜의 입력을 지원한다. 간단히 말해, Wacom 기술      을 적용한다.

**2) 개발 환경에 대한 조사**
 
1. 칠판 : LED 패널이 부착된 스크린

2. 강의실 PC : 

    CPU : Intel Core I7 6790

    Memory : 16GB DDR4

    HDD : 2TB

    OS : Windows 10

    Network Interface : Olleh KT Giga Internet
    
3. 서버

    CPU : 인텔 제온 E5-2697V3 (하스웰-EP)	

    Memory : 512GB

    HDD : WD 8TB PURPLE WD80PUZX (SATA3/5400/128M)

    OS : Windows Server 2012 R2

    Network Interface : Cehlsio Server Lan Card(T520-SO-CR/S1)
4. 개인 PC

    CPU : 인텔 펜티엄 G4400 (스카이레이크)	

    Memory : 2GB

    SSD : 128GB

    OS : Windows 10


#9. 과제 수행 내용에 대한 각자 의견 및 소감#

1. 2013136007 권기범

 이번 과제를 하면서 다른 조별과제랑 색다른 느낌이어서 새로웠다. 다른 조별과제는 토론하고 약간 두루뭉술한 느낌의 과제인데 컴퓨터 시스템 기초 및 설계의 과제는 아이디어를 세우는 모든 과정을 구체적으로 설계했다. 아이디어를 내기 전 불편한 점, 그 불편한 점에서 나온 요구사항, 그 요구사항을 충족시킬 만한 아이디어, 이렇게 나온 아이디어와 유사한 문제를 해결한 기존의 방법/아이디어에 대한 조사, 기존 방법/아이디어와 우리가 낸 아이디어의 차별성 및 장점, 모든 요건을 충족한 우리의 아이디어를 상세설계 이 모든 과정이 실제로 아이디어를 내고 그 아이템을 만드는 과정이랑 같고 그것을 하고 있어서 새롭고 재밌었다. 이번년도까지 프로그래밍 실력을 쌓고 다음연도부터 뭔가 하나를 만들어 볼 생각이었는데 이번 설계를 하면서 좋은 것들을 많이 얻어갔다. 이 과제를 하기 전에 내가 뭔가를 만들어 보려고 했으면 왜 이것을 만들려고 하는지도 모르고 다 만들어 놓고 며칠 혹은 몇 년 후에 내가 만든 것과 비슷한 내가 만든 것 보다 좋은 프로그램을 발견해 이걸 만들 때까지의 시간이 헛될 수도 있는 상황이 발생 할 수도 있었다. 뭔가를 만든다는 것이 이토록 체계적이었는지를 알게 된 나한테는 더할 나위 없이 좋은 과제였다. 

2. 2013136008 권진우

 이런 조별 과제는 컴퓨터 공학을 전공하는 사람이 아니면 하기 힘들 것 같다는 느낌이 들었다. 리눅스에서 github를 이용한 정보 공유라니 상상만 했지 실제로 직접 해볼줄은 상상도 하지 못했다. 한때 리눅스를 공부하기도 했지만 여러 가지 이유로 그만두게 되었는데 2학년 때 학과목으로 리눅스를 배우게 되어 좋았다. 용어나 명령어는 익숙하기 때문에 큰 어려움은 없었다. 문제 해결 방안을 도출할 때는 우리가 실생활에서 주로 겪는 일을 생각해보았다. 여러 가지 문제가 나왔지만 다른 사람들도 쉽게 공감을 할 수 있는 문제를 꼽았다. 그에 대한 시스템을 구성하고 설계하는 과정에서 이 조별과제는 뭔가 다르다는 것을 알게 되었다. 여타 다른 과목의 조별과제는 그저 조를 정하고 조원끼리 모여서 발표 자료를 만드는 것에 그치는 반면에 컴퓨터 시스템 기초 및 설계 과목의 조별 과제는 단순한 발표 자료를 만드는 것을 넘어서서 실생활 및 전공, 앞으로의 방향까지 생각할 수 있는 계기를 만들어 주었다. 무엇보다 github로 한 과제는 따로 모일 필요가 없어서 편했다. 조원들의 관심사도 서로 같아서 과제를 하는데 그 점이 과제를 좋은 방향으로 이끌어 나갔다고 생각한다. 다른 사람들이 한 샘플을 봤을 때 참 대단하다고 생각했는데 직접 하고 보니 썩 좋은 결과를 낸 것 같다.

3. 2015136029 김영진

 학교를 다니면서 여러 불편한 점이 존재하고 있었지만 그것을 실제로 어떻게 하면 더 편하게 바꿀 수 있을 지에 대해서는 잘 생각해보지 않았었다. 수학 수업을 들으면서 교수님의 필기를 따라가는 것은 실제로 많은 학생들이 어려워하는 부분이다. 잠깐 동안만 집중력이 흐트러져도 수업 내용 이해 자체가 어려워지기 때문이다. 이러한 문제를 실제로 해결할 수 있는 방안 자체를 조원들과 함께 직접 만들어보았다는 것이 매우 놀라웠다. 미래에는 이러한 전자 칠판이 실제로 사용될 수 있다면 매우 기쁠 것 같다는 생각이 들었다. 이러한 시스템을 만들기 위해서 상세설계를 진행하였는데 이 과정에서 설계의 어려움을 많이 느꼈다. 모든 부분을 각각 설계해야하고 각각의 부분이 서로 어떻게 맞물려 작동하는 지에 대해서도 전부 알아내야했다. 앞으로 시스템 설계를 할 때 이번 경험이 많은 도움이 될 것 같았다. 마지막으로 실제로 인터넷에서 기존의 제품이나 아이디어를 찾아보았는데 처음에 찾아볼 때는 큰 개념만을 가지고 찾아보아서 많은 내용을 찾아낼 수는 없었지만 점점 상세설계를 진행하면서 부분적으로 필요한 것을 찾아 볼 때는 최신 IT 기술이나 제품들도 많이 볼 수가 있었다. 실제로 신기했던 기술들이 굉장히 많이 있었다. 앞으로도 최신 기술들을 찾아볼 것이다.



