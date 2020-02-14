# MySQL com Docker 

O diretório sql-script serve para subir migrations ao banco mysql 


O DockerFile adiciona os arquivos na pasta docker-entrypoint-initdb.d. Tudo que estiver la dentro sera executado

COPY ./sql-scripts/ /docker-entrypoint-initdb.d/



 
