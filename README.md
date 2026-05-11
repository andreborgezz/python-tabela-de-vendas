# python-tabela-de-vendas
Este projeto tem como objetivo realizar o ETL (Extração, Transformação e Carga) de uma base de dados de vendas fictícia.  A ideia central é praticar a manipulação de dados utilizando Python e a biblioteca Pandas, simulando um cenário real onde dados brutos precisam ser limpos, padronizados e enriquecidos antes de qualquer análise.

🛠️ Tecnologias e Ferramentas
Python (Google Colab): Ambiente principal para análise.

Power Query (Excel): Utilizado para a limpeza e estruturação inicial dos dados brutos.

Claude AI: Utilizado para a geração do conjunto de dados sintéticos (vendas.csv).

### 🔄 Etapas de Tratamento (Power Query)
Para garantir a qualidade dos dados, foram aplicadas as seguintes etapas de limpeza e transformação:

Padronização de Tipos: Conversão correta de tipos de dados (Datas, Números e Texto).

Enriquecimento de Dados:

Extração de Ano e Mês a partir da data da venda.

Inserção do Nome do Mês para facilitar análises.

Organização Estrutural: Reordenação de colunas para melhorar a leitura da tabela.

### 🐍 Tratamento de Dados com Python (Pandas)
Após a estruturação inicial, utilizei o Python no Google Colab para realizar um tratamento de dados mais detalhado com a biblioteca Pandas. O objetivo foi corrigir inconsistências que prejudicariam as análises futuras.

**Etapas concluídas:**
* **Padronização de Texto:** Transformei os nomes dos produtos para caixa alta (MAIÚSCULO) para evitar duplicidade e garantir que o sistema reconheça itens iguais.
* **Correção de Inconsistências:** Ajustei nomes de produtos escritos de forma variada (ex: "IPHONE13" para "IPHONE 13") e corrigi problemas de acentuação causados por erros de codificação.
* **Tratamento de Dados Nulos:** Em vez de excluir linhas vazias na coluna de quantidade, utilizei a média de vendas de cada produto específico para preencher as lacunas de forma coerente.
* **Ajuste de Tipos e Organização:** Converti as quantidades para números inteiros, resetei o índice da tabela para manter a ordem e exportei o resultado final para o arquivo `vendas_formatado.csv`.

**Próximos passos:**
- [ ] Criar coluna de **Faturamento** (Quantidade × Preço Unitário).
- [ ] Gerar resumo estatístico (Total faturado e ticket médio).
- [ ] Criar visualizações para identificar os produtos com melhor performance.
