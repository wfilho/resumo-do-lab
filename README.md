# Resumo LAB

# Benefícios da Nuvem Azure – Resumo do Módulo (AZ-800)

Este módulo abordou os principais benefícios da computação em nuvem com foco na plataforma **Microsoft Azure**, destacando sua aplicabilidade em ambientes híbridos — combinando infraestrutura local com recursos em nuvem.

---

## 1. Benefícios da Nuvem Azure

Foi tratado como a adoção da nuvem Azure permite às organizações modernizar sua infraestrutura, reduzir custos operacionais e acessar tecnologias de ponta com alta disponibilidade e escalabilidade. Também foi abordada a importância da integração com ambientes locais, fundamental para estratégias híbridas.

---

## 2. Escalabilidade e Elasticidade

Foi tratado como a nuvem Azure permite ajustar a capacidade de processamento conforme a demanda do negócio.  
- **Escalabilidade**: capacidade de aumentar recursos vertical ou horizontalmente.
- **Elasticidade**: ajuste automático de recursos em tempo real, garantindo eficiência e controle de custos, especialmente em ambientes com variações de carga.

---

## 3. Confiabilidade, Previsibilidade e Segurança

Foi discutido como o Azure assegura:
- **Confiabilidade**, por meio de alta disponibilidade, redundância e failover automático.
- **Previsibilidade**, com modelos de cobrança baseados em consumo e ferramentas de monitoramento que facilitam o controle financeiro.
- **Segurança**, com criptografia, políticas de acesso, certificações internacionais e um ecossistema robusto voltado à proteção de dados e conformidade.

---

## 4. Governança e Gerenciabilidade

Neste tópico foi tratado como o Azure oferece controle e visibilidade sobre os ambientes:
- **Governança**: aplicação de políticas, controle de custos e gestão de identidades.
- **Gerenciabilidade**: monitoramento centralizado, automação de tarefas e padronização de configurações para garantir consistência, segurança e agilidade operacional.

---

## Tabela de SLA – Tempo Máximo de Inatividade Permitido

A tabela abaixo mostra quanto tempo de inatividade é tolerado com base no percentual de SLA acordado. Quanto maior o SLA, menor o tempo aceitável de indisponibilidade do serviço.

| **SLA**     | **Tempo de inatividade por semana** | **Tempo de inatividade por mês** | **Tempo de inatividade por ano** |
|-------------|-------------------------------------|----------------------------------|----------------------------------|
| 99%         | 1,68 hora                           | 7,2 horas                        | 3,65 dias                        |
| 99,9%       | 10,1 minutos                        | 43,2 minutos                     | 8,76 horas                       |
| 99,95%      | 5 minutos                           | 21,6 minutos                     | 4,38 horas                       |
| 99,99%      | 1,01 minuto                         | 4,32 minutos                     | 52,56 minutos                    |
| 99,999%     | 6 segundos                          | 25,9 segundos                    | 5,26 minutos                     |

### O que é SLA?

SLA (Service Level Agreement ou Acordo de Nível de Serviço) define o compromisso de disponibilidade e desempenho entre o provedor do serviço e o cliente. Ele especifica quanto tempo o serviço pode ficar indisponível em determinado período (semana, mês ou ano) sem descumprir o contrato. 

Essas métricas são fundamentais para aplicações críticas, pois influenciam diretamente no planejamento de contingência, na definição de estratégias de alta disponibilidade e nos critérios para escolha de provedores de nuvem ou infraestrutura. SLAs mais elevados, como 99,99% ou 99,999%, são normalmente exigidos em serviços financeiros, saúde, telecomunicações e outros setores que não podem tolerar indisponibilidades.

> **Importante**: Ao planejar uma arquitetura de alta disponibilidade, é essencial considerar o SLA de cada componente da solução, já que a falha de um único serviço pode impactar toda a operação.

---

> **Curso**: XP Inc. - Cloud com Inteligência Artificial
> **Plataforma**: DIO
