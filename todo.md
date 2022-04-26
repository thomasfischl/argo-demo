aws eks --region us-east-1 update-kubeconfig --name eks-lula3ydp

helm repo add dt-helm-repo http://10.179.26.53:8080/


curl --data-binary "@applications-0.1.0.tgz" http://10.179.26.53:8080/api/charts