# go-react-server

1. iniciando o go mod
go mod init github.com/jardelbordignon/go-react-server

2. config postgres no docker
  2.1 configurado docker-compose
  2.2 .env com as variáveis
  2.3 > docker compose up

3. config pgadmin no docker
  3.1 configurado docker-compose
  3.2 > docker compose up
  3.3 acessar localhost:5050 - servers -> Registrar -> Servidor
    na aba General o campo Nome pode ser qualquer um,
    na aba Conexão o campo Host name/address é nome do serviço docker, setar -> db e informar os demais campos
