# AzureDatabaseMigrationServices
```text
elements/azure/MigrateServiceColor/AzureDatabaseMigrationServices
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureDatabaseMigrationServices icon](../../../icons/azure/MigrateServiceColor/AzureDatabaseMigrationServices.png) | ![AzureDatabaseMigrationServices element](AzureDatabaseMigrationServices.element.png) | ![AzureDatabaseMigrationServices card](AzureDatabaseMigrationServices.card.png) |
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

' loads the AzureDatabaseMigrationServices element
include('elements/azure/MigrateServiceColor/AzureDatabaseMigrationServices')
AzureDatabaseMigrationServices('element', 'Database Migration Services', 'an optional tech field')
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

' loads the AzureDatabaseMigrationServices element
include('elements/azure/MigrateServiceColor/AzureDatabaseMigrationServices')
AzureDatabaseMigrationServices('element', 'Database Migration Services', 'an optional tech field')
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

' loads the AzureDatabaseMigrationServices card
include('elements/azure/MigrateServiceColor/AzureDatabaseMigrationServices')
AzureDatabaseMigrationServicesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureDatabaseMigrationServices card
include('elements/azure/MigrateServiceColor/AzureDatabaseMigrationServices')
AzureDatabaseMigrationServicesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
