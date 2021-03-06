# MaterialsDriveEta
```text
elements/materials/Notification/MaterialsDriveEta
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsDriveEta icon](../../../icons/materials/Notification/MaterialsDriveEta.png) | ![MaterialsDriveEta element](MaterialsDriveEta.element.png) | ![MaterialsDriveEta card](MaterialsDriveEta.card.png) |
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

' loads the MaterialsDriveEta element
include('elements/materials/Notification/MaterialsDriveEta')
MaterialsDriveEta('element', 'Drive Eta', 'an optional tech field')
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

' loads the MaterialsDriveEta element
include('elements/materials/Notification/MaterialsDriveEta')
MaterialsDriveEta('element', 'Drive Eta', 'an optional tech field')
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

' loads the MaterialsDriveEta card
include('elements/materials/Notification/MaterialsDriveEta')
MaterialsDriveEtaCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsDriveEta card
include('elements/materials/Notification/MaterialsDriveEta')
MaterialsDriveEtaCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
