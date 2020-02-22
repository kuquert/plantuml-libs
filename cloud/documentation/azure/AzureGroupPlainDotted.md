# AzureGroupPlainDotted
| Example | Resource |
| :-: | --- |
| ![AzureGroupPlainDotted group](AzureGroupPlainDotted.group.png) | `groups/azure/AzureGroupPlainDotted` |
## Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the AWS style
include('styles/aws')

' loads the AzureGroupPlainDotted group
include('groups/azure/AzureGroupPlainDotted')
AzureGroupPlainDotted('element', 'Plain Dotted', 'an optional tech field')
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

' loads the AWS style
include('styles/aws')

' loads the AzureGroupPlainDotted group
include('groups/azure/AzureGroupPlainDotted')
AzureGroupPlainDotted('element', 'Plain Dotted', 'an optional tech field')
@enduml
```