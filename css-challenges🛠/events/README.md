- 레이아웃부터 잡고 콘텐츠 넣기

- flexbox 사용할 때 "언제든지 깨질 수 있다" 인지하고 있기

  - 내용 많이 넣어보고 깨지면 안깨지게 만들어주기
    `flex-shrink: 0;` `min-width: 0;`

- 이미지 초기화

```css
img {
  max-width: 100%;
  height: auto;
  vertical-align: top;
}
```

- 리스트 왼쪽 정렬 맞춰주기
  - 디자이너가 여러 줄 디자인 안줬어도 내용 많이 넣어보고 정렬 맞춰주기
    `text-indent: -20px;`
