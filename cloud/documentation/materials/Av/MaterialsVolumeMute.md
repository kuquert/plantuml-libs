# MaterialsVolumeMute
```text
elements/materials/Av/MaterialsVolumeMute
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsVolumeMute icon](../../../icons/materials/Av/MaterialsVolumeMute.png) | ![MaterialsVolumeMute element](MaterialsVolumeMute.element.png) | ![MaterialsVolumeMute card](MaterialsVolumeMute.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the AWS style
include('styles/aws')

' loads the MaterialsVolumeMute element
include('elements/materials/Av/MaterialsVolumeMute')
MaterialsVolumeMute('element', 'Volume Mute', 'an optional tech field')
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

' loads the AWS style
include('styles/aws')

' loads the MaterialsVolumeMute element
include('elements/materials/Av/MaterialsVolumeMute')
MaterialsVolumeMute('element', 'Volume Mute', 'an optional tech field')
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

' loads the AWS style
include('styles/gcp')

' loads the MaterialsVolumeMute card
include('elements/materials/Av/MaterialsVolumeMute')
MaterialsVolumeMuteCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the GCP style
include('styles/gcp')

' loads the MaterialsVolumeMute card
include('elements/materials/Av/MaterialsVolumeMute')
MaterialsVolumeMuteCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```