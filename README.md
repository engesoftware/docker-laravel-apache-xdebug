# docker-laravel-apache-xdebug

Uma nova imagem do php 7.2, porém, dessa vez incluindo o apache. Preferi criar uma imagem separada pois não utilizo o OS alpine, dessa forma será utilizado apenas por quem precisar especificamente do apache. 

Esta imagem também não contem o OCI e por tanto não deverá ser utilizada para o oracle, usamos apenas com o postgres.

*Atenção*, essa imagem contém o xdebug e portanto deverá ser utilizada apenas em ambiente de desenvolvimento, para rodar testes unitários ou para debugar o código.
