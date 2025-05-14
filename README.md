# lab-cloudAI-dio
Repositorio que conterá meus estudos, anotações e resumos sobre Inteligência Artificial da Azure.

## Anotações 2 - BootCamp Java Cloud Native

# O que iremos aprender ?

Este curso apresenta a IA e os serviços da Microsoft que podem ser usados para criar soluções de IA
Você poderá identificar e descrever os principais conceitos de IA e os principais serviços de IA e machine learning no Microsoft Azure

# Conteúdo Programático

Visão geral da IA
Visão Computacional
Processamento de Linguagem Natural
Inteligência de Documentos e Mineração de Conhecimento
IA generativa

# Conceitos Fundamentais de IA - O que é Inteligência Artificial ?

Prever resultados e reconhecer padrões com base em dados históricos.
Extrair informações de fontes para obter conhecimento.
Compreender a linguagem e participar de conversas.
Reconhecer eventos anormais e tomar decisões.
Interpretando informações visuais

Machine Learning

Modelos preditivos baseados em dados e estatísticas.

Visão Computacional

Capacidades da IA para interpretar o mundo visualmente por meio de cameras, videos e imagens.

Processamento de Linguagem Natural

Capacidades da IA pra que um computador interprete a linguagem escrita ou falada e responda adequadamente.

Inteligência de Documentos

Capacidade de IA que lidam com o gerenciamento, processamento e o uso de grandes volumes de dados encontrados em formulários e documentos.

Mineração de Conhecimento

Capacidade da IA para extrai informações de grandes volumes de dados muitas vezes não estruturados para criar um armazenamento de conhecimento pesquisável

IA Generativa

Recursos de IA que criam conteúdo original em vários formatos, incluindo linguagem natural, imagem, código e muito mais.

Imparcialiadade

Principios de IA responsável: Inclusiveness, Fairness, Transparency, Accountability, Reliability and safety, Privacy and Security.

Confiabilidade e Segurança

Erros podem causar danos. Ex: Um veículo autonomo sofre uma falha no sistema e causa uma colisão.

Privacidade e Segurança

Dados privados podem ser expostos. Ex: Um bot de diagnóstico médico é treinado usando dados confidenciais de pacientes, que são armazenados de forma insegura

Inclusão e Transparência

As soluções podem não funcionar pra todos. Um aplicativo preditivo não fornece saída de áudio para usuarios com deficiencia.

Os usuarios devem confia em um sistema  complexo. Ex Uma ferramenta financeira baseada em IA faz recomendações de investimento.

Responsabilidade 

Quem é responsável pelas decisões baseadas na IA ? Ex: Uma pessoa inocente é condenda por um crime com base em provas de reconhecimento facial.



# 📄 Relatório Técnico: Organização e Pesquisa de Documentos com Azure Cognitive Search

## 1. Introdução

Este relatório descreve o processo de organização e pesquisa de documentos por meio da ingestão de dados e indexação utilizando o **Azure Cognitive Search**, uma solução de busca como serviço (Search-as-a-Service) da Microsoft. O objetivo é demonstrar como essa ferramenta pode ser utilizada para transformar grandes volumes de documentos não estruturados em informações pesquisáveis e acessíveis.

## 2. Visão Geral do Azure Cognitive Search

O **Azure Cognitive Search** é uma plataforma de busca baseada em nuvem que permite:

- Indexar dados estruturados e não estruturados.
- Aplicar habilidades cognitivas para extração de informações.
- Realizar buscas textuais com alta performance.
- Integrar com outras soluções do Azure, como Blob Storage, Cosmos DB, SQL Database, etc.

## 3. Etapas do Processo

### 3.1 Ingestão de Dados

A ingestão é o processo de entrada dos dados na plataforma. Pode ser feita a partir de:

- **Azure Blob Storage** (PDFs, DOCX, imagens, etc.)
- **SQL Database**
- **Cosmos DB**
- **APIs externas**

#### Ferramentas e Técnicas:
- **Data Source**: Define a origem dos dados.
- **Skillset**: Conjunto de habilidades cognitivas aplicadas aos dados (OCR, extração de entidades, tradução, etc.).
- **Indexer**: Responsável por ler os dados, aplicar o skillset e alimentar o índice.

---

### 3.2 Habilidades Cognitivas (Skillsets)

As habilidades cognitivas permitem enriquecer os dados durante a indexação. Exemplos:

- **OCR (Reconhecimento Óptico de Caracteres)**: Extrai texto de imagens e PDFs.
- **Extração de Entidades**: Identifica nomes, locais, datas, etc.
- **Detecção de Idioma e Tradução**
- **Análise de Sentimento e Classificação de Texto**

---

### 3.3 Indexação

A indexação transforma os dados processados em um formato pesquisável. Componentes principais:

- **Índice**: Estrutura que armazena os dados pesquisáveis.
- **Campos**: Definem os atributos dos documentos (ex: título, conteúdo, data).
- **Analisadores**: Tokenizam e normalizam o texto para busca eficiente.

---

### 3.4 Pesquisa

Após a indexação, os dados podem ser consultados por meio de:

- **API RESTful**
- **SDKs (.NET, Python, Java)**
- **Azure Portal**
- **Integração com aplicativos web (ex: Power BI, aplicativos personalizados)**

Funcionalidades de pesquisa incluem:

- Busca por texto completo
- Filtros e facetas
- Sugestões automáticas
- Destaque de trechos relevantes

---

## 4. Casos de Uso

- **Pesquisa Jurídica**: Indexação de processos e jurisprudências.
- **Gestão de Documentos Corporativos**: Busca em arquivos internos.
- **Análise de Currículos**: Extração de dados de candidatos.
- **Digitalização de Arquivos Físicos**: OCR e organização de documentos escaneados.

---

## 5. Benefícios

- Redução de tempo na busca por informações.
- Aumento da produtividade.
- Enriquecimento automático de dados.
- Escalabilidade e integração com outras soluções Azure.

---

## 6. Considerações Finais

O Azure Cognitive Search é uma solução poderosa para empresas que lidam com grandes volumes de documentos. Sua capacidade de aplicar inteligência artificial durante a ingestão e indexação permite transformar dados brutos em conhecimento acessível e útil.


