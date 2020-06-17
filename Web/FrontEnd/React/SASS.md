## SASS



### SASS 란?

#### SASS 란?

* SASS는 Syntactically Awesome Style Sheet의 줄임말로, 문장 구성적으로 끝내주는 스타일 시트라는 뜻이다. 
* SASS의 확장자는 .scss와 .sass가 있다.



#### .scss VS .sass

* 사실 둘 다 같은 파일을 의미한다.
* 그러나 구조적으로 차이가 있는데, scss는 `{} ;`를 사용한다.



#### SASS 설치

* `npm add sass`



### 변수(Variables)

* SASS에서는 변수를 정의할 때 `$`를 사용한다. 
* 변수의 이름은 사용자 지정, 값은 CSS의 속성을 주어야 한다. 



### 중첩

* SASS에서는 중첩으로 코드를 간략하게 한다. 

* ```css
  ul li a {
      display: block;
  }
  // css
  
  
  ul {
      li {
          a {
              display: block;
          }
      }
  }
  // sass
  ```

  