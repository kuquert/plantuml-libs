# AzureGroupDashed
| Example | Resource |
| :-: | --- |
| ![AzureGroupDashed group](AzureGroupDashed.group.png) | `groups/azure/AzureGroupDashed` |
## Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/azure')

' loads the AzureGroupDashed group
include('groups/azure/AzureGroupDashed')
AzureGroupDashed('element', 'Dashed', 'an optional tech field')
@enduml
```
## Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../"

' loads the library
!include ../../library.puml

' loads the style
include('styles/azure')

' loads the AzureGroupDashed group
include('groups/azure/AzureGroupDashed')
AzureGroupDashed('element', 'Dashed', 'an optional tech field')
@enduml
```
