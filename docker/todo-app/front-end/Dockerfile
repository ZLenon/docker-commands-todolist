FROM node:14-alpine
EXPOSE 3000
ADD ./node_modules.tar.gz ./
COPY . .
ENTRYPOINT [ "npm", "start" ]

# rode a partir da imagem do node na versão 14;
# exponha a porta 3000;
# adicione o arquivo node_modules.tar.gz à imagem;
# copie todos os arquivos da pasta front-end para a imagem.
# (você pode usar o caminho relativo, lembrando que a Dockerfile está em 
# ./docker/todo-app/front-end/Dockerfile);
# inicie a aplicação com o comando npm start.