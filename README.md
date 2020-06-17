# CSS-Layout

# display: inline-block 
- inline은 elemnet , 너비 높이 사용 X
- block이 너비와 높이 속성을 가짐
- block 속성에 해당 요소 인자 지정
```
.box:nth-child(index)
```
- block은 반응형에 맞추기 힘듬

# flexbox
- 기본적으로 inline-block이랑 동일하게 가로로 배치
- container가 있어야함(바로 아래) 붙어있는 부모가 자식의 위치를 움직임
- flex container의 flex-direction 기본값은 row(가로)
- flex-direction이 가로면 메인은 가로축 
- felx-direction이 세로(column)면 메인이 세로축
```
flex-direction: column(세로)
```
- justify-content(Main) 수평축에 있는 flex children의 위치 변경(center: 중간 / space-between : 중간에 공간 / space-around: 양옆에 공간 )

- align-items(cross): 세로축에 있는 방향으로 움직임(center: 중간 / flex-end : 맨아래 / flex-start: 맨위)

- align-self : 해당 자식 요소 하나만