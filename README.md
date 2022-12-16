Apply every config file in the k8s directory:

`kubectl apply -f k8s`

`kubectl create secret generic pgpassword --from-literal PGPASSWORD=<my_password>`

Ingress nginx link: https://kubernetes.github.io/ingress-nginx/
