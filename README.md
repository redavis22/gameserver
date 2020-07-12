# gameserver

  1  ls
    2  cat README-cloudshell.txt
    3  kubectl get all
    4  gcloud container clusters get-credentials my-first-cluster-1 --zone us-central1-c --project frdmcdrs
    5  kubectl get all
    6  kubectl create clusterrolebinding cluster-admin-binding   --clusterrole=cluster-admin --serviceaccount=kube-system:default
    7  helm repo add agones https://agones.dev/chart/stable
    8  helm install --name my-agones --namespace agones-system agones/agones
    9  kubectl get --namespace agones-system pods
   10  helm install  --namespace agones-system agones/agones
   11  helm install  --namespace agones-system agones/agones --generate-name
   12  helm install
   13  $ helm install my-release --namespace agones-system --create-namespace agones/agones
   14  helm install my-release --namespace agones-system --create-namespace agones/agones
   15  kubectl get --namespace agones-system pods
   16  kubectl describe --namespace agones-system pods
   17  kubectl create -f https://raw.githubusercontent.com/GoogleCloudPlatform/agones/release-0.9.0/examples/xonotic/gameserver.yaml
   18  kubectl get gameserver
   19  $ helm install my-release --namespace agones-system --create-namespace agones/agones
   20  helm install my-agnoes --namespace agones-system --create-namespace agones/agones
   21  helm repo add agones https://agones.dev/chart/stable
   22  helm install my-agones --namespace agones-system --create-namespace agones/agones
   23  kubectl create clusterrolebinding cluster-admin-binding   --clusterrole=cluster-admin --serviceaccount=kube-system:default
   24  kubectl create clusterrolebinding cluster-admin-binding   --clusterrole=cluster-admin --serviceaccount=kube-system:default
   25  kubectl get all
   26  ping 35.223.236.110
   27  ping google.com
   28  ping 35.223.236.110
   29  kubectl create clusterrolebinding cluster-admin-binding   --clusterrole=cluster-admin --serviceaccount=kube-system:default
   30  kubectl
   31  kubectl create clusterrolebinding cluster-admin-binding   --clusterrole=cluster-admin --serviceaccount=kube-system:default
   32  gcloud container clusters get-credentials my-first-cluster-1 --zone us-east1-b --project threadz-gaming
   33  kubectl create clusterrolebinding cluster-admin-binding   --clusterrole=cluster-admin --serviceaccount=kube-system:default
   34  helm repo add agones https://agones.dev/chart/stable
   35  helm install my-agones --namespace agones-system --create-namespace agones/agones
   36  helm install --name my-agones --namespace agones-system agones/agones
   37  kubectl get --namespace agones-system pods
   38  kubectl describe --namespace agones-system pods
   39  kubectl create -f https://raw.githubusercontent.com/GoogleCloudPlatform/agones/release-0.9.0/examples/xonotic/gameserver.yaml
   40  kubectl create -f https://raw.githubusercontent.com/googleforgames/agones/master/examples/xonotic/gameserver.yaml
   41  kubectl get gameserver
   42  kubectl get all
   43  history
