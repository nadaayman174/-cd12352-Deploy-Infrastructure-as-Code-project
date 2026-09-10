# CD12352 - Infrastructure as Code Project Solution
# [Nada Ayman]

## Spin up instructions

To create resources in network stack:

aws cloudformation create-stack \
  --stack-name Network-Stack \
  --template-body file://mynetwork.yml \
  --parameters file://mynetwork-parameters.json \
  --region us-east-1 



## Tear down instructions

To delete the resources without UI interaction:

aws cloudformation delete-stack \
    --stack-name Network-Stack \
    --region us-east-1


## Other considerations
TODO (optional)
