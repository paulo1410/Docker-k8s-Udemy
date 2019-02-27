#Use um docker image existente como base
FROM alpine

# Baixa de instale as dependências
RUN apk add --update redis

# Diga à imagem o que fazer quando o container iniciar
CMD ["redis-server"]
