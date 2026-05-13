# GetV1RunnerModels200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**GetV1RunnerModels200ResponseData**](GetV1RunnerModels200ResponseData.md) |  | [optional] 
**error** | [**Error**](Error.md) |  | [optional] 
**meta** | [**Meta**](Meta.md) |  | [optional] 
**success** | **bool** |  | 

## Example

```python
from lthn_api.models.get_v1_runner_models200_response import GetV1RunnerModels200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetV1RunnerModels200Response from a JSON string
get_v1_runner_models200_response_instance = GetV1RunnerModels200Response.from_json(json)
# print the JSON string representation of the object
print(GetV1RunnerModels200Response.to_json())

# convert the object into a dict
get_v1_runner_models200_response_dict = get_v1_runner_models200_response_instance.to_dict()
# create an instance of GetV1RunnerModels200Response from a dict
get_v1_runner_models200_response_from_dict = GetV1RunnerModels200Response.from_dict(get_v1_runner_models200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


