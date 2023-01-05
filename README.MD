Projeto sobre gRPC criado junto ao modulo de comunicação de sistemas do curso Full Cycle.

Os tipos de comunicação implementados foram: unary, server streaming, client streaming e bi directional streaming.

Para executar o projeto clone em sua maquina, vá até o diretorio e execute o comando ```go mod tidy``` para baixar os pacotes necessários.

Em seguida rode o servidor com o comando ```go run cmd/grpcServer/main.go```

Abra um novo terminal e execute o evans com o comando ```evans -r repl```

A partir daqui você consegue realizar as requests rpc, por exemplo, com o comando ```call ListCategories```, será retornado uma lista com todas as categorias