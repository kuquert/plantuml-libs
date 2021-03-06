# MaterialsTextsms
```text
elements/materials/Communication/MaterialsTextsms
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsTextsms icon](../../../icons/materials/Communication/MaterialsTextsms.png) | ![MaterialsTextsms element](MaterialsTextsms.element.png) | ![MaterialsTextsms card](MaterialsTextsms.card.png) |
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

' loads the MaterialsTextsms element
include('elements/materials/Communication/MaterialsTextsms')
MaterialsTextsms('element', 'Textsms', 'an optional tech field')
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

' loads the MaterialsTextsms element
include('elements/materials/Communication/MaterialsTextsms')
MaterialsTextsms('element', 'Textsms', 'an optional tech field')
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

' loads the MaterialsTextsms card
include('elements/materials/Communication/MaterialsTextsms')
MaterialsTextsmsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsTextsms card
include('elements/materials/Communication/MaterialsTextsms')
MaterialsTextsmsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
