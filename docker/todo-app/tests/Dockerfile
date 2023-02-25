FROM mjgargani/puppeteer:trybe1.0
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "start" ]

# rode a partir da imagem do mjgargani/puppeteer:trybe1.0;
# adicione o arquivo node_modules.tar.gz à imagem;
# copie todos os arquivos da pasta tests para a imagem. 
# (você pode usar o caminho relativo, lembrando que a Dockerfile está em 
# ./docker/todo-app/tests/Dockerfile);
# inicie os testes com o comando npm test.
