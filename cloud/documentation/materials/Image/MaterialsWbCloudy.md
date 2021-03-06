# MaterialsWbCloudy
```text
elements/materials/Image/MaterialsWbCloudy
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsWbCloudy icon](../../../icons/materials/Image/MaterialsWbCloudy.png) | ![MaterialsWbCloudy element](MaterialsWbCloudy.element.png) | ![MaterialsWbCloudy card](MaterialsWbCloudy.card.png) |
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

' loads the MaterialsWbCloudy element
include('elements/materials/Image/MaterialsWbCloudy')
MaterialsWbCloudy('element', 'Wb Cloudy', 'an optional tech field')
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

' loads the MaterialsWbCloudy element
include('elements/materials/Image/MaterialsWbCloudy')
MaterialsWbCloudy('element', 'Wb Cloudy', 'an optional tech field')
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

' loads the MaterialsWbCloudy card
include('elements/materials/Image/MaterialsWbCloudy')
MaterialsWbCloudyCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsWbCloudy card
include('elements/materials/Image/MaterialsWbCloudy')
MaterialsWbCloudyCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
