## HTML 태그 학습
1. 이미지
- 기본적으로 `<img src="이미지 주소" (생략가능: width="픽셀단위" height="픽셀단위")>`로 사용
- 캡션을 달기 위해서는 먼저 `<figure></figure>`를 해주고 그 안에 이미지를 넣고, 위 또는 아래에 `<figcaption></figcaption>`을 넣어준다.

2. 하이퍼링크
- `<a href="URL주소">단어 또는 문장</a>` 꼴로 사용

3. 리스트
- 순서 없는 리스트: `<ul></ul>`의 안에 `<li></li>`로 목록을 만들어 사용 
- 순서 있는 리스트: `<ol></ol>`의 안에 `<li></li>`로 목록을 만들어 사용 

4. 표
- `<table></table>`의 안에 행마다 `<tr></tr>`을, 열마다 제목행에서는 `<th></th>`, 일반 행에서는 `<td></td>`

- 예시: 

  ```html
  <table border="1">
      <tr><th>제목</th><th>장르</th></tr>
      <tr><td>프레임: 나를 바꾸는 심리학의 지혜</td><td>자기계발서</td></tr>
      <tr><td>멋진 신세계</td><td>소설</td></tr>
  </table>
  ```

5. 동영상
- ```html
    <video (생략하면 원본 크기: width="720" height="400") controls>
    	<source src="비디오 주소">
    </video>
    ```

    와 같이 사용한다.