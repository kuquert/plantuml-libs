# MaterialsAllOut
```text
elements/materials/Action/MaterialsAllOut
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsAllOut icon](../../../icons/materials/Action/MaterialsAllOut.png) | ![MaterialsAllOut element](MaterialsAllOut.element.png) | ![MaterialsAllOut card](MaterialsAllOut.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsAllOut element
include('elements/materials/Action/MaterialsAllOut')
MaterialsAllOut('element', 'All Out', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsAllOut element
include('elements/materials/Action/MaterialsAllOut')
MaterialsAllOut('element', 'All Out', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsAllOut card
include('elements/materials/Action/MaterialsAllOut')
MaterialsAllOutCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsAllOut card
include('elements/materials/Action/MaterialsAllOut')
MaterialsAllOutCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
