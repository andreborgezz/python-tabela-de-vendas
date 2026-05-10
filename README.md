# python-tabela-de-vendas
Este projeto tem como objetivo realizar o ETL (Extração, Transformação e Carga) de uma base de dados de vendas fictícia.  A ideia central é praticar a manipulação de dados utilizando Python e a biblioteca Pandas, simulando um cenário real onde dados brutos precisam ser limpos, padronizados e enriquecidos antes de qualquer análise.

🛠️ Tecnologias e Ferramentas
Python (Google Colab): Ambiente principal para análise.

Power Query (Excel): Utilizado para a limpeza e estruturação inicial dos dados brutos.

Claude AI: Utilizado para a geração do conjunto de dados sintéticos (vendas.csv).

🔄 Etapas de Tratamento (Power Query)
Para garantir a qualidade dos dados, foram aplicadas as seguintes etapas de limpeza e transformação:

Padronização de Tipos: Conversão correta de tipos de dados (Datas, Números e Texto).

Enriquecimento de Dados:

Extração de Ano e Mês a partir da data da venda.

Inserção do Nome do Mês para facilitar análises.

Organização Estrutural: Reordenação de colunas para melhorar a leitura da tabela.

Formatação de Texto: Aplicação de capitalização (Colocar Cada Palavra em Maiúscula) para padronizar nomes de produtos e status, removendo inconsistências de escrita.
