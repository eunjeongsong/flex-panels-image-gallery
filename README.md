# Flex Panels Image Gallery

## CSS

### box-sizing

box-sizing은 박스의 크기를 화면에 표시하는 방식을 변경하는 속성입니다. width와 height는 엘리먼트의 컨텐츠의 크기를 지정합니다. 따라서 테두리가 있는 경우에는 테두리의 두께로 인해서 원하는 크기를 찾기가 어렵습니다. box-sizing 속성을 border-box로 지정하면 테두리를 포함한 크기를 지정할 수 있기 때문에 예측하기가 더 쉽습니다. 최근엔 모든 엘리먼트에 이 값을 지정하는 경우가 늘고 있습니다.

- 기본값: content-box
- 상속: No
- 애니메이션: No
- 버전: CSS Level 3

1. content-box : 콘텐트 영역을 기준으로 크기를 정합니다.
2. border-box : 테두리를 기준으로 크기를 정합니다.
3. initial : 기본값으로 설정합니다.
4. inherit : 부모 요소의 속성값을 상속받습니다.

> [결론] border-box 설정시 border 를 박스 사이즈 안에 포함하겠다는 의미!

### What does flex: 1 mean?

```css
flex: 1;
display: flex;
justify-content: center;
align-items: center;
flex-direction: column;
```

> 이렇게 설정하면 아이템들을 가운데 정렬하고, 위에서 아래로 배치할 수 있음.
> flex-direction: column; 해주지 않으면 가로로 배치됨.
