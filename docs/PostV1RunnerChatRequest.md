# PostV1RunnerChatRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**messages** | [**List[PostV1RunnerChatRequestMessagesInner]**](PostV1RunnerChatRequestMessagesInner.md) |  | 

## Example

```python
from lthn_api.models.post_v1_runner_chat_request import PostV1RunnerChatRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PostV1RunnerChatRequest from a JSON string
post_v1_runner_chat_request_instance = PostV1RunnerChatRequest.from_json(json)
# print the JSON string representation of the object
print(PostV1RunnerChatRequest.to_json())

# convert the object into a dict
post_v1_runner_chat_request_dict = post_v1_runner_chat_request_instance.to_dict()
# create an instance of PostV1RunnerChatRequest from a dict
post_v1_runner_chat_request_from_dict = PostV1RunnerChatRequest.from_dict(post_v1_runner_chat_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


