# Books-N-Languages
* 프로그래밍 언어별 출판도서목록 분석
* Analysis of list of books already published by Programming Language <br/><br/>

## 프로젝트 의도

**1. 각 언어별 출판되는 책 정보 수집** <br/>
- '네이버 책(NAVER Books)' 기준 국내 출판되는 프로그래밍 언어 책 정보를 크롤링했습니다.<br/>
- 검색어는 '언어 + 프로그래밍'으로 통일<br/>

**2. 프로그래밍 언어별 인기도와 책 출판 사이의 연관성 확인** <br/>
-  가설 설정 : *'인기 있는 프로그래밍 언어일수록 해당 언어의 도서가 많이 출판될 것이다'*<br/>

**3. 국내 프로그래밍 언어 관련 출판 책 데이터의 상관관계 파악** <br/>
- 언어별 도서 가격, 페이지 수 등 기타 데이터 상관관계<br/><br/>

## 프로젝트 결과

**1. 프로그래밍 언어별 출판도서 수 분석**
![image](https://user-images.githubusercontent.com/91931949/141613243-a53e4414-408e-46d4-96b6-31804fbc46b5.png)

- 5개년도 기준, 출판 도서수는 R, SQL, Python 순으로 많음
- SQL은 세계 경향과 달리, 국내 출판 도서가 많은 것으로 나타남
- R도 PIOBE 인덱스 상으로는 14위이지만, 국내 도서는 많은 출판량을 보이고 있음 (2020년 이후에는 소폭 줄어듬)
- PIOBE 인덱스 참고 : <https://www.tiobe.com/tiobe-index/>

![image](https://user-images.githubusercontent.com/91931949/141613471-31296e81-52ae-4b5c-8b9f-56bb9c182e79.png)

*최근 2개년(최근)과 그 이전 3개년(그 이전)을 비교하였음*
- R 도서는 SQL과 Python과 달리, 최근에 그 이전에 비해 현저히 감소하였음
- 
