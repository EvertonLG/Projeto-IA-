# Projeto-IA-

# 🔎 Azure Cognitive Search: Utilizando AI Search para Indexação e Consulta de Dados

Este repositório apresenta um resumo prático do processo de configuração e uso do **Azure Cognitive Search**, uma poderosa ferramenta da Microsoft que permite indexar e consultar dados de forma inteligente, com suporte a recursos de IA como análise de sentimentos, extração de entidades e tradução automática.

---

## 📘 Objetivo do Projeto

Demonstrar como utilizar o **Azure Cognitive Search** para construir uma solução de busca inteligente, desde a criação de um índice até a consulta dos dados enriquecidos com IA, explorando recursos como:

- Análise Semântica
- Enriquecimento com Skills cognitivas
- Autocompletar e sugestões
- Facetas de navegação

---

## 🛠️ Passo a Passo: Como Configurar a Pesquisa

### 1. Criar o Serviço de Azure Cognitive Search

1. Acesse o portal do Azure.
2. Clique em **"Criar um recurso"** > **"Serviços de Pesquisa"**.
3. Defina nome, região, camada de preço e grupo de recursos.
4. Aguarde o provisionamento do serviço.

### 2. Preparar a Fonte de Dados

Você pode utilizar:
- Banco de dados SQL do Azure
- Armazenamento Blob (JSON, PDFs, imagens, etc)
- Cosmos DB
- Planilhas Excel

### 3. Criar a Fonte de Dados (Data Source)

1. No portal do Azure, vá até seu serviço de pesquisa.
2. Clique em **"Importar dados"**.
3. Escolha a fonte (ex: Azure Blob Storage).
4. Configure as credenciais de acesso e selecione os arquivos a serem indexados.

### 4. Definir o Indexador

1. O indexador conecta sua fonte de dados ao índice.
2. Configure o agendamento para indexação automática (tempo em minutos ou horas).
3. Você pode aplicar **Cognitive Skills** como:
   - OCR (leitura de imagens/PDFs)
   - Extração de entidades
   - Tradução de texto
   - Detecção de linguagem
   - Análise de sentimento

### 5. Criar o Índice de Busca

1. Defina os campos que serão indexados e pesquisáveis (ex: título, descrição, data, etc).
2. Marque campos como:
   - **Searchable**: pode ser pesquisado
   - **Filterable**: pode ser usado em filtros
   - **Facetable**: usado em facetas de navegação
   - **Sortable**: permite ordenação
   - **Retrievable**: aparece nos resultados

### 6. Configurar e Rodar o Indexador

1. Clique em **"Executar indexador"**.
2. Aguarde o processamento dos dados e enriquecimento com AI.
3. Visualize o conteúdo indexado no índice criado.

### 7. Testar Consultas

- Utilize a **interface de busca integrada** para fazer consultas manuais.
- Explore filtros, ordenações e destaque de trechos relevantes.
- Teste os recursos de **autocomplete** e **sugestões**.

---

## 💡 Insights Obtidos

- O **AI Search** pode transformar dados brutos (como PDFs ou imagens) em informações estruturadas e pesquisáveis com poucos cliques.
- A ferramenta reduz drasticamente o tempo necessário para implementar uma solução de busca com recursos avançados de NLP.
- A análise semântica e o suporte multilíngue permitem buscas mais precisas e inclusivas.
- A separação entre **indexador**, **fonte de dados** e **índice** permite flexibilidade na atualização e reuso dos componentes.

---

## 🚀 Possibilidades de Aplicação

- **Portais corporativos com pesquisa de documentos** (manuais, políticas, relatórios).
- **E-commerce inteligente**, com filtros dinâmicos, sugestões e facetas.
- **Sistemas jurídicos ou acadêmicos** com indexação automática de arquivos.
- **Chatbots e assistentes virtuais**, integrando respostas baseadas no índice.
- **Aplicações multilingues**, com tradução automática de conteúdo indexado.

---

## 🧠 Aprendizados Adquiridos

- Como configurar e utilizar os principais componentes do Azure Cognitive Search: **Data Source**, **Indexer** e **Index**.
- A importância de escolher corretamente os campos do índice com as propriedades ideais para a busca.
- Como aplicar **Cognitive Skills** para extrair valor de dados não estruturados.
- Que uma busca eficiente vai muito além do texto exato – envolve contexto, semântica e filtros bem definidos.

---

## 🔗 Recursos Complementares

- [Documentação Oficial do Azure Cognitive Search](https://learn.microsoft.com/azure/search/)
- [Exemplo de Configuração no Portal do Azure](https://portal.azure.com)
- [Microsoft Learn – Módulos de AI Search](https://learn.microsoft.com/training/paths/explore-ai-capabilities-azure-cognitive-search/)

---

## 👨‍💻 Desenvolvido por

Everton Lima Gomes  
Bootcamp Avanade | Curso: *Azure Cognitive Search: Utilizando AI Search para Indexação e Consulta de Dados*

---


