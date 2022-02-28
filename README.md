![Untitled Diagram-Page-1 drawio (1)](https://user-images.githubusercontent.com/82954458/155980888-bf65d3e7-281e-467a-86da-35181825c467.png)



## VPC

|Tags|VPC ID |IPv4 CIDR |Security groups|
|------|---------|---------|--------|
||vpc-0bdc9a2d7769558ed|172.31.0.0/16 |sg-0e11e68c73779a250 |

|Tags|Subnet resource ID |Route table ID|
|-------|------|-----|
||subnet-030510599251495b3|rtb-08550afac4a0b24de|
||subnet-05b30d765e457eb8f|rtb-08550afac4a0b24de|
||subnet-0e870afeeaf785a57|rtb-08550afac4a0b24de|
||subnet-0efbd77b48761c913|rtb-08550afac4a0b24de|
||subnet-01458218040d3ae86 |rtb-08550afac4a0b24de|
||subnet-0065ca9df131529bb |rtb-08550afac4a0b24de|

# VPC

|Tags|VPC ID |IPv4 CIDR |
|------|---------|---------|
|live-sample-vpc|vpc-0d105626b5933a035|10.10.0.0/16|

## SECURITY GROUPS

|Tags|Security groups| 
|------|---------|  
|live-sample-pritunl|sg-01f47c8b6943a808b | 
|stage-aurora-sg|sg-0219b7b0d5c8cb129|
|stage-sample-efs|sg-02d857584b88a52e5|
|stage-http-https|sg-046913bbd8d5a4ed3|
|stage-sample|sg-068a4f98e51b23904 |
|stage-sample-ssh|sg-07a23650f35256aa6 |
|live-sample-ssh|sg-09a6c793cc2b31333 |
|default|sg-09b78009f3bc90804 |
|live-http-https|sg-0e794452a86a3330e |

## SUBNET 

|Tags|Subnet ID| 
|------|---------| 
|live-sample-subnet-private-us-east-1a|subnet-01068cf8ad487b3e0 |
|live-sample-subnet-public-us-east-1c|subnet-02015386dc243e10a|
|live-sample-subnet-private-us-east-1b|subnet-0baad8304b1f54f02 |
|live-sample-subnet-private-us-east-1c|subnet-0ca156edb893f6ca1 |
|live-sample-subnet-public-us-east-1a	|subnet-0dbb9b74c40e80fff |
|live-sample-subnet-public-us-east-1b|subnet-0fbbda8b6630f75bd|

## ROUTE TABLE 

|Tags|Route Table ID| 
|------|---------| 
|live-sample-subnet-public-us-east-1c-rt|rtb-0ebe7426f913345a4|
|live-sample-subnet-public-us-east-1b-rt|rtb-03e7592c6f80dbd5e
|live-sample-subnet-public-us-east-1b-rt|rtb-07d19542a6263014e|
|live-sample-subnet-public-us-east-1a-rt|rtb-0e2bf5e29d1428f75|
|live-sample-subnet-private-us-east-1a-rt|rtb-0289009ef0a2668db|
|live-sample-subnet-private-us-east-1a-rt|rtb-01ce77e62f2f500db|

## INSTANCE

|Tags |Instance ID|Instance type|Private IPv4 addresses
|------|---------|---------|--------|
|stage-sample-0|i-0c8a6860e438adc2b|t3.small|10.10.12.236|
|live-sample-pritunl-0|i-00debe762c2a2549e|t3.small|10.10.122.166|

## LOAD BALANCER

|Tags |DNS name |ARN |
|------|------|------|
|sample-stage|sample-stage-565259004.us-east-1.elb.amazonaws.com|arn:aws:elasticloadbalancing:us-east-1:274086747439:loadbalancer/app/sample-stage/be483a3d0d440d07|

## RDS 

|DB identifier |Role| Engine| Region & AZ |Size|
|------|---------|---------|--------|--------|
|stage-sample-1 | Writer instance| Aurora MySQL | us-east-1a |db.t3.small |

## Elastic File System

|Tags |File system ID |
|------|---------|
|stage-sample|fs-073e6ab5e4a3acacd|
