# Kubernates_Workshop

Just for practicing with `Minikube`<br>
Note : nginx folder and Mongo_MongoExpress folder are used by `kubectl` command

## Repository structure

1. nginx - Basic nginx setting with namespace **park-test**
2. Mongo_MongoExpress - MongoExpress setup (Not a good practice for using mongoDB container as a database)
3. buildachart - An nginx helm chart
    
    - Run with `helm install park-chart buildachart/ --values buildachart/values.yaml`<br/>
    - Access with `minikube tunnel`
