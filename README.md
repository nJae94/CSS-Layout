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

# Grid
- grid-template-columns : 줄에 각각 크기 지정 가능

- column-gap : 컬럼 사이의 간격

- row-gap : 위아래 간격

- gap : 두개 합친거

- grid-template-rows : 컬럼의 높이 

- grid-template-columns, rows => repeat(횟수,크기) : grid 반복

- grid-template-areas : grid의 위치를 지정가능

- fr : 사용가능한 공간

- items은 셀 중에 하나 각 각

- justify-items : grid-container는 모든 grid자식을 갖고 자식을 늘려서 자신을 채움(stretch) (수평)

- align-items: grid 자식의 수직 위치 

- place-items y / x : 수직 수평 한번에 지정

- content는 전체 grid

- align-self : child에만 적용되는 컴포넌트(세로)

- justify-self : 가로

- place-self : 두개 합친거

- grid-auto-rows : 설정한 셀보다 많아질 경우 자동으로 크기 설정

- grid-auto-flow : cloumn자동 생성