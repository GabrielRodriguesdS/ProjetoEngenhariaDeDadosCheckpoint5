HOW BOOTCAMP
Checkpoint 5 – Projeto de Engenharia de Dados

Proposta do projeto

Extrair dados de imóveis do site https://vivareal.com.br/ com a idéia de poder avaliar qual o melhor negócio a se fazer na compra de um imóvel.

Objetivo do projeto

Após extração dos dados e tratamento, utilizar os dados com o objetivo de comparar valores, metragem e localização para mostrar aos clientes por meio de relatórios e dashboards onde possam tomar a melhor decisão.

Métodos

• Linguagem de programação Python: para a extração de dados do site https://vivareal.com.br/ e tratamento utilizando a biblioteca pandas. Após tratar os dados, subo para um bucket na AWS como um arquivo .csv.
• S3 para armazenamento dos dados após extração e tratamento.
• AWS Glue com o objetivo de ter os metadados e criar a tabela chamada Imóveis.
• AWS Athena para um rápido acesso aos dados antes de poder subir a uma ferramenta de visualização de dados e criação de dashboards.
• Power Bi para receber a tabela do AWS Athena e criação de dashboards e relatórios onde os clientes possam visualizar a melhor opção de compra de seu imóvel.


