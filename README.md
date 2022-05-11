# adguard running on kubernetes with ingress and certificates

Pre-requisities are cert-manager installed with nginx-ingress-controller.

- kubectl apply -f adguard.yaml
- kubectl apply -f adguard-ingress.yaml

- Run the getcert.sh script to "download" fullchain and privatekey files and place them in mountPath: /cert
(check manfiest file adguard.yaml)
