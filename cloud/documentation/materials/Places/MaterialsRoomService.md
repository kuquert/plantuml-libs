# MaterialsRoomService
```text
elements/materials/Places/MaterialsRoomService
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsRoomService icon](../../../icons/materials/Places/MaterialsRoomService.png) | ![MaterialsRoomService element](MaterialsRoomService.element.png) | ![MaterialsRoomService card](MaterialsRoomService.card.png) |
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

' loads the MaterialsRoomService element
include('elements/materials/Places/MaterialsRoomService')
MaterialsRoomService('element', 'Room Service', 'an optional tech field')
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

' loads the MaterialsRoomService element
include('elements/materials/Places/MaterialsRoomService')
MaterialsRoomService('element', 'Room Service', 'an optional tech field')
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

' loads the MaterialsRoomService card
include('elements/materials/Places/MaterialsRoomService')
MaterialsRoomServiceCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsRoomService card
include('elements/materials/Places/MaterialsRoomService')
MaterialsRoomServiceCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
