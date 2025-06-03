# Prototype Pollution Scan Report for https://blog.hubspot.com

## Finding 1
**Method**: GET
**Score**: `2`
**Risk Level**: `Low`
**Tested URL**: `https://blog.hubspot.com?constructor={"prototype": {"polluted": 1}}`
**Reflected**: `True` (constructor)
**DOM Mutation**: `False`
**Response Diff**: `results/response_diff_get_1.diff`

