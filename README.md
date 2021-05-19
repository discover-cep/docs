# Discover CEP

## Acesse os documentos da equipe em: https://placeholder.github.io/

## Repositórios de código fonte

### [Front-end](https://github.com/discover-cep/frontend)

### [Back-end](https://github.com/discover-cep/backend)

## Como testar o github pages

### Requisitos

[Docker](https://www.docker.com/)

### Intruções

Na primeira utilização, é necessário fazer o build do container, para isso, utilize o comando.
```
make build
```
Após isso basta iniciar o container com o comando.
```
make run
```
Se tudo der certo, será mostrado no seu terminal o socket para acesso como mostrado abaixo.

![Imagem do terminal](docs/assets/sucess.png)

###### Caso haja problemas de permissão, pode ser necessário utilizar os comando como super usuário(sudo) devido ao docker, existe também [outra solução](https://docs.docker.com/engine/security/rootless/), que consiste em utilizar o daemon do docker como um não-super-usuário.

