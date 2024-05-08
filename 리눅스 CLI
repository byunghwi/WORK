1. cat
- cat 명령은 파일(들)을 순서대로 읽고 그 내용을 읽은 순서대로 표준 출력(standard output)에 쓰는 명령
   cat [OPTION]... [FILE]...
      OPTION
        -n        : 모든 라인 앞에 라인 번호 출력. (빈 라인도 번호 출력)
        -b        : 비어 있지 않은 라인에만 번호 출력.
        -E        : 라인의 마지막에 $ 기호 출력. (빈 라인도 $ 기호 출력)
        -T        : 탭 문자를 ^I로 바꿔서 출력.
        -s        : 두 번 이상 연속된 빈 라인(empty line) 출력 안함.
        -v        : 탭(TAB)과 줄바꿈(LFD)을 제외한 nonprinting 문자를 ^, M-를 사용하여 표시.
        -e        : -vE와 결과 같음. 줄바꿈(LFD)을 포함한 nonprinting 문자 표시.
        -t        : -vT와 결과 같음. 탭(TAB)을 포함한 nonprinting 문자 표시.
        -A        : -vET와 같음. 탭(TAB), 줄바꿈(LFD)을 포함한 nonprinting 문자 표시.

EX)
  cat 사용 예	                       cat 명령 옵션
  1.파일 내용 출력	                     cat FILE 
  2.파일 생성	                         cat > FILE 
  3.라인마다 번호 출력	                 cat -n FILE 
  4.라인 끝에 $ 문자 출력	             cat -E FILE 
  5.탭을 ^I 로 출력	                   cat -T FILE 
  6.반복된 공백 라인 무시	               cat -s FILE 
  7.파일 복사, 합치기, 추가	             cat FILE > OUT 
  8.파일 사이에 내용 추가	               cat FILE1 - FILE2 
  9.파일 내용을 페이지 단위로 출력	     cat FILE | more 
  10.파일 내용 필터링	                 cat FILE | grep "STR" 
  11.모든 파일 내용 출력	               cat * 
  12.특정 확장자를 가진 파일 내용 출력	   cat *.txt 

참고: (https://recipes4dev.tistory.com/177)
