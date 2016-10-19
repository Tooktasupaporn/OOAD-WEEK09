![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU9ApaaiBbOeBYbDISqhKQZcKb3GzdJHqEIgXKb1IB14HcOAK9LlQab6VWf42HUNGsfU2j0W0000)

@startuml

class student {
  +ID()
}

class class {
  +hiddenMethod()
}

@enduml

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEpoqeBKajKj3IrLN8pS_BBCalud98pKi1IG80)

@startuml
computer *-- monitor
@enduml

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU8gpWMo2ZBoyr8LydLr5JBpIbAByb9B5AmK4jFJYrBJ4qioy_EukBWSKlDIW1e0)

@startuml

smartphone o-- internet : aggregation

@enduml

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLd3EpoqeBKajuk8gBKujKj252oXOAG155Eouu09QkWhPgPL9-KM9AK39ZCIoL0L3P7bTNOM0rABY_3oWh8r2VdbUCHUNGsfU2j0o0000)

@startuml
class Computer

user - Computer : use >
Computer *- keyborad : have 1 >
Computer -- Person : < owns

@enduml

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUBopSzLK39KKj3IrLLGoatCgrHII4fCgbImKaZEpoj9pCmhvkBYSaZDIm6g1W00)

@startuml

Mom "1" *-- "many" baby : contains


@enduml
