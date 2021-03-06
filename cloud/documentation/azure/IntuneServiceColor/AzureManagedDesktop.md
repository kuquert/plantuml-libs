# AzureManagedDesktop
```text
elements/azure/IntuneServiceColor/AzureManagedDesktop
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureManagedDesktop icon](../../../icons/azure/IntuneServiceColor/AzureManagedDesktop.png) | ![AzureManagedDesktop element](AzureManagedDesktop.element.png) | ![AzureManagedDesktop card](AzureManagedDesktop.card.png) |
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
include('styles/azure')

' loads the AzureManagedDesktop element
include('elements/azure/IntuneServiceColor/AzureManagedDesktop')
AzureManagedDesktop('element', 'Managed Desktop', 'an optional tech field')
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
include('styles/azure')

' loads the AzureManagedDesktop element
include('elements/azure/IntuneServiceColor/AzureManagedDesktop')
AzureManagedDesktop('element', 'Managed Desktop', 'an optional tech field')
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
include('styles/azure')

' loads the AzureManagedDesktop card
include('elements/azure/IntuneServiceColor/AzureManagedDesktop')
AzureManagedDesktopCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/azure')

' loads the AzureManagedDesktop card
include('elements/azure/IntuneServiceColor/AzureManagedDesktop')
AzureManagedDesktopCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
