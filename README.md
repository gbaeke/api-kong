# api-kong
Toy API with Kong Ingress Controller

When you want to use this example:
- replace API key in cred.yaml
- replace cert and auth in tls-wild-secret.yml with base64 encoded cert and key

Idea is to have two clusters, one in West-Europe and one in North Europe. Deploy all we files to West Europe with **kubectl apply -f .** and same for ne

Check out https://blog.baeke.info/?p=1532 for more info.
