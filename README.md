# cfn-example

## Overview

1. Network
   1. network.yaml
   2. security-group.yaml
   3. acm.yaml
   4. custom-header.yaml
   5. alb.yaml
2. DB
   1. aurora.yaml
3. ECS
   1. ecr.yaml
   2. iam-role.yaml
   3. log-group.yaml
   4. parameters.yaml
   5. task-def.yaml
   6. cluster.yaml
   7. service.yaml
   8. autoscaling.yaml

## ECR Image

ECR Image needs to expose the endpoint `/v1/health` and port `8088` for health check from ALB.

## Diagram

![image](https://user-images.githubusercontent.com/26246951/106484918-6e94ad00-64f3-11eb-84bf-8bb83dc65c55.png)

## TODO

- [ ] CloudFront
- [ ] ElastiCache
- [ ] DynamoDB
- [ ] CodeDeploy
