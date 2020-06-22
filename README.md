# C-Programming
## university assignment

### 2015-03-10 기초 1
    정수 데이터 입출력,
    scanf()함수 warning 해결을 위해 #define _CRT_SECURE_NO_WARNINGS 선언
### 2015-03-17 기초 2
    char 배열에 문자열 받기[scanf_s("%c", &ch, 1)]
    gets(str); gets()함수를 이용하여 문자열을 입력 받을 수 있다
### 2015-03-24 if, switch, 2진수
    조건문 생성, 문자를 입력받아 2진수를 출력
### 2015-03-31 반복문(for, do.while, while) 
    반복을 통한 출력 모양 만들기, 사용자가 원하는 숫자 찾기
### 2015-04-07 재귀함수, random
    재귀함수를 통해 반복문 작성
    rrand(), srand(), time()을 통해 random game만들기
### 2015-04-14 배열 함수 1 
    배열을 함수를 사용해서 이용
    복사, 비교, 초기화 등등
### 2015-04-28 배열 함수 2
    빈도수 계산, 크기순으로 정렬
    XOR연산을 이용하여 암호화하고 변환된 암호문을 원래의 값으로 복원하는 프로그램을 
### 2015-05-12 반복문 응용, 포인터 변수
    반복문을 통한 도형 만들기
    포인터 변수 선언 및 초기화
    [int *ptrint = &data;]
    일차원 배열과 포인터
    [int *pa = &a[0];  //*pa=a;  배열의 시작 주소를 포인터 변수로 초기화]
### 2015-05-19 함수 포인터
    함수 포인터를 사용한 호출
    void 포인터 변수
### 2015-05-26 문자열
    문자열 비교, 복사, 연결, 분리
### 2015-06-02 구조체
    구조체 정의 & 구조체 변수 선언
    구조체를 멤버로 갖는 구조체 정의  &  멤버 접근
    구조체를 멤버로 갖는 구조체 정의  &  멤버 접근
    구조체 배열
    구조체 포인트
### 2015-09-16 정렬
    선택 정렬, 버블정렬, 스택
### 2015-09-23 연산식, 배열
    메인함수의 매개변수로부터 값 받기
    연산식, 포인트 선언의 결과 예측
    파스칼의 삼각형
    배열 병합
### 2015-09-30 문자열 활용
    strtok()
    strcmp()
    strcpy()
### 2015-10-07 랜덤, 피보나츠, 최대공약수
    랜덤Game
    피보나츠 수를 재귀를 이용하여 구해보기
    재귀함수를 이용하여 최대 공약수 구하기
### 2015-10-14 계좌 프로그램
    지금까지 배운 지식을 활용해서 계좌 시스템 구성
    void userinfo(struct bankaccount *p);//사용자 정보 입력
    void printuser(struct bankaccount *p);//사용자 정보 추력
    void handlebank(struct bankaccount *p);//입금, 출금, 종료
    int checkaccount(struct bankaccount *p, char *chkuser);//사용자 계좌정보 체크
    nt checkpasswd(char *confirmpass, char *savedpass);//비밀번호 검사
    int deposit(int balance, int amount);//입금
    int withdraw(int balance, int amount);//출금
### 2015-11-04 파일 입출력 1
    간단한 파일 입출력 해보기
### 2015-11-11 파일 입출력 2
    사용자가 입력하는 내용을 입출력 해보기
    fwrite(), fread() 사용
    파일의 크기 출력
    fseek() ftell() 사용
    · fwrite(&ch, 사이즈, 횟수, 파일포인터); 또는 ftell(fp); 사용
### 2015-11-25 연결 리스트 함수
    //노드를 생성하는 함수
    LINK createNode(char *name){
        LINK cur;
	    cur = (NODE *) malloc(sizeof(NODE));
    }
### 2015-12-02 연결 리스트 구조체
    score 구조체를 만들고 구조체를 연결하는 리스트를 작성 그 후 파일에 입력
### 2015-12-15 TEST
    연결 리스트를 사용하는 문제