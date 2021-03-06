# AzureFreeServices
```text
elements/azure/ManagementAndGovernanceServiceColor/AzureFreeServices
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureFreeServices icon](../../../icons/azure/ManagementAndGovernanceServiceColor/AzureFreeServices.png) | ![AzureFreeServices element](AzureFreeServices.element.png) | ![AzureFreeServices card](AzureFreeServices.card.png) |
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

' loads the AzureFreeServices element
include('elements/azure/ManagementAndGovernanceServiceColor/AzureFreeServices')
AzureFreeServices('element', 'Free Services', 'an optional tech field')
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

' loads the AzureFreeServices element
include('elements/azure/ManagementAndGovernanceServiceColor/AzureFreeServices')
AzureFreeServices('element', 'Free Services', 'an optional tech field')
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

' loads the AzureFreeServices card
include('elements/azure/ManagementAndGovernanceServiceColor/AzureFreeServices')
AzureFreeServicesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureFreeServices card
include('elements/azure/ManagementAndGovernanceServiceColor/AzureFreeServices')
AzureFreeServicesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
