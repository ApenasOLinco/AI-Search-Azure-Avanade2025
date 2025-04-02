# 🔍 Configurando uma Pesquisa no Microsoft Azure

## 📌 Introdução
Este repositório documenta o processo de configuração de uma pesquisa utilizando o **Microsoft Azure Cognitive Search**. Essa ferramenta permite indexar, buscar e classificar dados de maneira eficiente.

## ⚙️ Passo a Passo para Configurar uma Pesquisa

### 1️⃣ Criar um Serviço de Pesquisa no Azure*
1. Acesse o [Portal do Azure](https://portal.azure.com).
2. No menu de pesquisa, digite **Azure Search** e clique em "Criar".
3. Escolha um nome para o serviço e a região onde será hospedado.
4. Defina um **plano de precificação**, conforme a necessidade do projeto.
5. Clique em **Criar** e aguarde a implantação.
* Com o mesmo método, criar serviços de Storage e AI Services.
* Ao criar Storage, utilizar a opção Locally-Redundant Storage (LRS) e permitir acesso Blob anônimo depois da criação

### 2️⃣ Configurar um Índice de Pesquisa
1. No painel do Azure Cognitive Search, acesse a aba **Índices**.
2. Clique em **Criar um Novo Índice**.
3. Defina os campos do índice, como:
   - **id** (identificador único)
   - **title** (título do documento)
   - **description** (descrição)
   - **category** (categoria do documento)
4. Escolha quais campos serão pesquisáveis e filtráveis.
5. Salve e finalize a criação do índice.

### 3️⃣ Importar Dados para o Índice
1. Acesse a aba **Origens de Dados**.
2. Selecione a origem (Azure Blob Storage, SQL Database, Cosmos DB, etc.).
3. Configure um **Indexer**, que é responsável por atualizar automaticamente o índice.
4. Inicie o processo de indexação e aguarde a conclusão.

### 4️⃣ Realizar Consultas na Pesquisa
1. Acesse o **Search Explorer** no painel do Cognitive Search.
2. Digite uma consulta simples, como:
   ```json
   {
      "search": "inteligência artificial"
   }
   ```
3. Teste diferentes filtros, ordenações e paginamentos.
4. Explore a opção de **busca semântica** para resultados mais precisos.

## 🔎 Insights e Possibilidades
### 📌 Casos de Uso
- **E-commerce**: Melhorar a busca de produtos em lojas online.
- **Suporte ao Cliente**: Recuperação rápida de FAQs e documentos.
- **Gestão de Conteúdo**: Análise de grandes volumes de textos e artigos.

### 🚀 Ferramentas Beneficiadas
- Aplicativos e sistemas que necessitam de pesquisa rápida.
- Soluções de IA para análise de documentos.
- Plataformas de suporte e autoatendimento.

## 🎓 Aprendizados e Considerações Finais
- Um índice bem estruturado melhora a relevância das buscas.
- A integração com **IA e Machine Learning** pode tornar as buscas mais inteligentes.
- O uso de **facetas e filtros** permite personalizar a experiência do usuário.

---
🚀 Projeto desenvolvido durante o bootcamp! Qualquer dúvida ou sugestão, fique à vontade para contribuir! 😃

