# Minha Carteira 📊

Plataforma web para **gestão, acompanhamento e análise de investimentos**, desenvolvida para centralizar informações financeiras e oferecer uma visão clara da evolução patrimonial do investidor.

O objetivo do projeto é permitir que usuários acompanhem suas carteiras de investimentos, registrem operações, monitorem rentabilidade e controlem a distribuição de seus ativos por meio de metas de alocação.

Além de funcionar como uma ferramenta de gestão financeira, o projeto busca aplicar conceitos de desenvolvimento Full Stack, integração entre serviços, automação de processos e análise de dados.

## 🎯 Objetivo do projeto

Desenvolver uma plataforma que permita ao investidor ter maior controle sobre seu patrimônio, acompanhando diferentes classes de ativos em um único ambiente.

A aplicação contará com recursos para:

- Cadastrar e gerenciar carteiras de investimentos.
- Adicionar ativos como criptomoedas, ações, FIIs e renda fixa.
- Registrar operações de compra e venda.
- Acompanhar cotações e valores atualizados dos ativos.
- Visualizar patrimônio total e evolução da carteira.
- Monitorar rentabilidade e histórico de movimentações.
- Definir metas percentuais de alocação por ativo.
- Comparar a distribuição atual da carteira com a distribuição desejada.
- Identificar desvios de alocação e valores necessários para rebalanceamento.

## ⚙️ Funcionalidades

### Gestão de carteira
Cadastro de carteiras, ativos e operações financeiras, permitindo acompanhar a composição do patrimônio e o histórico de movimentações.

### Dashboard financeiro
Visualização consolidada das informações da carteira, incluindo:

- Patrimônio total.
- Distribuição por classe de ativos.
- Rentabilidade.
- Evolução patrimonial.
- Histórico de aportes e movimentações.

### Metas de alocação
Possibilidade de definir um percentual desejado para cada ativo ou categoria.

O sistema compara a alocação real com a meta estabelecida, apresentando:

- Percentual atual.
- Percentual desejado.
- Desvio em pontos percentuais.
- Diferença financeira para atingir a alocação desejada.

### Assinaturas e conteúdo exclusivo
A plataforma contará com dois níveis de acesso:

- **Standard:** funcionalidades de gestão e acompanhamento de investimentos.
- **Premium:** recursos Standard e acesso a conteúdos exclusivos, como artigos, materiais e vídeos.

O controle de permissões será realizado no backend, considerando o status da assinatura e as funcionalidades disponíveis em cada plano.

## 🛠️ Stack tecnológica

### Frontend
- **Next.js:** framework React para desenvolvimento da interface e recursos de renderização.
- **TypeScript:** tipagem estática e maior segurança no desenvolvimento.
- **Tailwind CSS + shadcn/ui:** estilização e organização dos estilos.

### Backend
- **Node.js:** ambiente de execução JavaScript.
- **NestJS:** framework para construção de uma API modular e escalável.
- **TypeScript:** padronização e segurança de tipos.
- **REST API:** comunicação entre frontend, backend e serviços externos.

### Banco de dados e ORM
- **PostgreSQL:** armazenamento relacional dos dados da aplicação.
- **Prisma ORM:** mapeamento das entidades, consultas e gerenciamento de migrations.

### Autenticação e segurança
- **JWT:** validação de identidade e autorização das requisições.
- **Guards e RBAC:** controle de acesso baseado em permissões e níveis de usuário.
- **Environment Variables:** gerenciamento de credenciais e configurações sensíveis.

### Integrações e serviços externos
- **Stripe:** processamento de assinaturas e pagamentos.
- **CoinGecko API:** consulta de cotações de criptomoedas.
- **APIs financeiras:** integração para obtenção de cotações de outros ativos.
- **n8n:** automação de processos e integração entre serviços.
- **Brevo:** envio de e-mails transacionais e notificações.


## 🔄 Integrações e automações

- Consulta periódica de cotações de mercado.
- Atualização dos valores dos ativos.
- Processamento de pagamentos e eventos de assinatura via webhooks.
- Envio automatizado de notificações e e-mails.

## 🚀 Status do projeto

<sub>Em desenvolvimento — funcionalidades e integrações serão implementadas progressivamente.</sub>
