# AwsIotUtility
```text
elements/aws/InternetOfThings/AwsIotUtility
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsIotUtility icon](../../../icons/aws/InternetOfThings/AwsIotUtility.png) | ![AwsIotUtility element](AwsIotUtility.element.png) | ![AwsIotUtility card](AwsIotUtility.card.png) |
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
include('styles/aws')

' loads the AwsIotUtility element
include('elements/aws/InternetOfThings/AwsIotUtility')
AwsIotUtility('element', 'Iot Utility', 'an optional tech field')
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
include('styles/aws')

' loads the AwsIotUtility element
include('elements/aws/InternetOfThings/AwsIotUtility')
AwsIotUtility('element', 'Iot Utility', 'an optional tech field')
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
include('styles/aws')

' loads the AwsIotUtility card
include('elements/aws/InternetOfThings/AwsIotUtility')
AwsIotUtilityCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/aws')

' loads the AwsIotUtility card
include('elements/aws/InternetOfThings/AwsIotUtility')
AwsIotUtilityCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
