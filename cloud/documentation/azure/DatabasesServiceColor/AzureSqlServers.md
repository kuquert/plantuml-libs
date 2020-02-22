# AzureSqlServers
```text
elements/azure/DatabasesServiceColor/AzureSqlServers
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureSqlServers icon](../../../icons/azure/DatabasesServiceColor/AzureSqlServers.png) | ![AzureSqlServers element](AzureSqlServers.element.png) | ![AzureSqlServers card](AzureSqlServers.card.png) |
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

' loads the AzureSqlServers element
include('elements/azure/DatabasesServiceColor/AzureSqlServers')
AzureSqlServers('element', 'Sql Servers', 'an optional tech field')
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

' loads the AzureSqlServers element
include('elements/azure/DatabasesServiceColor/AzureSqlServers')
AzureSqlServers('element', 'Sql Servers', 'an optional tech field')
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

' loads the AzureSqlServers card
include('elements/azure/DatabasesServiceColor/AzureSqlServers')
AzureSqlServersCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureSqlServers card
include('elements/azure/DatabasesServiceColor/AzureSqlServers')
AzureSqlServersCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```