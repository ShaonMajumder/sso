# Keycloak
 
 - Run keycloak with docker
 ```bash
 sudo docker run -p 3001:3001 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin -e KEYCLOAK_FRONTEND_URL=http://127.0.0.1:3001 quay.io/keycloak/keycloak:22.0.1 start-dev --http-port=3001
 ```

- then visit to http://127.0.0.1:3001