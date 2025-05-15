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








# Exploração de Funcionalidades do Copilot e Ferramentas da OpenAI

## Introdução

Este documento fornece uma visão geral das funcionalidades do Copilot e das ferramentas da OpenAI, com ênfase nos filtros de conteúdo aplicados à criação assistida por Inteligência Artificial (IA).

## 1. Copilot

O Copilot é uma ferramenta de assistência de código desenvolvida pela OpenAI em colaboração com a GitHub. Ele utiliza modelos de linguagem avançados para sugerir linhas de código e trechos inteiros enquanto você programa.

### Funcionalidades Principais

- **Sugestões de Código**: O Copilot sugere automaticamente linhas de código com base no contexto atual.
- **Autocompletar**: Completa automaticamente funções e métodos.
- **Geração de Código**: Gera trechos de código a partir de descrições em linguagem natural.
- **Suporte a Múltiplas Linguagens**: Suporta várias linguagens de programação, incluindo Python, JavaScript, TypeScript, Ruby, Go, entre outras.

### Benefícios

- **Aumento de Produtividade**: Reduz o tempo de desenvolvimento ao fornecer sugestões rápidas e precisas.
- **Aprendizado Contínuo**: Ajuda desenvolvedores a aprender novas linguagens e frameworks.
- **Redução de Erros**: Minimiza erros comuns de codificação.

## 2. Ferramentas da OpenAI

A OpenAI oferece uma variedade de ferramentas e APIs que utilizam modelos de linguagem avançados para diversas aplicações.

### GPT-3

O GPT-3 é um dos modelos de linguagem mais avançados desenvolvidos pela OpenAI. Ele é capaz de entender e gerar texto em linguagem natural com alta precisão.

#### Funcionalidades

- **Geração de Texto**: Cria textos coerentes e contextualmente relevantes.
- **Tradução de Idiomas**: Traduz textos entre diferentes idiomas.
- **Resumo de Texto**: Resume textos longos em versões mais curtas e concisas.
- **Resposta a Perguntas**: Responde a perguntas com base em informações contextuais.

### DALL-E

O DALL-E é um modelo de geração de imagens que cria imagens a partir de descrições textuais.

#### Funcionalidades

- **Geração de Imagens**: Cria imagens únicas com base em descrições detalhadas.
- **Edição de Imagens**: Permite a edição de imagens geradas para ajustar detalhes específicos.

## 3. Filtros de Conteúdo

Para garantir a criação responsável e ética de conteúdo, a OpenAI implementa filtros de conteúdo rigorosos em suas ferramentas.

### Filtros de Conteúdo no Copilot

- **Detecção de Código Malicioso**: Bloqueia sugestões que possam conter código malicioso ou inseguro.
- **Filtragem de Conteúdo Sensível**: Evita a geração de código que possa ser considerado ofensivo ou inapropriado.

### Filtros de Conteúdo nas Ferramentas da OpenAI

- **Moderação de Texto**: Analisa e filtra textos gerados para remover conteúdo ofensivo, prejudicial ou inadequado.
- **Segurança de Dados**: Garante que dados sensíveis não sejam utilizados de forma inadequada durante a geração de conteúdo.

## Conclusão

As ferramentas do Copilot e da OpenAI oferecem uma ampla gama de funcionalidades para a criação assistida por IA, com ênfase na segurança e na ética. Os filtros de conteúdo garantem que o uso dessas ferramentas seja responsável e alinhado com as melhores práticas da indústria.








