# setup-doc-index_4_setup

- 이 문서는 메타 문서다 

## General Rules 

https://speakerdeck.com/jennybc/how-to-name-files?slide=27

### Rule Zero

- `_`는 메타 데이터 구분자 
- `-`는 띄어쓰기 

## Git Repo Naming

### General 

- category와 category 사이는 `_`로 연결한다. 
- category 내의 스페이스는 `-`로 연결한다 

### level-1 Category

- repo가 다루고 있는 영역을 가장 넓게 정의하는 카테고리 

|Name|Desc|
|:----:|-----|
|**work**|업무용 / 회사 업무 관련 |
|**test**|테스트용 / 광범위하게 |
|**setup**|설정용 / 설치, 유지 보수 관련 핵심 사항 |
|**doc**|문서 / 순서 문서용, application 단에서 핵심적으로 알아야 할 것과 같은 것|
|**lec**|발표 및 외부 강의 / 발표 자료|
|**TIL**|TOday I Learned, 구 Info| 
|**project**| 프로젝트 |

- 이외에 자명한 경우 해당 명칭을 level-1으로 활용한다. 
  - `streamlit_`

### level-2 Category (if necessary) 

- repo가 활용하고 있는 프로그래밍 랭귀지를 적는다. 
- 크게 문제가 안되면, full name을 적도록 하자. 

1. **python** 
2. **julia**
3. **rstat**

### level-3 Category (free style)

- 그때그때 적당한 형태로 이름을 붙이도록 하자. 

## Git Branch Naming 

- TBD 

## Git Comment Writing

- 아직 혼자 써서 본격적으로 하게 되지는 않더라. 

### Use cases 
- `WORKING` 작업중 
- `FIX` 문제점 해결 중 
- 파일이 하나 고쳐지면 자동으로 붙는 이름 활용 

