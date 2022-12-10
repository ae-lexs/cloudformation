# Networking

Creates the base AWS Networking resources.

## AWS Resources

- [VPC](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-vpc.html)
- [Subnet](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-subnet.html)

## Inputs

| Name    | Description                            |  Type  | Default |      Required      |
| :------ | :------------------------------------- | :----: | :-----: | :----------------: |
| VPCName | VPC Name | String |    -    | :heavy_check_mark: |
| ProjectTagValue | Tag: Project Name | String |    -    | :heavy_check_mark: |
