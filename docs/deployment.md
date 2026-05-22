# Deployment

kubectl apply -f kubernetes/

Verify:

kubectl get pods -n nexoryx-ai
kubectl get svc -n nexoryx-ai
kubectl get ingress -n nexoryx-ai
