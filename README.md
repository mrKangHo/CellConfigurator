# CellConfigurator

UITableView, UIcollectionView에서 Cell을 사용할때
여러 타입의 Cell을 사용하게 된다면 cellForRowAt, cellForItemAt 에서의 분기 처리가 늘어난다
해당 부분의 코드의 양을 줄이기 위해 프로토콜을 작성하였다.



출처 :
https://sangheon0724.medium.com/generic-protocol을-활용한-리팩토링-feat-omos-236c428a7100