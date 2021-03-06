# MaterialsFolderShared
```text
elements/materials/File/MaterialsFolderShared
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsFolderShared icon](../../../icons/materials/File/MaterialsFolderShared.png) | ![MaterialsFolderShared element](MaterialsFolderShared.element.png) | ![MaterialsFolderShared card](MaterialsFolderShared.card.png) |
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

' loads the MaterialsFolderShared element
include('elements/materials/File/MaterialsFolderShared')
MaterialsFolderShared('element', 'Folder Shared', 'an optional tech field')
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

' loads the MaterialsFolderShared element
include('elements/materials/File/MaterialsFolderShared')
MaterialsFolderShared('element', 'Folder Shared', 'an optional tech field')
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

' loads the MaterialsFolderShared card
include('elements/materials/File/MaterialsFolderShared')
MaterialsFolderSharedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsFolderShared card
include('elements/materials/File/MaterialsFolderShared')
MaterialsFolderSharedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
