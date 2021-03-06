# MARKDOWN
마크다운 문법을 공부하는 레포

### 1. 문단 구분을 위한 개행
문단 개행은 space를 두 번 이상 넣으면  
된다!
  
### 2. 헤더
헤더는 1~6 단계가 있으며 숫자가 커질수록 글자가 작아진다  
헤더로 지정할 문장 앞에 '# '을 붙이면 헤더로 지정된다  
# 헤더1
## 헤더2
### 헤더3
#### 헤더4
##### 헤더5
###### 헤더6  

  
### 3. 인용문
> 인용문은 문장 앞에 '>'를 넣으면 된다  
빈 줄이 없으면 하위 내용이 모두 인용 상자에 포함된다
  
### 4. 목록
**순서가 없는 목록  
목록을 '*', '-', '+' 등을 붙여서 작성하면 된다  
* 이렇게
- 하면
+ 된다

**순서가 있는 목록**  
1. 앞에 숫자를 붙이면
2. 순서가 있는 목록을 작성할 수 있다

**하위 목록**  
1. 하위 목록을 작성하려면  
2. 목록을 작성하고  
2.1. 하위 내용을 이렇게  
2.2. 써주면 된다  
3. 개행 문자를 넣어주지 않으면 전부 한 줄로 출력되니 주의!  
  
### 5. 코드블록
```프로그래밍 언어
내용을 ```(백틱 3개)로 감싸면 코드블록을 작성할 수 있다
<pre> 태그와 같이 공백이나 탭이 작성한대로 들어간다
```  

```// Java
publi class Hello{
  public static void main(String[] args) {
    System.out.println("Hello, World!");
  }
}
```  
  
### 6. 가로선  
'-', '*' 등의 문자를 3개 이상 연달아 입력하면 가로선이 입력된다  
---  
***  
  
### 7. 하이퍼링크  
'[하이퍼링크 텍스트](링크 URL "설명문구")'의 형식으로 하이퍼링크를 입력할 수 있다  
[YOUTUBE](https://www.youtube.com)  
  
### 8. 강조
'** 문자 ** '(띄어쓰기 없이) 문자를 감싸면 문자가 **bold**로 입력된다.  
  
### 9. 이미지  
'![디스플레이 될 텍스트](이미지 주소 "설명문구")'의 형식으로 이미지를 입력할 수 있다
![TEST_IMG](https://user-images.githubusercontent.com/96039889/147905330-ce2b43a7-8170-46cc-96f3-8afaa8892e03.gif "제 프사입니다")  
  
### 10. 표  
|표는|파이프로|나눠서|작성합니다|
|:--|:-:|--:|:--|
|정렬은|':', '-' 기호로|조절가능|합니다|
|':--'|왼쪽정렬|입니다|세미콜론이 왼쪽임|
|'--:'|오른쪽정렬|입니다|세미콜론이 오른쪽임|
|':-:'|가운데정렬|입니다|세미콜론이 양쪽임|
