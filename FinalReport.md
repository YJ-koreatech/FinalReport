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
void img_save_time(int sleep_time=5){

   sleep(sleep_time);

   void img_save();

}

//칠판에 인식된 것들을 거리에 맞추어 저장
void img_save_distance(int space, int distance = 5, int distancestate = 0){

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
void img_save(char img[1900][1200]){

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
img_save_final(char scr_img[100][1900][1200], char img_final[1900][1200]){int i = 0;

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



