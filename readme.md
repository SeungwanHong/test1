# 마크다운 기본 문법(참조)
***
|비고|마크다운|변환후 모습|
|:-------|:-------|:-------|
|강조|기울임(*), 굵게(__) ()사이의 택스처를 강조하려는 내용 앞 뒤에 붙이면된다.|*기울임*, __굵게__|
|인라인 링크||[참조1] |
|참조 링크|참조 링크는 아래 내용을 참고하자|[참조2] |
|URL만으로 링크하기|아래 내용 참조|[참조3]|
|수평선|(-),(*),(_) 3개이상 나열하면된다.|___|
|각주|각주 [각주] 는 이렇게 만든다. |아래 [참조4]|
|줄넘기기|각 라인의 끝에  2개 이상의 스페이스를 넣으면  줄 넘기기(개행)가 된다.|[참조5]|
|문단 나누기|문단을 나눌 때는 문단과 문단 사이에 한 줄을 비워놓으면 된다.||
|순서없는 리스트|-, +, *을 맨앞에 적고 스페이스 한칸 이후 작성하면된다.|[참조6]|
|순서있는 리스트|숫자 다음 .을 찍는다. 적힌 숫자랑 상관없이 순서대로 번호가 매겨진다.|[참조7]|
|인용|>,>> 꺽새의 갯수에 따라 들여쓰기가 일어난다.|[참조8]|
|코드|`를 양쪽에 적으면된다.|`test`[참조9]|
|코드 블럭|` 3개를 양쪽에 적으면된다.|[참조10]|
|제목|#의 개수에 따라 h1,h2등으로 사용가능하다.|[참조11]|
|테이블|현재 테이블 상태 확인|ㅅㄱ|
***
[참조1]: 인라인링크  
[링크](http://example.com).  

[참조2]: 참조링크
[링크1][1] 과 [링크2][2].
[1]: http://example.com/ "링크제목1"
[2]: http://example.org/ "링크제목2"
[참조3]: url링크
<http://example.com/>
<me@privacy.net>

[참조4]: 각주
[각주]: 각주다.

[참조5]: 줄개행
ㅇㄴㅁㅇ  
ㅇㄴㅁㅇㄴㅁ  

[참조6]: 리스트
+ 1
* 2
* 3

[참조7]: 순서있는리스트
1. 1번째
2. 2번째
2. 번호에 상관없다.

[참조8]: 인용
>인용 1단계
>>인용 2단계
>>>인용 3단계

[참조9]: 코드한줄

`코드이다.`

[참조10]: 코드블럭

```
코드블럭이다.
```
[참조11]: 제목
# h1
## h2
### h3
