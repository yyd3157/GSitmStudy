## 문서 객체 모델(DOM)
+ 웹에서 자바스크립트를 사용하는 이유는 어떤 조건에 맞거나 사용자의 동작이 있을 때 웹문서 전체 또는 일부분이 동적으로 반응하게 하는 것

### id 선택자롤 접근하는 getElemenById()메서드
+ 요소명.getElemenById("id명")

### class값으로 접근하는 getElementsByClassName()메서드
+ 요소명.getElementsByClassName("class명")

### 태그 이름으로 접근하는 getElementsByTagName()메서드
+ 요소명.getElementsByTagName("태그명")

### 웹 요소의 내용을 수정하는 innerText,innerHTML 프로퍼티
+ 요소명.innerText = 내용 : 텍스트 내용을 표시
+ 요소명.innerHtml = 내용 : HTML 태그까지 반영하여 표시

### 속성을 가져오거나 수정 getAttribute(),setAttribute() 메서드
+ getAttribute("속성명") : 속성에 접근
+ setAttribute("속성명","값") : 접근한 속성의 값을 수정

### 이벤트 처리
+ 요소.addEventListener(이벤트, 함수, 캡처여부); : addEventListener()메서드와 event 객페를 사용하면 한 요소에 어려 이벤트 처리기 실행 가능

### css 속성에 접근
+ document.요소명.style.속성명 : 스타일 속성값을 가져와서 그 값을 원하는 대로 수정

### 텍스트 노드를 사용하는 새로운 요소 추가하기
1. createElement() : 새로운 요소 노드를 생성
2. createTextNode() : 새로운 텍스트 노드를 생성
3. 부모노드.appendChild() : 텍스트 노드를 요소 노드의 자식으로 연결
4. appendChild() : 요소 노드를 DOM에 연결

### 속성값이 있는 새로운 요소 추가하기
1. creatElement() : 새로운 요소 노드를 추가
2. createAttribute() : 새로운 속성 노드를 추가
3. 속성값 지정하기 : 속성값을 프로퍼티로 지정
4. setAttributeNode() : 속성 노드를 요소 노드의 자식으로 연결
5. appendChild() : 요소 노드를 DOM에 연결

### 노드삭제
+ 부모노드.removeChild(자식노드)
