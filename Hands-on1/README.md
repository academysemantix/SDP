> :construction: Tutorial em construção :construction:

# **SDP Hands-on 1**: Pipeline e Connectors
## **Objetivo**: Uso prático do SDP para upload de uma base


### Acessar a Plataforma:
Para realizar esse tutorial, você precisa ter uma **conta de SDP**
Acesse o site [console.semantix.cloud](https://console.semantix.cloud/) para ter acesso a plataforma do SDP, digite o e-mail e senha enviados via *e-mail* OU CREDENCIAIS e click em "Login to Continue", como apresentada na imagem:

![Tela de Login](https://github.com/academysemantix/SDP/blob/main/Hands-on1/images/tela_login_sdp.png)

### Preparar os Dados:

Após logar na plataforma, o próximo passo é preparar os dados.....

### Ingerir os Dados:

## Criar Pipeline
# Create a Pipeline with a API Connector

Now, let's create a Pipeline that will extract the data from a API, in this example we will be using the Shopify API.

1-  You go to the pipelines using the sidebar and clicking the pipeline symbol: <img src="/img/pipeline.svg" alt="pipeline" width="20px" />

2-  Then click the "+New Pipeline" button, if you don't have a pipeline it will be in the middle of your screen, otherwise it will be in the top right:

![+ New Pipeline](/img/pipeline/api-component/api_component_2.png)

3-  Choose your data source:

![Define Source](/img/pipeline/api-component/api_component_3.png)

4-  After you chose the data source insert your credentials:

![Define Source](/img/pipeline/api-component/api_component_4.png)

5-  Select the objects that you want to collect the data from and which table in the raw layer you want it to go to (output path):

![Select Objects](/img/pipeline/api-component/api_component_5.png)

6-  And then select your ingestion frequency preference, or customize it using a [cron expression](https://crontab.guru/):

![Schedule your Pipeline](/img/pipeline/api-component/api_component_6.png)

and easy like that you have created your pipeline that is connected to the shopify API, now your data will be periodically ingested into the raw layer of the data lake. You can also manage and edit your pipeline if you want to, if you want to know how to do that, go to the ["Manage Your Pipeline"](/docs/pipeline/manage-pipeline) section

### Transformar os Dados:

Guia Jobs...

### Próximos Passos:

## Autores

| [<img src="https://avatars.githubusercontent.com/u/23451074?v=4" width=115><br><sub>Rodrigo Augusto Rebouças</sub>](https://github.com/rodrigo-reboucas) |  [<img src="gitVasco" width=115><br><sub>Vasco Braga</sub>](gitvaso) |
| :---: | :---: |
