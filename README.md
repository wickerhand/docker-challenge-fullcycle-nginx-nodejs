# Docker challenge - Nginx with Nodejs

O desafio consistia em:
- praticar a utilização do nginx como proxy reverso. 
- Ao usuário fazer uma request GET no endereço `http://localhost:8080` (Container Nginx) o Nginx irá direcionar a chamada para o container da aplicação NodeJS
- A aplicação node deverá fazer registros de nomes na tabela people do mySQL
- Ao acessarmos o endereço `http://localhost:8080` a aplicação deverá retornar `<h1>Full Cycle Rocks!</h1>` e a lista com os nomes registrados no banco de dados mySQL

Para subir o container, navegue no seu terminal até o caminho que se encontra a raiz do projeto ex: `/Users/seuusuario/Curso-FullCycle/nginx-nodejs-challenge`

Rode o comando: `docker-compose up -d`

Após os containers serem montados, no seu navegador acesse o link: [http://localhost:8080]