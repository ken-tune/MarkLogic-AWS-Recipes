# MarkLogic AWS Recipes

The purpose of this project is to put together a number of recipes for tasks related to deploying MarkLogic in AWS.

## Recipe 1 - MarkLogic Cluster in a VPC  

This first recipe concerns deployment of MarkLogic to a Virtual Private Cloud (VPC). The recipe consists of a [Cloud Formation Template](https://aws.amazon.com/cloudformation/) for creating a VPC, and a second template allowing deployment of a MarkLogic cluster into that VPC. The templates may be found at [example-1/MarkLogic-Sample-VPC-1.json](example-1/MarkLogic-Sample-VPC-1.json) and [example-1/ThreePlusClusterForVPC-1.json](example-1/ThreePlusClusterForVPC-1.json) respectively. There is also a [pdf document](http://ken-tune.github.io/MarkLogic-AWS-Recipes/docs/VPCMarkLogicClusterSetup-1.pdf),including screenshots, which discusses the templates, the assets they create and the execution process in more detail.


