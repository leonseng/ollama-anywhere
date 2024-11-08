# Ollama Anywhere Anytime

Enable developers securely access to Ollama, whether they have access to the enterprise GPU cluster, or are on the road with just their laptops.


Create CSG and configure it with files in the [nginx](./nginx) directory on NGINX One Console

```
cp example.env .env
```

Update values in `.env`

```
mkdir nginx/ssl
```

Create server cert key pair for
- ollama-proxy.local
- ollama.localhost
- openwebui.localhost

```
docker compose up -d
```