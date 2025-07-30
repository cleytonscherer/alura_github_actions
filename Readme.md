## Executa o lint do go validando o projeto
docker run --rm -itv $(pwd):/app -w /app golangci/golangci-lint golangci-lint run controllers/ database/ models/ routes/
