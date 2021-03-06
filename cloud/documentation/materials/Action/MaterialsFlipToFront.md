# MaterialsFlipToFront
```text
elements/materials/Action/MaterialsFlipToFront
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsFlipToFront icon](../../../icons/materials/Action/MaterialsFlipToFront.png) | ![MaterialsFlipToFront element](MaterialsFlipToFront.element.png) | ![MaterialsFlipToFront card](MaterialsFlipToFront.card.png) |
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

' loads the MaterialsFlipToFront element
include('elements/materials/Action/MaterialsFlipToFront')
MaterialsFlipToFront('element', 'Flip To Front', 'an optional tech field')
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

' loads the MaterialsFlipToFront element
include('elements/materials/Action/MaterialsFlipToFront')
MaterialsFlipToFront('element', 'Flip To Front', 'an optional tech field')
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

' loads the MaterialsFlipToFront card
include('elements/materials/Action/MaterialsFlipToFront')
MaterialsFlipToFrontCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsFlipToFront card
include('elements/materials/Action/MaterialsFlipToFront')
MaterialsFlipToFrontCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
