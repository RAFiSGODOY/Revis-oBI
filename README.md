# Revisao-BI

 ## O que é BI (Business Intelligence) ? :
Bussines Intelligence  seria o conjunto de processos e ferramentas que proporcionam o processamento e transformação de dados brutos em informções valiosas para a tomada de decisão e formação de conhecimento;

## Etapas BI

### Planejamento 
Visa garantir que todas as partes envolvidas no ciclo de vida dos dados estejam alinhadas e que as necessidades do negócio sejam bem compreendidas antes da implementação de pipelines ou sistemas;

### Levantamento do Objetivo 
A definição de um objetivo de BI deve focar no impacto positivo para o negócio como um todo, e não apenas em características específicas do produto ou serviço. Um exemplo seria "Reduzir o tempo de processamento de pedidos em 30% nos próximos 12 meses para aumentar a satisfação do cliente e otimizar a eficiência operacional


### Levantamento de Indicadores 
 Processo de definir e selecionar métricas específicas que permitirão monitorar e avaliar o progresso em relação aos objetivos de negócio. Os indicadores servem para medir a performance de processos e ações, fornecendo dados quantificáveis que ajudam a guiar decisões estratégicas

## Estudo de Fontes de Dados 
 Qual a fonte de dados disponível para medir o indicador;
  Ex:
    - Banco de Dados
    - Planilha Excel
    - Log de Sistema

### Fontes de Dados 

Estruturados : SGDB , API;

Não Estruturados: Planilhas, Videos, Fotos, Audio, Logs, Gmail;


### OLTP ( Transacional )
Otimizado para inserção, atualização e consistência dos dados em tempo real;

### OLAP ( Analítico )
Otimizado para leitura pesada e análises de dados complexos;

( Dashboards de BI devem evitar consumir dados diretamente de bancos OLTP )

### ETL 
 Processo de extrair, transformar e por fim carregar os dados em um banco OLAP (Data WareHouse)

 ### Data WareHouse 
 Organiza as tabelas em fatos e dimensões

 ### Fato DW 
  Guarda Eventos numéricos, vendas, lucros ou quantidades, responde a "o que, quanto e quando", sendo base para as análises e se conectando a dimensões para dar contexto;

  
 

 

 
