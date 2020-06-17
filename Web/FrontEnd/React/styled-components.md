### styled-components



```react
import styled, { createGlobalStyle } from 'styled-components';

const Box = styled.HTMLElement`
	css;
	css;
	css;
`
// HTMLElement : 원하는 HTML 요소

const Box2 = styled(Box.withComponent('HTMLElement2'))`
	css;
	css;
`

// Box2는 Box를 상속받아 withComponent 함수의 요소로 HTML 요소를 넣은 다음, 새로운 css를 넣는 것이다.

const GlobalStyle = createGlobalStyle`
	body {
		padding: 0; margin: 0;
	}
`
// createGlobalStyle을 통해, body 태그를 제어할 수 있다.
```

