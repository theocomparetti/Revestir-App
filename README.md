# Revestir-App
Documentação e modelação de arquitetura para um sistema solidário de doações.
# 🚀 Projeto Revestir: Engenharia de Requisitos e Arquitetura de Sistemas

## 📌 O Desafio de Negócio
[span_0](start_span)O projeto Revestir foi idealizado para conectar diferentes classes sociais, visando a doação de roupas para promover a solidariedade e reduzir o desperdício[span_0](end_span). [span_1](start_span)O aplicativo foca na arrecadação e doação para quem necessita, interligando doadores e organizações sem fins lucrativos[span_1](end_span).

## ⚙️ Arquitetura e Modelagem de Dados
[span_2](start_span)Para garantir escalabilidade e eficiência, a infraestrutura e os dados foram planejados com foco em boas práticas de mercado[span_2](end_span):
* **[span_3](start_span)[span_4](start_span)Backend:** Estruturação utilizando Node.js com Express para o servidor, garantindo fácil integração com APIs RESTful[span_3](end_span)[span_4](end_span).
* **[span_5](start_span)Banco de Dados:** Utilização do SQLite, um banco de dados relacional leve e embutido[span_5](end_span)[span_6](start_span), com modelagem preparada para futura migração para MongoDB ou PostgreSQL conforme a escalabilidade exigida[span_6](end_span).
* **[span_7](start_span)Interoperabilidade:** Planejamento de consumo de APIs abertas, como Google Maps para geolocalização de pontos de coleta[span_7](end_span) [span_8](start_span)e integração com redes sociais[span_8](end_span).

## 📋 Engenharia de Requisitos
[span_9](start_span)Mapeamento detalhado das necessidades operacionais do sistema[span_9](end_span):
* **[span_10](start_span)Requisitos Funcionais:** Estruturação do fluxo de cadastro[span_10](end_span)[span_11](start_span), autenticação de usuários[span_11](end_span)[span_12](start_span), gestão de itens para doação[span_12](end_span) [span_13](start_span)e sistema interno de mensagens e notificações[span_13](end_span).
* **[span_14](start_span)Requisitos Não Funcionais:** Foco na eficiência com baixo tempo de resposta[span_14](end_span)[span_15](start_span), usabilidade com interface intuitiva[span_15](end_span) [span_16](start_span)e portabilidade entre diferentes sistemas operacionais[span_16](end_span).

## 🔒 Segurança da Informação e Governança
[span_17](start_span)[span_18](start_span)A proteção dos dados e a conformidade legal foram tratadas como prioridades no desenvolvimento[span_17](end_span)[span_18](end_span):
* **[span_19](start_span)[span_20](start_span)Compliance:** Sistema projetado em total conformidade com a LGPD (Lei Geral de Proteção de Dados), garantindo a privacidade dos usuários[span_19](end_span)[span_20](end_span).
* **[span_21](start_span)Autenticação Segura:** Implementação do padrão JWT (JSON Web Tokens)[span_21](end_span) [span_22](start_span)e previsão de Autenticação Multifator (MFA)[span_22](end_span).
* **[span_23](start_span)[span_24](start_span)Criptografia:** Utilização de algoritmos de hash seguros (bcrypt) para armazenamento de senhas[span_23](end_span)[span_24](end_span)[span_25](start_span), além de criptografia SSL/TLS para dados em trânsito e AES para dados em repouso[span_25](end_span).
