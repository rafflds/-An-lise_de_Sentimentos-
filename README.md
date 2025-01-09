# 🚀 Sonic 3 Análise de Sentimentos 

Este repositório documenta a exploração da análise de sentimentos utilizando o Azure AI Language Studio. Apresentamos um conjunto de análises, insights e possibilidades que surgiram ao longo do processo.

## ⚙️ Passo a Passo para Criar a Aplicação no Azure

Antes de começar a análise, é necessário configurar o ambiente no Azure. Siga estes passos para criar sua aplicação:

1.  **Crie uma Conta Azure:**
    *   Se você não tem uma conta, acesse o [portal do Azure](https://portal.azure.com/) e crie uma conta gratuita.

2.  **Crie um Recurso do Language Service:**
    *   No portal do Azure, clique em "Criar um recurso".
    *   Pesquise por "Language Service" e selecione o recurso.
    *   Clique em "Criar".
    *   Preencha os detalhes do recurso:
        *   **Assinatura:** Selecione sua assinatura.
        *   **Grupo de recursos:** Crie um novo grupo de recursos ou selecione um existente.
        *   **Região:** Escolha a região mais próxima.
        *   **Nome:** Dê um nome ao seu recurso (ex: `meu-language-service`).
        *   **Tipo de preço:** Selecione um plano de preços. (O plano gratuito é suficiente para testes.)
    *   Clique em "Revisar + criar" e depois em "Criar".

3.  **Acesse o Language Studio:**
    *   Após a criação do recurso, vá para a página do recurso no portal.
    *   Na seção "Gerenciamento de recursos", clique em "Language Studio".

4.  **Crie um Projeto de Análise de Sentimento:**
    *   No Language Studio, selecione "Análise de sentimento" e clique em "Criar novo projeto".
    *   Dê um nome ao seu projeto (ex: `analise-sentimento-projeto`).
    *   Escolha o idioma padrão do seu projeto.
    *   Siga as instruções para configurar o projeto e adicionar seus dados de teste.

5.  **Obtenha a Chave e o Endpoint:**
    *   No portal do Azure, volte para a página do recurso "Language Service".
    *   Na seção "Gerenciamento de recursos", clique em "Chaves e Endpoint".
    *   Copie a chave de acesso e o endpoint para usar em suas aplicações.

Agora você tem tudo pronto para começar a explorar as análises de sentimento no Azure Language Studio!

## 🖼️ Análises e Processos Detalhados

### Análise 1: Sentimento Predominante

![image](https://github.com/user-attachments/assets/6ea65f38-070e-413c-92d1-b8861bae1782)

**Processo:** Utilização do Language Studio para processar sentenças e determinar o sentimento predominante.

**Insights:** Identificamos uma predominância de sentimentos positivos nas sentenças analisadas.

**Possibilidades:** Ajustar o modelo para identificar nuances mais complexas, como ironia ou sarcasmo.

---
### Análise 2: Comparação de Modelos

![image](https://github.com/user-attachments/assets/6ec0fffc-491b-4b5c-86d6-669e95e206b1)

**Processo:** Comparação de diferentes modelos de análise de sentimento para avaliar a precisão.

**Insights:** O Modelo X apresentou maior acurácia em relação ao Modelo Y.

**Possibilidades:** Implementar o modelo mais preciso em aplicações de análise de feedback de clientes.

---
### Análise 3: Sentimentos em Tempo Real

![image](https://github.com/user-attachments/assets/817796cb-612c-4933-a902-63111d5e494f)

**Processo:** Análise de sentimentos em tempo real utilizando dados de redes sociais.

**Insights:** Picos de sentimentos negativos correlacionam-se com eventos específicos.

**Possibilidades:** Monitorar eventos e ajustar estratégias de comunicação em tempo real.

---

### Análise 4: Análise Multilinguística

![image](https://github.com/user-attachments/assets/856e2fdd-b9e7-49cd-9ba9-8dbdb5d83849)

**Processo:** Avaliação de sentimentos em diferentes idiomas.

**Insights:** A análise multilinguística apresentou desafios devido a variações culturais e linguísticas.

**Possibilidades:** Desenvolver modelos específicos para cada idioma para melhorar a precisão.

---

### Análise 5: Integração com BI

![image](https://github.com/user-attachments/assets/89954ac1-20cf-47fa-8e1c-af4473554103)

**Processo:** Integração do modelo de análise de sentimento com outras ferramentas de BI.

**Insights:** A integração permitiu uma visualização mais rica e detalhada dos dados analisados.

**Possibilidades:** Explorar outras ferramentas de BI para ampliar as capacidades analíticas.

---
### Análise 6: Análise de Dados Históricos

![image](https://github.com/user-attachments/assets/d558aa82-9462-48a3-b247-eae8f9e15aa7)

**Processo:** Análise de sentimentos em dados históricos.

**Insights:** Identificação de tendências de sentimento ao longo do tempo.

**Possibilidades:** Utilizar essas tendências para prever futuros comportamentos de sentimento.

---
### Análise 7: Comparação Manual vs. Automatizada

![image](https://github.com/user-attachments/assets/20d8ea59-83c9-4110-90ff-0d6f3b578032)

**Processo:** Comparação entre análises manuais e automatizadas.

**Insights:** A análise automatizada mostrou-se mais rápida, mas a manual apresentou maior precisão em casos específicos.

**Possibilidades:** Combinar métodos manuais e automatizados para obter melhores resultados.

---

## 💡 Próximos Passos

- Refinar modelos para tratar nuances de linguagem.
- Expandir a análise para outros conjuntos de dados.
- Aprofundar a integração com outras ferramentas e plataformas.
- Explorar o uso da análise de sentimento para tomada de decisões.

Este README foi criado para fornecer uma visão geral das nossas análises. Esperamos que seja útil para outros interessados na área.
