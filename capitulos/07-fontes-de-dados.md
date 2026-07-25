# 📖 Capítulo 7

# Fontes de Dados

<img width="195" height="221" alt="image" src="https://github.com/user-attachments/assets/c5a61552-51e3-4746-aff9-40ded244e4d0" />


## Introdução

Depois de compreender o problema de negócio e levantar os requisitos da solução, chega o momento de identificar uma das partes mais importantes de qualquer projeto de Engenharia de Dados: as fontes de dados.

Não existe pipeline, dashboard ou modelo analítico sem dados de origem.

O papel do Engenheiro de Dados é localizar essas informações, entender como são geradas e avaliar se possuem qualidade suficiente para atender às necessidades do negócio.

Essa etapa evita que decisões importantes sejam tomadas com base em informações incompletas ou inconsistentes.

---

## O que são fontes de dados?

Fontes de dados são todos os locais onde as informações utilizadas pela empresa são armazenadas ou produzidas.

Esses dados podem estar distribuídos em diversos sistemas, plataformas ou arquivos.

Alguns exemplos são:

- Bancos de dados relacionais
- APIs
- Sistemas ERP
- Sistemas CRM
- Arquivos CSV
- Planilhas Excel
- Aplicações Web
- Sistemas legados
- Plataformas de Marketing
- Sensores IoT
- Logs de aplicações

Na prática, um único projeto pode consumir dados provenientes de dezenas de fontes diferentes.

---

## Conhecendo cada fonte

Encontrar uma base de dados não significa que ela esteja pronta para ser utilizada.

Antes de iniciar qualquer integração, o Engenheiro de Dados precisa responder perguntas importantes.

### Quem é o responsável pelos dados?

Toda fonte deve possuir uma área responsável pela manutenção das informações.

### Com que frequência os dados são atualizados?

- Tempo real
- A cada hora
- Diariamente
- Semanalmente

Essa resposta influencia diretamente a arquitetura da solução.

### Os dados são confiáveis?

É necessário verificar:

- Dados duplicados
- Valores nulos
- Informações inconsistentes
- Registros incompletos
- Problemas de padronização

Quanto maior a qualidade da origem, menor será o esforço de tratamento posteriormente.

---

## Estudo de Caso

Na **CloudOffice**, o objetivo é entender por que os clientes estão cancelando suas assinaturas.

Durante a investigação foram identificadas quatro fontes principais.

### Sistema de Assinaturas

Contém informações sobre:

- Cliente
- Plano contratado
- Data da contratação
- Situação da assinatura

### Sistema Financeiro

Responsável pelos pagamentos.

Permite identificar:

- Inadimplência
- Valor pago
- Data de vencimento

### CRM

Armazena o relacionamento com o cliente.

Inclui:

- Chamados
- Reclamações
- Histórico de atendimento

### Google Analytics

Fornece informações sobre o comportamento dos usuários na plataforma.

Cada uma dessas fontes responde apenas parte do problema.

Somente quando integradas é possível obter uma visão completa do cliente.

---

## Nem todos os dados são necessários

Um erro comum em projetos de Engenharia de Dados é tentar importar todas as tabelas disponíveis.

Mais dados não significam mais conhecimento.

O ideal é selecionar apenas as informações que realmente ajudam a responder às perguntas definidas durante o levantamento de requisitos.

Essa abordagem reduz custos, simplifica as pipelines e facilita a manutenção da solução.

---

## Boas práticas

Ao identificar novas fontes de dados, procure sempre documentar:

- Nome da fonte
- Responsável
- Frequência de atualização
- Formato dos dados
- Método de acesso
- Volume estimado
- Principais regras de negócio
- Problemas conhecidos

Essa documentação será extremamente útil durante toda a evolução do projeto.

---

## Conclusão

Conhecer as fontes de dados significa compreender a origem das informações que sustentarão toda a solução analítica.

Uma arquitetura de dados confiável começa com fontes bem identificadas, documentadas e compreendidas.

No próximo capítulo veremos como as regras de negócio influenciam a interpretação desses dados e por que duas empresas podem utilizar a mesma informação de maneiras completamente diferentes.

---

⬅️ **Capítulo anterior:** [Levantamento de Requisitos](06-levantamento-de-requisitos.md)

➡️ **Próximo capítulo:** [Regras de Negócio](08-regras-de-negocio.md)
