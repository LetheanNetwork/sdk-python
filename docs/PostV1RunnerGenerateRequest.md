# PostV1RunnerGenerateRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prompt** | **str** |  | 

## Example

```python
from lthn_api.models.post_v1_runner_generate_request import PostV1RunnerGenerateRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PostV1RunnerGenerateRequest from a JSON string
post_v1_runner_generate_request_instance = PostV1RunnerGenerateRequest.from_json(json)
# print the JSON string representation of the object
print(PostV1RunnerGenerateRequest.to_json())

# convert the object into a dict
post_v1_runner_generate_request_dict = post_v1_runner_generate_request_instance.to_dict()
# create an instance of PostV1RunnerGenerateRequest from a dict
post_v1_runner_generate_request_from_dict = PostV1RunnerGenerateRequest.from_dict(post_v1_runner_generate_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


