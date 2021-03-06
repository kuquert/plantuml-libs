# AzureWebAppFirewall
```text
elements/azure/OtherCategoryServiceIcon/AzureWebAppFirewall
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureWebAppFirewall icon](../../../icons/azure/OtherCategoryServiceIcon/AzureWebAppFirewall.png) | ![AzureWebAppFirewall element](AzureWebAppFirewall.element.png) | ![AzureWebAppFirewall card](AzureWebAppFirewall.card.png) |
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

' loads the AzureWebAppFirewall element
include('elements/azure/OtherCategoryServiceIcon/AzureWebAppFirewall')
AzureWebAppFirewall('element', 'Web App Firewall', 'an optional tech field')
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

' loads the AzureWebAppFirewall element
include('elements/azure/OtherCategoryServiceIcon/AzureWebAppFirewall')
AzureWebAppFirewall('element', 'Web App Firewall', 'an optional tech field')
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

' loads the AzureWebAppFirewall card
include('elements/azure/OtherCategoryServiceIcon/AzureWebAppFirewall')
AzureWebAppFirewallCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureWebAppFirewall card
include('elements/azure/OtherCategoryServiceIcon/AzureWebAppFirewall')
AzureWebAppFirewallCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
