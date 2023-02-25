FROM node:14-alpine
WORKDIR /app
EXPOSE 3001
ADD ./node_modules.tar.gz ./
COPY . .
ENTRYPOINT [ "npm", "start" ]

# rode a partir da imagem do node na versão 14;
# exponha a porta 3001;
# adicione o arquivo node_modules.tar.gz à imagem;
# copie todos os arquivos da pasta back-end para a imagem. 
# (você pode usar o caminho relativo, lembrando que a Dockerfile está em 
# ./docker/todo-app/back-end/Dockerfile);
# inicie a aplicação com o comando npm start.
