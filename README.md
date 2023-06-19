# multinode-kraft-docker
A quick docker-compose that spins up a KRaft cluster with multiple nodes and controllers in isolated mode

To use:

`wget https://raw.githubusercontent.com/nhaq-confluent/multinode-kraft-docker/main/docker-compose.yml`

Then
`docker-compose up -d`

You should then be able to shutdown individual KRaft controllers and see the KRaft quorum leader change. 
