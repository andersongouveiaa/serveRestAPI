# Bootcamp Qualiters club
Teste de API rest do manual a CI/CD serveRestAPI

## O que é
Repositório criado para o bootcamp de Testes de API Rest.

## Tecnologias utilizadas
- postman
- node version v20.9.0
- Newman v6.2.1
- Newman-reporter-html

## Documentação

- Doc da API: [Consulte Swagger](https://serverest.dev/)


## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Segundo: Realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: Realize a instalação das dependência dos relatórios (Opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
```
 npm install -g newman-reporter-html
```

## Como rodar os testes

### Pelo Postman web ou desktop
- Importe a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo newman
- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
  ```
   newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
  ```

-Execute os testes com relatório
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```

### Report

Se você optar por rodar os testes com o report html extra, você vai gerar um arquivo html com o resultado dos testes e para verificar as validações voce pode abrir a pasta **newman** que foi criada no local que os arquivos de collection e environment se encontram.


## Contato
- Email: andersondgouveia@gmail.com


  
