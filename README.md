# My Helm Chart

helm repo add helm-repo-pub https://github.com/ohsaeu/helm-repo-pub.git
helm repo list
helm repo update
helm search repo mynginx
helm install webserver helm-repo-pub/mynginx
