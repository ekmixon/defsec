
### SAM API stages for V1 and V2 should have access logging enabled

API Gateway stages should have access log settings block configured to track all access to a particular stage. This should be applied to both v1 and v2 gateway stages.

### Impact
Logging provides vital information about access and usage

<!-- DO NOT CHANGE -->
{{ remediationActions }}

### Links
- https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-resource-api.html#sam-api-accesslogsetting
        