## Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

### Azure Cognitive Search AI900
Utilizando AI Search para indexação e consulta de informações.

A pesquisa de inteligência artificial do Azure para a Fourth Coffee foi conduzida.

Este arquivo contém o guia completo para configurar uma solução de mineração de conhecimento utilizando a Pesquisa de Inteligência Avançada do Azure. O objetivo é facilitar a busca por informações sobre as experiências do cliente a partir de avaliações de clientes.

## Configuração de Pesquisa com Azure Cognitive Search

### Passo 1: Criar um Serviço de Azure Cognitive Search

1. Acesse o [Portal do Azure](https://portal.azure.com/) e clique em "Criar um recurso".
2. Procure por "Azure Cognitive Search" e clique em "Criar".
3. Preencha os detalhes como nome, assinatura, grupo de recursos e localização.
4. Selecione o nível de preços adequado para suas necessidades.
5. Clique em "Revisar + Criar" e depois em "Criar".

## Passo 2: Ingestão de Dados

1. Após criar o serviço, acesse o portal do Azure e abra o serviço de Azure Cognitive Search.
2. No menu à esquerda, selecione "Índices" e clique em "Criar índice".
3. Defina o esquema do índice, especificando os campos que deseja indexar.
4. Configure a origem dos dados, que pode ser um banco de dados, um blob storage ou outro serviço.
5. Mapeie os campos do seu conjunto de dados para os campos do índice.
6. Execute o processo de ingestão para indexar os dados.

## Passo 3: Configuração da Pesquisa

1. Configure os parâmetros de pesquisa, como consulta, filtros e ordenação, no portal do Azure.

2. Teste diferentes consultas para garantir que os resultados sejam precisos e relevantes.

3. Explore recursos avançados, como pesquisa por facetas e resumo de contexto, para melhorar a experiência do usuário.
   

## Insights e Possibilidades

Durante este processo, você pode obter alguns insights interessantes:

- A importância de um esquema de índice bem projetado para uma pesquisa eficaz.
- O impacto dos analisadores de texto e filtros de pesquisa na qualidade dos resultados.
- As possibilidades de integração com outras ferramentas, como chatbots e assistentes virtuais, para oferecer uma experiência de pesquisa mais interativa.

Além disso, algumas ferramentas que podem se beneficiar do Azure Cognitive Search incluem:

- Sites de comércio eletrônico, para pesquisa de produtos.
- Portais de informações, para pesquisa de documentos e artigos.
- Aplicativos de atendimento ao cliente, para pesquisa de perguntas frequentes e solução de problemas.

## Aprendizados Adquiridos

Ao configurar uma pesquisa com Azure Cognitive Search, você pode aprender sobre:

- Design de esquema de índice e mapeamento de campos de dados.
- Uso de analisadores de texto e filtros de pesquisa para melhorar a relevância dos resultados.
- Implementação de consultas avançadas e recursos de pesquisa para uma experiência de usuário aprimorada.

## Entendendo melhor:

Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

##### O procedimento é dividido em três fases:

1. Adicionar recursos ao Azure:
   Criar um recurso de pesquisa em inteligência artificial no Azure.
   Criar um serviço de inteligência artificial no Azure.
   Criação de uma conta de armazenamento.

2. Extrair informações de uma fonte de dados:
    Ajustar a conexão com o armazenamento de blob do Azure.
   Realizar a transferência de documentos para o armazenamento.

3. Aprimorar informações por meio de habilidades de inteligência artificial:
    Criar um assistente de importação de dados.
   Aumentar a capacidade cognitiva para enriquecer os dados.

4. Usar o indexador do Azure no site do Azure:
    Elaborar um índice de Pesquisa de Inteligência Avaliativa do Azure.
   Configurar um indexador para obter informações dos documentos.

5. Verifique o seu índice de pesquisa.
    Aplicar o Search Explorer para testar as consultas.

6. Revisar resultados armazenados em um Knowledge Store:
    Acessar a Knowledge Store para visualizar dados atualizados.

#####  Recursos do Azure necessários:

Certifique-se de oferecer os seguintes recursos em sua assinatura do Azure:
-  Avaliação da inteligência artificial do Azure.
- Serviços de inteligência artificial do Azure.
- Avaliação de armazenamento

Categorias Insights e Aprendizado

##### Durante o processo, você terá a chance de aprender sobre:

-  Configuração da Pesquisa de Inteligência de Área do Azure.
- Uso de capacidades mentais para enriquecer dados.
-  Avaliação dos indicadores de pesquisa.
- Avaliação da Loja de Tecnologia da Informação.

As Possibilidades de Ferramentas são apresentadas abaixo.

Além disso, esta solução pode ser integrada a diversas outras ferramentas, como:

Aproveite o potencial da Pesquisa de IA do Azure para aprimorar a compreensão das experiências do cliente na Fourth Coffee.

---



#### Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados
Teste 4 do Bootcamp Azure Fundamentals AI 900 da DIO

<h3> Pesquisa Cognitiva do Azure</h3><br>

<h3>O que é mineração de conhecimento?</h3>
<br>
- O dados são bloqueados em documentos, PDFs, notas manuscritas, etc.
<br>
- A mineração de conhecimento encontra insights em escala
<br>
- O Azure Cognitive Search é a plataforma de mineração de conhecimento alimentada por IA do Azure.
<br>
<br>
<h3>Soluções de Pesquisa Cognitiva do Azure</h3>

<h3>Ingestação de dados:</h3>
 - Azure Blob Storage Containers<br>
 - Azure Data Lake Storage Gen2<br>
 - Azure Table Storage<br>
<br>
<h3>Enriquecimento e índice de IA:</h3>
Permite uma compreensão mais progunda;<br>
Visão, Procesamento de Linguagem Natural, etc;<br>
A indexação torna o conteúdo pesquisável.<br>
<br>
<h3>Enriquecimento de IA</h3>
Pesquisa Cognitiva do Azure<br>
O enriquecimento de IA torna o conteúdo mais útil para fins de pesquisa.<br>
O conteúdo enriquecido é criado por conjutnos de habilidades, como:<br>
 - Reconhecer entidades no texto<br>
 - Traduzir texto<br>
 - Avalie o sentimento<br>
<br>


**DESAFIO**<br>
Para criar Azure AI Search:<br>

Abrir a assinatura do Azure, criar um novo recurso e dar um nome excluviso para ele, selecionar assinatura, grupo de recursos, localização e no Pricing tier, selecionar o nível básico (Basic).
Após, clicar em Review + create e aguarda a finalização.
<br>
Em seguida, é necessário criar um recurso de IA. Para isso é necessário ir em Criar recurso (create a resource), clicar em IA + Machine Learning, em seguida clicar em Serviços Cognitivos(Azure AI Services), clicar em Criar(create) e novamente preenche os dados como no passo anterior, selecionando no Pricing tier, a opção Standard S0 e marcar a caixinha no final da página. Para finalizar clicar em Review + create.
<br>
Para criar uma conta de armazenamento, é necessário ir em Storage accounts, clicar em Create(criar), preencher as opções correspondentes ao laborário: assinatura, resource group, storage account name(precisa ser um nome único entre 3 e 24 caracteres), região, performance (é necessário ticar Standard) e redundância (marcar a primeira opção da lista - LRS). Concluído o processo, basta clicar em Review + create, sem a necessidade de preencher os demais campos das abas apresentadas no menu superior.
<br>
Após criar o storage, basta selecioná-lo, clicar em configurações e permitir o acesso anônimo de Blob (ele vem desabilitado e precisa habilitar a opção) para então, salvar as configurações.
Em Data storage, seleciona Containers, clica em + Container e escolhe a opção de Container anônimo (na documentação, o nome sugerido foi Coffee-Reviews, porém a plataforma só aceita letras minúsculas e sem traço). Feita a alteração, clica em Create.
<br>
Após criar o Storage account, será necessário carregar com arquivos disponibilizados na documentação (baixar pasta zipada e extrair os arquivos na máquina para fazer o upload na plataforma). Após carregar os arquivos clica em Storage accounts, no topo da página e no buscador, ainda na parte superior, pesquisa por AI Search, clica nele e seguida em importar dados. Para tal, é necessário seguir o passa a passo que se encontra na documentação (https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html), para preencher alguns campos de conexão, ou seja será necessário apontar aonde estão os documentos e os tipos de informações que quer dos documentos, para que a busca possa retornar uma pesquisa.
<br>

![Imagem do WhatsApp de 2024-04-14 à(s) 23 50 26_49b3fc0b](https://github.com/Edivania88Duarte/-Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/assets/120994730/073ef210-87d0-4706-9e3d-76ae7c38e411)

<br>
<h3>Passo a passo para importar dados:</h3><br>
<br>
Na página Conectar-se aos seus dados , na lista Fonte de Dados , selecione Azure Blob Storage . Preencha os detalhes do armazenamento de dados com os seguintes valores:<br>
Fonte de dados : Armazenamento de Blobs do Azure<br>
Nome da fonte de dados : coffee-customer-data<br>
Dados a extrair : Conteúdo e metadados<br>
Modo de análise : Padrão<br>
Cadeia de conexão : *Selecione Escolha uma conexão existente . Selecione sua conta de armazenamento, selecione o contêiner de avaliações de café e clique em Selecionar <br>
Autenticação de identidade gerenciada : Nenhuma<br>
Nome do contêiner : esta configuração é preenchida automaticamente depois que você escolhe uma conexão existente<br>
Pasta Blob : deixe em branco<br>
Descrição : Avaliações sobre Fourth Coffee Shops.<br>


![Imagem do WhatsApp de 2024-04-16 à(s) 23 39 28_4b19cebb](https://github.com/Edivania88Duarte/-Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/assets/120994730/1dcab40d-59b1-4793-a7ee-f1ddb52c4e86)

<br>


![Imagem do WhatsApp de 2024-04-16 à(s) 23 52 05_254fc710](https://github.com/Edivania88Duarte/-Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/assets/120994730/4688987d-4bd5-4706-b603-1bc000e2ed33)

<br>
<br>
<h3>Objetivo geral da aplicação:</h3><br>
Extrai os campos de metadados do documento e o conteúdo da fonte de dados.<br>
Executa o conjunto de habilidades cognitivas para gerar campos mais enriquecidos.<br>
Mapeia os campos extraídos para o índice.<br>
<br>


![Imagem do WhatsApp de 2024-04-17 à(s) 00 05 17_1b4a20d5](https://github.com/Edivania88Duarte/-Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/assets/120994730/a18f227a-5aa4-40ca-a408-8fc51bafabc3)

<br>

<h3> Links: </h3> <br>

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html
