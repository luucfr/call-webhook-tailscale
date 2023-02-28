# call-webhook-tailscale

#### Remplacer le fichier script avec vos identifiants
#### Exemple:
```
docker-compose up -d
docker exec call-webhook-tailscale_tailscale_1 tailscale up --accept-routes --authkey VOTRE_KEY_TAILSCALE
docker exec call-webhook-tailscale_curl_1 curl -X POST --insecure https://votre-url-webhook.com/...
docker-compose down
```
