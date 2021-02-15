---
layout: post
title:  "Jupyter Notebook 초간단 사용법"
---


### Jupyter Notebook
- mode
  - 명령모드 (ESC)
  - 편집모드 (enter)
- style
   - makrdown(명령모드 + m) : 셀 안의 설명을 작성할 때 사용
   - code(명령모드 + y) : 파이썬 코드 작성 시 사용
- 단축키
  - 셀 실행 : shift + enter
  - 셀 삭제: (명령모드) x
  - 되돌리기 : (명령모드) z
  - 셀 생성 : (명령모드) a(위에) b(아래에)
  - 셀 반복 실행: ctrl + enter 

### Magic Command
 - 셀 내부에서 특별하게 동작하는 커멘드
 - % : 한 줄의 magic command 를 동작
 - %%: 셀 단위의 magic command 를 동작
 - 주요 magic command
    - %pwd : 현재 주피터 노트북 파일의 경로
    - %ls : 현재 디렉토리의 파일 리스트
    - %whos: 현재 선언된 변수들 출력
    - %reset : 현재 선언된 변수들 모두 삭제

### Shell Command
  - 주피터 노트북을 실행 쉘 환경의 명령을 사용
  - 명령어 앞에 !를 붙여서 실행
  - 주요 명령어 : ls, cat, echo ,,
