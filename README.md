Steps to Reproduce 

1. set the secret
  ```export secret_token=1223```
2. Run the docker compose
  ```docker compose up --buil```
3. Check the secret file in container
  In New terminal ```docker compose exec -it web sh``` and ```cat ~/.secret```
