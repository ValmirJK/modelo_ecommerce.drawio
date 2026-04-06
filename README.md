# Projeto: Modelagem de Banco de Dados - E-commerce Refinado

Este repositório apresenta o refinamento do modelo conceitual de um sistema de E-commerce, desenvolvido para atender a requisitos de negócio específicos de identificação de cliente, pagamentos e logística.

## 📝 Descrição do Projeto
O objetivo foi evoluir um esquema de banco de dados para suportar regras de negócio mais robustas, garantindo a integridade dos dados e a rastreabilidade das operações.

## 🛠️ Requisitos Atendidos
- **Diferenciação de Cliente (PF/PJ):** Implementação de regra onde o cliente é Pessoa Física (CPF) ou Pessoa Jurídica (CNPJ), sendo mutuamente exclusivo.
- **Gestão de Pagamentos:** Suporte ao cadastro de múltiplas formas de pagamento por cliente.
- **Logística de Entrega:** Entidade dedicada para controle de status e código de rastreio de cada pedido.

## 📐 Estrutura do Modelo
O esquema foi desenhado utilizando o **draw.io**.
- Arquivo editável: `modelo_ecommerce.drawio`
- Representação visual: `modelo_ecommerce.png`

## 🚀 Como visualizar
1. O diagrama está disponível na imagem abaixo.
2. Para edições, faça o download do arquivo `.drawio` e abra em [app.diagrams.net](https://app.diagrams.net/).

![Diagrama do Projeto](modelo_ecommerce.png)
