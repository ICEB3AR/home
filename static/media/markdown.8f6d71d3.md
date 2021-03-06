# TistoryPostChecker

## 기능  

* 내 블로그 글들이 `제목`으로 검색하였을 때 가장 `첫 페이지`에 노출이 되는지 확인할 수 있는 스크립트입니다. 

## 사전 설치가 필요한 것  

* python 2 or 3
* requests 모듈  
`pip install requests`를 통해 requests모듈을 설치해주세요

## 안내사항
**본 스크립트는 티스토리 아이디나 비밀번호등 어떠한 개인정보도 다른곳으로 전송하거나 저장하지 않습니다.**  
`검색이 안된다`의 기준은 글 제목을 검색하였을 때 첫 페이지에 노출되지 않는 경우입니다. 


## 사용법  
1. `python2`를 사용한다면 `TistoryPostChecker_2.py`, `python3`를 사용한다면 `TistoryPostChecker.py`를 다운로드합니다.
2. 에디터를 이용해서 파일을 열고 `아이디`, `비밀번호`, `블로그이름`을 각 필드에 입력합니다.
![](https://i.imgur.com/OSaOPGc.png)
3. `python TistoryPostChecker_2.py` (python2) 또는 `python3 TistoryPostChecker.py` (python3) 로 스크립트를 실행합니다.
4. 첫 실행에서는 `메일함에서 로그인 인증을 해주세요`라고 출력되게됩니다. 가입한 이메일의 메일함에서 인증을 진행해주세요.
5. 각 글별로 구글, 다음, 네이버에서의 검색을 한뒤, 결과가 보여집니다.
```
[*] 공개된 포스트 수 : 10

[*] [ctf apk문제]CyberTruck Challenge 2019  #Challenge 1
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] [크롤링] python webdriver로 크롬창 열기 (selenium)
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] Python Random 모듈 함수 정리, 사용법
	[-] 구글에서 검색안됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] [티스토리 구글 노출 팁]티스토리 글을 구글에 색인요청하기 구) fetch as google
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] [놀러가자] 경기 2020년 1월 하반기 축제 정보! 2020년 1월 22일 ~ 2020년 1월 31일
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] [놀러가자] 서울 2020년 1월 하반기 축제 정보! 2020년 1월 22일 ~ 2020년 1월 31일
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] 디데이 앱 따라 만들며 배우는 React Native #3 레이아웃 구성하기
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] [pwnable] 우분투 설치 후 깔아야 하는 것들 모음
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] 디데이 앱 따라 만들며 배우는 React Native #2 Component와 메인화면 분할
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] 디데이 앱 따라 만들며 배우는 React Native #1 리액트 네이티브 맛보기
	[+] 구글에서 검색됨.
	[+] 다음에서 검색됨.
	[+] 네이버에서 검색됨.

[*] 구글 검색이 안되는 포스트 : 
	Python Random 모듈 함수 정리, 사용법
```
