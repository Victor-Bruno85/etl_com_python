# ETL utilizando linguagem Python

Observamos que um processo de integração e análise de dados depende de um passo anterior que é justamente onde entra o ETL. O ETL, bem como o ELT e a ingestão de dados, visa preparar o conjunto de dados para que se possa realizar posteriores trabalhos.

Baseado no conteúdo estudado, um fluxo considerando duas fontes distintas de dados levando em conta as seguintes restrições:

Serão considerados dois tipos de fontes diferentes:

- A primeira será o arquivo CSV.

- A segunda será o arquivo de texto contendo um dicionário de termos.

O fluxo deverá compreender as seguintes etapas:

- Carregar os dados do CSV.

- Carregar dados do arquivo texto.

- Associar cada termo contido no arquivo texto com a coluna “Categoria” do arquivo CSV.

- Formatar os dados da coluna “Valor” para ser exibido em formato monetário. Exemplo: “10.0” será exibido como “R$ 10,00”.

- Escrever a saída deste processo em um arquivo CSV chamado “Resultado.csv”.
