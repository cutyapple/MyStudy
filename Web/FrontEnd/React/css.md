### css



#### classnames

* `npm add classnames`

* ```react
  import cn from 'classnames';
  
  cn('a', 'b'); // 'a b'
  cn('a', { b: true }); // 'a b'
  cn('a', { b: false }); // 'a'
  cn('a', { 'b', 'c' }); // 'a b c'
  ```

* cn 메서드를 이용하여 클래스에 붙이는 값을 제어할 수 있다. 