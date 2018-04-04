<h1>블랙잭& TDD (개인 프로젝트)</h1>

개발기간
3.29 ~ 4.2

개발동기 
객체지향을 이해하는데는 뷰와 데이터베이스가 연결된 게시판보다, 도메인 규칙이 충분한 카드 게임이 좋을 것 같아서 구현해보았습니다.

또한 TDD에 대해 이해하기에도 좋을 것 같아서,
테스트 주도 개발(채수원 저)를 참고하여
TDD를 하며 게임을 구현해보았습니다.


<h2>테스트 순서</h2>

1 실패하는 테스트 코드

2 Test 결과 화면(빨강)

![13](https://user-images.githubusercontent.com/32535590/38289628-20b38cca-3812-11e8-92f9-418ff148af21.PNG)


3 테스트에 통과할만한 작은 코드 작성

![10-3](https://user-images.githubusercontent.com/32535590/38289720-93c2ecec-3812-11e8-9f89-b0f0be021423.PNG)


4 Test 성공 결과 화면 (초록)

![10](https://user-images.githubusercontent.com/32535590/38289604-0369b392-3812-11e8-83eb-548a4cc00f65.PNG)


5 리팩토링 코드 (예시)
![4](https://user-images.githubusercontent.com/32535590/38292956-c0ca9f88-3820-11e8-980c-435e7cff21ad.PNG)

-> 매직넘버를 상수로 치환

![5](https://user-images.githubusercontent.com/32535590/38292997-e1d6a26c-3820-11e8-900c-59838a76bd15.PNG)

-> 기존 코드에서 매직넘버를 상수로 변경 

![6](https://user-images.githubusercontent.com/32535590/38292998-e50256f2-3820-11e8-9275-24a756c69d1e.PNG)



<h2>구현 과정 설명(네이버 블로그)</h2>

1 깃허브 연동 https://blog.naver.com/bell2017/221236035592

2 블랙잭 요구분석 및 모델링 https://blog.naver.com/bell2017/221240385067

3 객체 추상화 https://blog.naver.com/bell2017/221240394331

4 TDD 하면서 구현  https://blog.naver.com/bell2017/221240568494

5 리팩토링   https://blog.naver.com/bell2017/221244768096
 


<h2>개선사항</h2>

1 프레임워크 네티를 사용하여 다인용 블랙잭 게임 구현.

2 화면(뷰)를 공부하여 화면 동작 추가.

3 테스트 커버리지 100%에 가깝게 추가 



<h2>참고자료</h2>

1 테스트 주도 개발(채수원 저)
2 자바로 배우는 리팩토링 입문(유키 히로시 저)
