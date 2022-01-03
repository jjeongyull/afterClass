# 제목 : readme 
## markedown language: 사용설명서 만들기
### 소제목

<img src="./mainconcept/plani.png">

```
사용되는 폰트
색상, 컨샙

1. 로고는 이미지로
2. 플랜아이에대한 설명
 타임라인 3초정도 지나가는게 애니메이션되며 나타남
3. 문장을 시간이 지나면 타임라인따라 자동으로 상하로 스크롤되며 
메세지가 오른쪽에서 왼쪽으로 들어오며 타임라인 시간에 따라 메세지라고 써있는 단어도 다른 단어로 바뀌며 오른쪽에서 왼쪽으로 들어온다
```

# 기호이름

1. `백틱 : **1번 왼쪽**의 작은 따옴표
1. ~ 틸드
1. ^ 캐럿
1. & 앰퍼센트
1. | 파이프
1. \ 백슬래시
1. / 슬래시

# 파일명, 폴더명 사용시 주의점
1. 1영문으로 시작
2. 의미있는 파일명
3. 파일명, 폴더명은 반드시 띄어쓰기 사용하지말것
, 서버 : 리눅스 환경
1. 대소문자 구분해서 사용할 것

# 이름만드는 규칙 : 문화
1. 카멜표기법 : 단어와 단어사이 첫글자는 대문자
2. 스네이크 표기법 : 단어와 단서사이를 -로 표시
3. 파스칼 표기법 : 첫글자를 대문자로 사용
4. 

# 이미지 파일 확장자
## 웹에 업로드 할수 있는 확장자
- jpg : 투명표현이 불가능
- png : 투명표현이 가능
- gif : 투명표현, 애니메이션가능
- webm : 새로운 이미지 포맷


# 이모지 : 윈도우 기능


# git : 리눅스 명령 화경
git-scm.com 다운로드
폴더이동 > 마우스 오른쪽 버튼> git bash here

# git upload

```
echo "# afterClass" >> README.md
// 문서를 만든다.
git init
// git 폴더 초기화
git add README.md
// git 업로드할 파일 선택
git commit -m "first commit"
// 버전관리에
git branch -M main
// master => main
git remote add origin https://github.com/jjeongyull/afterClass.git
// 업로드할 폴더와 로컬폴더를 연결
// staging : 업로드할 준비
git push -u origin main
// 진짜업로드
```

# 두번째 접속 후 업로드 
```
git remote add origin https://github.com/jjeongyull/afterClass.git
git branch -M main
git push -u origin main
```