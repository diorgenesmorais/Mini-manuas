# Vue.js

> Manual prático sobre Vue.js

# mudar a porta do serviço que roda o Vue (npm run dev)
# no arquivo 'webpack.config.js' do projeto colocar as seguintes parâmetros no 'devServer':
```
devServer: {
    ...,
    inline:true,
    port: 8008
},
```

[onde encontrei a dica](https://stackoverflow.com/questions/33272967/how-to-make-the-webpack-dev-server-run-on-port-80-and-on-0-0-0-0-to-make-it-publ)

# instalar o Vue globalmente
```
npm install -g vue-cli
```

# listar os templates de vue-cli
```
vue list
```

# criar um projeto
```
vue init webpack-simple nome-do-projeto
```

# instalar dependências
```
npm install
```

# executar a aplicação
```
npm run dev
```


