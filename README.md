# Var-myeongso
네이밍이 어려운 개발자를 위한 변수명 검색 서비스 / 2022    
[김진환](https://github.com/ecsimsw), [조윤근](https://github.com/Yunkeun), [소재헌](https://github.com/Jaeheon-So)

### Feature
- 검색 대상이 될 코드 저장소 크롤링한다.
- 코드 내 클래스명, 변수명, 코드에 사용된 단어를 파싱하고 ES에 저장한다.
- 클래스명으로, 변수명, 일반 단어를 검색할 수 있다.
- 원본 저장소의 Star 수를 우선으로 검색 결과 페이지가 출력된다.

### Scenario

- 메인 페이지
<img width="800" alt="image" src="https://user-images.githubusercontent.com/70425484/178231443-cd780bb5-19eb-4064-ba27-366c8487db7c.png">
    
- 기본 검색(Word): Word 검색은 검색어 ‘id’가 포함된 모든 코드가 검색된다.
<img width="800" alt="image" src="https://user-images.githubusercontent.com/70425484/178231470-ad9fd9c2-af2c-4b3a-9dbb-cb7b5e8be5c9.png">

- 변수명 검색: Variable 검색은 변수명이 ‘id’인 모든 코드가 검색된다.
<img width="800" alt="image" src="https://user-images.githubusercontent.com/70425484/178231499-2840e653-3606-48af-9682-0e6853be99ee.png">

- 클래스명 검색: Class 검색은 클래스명이 ‘HelloWorld’인 모든 코드가 검색된다.
<img width="800" alt="image" src="https://user-images.githubusercontent.com/70425484/178231528-bad024b9-f01f-4e12-a6ed-187d9b849ed6.png">
