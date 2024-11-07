# CD12352 - Infrastructure as Code Project Solution
# Nikolaos Takos

## Spin up instructions
./create.sh udagram-Network network.yml network-parameters.json aws-user-profile
./create.sh udagram-Server udagram.yml udagram-parameters.json aws-user-profile

## Tear down instructions
./delete.sh udagram-Network
./delete.sh udagram-Server

## Update instructions
./update.sh udagram-Network network.yml network-parameters.json aws-user-profile
./update.sh udagram-Server udagram.yml udagram-parameters.json aws-user-profile


## URL
http://udagra-webap-pkdjagln0fee-1159133205.us-east-1.elb.amazonaws.com/

