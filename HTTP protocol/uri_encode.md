# URI encode



## 개요

URI은 ASCII 문자집합에 속한 문자로만 사용가능하도록 정의됨.

그러나 URI파라미터 등으로 다양한 언어가 사용될 수 있고,
URI에 예약되어 사용할 수 없는 문자(공백을 포함)들을 처리하기 위해서 사용됨.

%를 이용해서 변환하여 전달함.

```
Hello new world
```

 의 경우 공백은 URI에 사용할 수 없음으로 변환시

``` 
Hello%20new%20world
```

공백이 %20으로 변환된다.





---

### 참조

1. w3school - HTML URL Encoding Reference : https://www.w3schools.com/tags/ref_urlencode.asp
2. Encoding URL (a.k.a Percent Encoding) - 관련 블로그 글 : http://regularmotion.kr/url-encoding-url/
3. URL encode 예약문자 사용시 문제점- 관련 블로그 글 : https://bluestarblogkr.blogspot.com/2011/10/url-encoding.html
4. URI encode/decode 테스트가능한 사이트 : https://meyerweb.com/eric/tools/dencoder/