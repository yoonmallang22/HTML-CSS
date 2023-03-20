- 버튼 색상, 페이지 나중에 자바스크립트로 `class="on"` 유무로 제어할 예정이다

- 더미 이미지
  실제 사용할 이미지를 넣기 전에 매우 간단하게 이미지 영역을 잡아줄 수 있다

```html
<img src="http://placehold.it/500x500" alt="" />
```

- 디자이너에게 받은 이미지마다 크기, 비율이 다를 수 있기 때문에
  유지보수 측면에서 이렇게 작성해준다

```css
width: 100%;
aspect-ratio: 180 / 250;
object-fit: cover;
```

- 길이가 길어질 수 있는 텍스트도 유지보수 측면에서 말줄임 표시를 작성해준다

```css
white-space: nowrap;
text-overflow: ellipsis;
overflow: hidden;
```

- focus 디자인도 잘 확인하는게 좋다

```css
.btn-group a:focus {
  /* outline 위로 올라오게 */
  z-index: 1;
}
```
