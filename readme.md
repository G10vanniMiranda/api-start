#### Criando uma API

* 1. comando para iniciar um projeto nodeJS <br>
```
npm init -y
```

* 2. Dependência json-server <br />
```
npm install json-server
```

* 3. criar um arquivo banco.json <br />

* 4. colocar os dados iniciais. banco.json <br />
```
{
    "usuario" : [
        { 
            "id" : 1,
            "nome": "Rodrigo Nascimento",
            "telefone": "62 9999-8888",
            "email": "admin@gmail.com",
            "senha": "123456"
        },
        { 
            "id" : 2,
            "nome": "Antônio Silva",
            "telefone": "62 9999-8888",
            "email": "admin@gmail.com",
            "senha": "123456"
        }

    ]
}
```

* 5. Rodar nossa api <br>
```
npx json-server banco.json
```

#### Referências
* Biblioteca ou Tecnologia
* 3. Java ( + Complexos )
* 4. Python
* 5. CSharp ( + Complexos )
* 1. PHP
* 2. NodeJS

#### Endpoint

* cadastrar

* Deletar

* Listar

* Atualizar / Editar