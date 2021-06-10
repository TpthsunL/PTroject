# Practice_code

오늘의 코드 따라하기

1. 댓글분석 
- 2021_06_09 : 11번까지 이해

몰랐던 부분 
#라이브러리 로드
#requesets는 작은 웹브라우저로 웹사이트 내용을 가져온다.
import requests
#BeautifulSoup 을 통해 읽어 온 웹페이지를 파싱한다. 
from bs4 import BeautifulSoup as bs 
#크롤링 후 결과를 데이터프레임 형태로 보기 위해 불러온다. 
