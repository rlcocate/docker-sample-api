# docker-sample-api
Amostra de API Nodejs para ser executada em uma imagem Docker. 
Criada com o Dockerfile.

# Processo de criação da imagem:
» docker image build -t docker-api:1.0 .

- Parâmetro -t serve para nomear imagem: nome:versão
- '.' ao final específica o diretório onde está o Dockerfile (no caso a Raiz do API) 

# Comando para executar a imagem gerada
» docker conteiner run --publish 8080:3000 --detach --name api dockerapi:1.0

- <strong>--publish:</strong> cuida do redirecionamento da porta de execução.
- <strong>--detach:</strong> define ao Docker que deverá executar este conteiner em backgroud par anão travar o terminal que acabou de ser executado.
- <strong>--name:</strong> nome do conteiner
