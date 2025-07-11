# Case_iFood
Plataforma utilizada: Databricks

Linguagens: Python para análises estatísticas
            Pyspark para ETL

### Primeiro passo - Extrair bases


    Urls:
    "order": "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/order.json.gz",
    "consumer": "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/consumer.csv.gz",
    "restaurant": "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/restaurant.csv.gz",
    "ab_test": "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/ab_test_ref.tar.gz"

Para rodar os scripts: fazer upload dos arquivos descompactados no catálogo do Databricks com os caminhos:
    "order": "workspace.tabelas_ifood.order",
    "consumer": "workspace.tabelas_ifood.consumer",
    "restaurant": "workspace.tabelas_ifood.restaurant",
    "ab_test": "workspace.tabelas_ifood.ab_test"

### Segundo passo - Rodar scripts de ETL

Primeiro script: *view_order_details.ipynb*

Segundo script: *view_user_orders.ipynb*

### Terceiro passo - Rodar scripts de analytics

Resposta Desafio 1-a): *analise_teste_ab.ipynb*

Resposta Desafio 1-b): *analise_precos.ipynb*

Resposta Desafio 2-a,b) : *segmentacao_users.ipynb*

Resposta Desafio 3 : *simulacoes.ipynb*

### Relatório
*Relatotio_case_iFood.pdf*




