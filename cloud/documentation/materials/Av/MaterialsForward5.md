# MaterialsForward5
```text
elements/materials/Av/MaterialsForward5
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsForward5 icon](../../../icons/materials/Av/MaterialsForward5.png) | ![MaterialsForward5 element](MaterialsForward5.element.png) | ![MaterialsForward5 card](MaterialsForward5.card.png) |
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

' loads the MaterialsForward5 element
include('elements/materials/Av/MaterialsForward5')
MaterialsForward5('element', 'Forward5', 'an optional tech field')
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

' loads the MaterialsForward5 element
include('elements/materials/Av/MaterialsForward5')
MaterialsForward5('element', 'Forward5', 'an optional tech field')
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

' loads the MaterialsForward5 card
include('elements/materials/Av/MaterialsForward5')
MaterialsForward5Card('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsForward5 card
include('elements/materials/Av/MaterialsForward5')
MaterialsForward5Card('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
