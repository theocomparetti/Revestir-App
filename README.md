# projeto-revestir-arquitetura
Documentação e modelação de arquitetura para um sistema solidário de doações.
# 🚀 Projeto Revestir: Engenharia de Requisitos e Arquitetura de Sistemas

![Image](https://github.com/user-attachments/assets/3504f8d3-678e-42a7-a91b-a77e0dd3632a)

## 📌 O Desafio de Negócio
O projeto Revestir foi idealizado para conectar diferentes classes sociais, visando a doação de roupas para promover a solidariedade e reduzir o desperdício. O aplicativo foca na arrecadação e doação para quem necessita, interligando doadores e organizações sem fins lucrativos.

## ⚙️ Arquitetura e Modelagem de Dados
Para garantir escalabilidade e eficiência, a infraestrutura e os dados foram planejados com foco em boas práticas de mercado:
* **Backend:** Estruturação utilizando Node.js com Express para o servidor, garantindo fácil integração com APIs RESTful.
* **Banco de Dados:** Utilização do SQLite, um banco de dados relacional leve e embutido, com modelagem preparada para futura migração para MongoDB ou PostgreSQL conforme a escalabilidade exigida.
* **Interoperabilidade:** Planejamento de consumo de APIs abertas, como Google Maps para geolocalização de pontos de coleta e integração com redes sociais.

## 📋 Engenharia de Requisitos
Mapeamento detalhado das necessidades operacionais do sistema:
* **Requisitos Funcionais:** Estruturação do fluxo de cadastro, autenticação de usuários, gestão de itens para doação e sistema interno de mensagens e notificações.
* **Requisitos Não Funcionais:** Foco na eficiência com baixo tempo de resposta, usabilidade com interface intuitiva e portabilidade entre diferentes sistemas operacionais.

## 🔒 Segurança da Informação e Governança
A proteção dos dados e a conformidade legal foram tratadas como prioridades no desenvolvimento:
* **Compliance:** Sistema projetado em total conformidade com a LGPD (Lei Geral de Proteção de Dados), garantindo a privacidade dos usuários.
* **Autenticação Segura:** Implementação do padrão JWT (JSON Web Tokens) e previsão de Autenticação Multifator (MFA).
* **Criptografia:** Utilização de algoritmos de hash seguros (bcrypt) para armazenamento de senhas, além de criptografia SSL/TLS para dados em trânsito e AES para dados em repouso.
* **SITE PRONTO:** [REVESTIR.WEBSITE.pdf](https://github.com/user-attachments/files/25877684/REVESTIR.WEBSITE.pdf)
* **TELA LOGIN:**  ![Image](https://github.com/user-attachments/assets/fdb5f4be-11f2-46f8-a446-039ccc6c278e)
*
