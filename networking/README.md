# Networking

Creates the base AWS Networking resources.

## AWS Resources

![networking](https://user-images.githubusercontent.com/26026175/206866760-80ee4c09-6e7c-4d06-bde7-5d5d03115b79.png)

- [VPC](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-vpc.html)
- [Subnet](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-subnet.html)

## Inputs

| Name    | Description                            |  Type  | Default |      Required      |
| :------ | :------------------------------------- | :----: | :-----: | :----------------: |
| VPCName | VPC Name | String |    -    | :heavy_check_mark: |
| ProjectTagValue | Tag: Project Name | String |    -    | :heavy_check_mark: |
