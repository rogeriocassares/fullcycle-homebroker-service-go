
Create go.mod
go mod init github.com/rogeriocassares/fullcycle-homebroker-service-go

Create internal/market/entity folder to create the application lib
mkdir -p internal/market/entity

Verify dependencies and download the missing ones
go mod tidy

AULA 02 01:02