# GetHealth429Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**error** | [**Error**](Error.md) |  | [optional] 
**meta** | [**Meta**](Meta.md) |  | [optional] 
**success** | **bool** |  | 

## Example

```python
from lthn_api.models.get_health429_response import GetHealth429Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetHealth429Response from a JSON string
get_health429_response_instance = GetHealth429Response.from_json(json)
# print the JSON string representation of the object
print(GetHealth429Response.to_json())

# convert the object into a dict
get_health429_response_dict = get_health429_response_instance.to_dict()
# create an instance of GetHealth429Response from a dict
get_health429_response_from_dict = GetHealth429Response.from_dict(get_health429_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


