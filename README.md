# 😲 What happend? Open mail!

당신 주변의 다양한 이야기를 어떻게 하면 쉽게 알려줄 수 있을까요? 🤷🏻‍♀️

	호외요~ 호외~ 🔉🔉
	
	우리 팀 김 책임이 오늘 생일이라고?? 옆 팀에 이 사원이 새로 들어왔다고!?
	오늘 주간보고 쓰는 날이었어??
	
	또... 나만 몰랐어?

이런 고민 다들 해보신적 있으시죠? `openmail`은 이러한 질문에 답해주고 싶었습니다.

> 도대체 이 세상이 어떻게 돌아가는지는 몰라도, 우리 팀 돌아가는거는 알고 싶어!


---

## Structure
openmail은 다음과 같은 구조를 가지고 있는 프로그램입니다.
 
1.  노션에 입력된 조직에 관련한 다양한 정보를 수집합니다.
2. 정기적으로 알려줘야 할 정보 혹은 새로운 정보를 찾아냅니다.
3. 조직원의 메일로 발송해줍니다! 📮

## Rule

- 상호 피드백은 가감없이
-  호칭은 ~님 준수, 하지만 자유롭게 써도 👌

## Contents
openmail은 아래와 같은 콘텐츠를 포함하고 있습니다.

	1. 매주 주간보고 작성 이메일 알림
	2. 조직원 생일 및 입사 N주년 알림
	3. Welcome! 👋🏻 입사자 알리미!!
	4. 입사자 onboarding letter [7일]
	5. 패밀리데이 알림
	6. 세미나 참여 링크

## 진행사항
openmail은 python과 notion api를 활용해 개발하고 있습니다.

	1. 개발 크루 모집 완료(chuck, Wilberforce, niceguy1575)

	2. 기능 개발 (100%)
		*  notion API 데이터 수집 기능 (100%)
		*  smtp mail to @everyone (Simple Mail Transform Protocol), python. (100%)
		*  알림 정보 생산 (100%)
	
	3. Class 모듈화 (100%)
	4. 사내 서버 배치화 (0%)

* 향후 teams api를 활용한 메시지 전달 기능 추가 예정 (@Wilberforce)

## Issue

1. 노션 시스템시간과 korea time간의 차이가 발생하기 때문에 배치는 반드시 오전 9시 이후에 수행할것

👉 반영 완료
