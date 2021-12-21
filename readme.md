# ProjName: Git cherry-pick Test    

### Stack
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">


### Summary
0. 깃 init, release, develop 두 가지 브랜치 생성.
1. dev에 수백개의 커밋을 쌓는다.
2. 검색할 커밋 메시지 검색어들을 저장한 파일을 마련한다.
3. 2번 파일을 통해 깃 로그에서 grep로 커밋들의 해시를 얻는다.
4. 체리 픽을 사용하여 3번 커밋들만 머지해본다.
    
    
### 결론    
git grep로 검색할 때, 내 컴퓨터 기준으로 145여개 티켓을 검색할 수 있다. 
cherry-pick으로 머지할 때, 내 컴퓨터 기준으로 70여개 커밋 해시를 선택할 수 있다.
