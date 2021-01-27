# Docker e Node:
 Testando as funções do Docker.
 Para instalar a imagem do programa entre no *PowerShell* e use o comando:
 
 ```sh
 docker push kmuv1t/node
 ```
 
 depois disso use o comando:
 
 ```sh
 docker run -d -p 8080:3000 kmuv1t/node
 ```

 E por último para testar, acesse o navegador e insira:
 
 ```sh
 localhost:8080
  ```
  
 Caso não tenha o Docker instalado, use este link:
 https://www.docker.com/products/docker-desktop
