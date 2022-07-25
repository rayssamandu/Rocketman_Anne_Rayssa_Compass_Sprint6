Olá, meu nome é **Anne Rayssa**, e faço parte do Programa de Bolsas de Automação de Testes de APIs com Postman da Compass.uol. O presente repositório refere-se a elaboração do **Projeto Final da 6ª Sprint**, que versou sobre a realização de **Testes com Postman na API ServeRest**.

**A fim de cumprir o projeto na sua integralidade, foram elaborados e devidamente adicionados no presente repositório:**
1️⃣ Plano de Testes
2️⃣ Testes Automatizados da API ServeRest através do Postman
3️⃣ Relatório Final de Execução
4️⃣ Relatório HTML extraídodo Newman

**A API objeto de estudo pode ser localizada através do link https://serverest.dev/, sendo possível executá-la localmente com NPM, devendo ser seguido os seguintes passos:**
1️⃣ Execute o seguinte comando no terminal: npx serverest@latest;
2️⃣ Quer saber as rotas disponíveis e como utilizá-las? Acesse http://localhost:3000. Para outras dúvidas acesse github.com/ServeRest/ServeRest;
3️⃣ Adicione o link da API local no Enviroment do Postman através de uma variável;
4️⃣ Todos os testes foram executados no Enviroment Local.

**Os Testes Automatizados e o Ambiente utilizado foram adicionados no presente repositório em formato JSON.**

**Para gerar o Relatório HTML extraído do Newman, siga os seguintes passos, que também podem ser acessados através do link https://adevait.com/qa/how-to-create-elegant-html-reports-in-postman#installing-newman-and-html-reporters:**
1️⃣ Instale o NodeJS e npm:
  Podemos baixar o NodeJS do site oficial ( https://nodejs.org/ ). Apenas certifique-se de instalar a versão que corresponde ao seu sistema operacional. Durante a configuração da instalação, confirme se o gerenciador de pacotes npm está selecionado, pois usaremos este pacote na próxima etapa.
2️⃣ Instale o Newman e HTLM Reporters:
  Newman é o executor de coleção que nos permite executar e testar uma coleção Postman a partir da linha de comando. A instalação é bem simples. Use cmd mais uma vez e digite: npm install -g newman
  Assim que a instalação do Newman estiver concluída, podemos instalar os repórteres digitando:
npm install -g newman-reporter-html
npm install -g newman-reporter-htmlextra
3️⃣ Exporte coleções e ambientes do Postman:
  Isso pode ser feito usando o Postman selecionando Exportar na pasta da coleção e salvando-os como um arquivo JSON. Também temos que exportar o ambiente e salvá-lo como um arquivo JSON.
4️⃣ Gerando o relatório:
  Primeiro, precisamos abrir o cmd e acessar a pasta onde salvamos nossos arquivos JSON (por exemplo, cd C:\Users\YourName\ExportedJSONs). Uma vez que acessamos esta pasta, podemos executar os arquivos dentro dela usando este comando: newman run YourCollectionName.json -e YourEnvironment.json -n 2 -r htmlextra
  Observe que você terá que substituir YourCollectionName e YourEnvironment pelo nome de seus arquivos exportados. Tenha em mente que -n 2 se refere ao número de iterações que você deseja. Por exemplo, você pode tentar -n 5 se quiser 5 iterações. Isso será mostrado em seu painel HTML. Assim que executarmos o comando, uma pasta chamada Newman será criada na origem da nossa pasta de coleções. Abra-o usando seu navegador favorito e você encontrará os resultados do teste em um arquivo HTML.


💜 **Galera que fez acontecer:**

Um agradecimento para toda a squad que compõe a equipe Rocketman, em especial a:
-> Ewerton Alexander, que me ajudou com os PreRequests.
-> Ana Luiza e Luciana, minha squad na sprint 3, que me auxiliaram a criar o modelo de Plano de Testes que foi aprimorado para o Projeto Final.
-> Dennis Duarte, que me ensinou a apagar a base de dados da API localmente.
