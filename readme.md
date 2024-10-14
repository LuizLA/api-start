### Comandos terminal

* comando para listar pastas ou diretorio <br>
ls

* limpar tela <br>
clear

* entrar em um diretorio / pasta <br>
cd api

* voltar um diretorio <br>
cd ..

### criando uma api com json
* verificar se a maquina tem o nodeJS instalado.
    node -v
* npm init -y
* npm install json-server

* criar um arquivo dados.json
 ```
  {
    "usuarios": [
        { "id": 1, "email": "rodrigo@gmail.com", "senha": "123" },
        { "id": 2, "email": "luiz@gmail.com",    "senha": "123" }
    ]
}
```

* comando para rodar a api
npm json-server dados.json