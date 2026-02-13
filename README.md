# ASICS
## 작업기록
### 2026/02/04
* index html 작성
### 2026/02/10
* **1차 피드백 후 태그 수정**
* 'pab' -> 'fab' class명 수정
### 2026/02/11
* main 영역 class 각 의미에 맞게 수정
* main 중간에 div안에 hero bnr 하나만 있어서 불필요한 div 삭제
* 띠배너(top_bnr) 슬라이드 형식으로 수정
* gnb에서 펼쳐지는 메뉴 작성
* **2차 피드백 후 태그 수정**
* 띠배너 뷰포트 영역 추가
* 필수 속성 수정 및 추가
* 펼쳐지는 메뉴 영역 수정
* span 제거 (로그인/회원가입, footer-fnb)
* footer 부분 수정 (div, f_logo)
* main 전체적인 순서 및 레이아웃 수정
    * .gel_nyc_wrap 완료
    * .sports_shop_wrap 완료
    * .hero_bnr_slide_wrap 이미지 변경 및 txt_box 수정
### 2026/02/12
* main 수정
    * .hero_bnr_slide_wrap 완료
    * top_bnr 수정
    * 슬라이드 배너들의 하단 페이지 바 추가
    * .marathon_wrap 추가
    * .Sportstyle_hero_bnr 수정
### 2026/02/13
* marathon_wrap 이미지 추가
* **3차 피드백 후 태그 수정**
* `<a href="#">` 수정 (그만 빼먹어 제발)
* footer sns_list 순서 변경
* input id 추가
* page_bar 수정
* tab_menu 더보기 위치 수정
* gnb - ... - div class="ad_box" 수정
* tab_menu - ... - span class="new" "member" 추가
* sportstyle_bnr - div="bnr_txt_box" 그룹 묶기
* bg img 태그 삭제 및 각주 표시
* slide에 개별 이름 부여 (slide숫자)
* css 선택자 작성 완료
## 피드백 내용 정리
### 2026/02/10 (1차)
* 띠배너
    * 슬라이드 형식으로 수정
    * txt 클릭되는 영역임 => `a`태그 사용
    * 닫기버튼에 `class=""` 속성 부여
* 태그들의 필수 속성 잊지말고 쓰기!
* pab (x) fab (o)
* main 영역의 `class="contents"`(x) 각 영역 의미에 맞게 이름 부여하기
    (이름을 contenrs로만 반복해서 부여하면 각 영역에 어떤 것이 있는지 펼쳐보지 않으면 몰라서 불편함)
* footer 영역 크게 1행 3열로 묶고 그 안에 상황에 맞게 또 묶어주기
    (디자인이 같은 방향이 아니거나 여백이 많이 있는 경우 묶기)
* gnb의 밑으로 펼쳐지는 서브메뉴 추가로 만들기 (men,women 정도만)
### 2026/02/11 (2차)
* 바뀐 원본 사이트와 구성 동일하게 바꾸기
* top_bnr의 뷰포트 만들기
* 펼쳐지는 메뉴에서 men에 밑줄쳐진 것은 활성화(X) => 활성화 된다고 생각하고 만든 태그 삭제
* 제발 속성 똑바로 작성하기
    * `<a href="">`
    * form속성 name(X) input속성 name(O)
    * button속성 id
* 전체가 강조되는 경우에는 span으로 묶어줄 필요가 없음 (부분이 강조될때만 묶어주기)
* slide_container 안 li태그 확인하기 
* ad_bnr이 원본 사이트에서는 하나의 이미지로 되어있지만 백그라운드 이미지+내용 조합으로 변경하기
* p가 많이 나올 구간 이름 부여(class, 열지 않아도 뭐가 있는지 알 수 있도록)
* fnb -> ul-li로 묶고 안에 a또는 div - a 구조 / spand보다는 em이지만 굳이 묶을 필요는 없음
* footer로고의 경우 페이지가 새로고침되는 것이므로 #gnb가 아니라 ./index
* f_left에서 하단 div안 방향 재확인 하고 수정 (div추가)
### 2026/02/13(3차)
* **<a href="#">**
* gnb안 lnb 영역 `ul-li(메뉴) / div (광고 이미지)` 으로 나누기
* input에 id 추가하기
* hero_bnr_slide img 안 <p> -> <h>로 수정
* page_bar의 경우 바탕이 되는 전체 바 부분 1, 움직이는 바 1 총 2개로 구성된 것임
* tab_menu 안 더보기 버튼은 ul 부모 div와 형제로 두기
* tab_menu - ul - li - <p>new</p>옆에 추가로 멤버스 전용도 오는 것을 고려해서 안에 <span>태그 추가 및 이름 부여하기
* sportstyle_bnr txt 묶어주기
* footer 영역에 sns_list는 제일 하단에 가도록 (애매하게 중간에 껴있지 않도록)
* bg_img의 경우에는 css로 작업하면 되므로 태그 불필요
## 자주 실수하는 부분 / 헷갈리는 부분
* 속성 값 빼먹지 말기!!제발.
    * **`<a href="#">`**
    * `<form action="" method="">`
    * `<input type="" name="">`
    * `<button type="" id="">`
* 
