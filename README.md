# K8S-Proxy
K8S Proxy example

We can send a request using the following pattern:
http://localhost:8080/api/v1/namespaces/<NAMESPACE>/services/<SERVICE-NAME> 
  
Let’s create a resource from our dashboard using the proxy_eample.yaml example, and then run:
http://localhost:8080/api/v1/namespaces/default/services/my-internal-service 

Services address can be found here: http://localhost:8080/api/v1/namespaces/default/services 
