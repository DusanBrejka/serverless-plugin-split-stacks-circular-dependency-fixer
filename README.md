# serverless-plugin-split-stacks-circular-dependency-fixer
This plugin fixes circular dependencies created in complex projects by serverless-plugin-split-stacks.

## Fixes issue:
`
The CloudFormation template is invalid: Circular dependency between resources: 
[ApiGatewayUsagePlanKey2, ApiGatewayUsagePlanKey1, WebrtcNestedStack, ApiGatewayDeployment1528886435994, ApiGatewayUsagePlan, pathmapping, RequestWebrtcServerPingModel, ModelNestedStack, ApiGatewayApiKey2, ApiGatewayApiKey1]
`
