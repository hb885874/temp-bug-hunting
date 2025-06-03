# Prototype Pollution Scan Report for https://connect.hubspot.com

## Finding 1
**Method**: GET
**Tested URL**: `https://connect.hubspot.com?constructor={"prototype": {"polluted": 1}}`
**Reflected**: `True` (constructor)
**DOM Mutation**: `False`


## Finding 2
**Method**: POST
**Tested URL**: `https://connect.hubspot.com`
**Payload**: `{"constructor": {"prototype": {"polluted": 1}}}`
**Reflected**: `True` (constructor)
**DOM Mutation**: `False`

