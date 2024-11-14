# 🚀 Bootcamp Microsoft Azure AI-900 - Azure Cognitive Search

Este repositório é dedicado ao aprendizado de **Azure Cognitive Search** no Microsoft Azure, explorado durante o Bootcamp AI-900. Aqui, vamos explorar os principais recursos e etapas de criação de um serviço de busca inteligente e personalizável no Azure, aplicável para indexação de dados e criação de experiências de pesquisa avançada.

## 📋 Conteúdo

1. 🌐 [Visão Geral do Azure Cognitive Search](#-visão-geral-do-azure-cognitive-search)
2. 📊 [Configuração do Serviço](#-configuração-do-serviço)
3. 🔎 [Indexação de Dados](#-indexação-de-dados)
4. 🛠️ [Ferramentas e APIs](#-ferramentas-e-apis)
5. 🚀 [Explorando as Capacidades de Busca](#-explorando-as-capacidades-de-busca)
6. 📚 [Recursos Adicionais](#-recursos-adicionais)

---

## 🌐 Visão Geral do Azure Cognitive Search

O Azure Cognitive Search é um serviço de pesquisa como serviço (Search-as-a-Service) da Microsoft, que permite a criação de buscas sofisticadas e insights de dados por meio de modelos de inteligência artificial (IA). Com ele, é possível realizar:

- Indexação de diferentes fontes de dados.
- Criação de filtros e classificação personalizada.
- Integração de análises de texto, reconhecimento de entidades e outros recursos de IA.

## 📊 Configuração do Serviço

Para configurar o serviço Azure Cognitive Search:

1. Acesse o [Portal do Azure](https://portal.azure.com).
2. No menu esquerdo, selecione **Create a resource** (Criar um recurso).
3. Procure por **Azure Cognitive Search** e selecione **Create** (Criar).
4. Complete os campos necessários:
   - **Nome do serviço**
   - **Região**
   - **Camada de preço**

Após a configuração, o serviço estará disponível no portal para configuração de índices e fontes de dados.

## 🔎 Indexação de Dados

A indexação de dados é essencial para preparar os dados para busca. Siga os passos para criar e gerenciar um índice:

1. No painel do serviço de busca, selecione **Indexes** (Índices) e clique em **New Index** (Novo Índice).
2. Defina o esquema do índice, incluindo campos como:
   - `ID` (identificador único)
   - `Title` (título do documento)
   - `Content` (conteúdo para busca)

3. **Adicionar fontes de dados**:
   - Conecte o índice a uma fonte de dados, como **Azure Blob Storage**, **Azure SQL Database**, ou **Cosmos DB**.

Após criar o índice, você poderá configurar a frequência de atualização e iniciar o processo de indexação.

## 🛠️ Ferramentas e APIs

O Azure Cognitive Search oferece várias ferramentas e APIs para auxiliar no desenvolvimento e gerenciamento de buscas:

- **REST API**: Permite interações programáticas para configuração de índices, consultas e gestão de fontes de dados.
- **SDKs**: Disponíveis para diversas linguagens como Python, .NET e JavaScript, permitindo uma integração fácil.
- **Azure Portal**: Interface gráfica para configuração, visualização e monitoramento dos recursos do Azure Cognitive Search.

## 🚀 Explorando as Capacidades de Busca

Com o índice configurado, você pode explorar os recursos avançados de busca que o Azure Cognitive Search oferece:

- **Busca Full-text**: Pesquisa baseada em texto completo com suporte para operadores booleanos, fuzzy search e busca por sinônimos.
- **Filtros e Ordenação**: Personalize a pesquisa adicionando filtros e regras de ordenação para adaptar os resultados às necessidades dos usuários.
- **Análise de Linguagem Natural**: Integração com o Language Studio para análise de sentimentos, extração de entidades e outras capacidades de NLP.

## 📚 Recursos Adicionais

Para mais informações e documentação completa, consulte:
- 📑[Tutorial: Explorar um índice de pesquisa do Azure AI (IU)](https://aka.ms/ai900-ai-search)

- 📘 [Documentação Oficial do Azure Cognitive Search](https://docs.microsoft.com/azure/search/)
- 📹 [Tutoriais em Vídeo do Azure Cognitive Search](https://azure.microsoft.com/en-us/resources/videos/index/?services=search)

