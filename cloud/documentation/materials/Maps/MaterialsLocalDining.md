# MaterialsLocalDining
```text
elements/materials/Maps/MaterialsLocalDining
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsLocalDining icon](../../../icons/materials/Maps/MaterialsLocalDining.png) | ![MaterialsLocalDining element](MaterialsLocalDining.element.png) | ![MaterialsLocalDining card](MaterialsLocalDining.card.png) |
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

' loads the MaterialsLocalDining element
include('elements/materials/Maps/MaterialsLocalDining')
MaterialsLocalDining('element', 'Local Dining', 'an optional tech field')
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

' loads the MaterialsLocalDining element
include('elements/materials/Maps/MaterialsLocalDining')
MaterialsLocalDining('element', 'Local Dining', 'an optional tech field')
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

' loads the MaterialsLocalDining card
include('elements/materials/Maps/MaterialsLocalDining')
MaterialsLocalDiningCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsLocalDining card
include('elements/materials/Maps/MaterialsLocalDining')
MaterialsLocalDiningCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
