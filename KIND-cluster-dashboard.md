https://istio.io/latest/docs/setup/platform-setup/kind/



http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/#/pod?namespace=default


token=$(kubectl -n kubernetes-dashboard create token admin-user)

echo $token

