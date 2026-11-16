# 🚘 Dashboard Estratégico de Marketing — Porsche

Projeto de análise de dados e visualização interativa desenvolvida para orientar campanhas comerciais da Porsche, identificando modelos mais rentáveis, mercados prioritários e perfis de conversão.

---

## 📂 Estrutura do Projeto

* **`PLANILHA_DO_EXCEL_PORSHE.xlsx`**: Base de dados contendo histórico de vendas, modelos, localização geográfica, formas de pagamento e status de entrega.
* **`perguntas de negócio e prompt projeto3.docx`**: Documento de planejamento analítico com as perguntas de negócio e diretrizes utilizadas para instruir a Inteligência Artificial.
* **`index.html`**: Dashboard web responsivo gerado a partir da análise dos dados, apresentando KPIs, métricas de desempenho e insights acionáveis.

---

## 🤖 A Importância de Prompts Simples e Direcionados

A construção deste dashboard demonstra como **prompts claros, objetivos e orientados a perguntas de negócio** aceleram a entrega de valor em projetos de dados:

* **Foco no que importa:** Em vez de pedir uma "análise geral", o direcionamento por etapas (*Produto ➜ Localização ➜ Perfil de Compra ➜ Ação*) guia a IA a extrair exatamente os indicadores necessários para a tomada de decisão.
* **Agilidade na prototipação:** Instruções bem estruturadas permitem transformar planilhas brutas em interfaces visuais funcionais (`HTML/CSS`) em poucos minutos.

---

## ⚠️ Boas Práticas: Prevenção de Alucinações e Privacidade de Dados

Ao utilizar ferramentas de Inteligência Artificial para análise de dados e geração de código, dois cuidados são indispensáveis:

### 1. Como evitar que a IA "alucine"
* **Contextualização fechada:** Forneça sempre a base de dados real e instrua a IA a responder *exclusivamente* com base nos números enviados, sem estimar ou inventar métricas ausentes.
* **Prompts granulares:** Divida solicitações complexas em perguntas menores e lógicas (como feito no documento de planejamento), facilitando a validação de cada cálculo gerado antes de avançar para o visual.
* **Auditoria humana:** Sempre confira os KPIs exibidos no front-end (`index.html`) cruzando-os com as fórmulas da planilha original.

### 2. Segurança e Privacidade (LGPD) — Nunca envie dados sensíveis
* **Anonimização obrigatória:** Jamais insira informações pessoais identificáveis (PII) em prompts ou planilhas enviadas a ferramentas de IA públicas, tais como **nome completo, CPF, RG, endereço residencial, telefone ou dados bancários**.
* **Uso de IDs e dados agregados:** Substitua identificadores pessoais por códigos anônimos (ex: `Cliente_001`) e utilize recortes geográficos amplos (como Cidade ou Estado) em vez de endereços exatos, garantindo conformidade com a **LGPD** e a segurança corporativa.
