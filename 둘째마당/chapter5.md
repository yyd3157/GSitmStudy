### form
## form 만드는 태그
``` <form [속성="속성값"]>여러 폼 요소</form> ```

## form 요소를 그룹으로 묶는 태그
<fieldset> : 폼 안의 여러구역
<legend> : fieldset으로 묶은 그룹의 제목 설정

## 날짜 입력 input type
<input type="date">
<input type="month">
<input type="week">
  
## 전송과 리셋
``` <input type="submit" value="전송"> ```
``` <input type="reset" value="리셋"> ```
  
## input 태그 주요 속성
autofocus 속성은 웹 문서를 열면 텍스트 필드에 바로 입력할 수 있도록 만듬
placeholder 속성은 텍스트를 입력할 때 입력칸에 적당한 힌트내용을 표시
readonly 읽기전용으로 만듬
  
## form에서 사용하는 여러 가지 태그
+ 텍스트 여러 줄 입력
  ``` <textarea>text</textarea> ```
+ 데이터 목록 생성
  ``` <input type="text" list="데이터 목록 id">
      <detalist id="데이터 목록 id">
        <option value="서버로 보낼 값1">선택1</option>
        <option value="서버로 보낼 값2">선택2</option>
  </detalist>
