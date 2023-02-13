

Criar imagem 
docker build . -t elias/app


#Como nao definimos a porta no nginx por padrao ele pega a 80
 Subir 
 docker run -p 8080:80 -d elias/app