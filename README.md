# docker-sample-api
Amostra de API Nodejs para ser executada em uma imagem Docker. 
Criada com o Dockerfile.

#
Processo de criação da imagem:
» docker image build -t docker-api:1.0 .

- Parâmetro -t serve para nomear imagem: nome:versão
- '.' ao final específica o diretório onde está o Dockerfile (no caso a Raiz do API) 
