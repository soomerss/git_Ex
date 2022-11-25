# git 명령어

## 기본 명령어

 git log : git의 작업 이력을 알 수 있다.
 
 ### 옵션
* -p, --patch : 파일 단위의 변경 내용을 보여줍니다.
* -[NUMBER] : 최근 몇 개의 커밋을 보여줄지 지정
* --stat : 각 커밋의 통계 정보(파일의 수정 및 각 파일의 Line 추가 및 삭제 여부) 확인
* --pretty={option} : 커밋 로그를 보여주는 형식을 지정할 수 있다.
* 상세 Option 표

| **형식** | 설명       | **형식** | 설명         |
|-----|----------|----|------------|
| **%H** | 커밋 해시    | %**ae** | 저자 이메일     |
| **%h** | 짧은 커밋 해시 | %**ar** | 저자 상대적 시각  |
| **%T** | 트리 해시    | %**cn** | 커미터 이름     |
| **%t** | 짧은 트리 해시 | %**ce** | 커미터 이메일    |
| **%P** | 부모 해시    | %**cr** | 커미터 상대적 시각 |
| **%p** | 짧은 부모 해시 | **%s** | 커밋 요약      |
| %**an** | 저자 이름    |    |            |

git commit : 스테이징 상태에 있는 파일을 커밋한다.
:art: 
