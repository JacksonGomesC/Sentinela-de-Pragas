Projeto: Setinela de Pragas
1. Identificação do Grupo
Instituição: Faculdade Engenheiro Salvador Arena (FESA)
Curso: Engenharia de Controle e Automação
Grupo: A
Integrantes: * Antônio Jack S.Monte - RA: 062220002
Giovanna Alves Gonçalves - RA: 062220006
José de Jesus Amaral - RA: 062220033
Jackson Gomes Cerqueira - RA: 062220030
---
2. Área Problema Selecionada
Selecione a trilha tecnológica do projeto (marque com um [x]):
[ ] Saúde 4.0: Robótica Assistiva (Controladores Inteligentes/Fuzzy)
[ ] Smart Grid: Eficiência Energética e Descarbonização
[X] Agtech: Automação de Precisão e Visão Computacional
[ ] Logística Autônoma: Coordenação de AGVs e Otimização de Rotas
---
3. Diagnóstico e Definição do Agente
Nesta seção, descrevemos o cenário de atuação e a modelagem do agente inteligente.
Contexto: Agronegócio.
Problema: O monitoramento tradicional é manual, lento e amostral (o técnico olha apenas algumas plantas). Isso gera falhas de detecção precoce, onde o foco da praga só é descoberto quando já está em estágio avançado de infestação.
Impacto: O diagnóstico automatizado permite uma varredura censitária (olhar 100% das plantas) de grandes extensões. O agente não apenas detecta a praga, mas cria um "mapa de calor" preciso, permitindo que o produtor direcione a pulverização manual ou mecanizada exatamente onde é necessário, sem desperdiçar recursos em áreas saudáveis.
Modelagem PEAS (Agente Inteligente)
Componente	Descrição
Performance (P)	Critérios de sucesso (ex: precisão de acerto, kWh economizados).
Ambiente (E)	Onde o agente opera (ex: armazém simulado, rede elétrica).
Atuadores (A)	Como o agente age (ex: acionamento de motores, válvulas).
**Sensores (S) **	Como o agente percebe o ambiente (ex: câmeras, sensores de carga).
---
4. Arquitetura de Dados e IA
Definição das fontes de dados e da inteligência por trás da solução.
Origem dos Dados: [Link para dataset no Kaggle/UCI ou descrição da fonte].
Lógica de IA: [Técnica utilizada: ex: Redes Neurais, Lógica Fuzzy, Busca A*].
Justificativa: Por que essa técnica é ideal para este problema específico?
---
5. Plano de Tratamento de Dados (ETL)
O fluxo de processamento dos dados segue estas etapas:
Extração: Coleta de dados via arquivos [CSV/JSON] ou simulação.
Transformação: Limpeza de nulos, normalização e engenharia de atributos.
Carga: Disponibilização dos dados para o treinamento do modelo de IA.
---
6. Estrutura do Repositório
Organização simplificada para o Milestone 1:
`/data`: Arquivos de dados originais (raw) e tratados (processed).
`/notebooks`: Experimentos iniciais e análise exploratória.
`/scripts`: Códigos Python (.py) contendo a lógica do agente e do ETL.
`requirements.txt`: Lista de bibliotecas para rodar o projeto.
`README.md`: Documentação atual do projeto.
---
7. Instruções para Execução
Para reproduzir o ambiente e testar o diagnóstico:
Clone este repositório.
Instale as dependências:
```bash
   pip install -r requirements.txt
