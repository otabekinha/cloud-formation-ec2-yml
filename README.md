# cloud-formation-ec2-yml

## Code

```
---
Resources:
  MyInstance:
  Type: AWS::EC2::Instance
  Properties:
    AvailabilityZone: us-east-1a
    ImageId: ami-a4c7edb2
    InstanceType: t2.micro 
```
