# 📖 Capítulo 6

# Levantamento de Requisitos

<img width="170" height="241" alt="image" src="https://github.com/user-attachments/assets/a7c1cc74-345c-45b7-91b6-c7bab9bd62f5" />


## Introdução

Depois de compreender o problema de negócio, conhecer os stakeholders e fazer as perguntas certas, chega o momento de organizar todas essas informações.

Essa etapa é chamada de **levantamento de requisitos**.

Os requisitos representam tudo aquilo que a solução deverá atender para gerar valor ao negócio. Eles funcionam como um guia para toda a equipe envolvida no projeto, reduzindo ambiguidades e evitando retrabalho.

Sem requisitos bem definidos, diferentes pessoas podem interpretar o mesmo problema de maneiras distintas, comprometendo a qualidade da entrega.

---

## O que são requisitos?

Requisitos são necessidades ou expectativas que a solução deve atender.

Eles descrevem o que será desenvolvido, quais informações deverão estar disponíveis e quais regras deverão ser respeitadas durante a construção do projeto.

Um bom levantamento de requisitos garante que todos os envolvidos compartilhem a mesma visão sobre os objetivos da solução.

---

## Tipos de requisitos

Durante um projeto de Engenharia de Dados, normalmente trabalhamos com dois grupos principais.

### Requisitos Funcionais

Descrevem **o que a solução deve fazer**.

Exemplos:

- Integrar dados de diferentes sistemas.
- Calcular indicadores de churn.
- Disponibilizar uma tabela para consumo pelo BI.
- Atualizar os dados diariamente.

---

### Requisitos Não Funcionais

Descrevem **como a solução deve funcionar**.

Exemplos:

- Garantir alta disponibilidade.
- Permitir crescimento do volume de dados.
- Possuir controle de acesso.
- Executar o processamento em até 30 minutos.
- Registrar logs de execução.

Embora não estejam diretamente ligados às funcionalidades, esses requisitos são fundamentais para a qualidade da solução.

# 🧩 Estudo de Caso

Na **CloudOffice**, após as reuniões com as áreas envolvidas, foram definidos alguns requisitos.

### Funcionais

- Consolidar informações de clientes, assinaturas e pagamentos.
- Calcular mensalmente a taxa de cancelamento.
- Disponibilizar indicadores para o time de BI.

### Não Funcionais

- Atualização diária às 2h da manhã.
- Histórico completo dos últimos cinco anos.
- Controle de acesso por área da empresa.
- Monitoramento automático das pipelines.

Com esses requisitos documentados, toda a equipe passou a trabalhar com os mesmos objetivos.

---

## Boas práticas

Durante o levantamento de requisitos, algumas práticas ajudam a evitar problemas futuros.

- Documentar todas as decisões.
- Validar os requisitos com os stakeholders.
- Evitar interpretações subjetivas.
- Priorizar requisitos realmente importantes.
- Revisar continuamente conforme o projeto evolui.

Lembre-se de que requisitos podem mudar ao longo do tempo. Por isso, a comunicação entre negócio e tecnologia deve ser constante.

---

## Conclusão

O levantamento de requisitos transforma necessidades do negócio em objetivos claros para a equipe técnica.

Essa documentação servirá como base para todas as decisões de arquitetura, modelagem e desenvolvimento que serão tomadas nos próximos capítulos.

Agora que sabemos o que deve ser construído, é hora de descobrir de onde virão as informações necessárias.

---


