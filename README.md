# CD12352 - Infrastructure as Code Project Solution
# Nikolaos Takos

## Spin up instructions
./create.sh udagram-Network network.yml network-parameters.json aws-user-profile
./create.sh udagram-Servers udagram.yml udagram-parameters.json aws-user-profile

## Tear down instructions
./delete.sh udagram-Network
./delete.sh udagram-Servers

## Update instructions
./update.sh udagram-Network network.yml network-parameters.json aws-user-profile
./update.sh udagram-Servers servers.yml server-parameters.json aws-user-profile

## Other comments
Used us-east-1 region.
