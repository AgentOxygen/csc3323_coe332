#Part A:
     1. The yaml file is "partA-pod.yml" and the command used was `kubectl -f apply partA-pod.yml`
<br>
     2. Using the command `kubectl get pods --selector "greeting"` outputs the following
     > NAME    READY   STATUS    RESTARTS   AGE
     > hello   1/1     Running   0          5m10s
<br>
     3. Using the commande `kubectl logs hello` returns the output `Hello, Cameron!`
<br>
     4. I deleted the pod using `kubectl delete pods hello`

#Part B:

     