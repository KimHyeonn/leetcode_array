# pywork

# 2021. 06. 03. ~ 2021. 06. 17. python 활용 데이터 분석 관련 학습 내용 정리

# 일자별 정리

# 일자별 내용 - pywork.txt에서 확인 가능

210603 	Series 
	DataFrame

210604 	DataFrame 병합
	시각화

210607_1 스크래핑, 크롤링, 
	BeautifulSoup
	urllib + BeautifulSoup
	Selenium + BeautifulSoup

210607_2	(from konlpy.tag import Okt
	import re)
	(from wordcloud import WordCloud
	import matplotlib.pyplot as plt)
	워드클라우드 만들기
	(from PIL import Image)

210608	기술통계 (mean, std..)
	시각화 (도수분포표, boxplot_이상치관련, subplots)
	groupby
	pivot_table
	crosstab
	matplotlib barplot vs pandas barplot
	* tips / iris 연습문제

210609	GET ; selenium -> webdriver -> starbucks 서울 매장 -> beautifulsoup parsing
	POST ; webdriver -> 금거래소 시세테이블 
	post 는 페이지들마다 접근방식이 달라져서, 차라리 보이는대로 다 가져오는 방법, 즉 selenium 활용 -> 버튼 찾고, 버튼 눌러가면서 (.click()) 페이지 가져옴

210610	통계(모평균 모표준편차 표본평균 표본표준편차..)
	영화평점 연습문제

210611	네이버 영화 천문 평점 가져오기, 리뷰 크롤링
	-> 데이터프레임화

210614	상관분석
	-> iris 데이터
	t검정
	두 집단 평균 차이 검정 (levene() -> t-test)
	카이제곱검정
	연습문제 ; 부모 학력과 자녀의 대학진학여부 관계 검토,
		  diamonds

210615	ML ; decision tree 모형
	파라미터 튜닝

210616	ML ; 로지스틱 회귀모형
	+ 주성분 분석

210617	천문 분석
	(리뷰 크롤링 이후 - 알바가 존재하는지)
