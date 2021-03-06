# MaterialsDoNotDisturbOn
```text
elements/materials/Notification/MaterialsDoNotDisturbOn
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsDoNotDisturbOn icon](../../../icons/materials/Notification/MaterialsDoNotDisturbOn.png) | ![MaterialsDoNotDisturbOn element](MaterialsDoNotDisturbOn.element.png) | ![MaterialsDoNotDisturbOn card](MaterialsDoNotDisturbOn.card.png) |
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

' loads the MaterialsDoNotDisturbOn element
include('elements/materials/Notification/MaterialsDoNotDisturbOn')
MaterialsDoNotDisturbOn('element', 'Do Not Disturb On', 'an optional tech field')
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

' loads the MaterialsDoNotDisturbOn element
include('elements/materials/Notification/MaterialsDoNotDisturbOn')
MaterialsDoNotDisturbOn('element', 'Do Not Disturb On', 'an optional tech field')
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

' loads the MaterialsDoNotDisturbOn card
include('elements/materials/Notification/MaterialsDoNotDisturbOn')
MaterialsDoNotDisturbOnCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsDoNotDisturbOn card
include('elements/materials/Notification/MaterialsDoNotDisturbOn')
MaterialsDoNotDisturbOnCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
