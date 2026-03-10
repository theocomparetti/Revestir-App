# Revestir-App
Documentação e modelação de arquitetura para um sistema solidário de doações.
# 🚀 Projeto Revestir: Engenharia de Requisitos e Arquitetura de Sistemas

## 📌 O Desafio e Objetivo do Negócio
[span_0](start_span)O projeto Revestir foi idealizado para conectar diferentes classes sociais através da doação de roupas, promovendo a solidariedade e a redução do desperdício[span_0](end_span). [span_1](start_span)O objetivo central do sistema é a arrecadação de roupas e a sua doação a quem mais necessita, interligando doadores e organizações sem fins lucrativos de forma ágil e segura[span_1](end_span). O meu papel incidiu na estruturação lógica, documentação técnica e modelação da arquitetura base.

## ⚙️ Infraestrutura e Modelação de Dados
Para garantir que a aplicação fosse escalável e de fácil manutenção, a infraestrutura e a gestão de dados foram planeadas considerando as melhores práticas do mercado:
* **[span_2](start_span)[span_3](start_span)Backend e APIs:** A arquitetura do servidor foi planeada utilizando Node.js com Express, privilegiando a escalabilidade e a fácil integração através de APIs RESTful[span_2](end_span)[span_3](end_span).
* **[span_4](start_span)Bases de Dados:** Foi considerada a utilização do SQLite como uma solução relacional leve e embutida[span_4](end_span)[span_5](start_span), existindo a viabilidade de expansão para sistemas mais robustos como o MongoDB (NoSQL) ou PostgreSQL (SQL) consoante a evolução da estrutura de dados[span_5](end_span).
* **[span_6](start_span)Interoperabilidade:** O sistema foi desenhado para consumir APIs abertas, permitindo funcionalidades como a geolocalização (via Google Maps) para facilitar a descoberta de pontos de recolha e beneficiários próximos[span_6](end_span).

## 📋 Engenharia de Requisitos (Visão de Gestão de TI)
A definição clara das regras de negócio é fundamental para o sucesso de qualquer implementação tecnológica. O projeto foi mapeado dividindo as necessidades operacionais:
* **[span_7](start_span)Requisitos Funcionais:** Estruturação da lógica de registo de utilizadores, autenticação[span_7](end_span)[span_8](start_span), gestão detalhada do inventário de doações (categorização, tamanho, condição e fotos)[span_8](end_span) [span_9](start_span)e implementação de um sistema de mensagens/notificações entre as partes[span_9](end_span).
* **[span_10](start_span)Requisitos Não Funcionais (Performance e Operação):** Foco num baixo tempo de resposta em todas as funcionalidades[span_10](end_span)[span_11](start_span), otimização para diferentes dispositivos e redes[span_11](end_span)[span_12](start_span), e portabilidade com compatibilidade transversal a diversos sistemas operativos e navegadores[span_12](end_span).

## 🔒 Segurança da Informação e Conformidade (Compliance)
Um dos pilares deste projeto foi garantir a integridade dos dados dos utilizadores e a conformidade legal:
* **[span_13](start_span)[span_14](start_span)Governança de Dados:** O sistema foi desenhado em total conformidade com a LGPD (Lei Geral de Proteção de Dados), garantindo políticas de privacidade transparentes sobre a recolha e uso das informações pessoais[span_13](end_span)[span_14](end_span).
* **[span_15](start_span)[span_16](start_span)Autenticação:** Planeamento de autenticação segura utilizando o padrão JWT (JSON Web Tokens) para validar os acessos[span_15](end_span)[span_16](end_span).
* **[span_17](start_span)[span_18](start_span)Criptografia e Proteção:** Previsão de armazenamento seguro de senhas através de algoritmos de hash como o bcrypt, além da utilização de criptografia para dados em trânsito (SSL/TLS) e dados em repouso (AES)[span_17](end_span)[span_18](end_span).

## 💡 Conclusão
[span_19](start_span)Este projeto académico permitiu-me aplicar na prática os conceitos de modularidade, gestão de requisitos, segurança e tratamento de erros[span_19](end_span). [span_20](start_span)Compreendi que a construção de um sistema robusto vai muito além do código: exige uma visão estratégica para garantir que a tecnologia cumpra de facto o seu propósito e cause um impacto social positivo[span_20](end_span).
