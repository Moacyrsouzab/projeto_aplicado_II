# Análise de Assinaturas e Cancelamentos NETFLIX - Projeto Aplicado II

## Equipe  
* *KAIQUE NASCIMENTO DE PAULA* - RA: 24024831  
* *MOACYR SOUZA BARROS* - RA: 10441179  
* *MIGUEL SHIRAISHI* - RA: 10431805  
* *FLÁVIO ESTEVAM NOGUEIRA* - RA: 10441572  

---

## 1. Definição da Organização  

### *Organização: Netflix*  
A Netflix é uma empresa global de entretenimento que oferece serviços de streaming de filmes, séries e documentários via internet. Sua plataforma está disponível em mais de 190 países e conta com uma ampla base de assinantes que podem escolher entre diferentes tipos de assinatura (Basic, Standard, Premium).  

### *Missão*  
Proporcionar uma experiência de entretenimento personalizada e de alta qualidade para seus assinantes ao redor do mundo, através de uma vasta biblioteca de conteúdos e de um serviço inovador.  

### *Modelo de Receita*  
A receita da Netflix é baseada em assinaturas mensais, com diferentes planos que oferecem variações na qualidade do streaming e no número de telas simultâneas. A empresa utiliza análises de dados extensivas para personalizar recomendações de conteúdo e otimizar a retenção de usuários.  

---

## 2. Apresentação dos Dados Utilizados (Metadados)  

A base de dados fornecida contém informações sobre os assinantes da plataforma, suas assinaturas e características demográficas.  

| Coluna              | Descrição                                                   | Tipo de Dado  |
|---------------------|------------------------------------------------------------|---------------|
| User ID            | Identificador único de cada usuário                        | Numérico     |
| Subscription Type  | Tipo de assinatura (Basic, Standard, Premium)              | Categórico   |
| Monthly Revenue    | Receita mensal gerada por cada usuário (em dólares)       | Numérico     |
| Join Date          | Data de adesão do usuário à plataforma (dd-mm-aa)         | Data         |
| Last Payment Date  | Data do último pagamento realizado pelo usuário (dd-mm-aa) | Data         |
| Country           | País de origem/residência do usuário                       | Categórico   |
| Age                | Idade do usuário                                           | Numérico     |
| Gender            | Gênero do usuário (Masculino, Feminino)                   | Categórico   |
| Device            | Dispositivo usado para acessar a plataforma                 | Categórico   |
| Plan Duration     | Duração do plano atual do usuário (1 mês, 6 meses, etc.)  | Categórico   |

---

## 3. Objetivos e Metas  

### *Objetivo Geral*  
Explorar dados demográficos e comportamentais dos assinantes da Netflix para gerar insights sobre comportamento do usuário, prever cancelamentos (*churn*) e identificar oportunidades de campanhas para aumentar a retenção e o engajamento.  

### *Objetivos Específicos*  
- Analisar o comportamento dos usuários com base no país, idade, gênero e dispositivo utilizado;  
- Identificar possíveis cancelamentos e desenvolver estudos/propostas para minimizar o churn;  
- Propor estratégias de retenção e campanhas de marketing com base nos dados analisados.  

---

## 4. Cronograma de Atividades (Estimativa)  

| Fase                        | Tarefa                                              | Status    | Data de Entrega |
|-----------------------------|----------------------------------------------------|----------|----------------|
| *Etapa 1*                 | Definição da organização, área de atuação e dados | Feito | 03/03/2025     |
| *Etapa 2*                 | Desenvolvimento de visualizações e narrativas     | Pendente | 31/03/2025     |
| *Etapa 3*                 | Análise dos resultados e previsão de churn       | Pendente | 28/04/2025     |
| *Etapa 4*                 | Apresentação final do projeto                     | Pendente | 26/05/2025     |

---

## 5. Estrutura do Repositório  

O projeto está organizado da seguinte forma no repositório:  

📂 projeto_aplicado_II
│
│-- 📁 data/ # Arquivos de dados utilizados na análise
│ │-- 📄 Netflix_Userbase.csv # Dataset com os dados da Netflix
│
│-- 📄 README.md # Documentação do projeto
