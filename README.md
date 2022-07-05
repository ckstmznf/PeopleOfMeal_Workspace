# 개요
- 급식 평점 앱
- 급식의 민족은 전국의 모든 학교의 급식에 대한 평점을 줄수 있는 학교 급식 평점앱입니다.

# 기획 배경
- 오늘 급식이 맛있었는지, 맛없었는지를 전교생이 볼 수 있는 커뮤니티 필요
- 영양사 선생님께서 급식에 대한 만족도를 알아볼 수 있는 플랫폼 필요

# 기획 목표
- 학생들이 급식 정보를 보고, 급식을 먹은 후 평점을 남길 수 있는 서비스 제작
- 학교 급식에 대한 객관적인 수치를 표현

# 기술 스택
- Flutter 3.0
    - http: ^0.13.4
    - provider: ^6.0.3
    - flutter_rating_bar: ^4.0.1
    - fluttertoast: ^8.0.9
    - shared_preferences: ^2.0.15
    
- Django
- Neis API [바로가기](https://open.neis.go.kr/portal/mainPage.do)

# 기능 기획
> 취소선을 초기 기획에는 있지만 아직 기능 구현 안됨
- 로그인 화면
    - ~~구글 로그인~~
    - ~~로그인 후 앱 실행이 처음이면 학교 설정 화면으로 이동~~
- 학교 설정 화면
    - 학교 검색
    - 검색 결과중 하나 선택 → 시간 설정 화면으로 이동
- 점심시간 설정 화면
    - 점심 시간을 입력 받는다.
    - 시간 설정 버튼 누르면 timePicker 열기
    - timePicler에서 선택된 시간을 화면에 보여준다.
    - 다음 버튼 → 메인 화면
- 메인 화면
    - 일주일 급식 정보를 보여준다.
    - 오늘의 급식을 보여준다.
    - ~~급식시간까지 남은 시간 보여준다.~~
    - 우리학교 급식 평점을 보여준다.
    - ~~급식 시간이 지났으면서, 아직 평점을 주지 않았다면~~
    - 최상단에 별점 ui로 별점을 줄 수 있게 설정  
