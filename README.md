# amholdings/docker-oracle-jdk8
Docker OracleJDK 1.8 (Java SE Development Kit 8u60)

# Build Container:  
git clone https://github.com/amholdings/docker-oracle-jdk8.git

cd docker-oracle-jdk8

docker build --tag="docker-oracle-jdk8" .

# Run Container: 
docker run -it --rm  --name "docker-oracle-jdk8" amholdings/docker-oracle-jdk8
