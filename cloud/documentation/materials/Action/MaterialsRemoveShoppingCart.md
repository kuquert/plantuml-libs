# MaterialsRemoveShoppingCart
```text
elements/materials/Action/MaterialsRemoveShoppingCart
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsRemoveShoppingCart icon](../../../icons/materials/Action/MaterialsRemoveShoppingCart.png) | ![MaterialsRemoveShoppingCart element](MaterialsRemoveShoppingCart.element.png) | ![MaterialsRemoveShoppingCart card](MaterialsRemoveShoppingCart.card.png) |
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

' loads the MaterialsRemoveShoppingCart element
include('elements/materials/Action/MaterialsRemoveShoppingCart')
MaterialsRemoveShoppingCart('element', 'Remove Shopping Cart', 'an optional tech field')
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

' loads the MaterialsRemoveShoppingCart element
include('elements/materials/Action/MaterialsRemoveShoppingCart')
MaterialsRemoveShoppingCart('element', 'Remove Shopping Cart', 'an optional tech field')
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

' loads the MaterialsRemoveShoppingCart card
include('elements/materials/Action/MaterialsRemoveShoppingCart')
MaterialsRemoveShoppingCartCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsRemoveShoppingCart card
include('elements/materials/Action/MaterialsRemoveShoppingCart')
MaterialsRemoveShoppingCartCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
