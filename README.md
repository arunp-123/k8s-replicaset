Create namespace:
# kubectl create namespace my-app

# kubectl apply -f replicaset.yml
View ReplicaSets
# kubectl get rs -n my-app
View Pods created by the ReplicaSet          
# kubectl get pods -n my-app       

Lists all Pods in the my-app namespace and displays the labels assigned to each Pod.

# kubectl get pods -n my-app --show-labels

Lists all the pods in specific name space and displays additional details about the pods. 

# kubectl get pods -n my-app   -o wide

Deleting:

$ kubectl delete -f replicaset.yml
