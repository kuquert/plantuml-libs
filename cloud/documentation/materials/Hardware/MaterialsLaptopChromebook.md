# MaterialsLaptopChromebook
```text
elements/materials/Hardware/MaterialsLaptopChromebook
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsLaptopChromebook icon](../../../icons/materials/Hardware/MaterialsLaptopChromebook.png) | ![MaterialsLaptopChromebook element](MaterialsLaptopChromebook.element.png) | ![MaterialsLaptopChromebook card](MaterialsLaptopChromebook.card.png) |
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

' loads the MaterialsLaptopChromebook element
include('elements/materials/Hardware/MaterialsLaptopChromebook')
MaterialsLaptopChromebook('element', 'Laptop Chromebook', 'an optional tech field')
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

' loads the MaterialsLaptopChromebook element
include('elements/materials/Hardware/MaterialsLaptopChromebook')
MaterialsLaptopChromebook('element', 'Laptop Chromebook', 'an optional tech field')
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

' loads the MaterialsLaptopChromebook card
include('elements/materials/Hardware/MaterialsLaptopChromebook')
MaterialsLaptopChromebookCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsLaptopChromebook card
include('elements/materials/Hardware/MaterialsLaptopChromebook')
MaterialsLaptopChromebookCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
