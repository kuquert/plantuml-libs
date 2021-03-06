# AzureFirewall
```text
elements/azure/NetworkingServiceColor/AzureFirewall
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureFirewall icon](../../../icons/azure/NetworkingServiceColor/AzureFirewall.png) | ![AzureFirewall element](AzureFirewall.element.png) | ![AzureFirewall card](AzureFirewall.card.png) |
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

' loads the AzureFirewall element
include('elements/azure/NetworkingServiceColor/AzureFirewall')
AzureFirewall('element', 'Firewall', 'an optional tech field')
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

' loads the AzureFirewall element
include('elements/azure/NetworkingServiceColor/AzureFirewall')
AzureFirewall('element', 'Firewall', 'an optional tech field')
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

' loads the AzureFirewall card
include('elements/azure/NetworkingServiceColor/AzureFirewall')
AzureFirewallCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureFirewall card
include('elements/azure/NetworkingServiceColor/AzureFirewall')
AzureFirewallCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
