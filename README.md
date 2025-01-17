# CEOS 15th Front-end 1st Study
안녕하세요! CEOS 프론트 15기 김채림입니다. 분명 바닐라 자바스크립트로 to do list를 만들어본 경험이 있는데 처음하는 것처럼 새로웠던 과제였습니다. 다시 한 번 자바스크립트를 제대로 공부해봐야겠다는 생각이 든 시간이었어요. 여전히 좋은 코드는 어떻게 써야하는지 잘 모르겠고 어렵네요 ...ㅜ 만들면서도 이게 맞나????라는 질문을 계속 했던 것 같습니다.

**💻 배포링크**

 https://vanilla-todo-15th-i384hlwil-chaaerim.vercel.app/

<br>

**📗 추가한 내용**

크게 추가를 한 부분은 없고 투두리스트다 보니 시간이 같이 표시되면 좋을 것 같아 간단히 위에 추가해보았습니다!

<br>

**✏️ 어려웠던 부분**

가장 어려움을 겪었던 부분은 **todo와 done todo를 카운팅하는 부분**이었습니다. todo 객체의 ` isCompleted`가 `true`, `false`일 때를 나누어 done todo와 todo의 개수를 세어보려고 했는데 잘 읽어들이지 못하는 것 같았습니다. 그래서 처음에 만들었던 코드를 지우고 count를 하는 전역변수를 만드려다가... 제가 done으로 투두를 이동시키는 `moveToDone`메소드에서 isCompleted를 바꾸고 toDos배열에 반영을 안했다는 사실을 뒤늦게 깨달았습니다.. 
기능단위로 커밋을 해보는 것이 처음이라 커밋도 어려운 부분 중 하나였던 것 같습니다. 

<br>

**😅 아쉬운 부분**

시간 부족의 관계로 로컬스토리지를 활용하지 못했는데 이 부분이 아쉽습니다. 이 부분은 주말에 다시 추가해보려고 합니다. 그리고 스크롤바 밑에 하얀 박스가 생겨서 거슬리는데 해결을 못했습니다ㅜ 혹시 해결법을 아신다면 알려주시면 감사하겠습니다!!

---
### ⁉️ Key Questions
1. DOM은 무엇인가요?
**DOM**이란 프로그래밍 인터페이스로 HTML에 접근해서 이를 조작할 수 있는 모델을 뜻합니다. DOM을 통해 자바스크립트를 가지고 HTML에 접근하여 삭제, 수정 등을 가능하게 해줍니다. 

2. HTML (tag) Element를 JavaScript로 생성하는 방법은 어떤 것이 있고, 어떤 방법이 가장 적합할까요?
`document.createElement()`를 이용해서 HTML 요소를 추가할 수 있습니다. 

3. Semantic tag에는 어떤 것이 있으며, 이를 사용하는 이유는 무엇일까요?
**Semantic tag**란 의미가 있는 태그를 뜻합니다. `<div>`, `<span>`과 같은 경우는 태그 이름만 봐서는 어떤 내용이 포함되어있는지 유추할 수가 없지만 `<form>`, `<article>`과 같은 시맨틱 태그를 활용하면 내용 짐작이 가능해집니다. 
검색엔진 같은 경우도 태그를 기반으로 검색 키워드의 우선순위를 판단하므로 적절하게 시맨틱 태그를 활용하는 것이 좋습니다. 
저도 div, span을 사용하기 전에 다시 한 번 고민하는 습관을 들여야겠습니다 .. ㅎ

4. Flexbox Layout은 무엇이며, 어떻게 사용하나요?
**Flexbox Layout**을 이용하면 box와 item을 행, 열로 자유자재로 배치 시켜줄 수 있습니다. flexbox 의 컨테이너 박스에 적용되는 속성값들이 존재하고, 각각의 item에 적용할 수 있는 속성값이 존재합니다. 또한 flexbox에는 중심축과 반대축 이 있는데(수평축, 수직축), 중심축을 수평, 수직에 두느냐에 따라 반대축이 바뀌도록 설정할 수도 있습니다. 
저는 보통 수평으로 반복적인 것을 배치할 때 `<li>`로 만들고 flexbox를 이용해서 가로로 놓이게 하는 방법을 사용했던 것 같습니다.

5. JavaScript가 다른 언어들에 비해 주목할 만한 점에는 어떤 것들이 있나요?
**JavaScript**는 타입을 명시할 필요가 없는 인터프리터 언어로 클라이언트에서 처리됩니다. 사용하기 편하기 때문에 웹문서를 동적으로 만들어야 할 때 많이 사용하는 것 같습니다. 변수형을 선언하지 않아도 된다는 점과 컴파일 과정이 없다는 것 또한 JavaScript의 장점이 될 수 있다고 생각합니다. 

6. 코드에서 주석을 다는 바람직한 방법은 무엇일까요?
다른 사람들도 빠르게 이해할 수 있도록 간결하고 정확하게 주석을 다는 것이 중요한 것 같습니다.


