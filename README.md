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

- flex-wrap : wrap - 기본적으로 width를 신경쓰지 않는 flex가 width 지키도록

- flex-shrink : element의 행동 정의 flex-wrap이 nowrap일때 크기가 줄어들어 width 유지되지 않고 줄어들때  비율 정의 

- flex-grow : shrink의 반대 개념

- flex-basis : child에서 적용되는 property element에게 최초 크기 지정실제 크기 X / main 축의 최초 크기 row면 가로 column이면 세로