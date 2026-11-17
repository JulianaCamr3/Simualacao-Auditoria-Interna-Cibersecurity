# Simualacao-Auditoria-Interna-Cibersecurity
Simulação de uma auditoria interna de uma empresa fictícia para aplicar conhecimentos práticos da área de cibersegurança.

# Simulação de Auditoria Interna de Cibersegurança

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Category](https://img.shields.io/badge/Category-Cybersecurity-blue)
![Type](https://img.shields.io/badge/Type-Internal%20Security%20Audit-orange)

## 1. Introdução

Este projeto apresenta uma simulação de auditoria interna de cibersegurança realizada em uma empresa fictícia, com o objetivo de avaliar o nível de maturidade dos controles de segurança da informação, identificar vulnerabilidades, analisar riscos e propor medidas corretivas.

A auditoria foi estruturada considerando boas práticas e recomendações de frameworks reconhecidos internacionalmente:

- ISO/IEC 27001:2022 – Sistema de Gestão de Segurança da Informação.
- NIST Cybersecurity Framework 2.0.
- CIS Critical Security Controls v8.
- Lei Geral de Proteção de Dados (LGPD – Lei nº 13.709/2018).

> **Importante:** Este projeto é uma simulação educacional. A empresa, os sistemas, os ativos, os registros e as evidências apresentados são fictícios.

---

## 2. Identificação da Empresa

| Informação | Descrição |
|---|---|
| Empresa | TechSolutions Tecnologia Ltda. |
| Segmento | Desenvolvimento de software e serviços de TI |
| Funcionários | 120 |
| Localização | São Paulo - SP |
| Infraestrutura | Ambiente híbrido (Cloud e On-premises) |
| Sistemas operacionais | Windows 10/11 e Ubuntu Server |
| Provedor Cloud | Amazon Web Services (AWS) |
| Firewall | Firewall corporativo |
| Antivírus | Microsoft Defender |
| Monitoramento | Monitoramento básico de infraestrutura |
| Dados tratados | Dados pessoais de clientes e funcionários |

### 2.1. Contexto organizacional

A TechSolutions Tecnologia Ltda. é uma empresa fictícia que desenvolve soluções de software para outras organizações.

A empresa armazena informações de clientes, dados cadastrais, documentos corporativos e informações relacionadas aos seus funcionários.

Recentemente, a diretoria identificou a necessidade de melhorar os controles de segurança da informação após receber alertas sobre tentativas de acesso não autorizado aos seus sistemas.

Diante desse cenário, foi solicitada uma auditoria interna para avaliar os controles existentes e identificar possíveis riscos ao ambiente corporativo.

---

## 3. Objetivos da Auditoria

Os principais objetivos desta auditoria são:

1. Avaliar os controles de segurança da informação existentes.
2. Identificar vulnerabilidades na infraestrutura tecnológica.
3. Verificar a existência de políticas e procedimentos de segurança.
4. Avaliar os mecanismos de autenticação e controle de acesso.
5. Analisar a proteção dos endpoints corporativos.
6. Verificar os processos de backup e recuperação de dados.
7. Avaliar os mecanismos de monitoramento e registro de eventos.
8. Identificar riscos relacionados ao tratamento de dados pessoais.
9. Elaborar recomendações para reduzir os riscos identificados.

---

## 4. Escopo da Auditoria

A auditoria contempla os seguintes ambientes:

| Área | Escopo |
|---|---|
| Infraestrutura | Servidores, estações de trabalho e rede corporativa |
| Cloud | Recursos hospedados na AWS |
| Identidade e acesso | Contas de usuários, permissões e autenticação |
| Endpoints | Antivírus, atualizações e proteção das estações |
| Rede | Firewall, segmentação e controle de tráfego |
| Backup | Políticas de backup e recuperação |
| Monitoramento | Logs, alertas e acompanhamento de eventos |
| Governança | Políticas e procedimentos de segurança |
| Privacidade | Tratamento e proteção de dados pessoais |

### 4.1. Limitações

Esta simulação não contempla testes de invasão, exploração de vulnerabilidades ou acesso a sistemas reais.

As avaliações foram realizadas exclusivamente com base em cenários hipotéticos, documentos fictícios e evidências simuladas.

---

## 5. Metodologia

A auditoria foi dividida em cinco etapas.

### Etapa 1 – Planejamento

- Definição dos objetivos.
- Identificação dos ativos.
- Definição do escopo.
- Seleção dos controles que serão avaliados.

### Etapa 2 – Coleta de informações

- Análise de políticas internas.
- Revisão de configurações de segurança.
- Análise de registros de eventos.
- Verificação dos processos de gerenciamento de usuários.
- Entrevistas simuladas com responsáveis técnicos.

### Etapa 3 – Avaliação dos controles

Foram avaliados os controles de segurança considerando três classificações:

| Classificação | Significado |
|---|---|
| Conforme | O controle atende aos requisitos avaliados. |
| Parcialmente conforme | O controle existe, mas apresenta deficiências. |
| Não conforme | O controle não existe ou não atende aos requisitos mínimos avaliados. |

### Etapa 4 – Identificação e análise de riscos

Os problemas identificados foram classificados de acordo com sua criticidade.

| Criticidade | Descrição |
|---|---|
| Crítica | Risco elevado de comprometimento significativo dos ativos ou operações. |
| Alta | Pode permitir acesso não autorizado ou comprometer informações importantes. |
| Média | Representa uma deficiência que pode facilitar incidentes de segurança. |
| Baixa | Deficiência com impacto limitado, mas que deve ser corrigida. |

### Etapa 5 – Relatório e recomendações

Elaboração dos resultados, classificação das não conformidades e definição de um plano de ação para mitigação dos riscos.

---

# 6. Execução da Auditoria

## 6.1. Controle de acesso e autenticação

**Objetivo:** Verificar se os acessos aos sistemas corporativos são realizados de maneira segura e controlada.

**Procedimentos realizados:**

- Verificação da existência de políticas de senhas.
- Avaliação da utilização de autenticação multifator (MFA).
- Verificação das permissões de usuários.
- Análise do processo de criação e desativação de contas.
- Identificação de contas administrativas.

**Evidências simuladas:**

Durante a avaliação, foram identificados os seguintes problemas:

1. Alguns usuários possuem privilégios administrativos sem justificativa documentada.
2. A autenticação multifator não está habilitada em todos os serviços corporativos.
3. Existem contas de ex-funcionários que ainda permanecem habilitadas.
4. Não existe revisão periódica formal das permissões.

**Resultado:** Não conforme.

**Classificação do risco:** Alta.

**Recomendações:**

- Implementar autenticação multifator em todos os serviços que suportam o recurso.
- Aplicar o princípio do menor privilégio.
- Revisar periodicamente as permissões.
- Desativar imediatamente contas de usuários desligados.
- Implementar um processo formal de gerenciamento de identidades e acessos.

---

## 6.2. Segurança de endpoints

**Objetivo:** Avaliar a proteção das estações de trabalho e servidores corporativos.

**Procedimentos realizados:**

- Verificação da existência de antivírus.
- Avaliação das atualizações de segurança.
- Verificação das políticas de proteção.
- Análise da existência de ferramentas de monitoramento.

**Evidências simuladas:**

Foram identificadas as seguintes situações:

1. Algumas estações de trabalho estão com atualizações de segurança pendentes.
2. Não existe inventário atualizado de todos os endpoints.
3. Algumas máquinas não possuem políticas centralizadas de segurança.
4. Não existe monitoramento centralizado de todos os eventos de segurança.

**Resultado:** Parcialmente conforme.

**Classificação do risco:** Alta.

**Recomendações:**

- Implementar gerenciamento centralizado de endpoints.
- Estabelecer uma política de atualização de segurança.
- Manter inventário atualizado dos dispositivos.
- Centralizar os registros de eventos.
- Avaliar a implementação de uma solução EDR.

---

## 6.3. Segurança de rede

**Objetivo:** Avaliar os controles de proteção da rede corporativa.

**Procedimentos realizados:**

- Análise das políticas de firewall.
- Verificação da segmentação de rede.
- Avaliação das regras de entrada e saída.
- Identificação de serviços desnecessariamente expostos.

**Evidências simuladas:**

Durante a auditoria, foram identificados:

1. Regras de firewall excessivamente permissivas.
2. Ausência de segmentação adequada entre a rede administrativa e a rede de usuários.
3. Serviços de gerenciamento acessíveis a partir de redes não confiáveis.
4. Ausência de revisão periódica das regras de firewall.

**Resultado:** Não conforme.

**Classificação do risco:** Crítica.

**Recomendações:**

- Revisar todas as regras de firewall.
- Restringir o acesso administrativo a redes confiáveis.
- Implementar segmentação de rede.
- Remover regras desnecessárias.
- Registrar e documentar alterações nas políticas de firewall.

---

## 6.4. Segurança em Cloud Computing

**Objetivo:** Avaliar os controles de segurança dos recursos hospedados na AWS.

**Procedimentos realizados:**

- Análise das permissões IAM.
- Verificação dos Security Groups.
- Avaliação da exposição de recursos.
- Verificação da proteção de dados armazenados.
- Análise dos registros de atividades.

**Evidências simuladas:**

Foram identificados os seguintes problemas:

1. Existência de uma política IAM com permissões excessivas.
2. Um bucket S3 apresenta configuração de acesso público desnecessária.
3. Alguns recursos não possuem monitoramento adequado.
4. Não existe revisão periódica das permissões administrativas.

**Resultado:** Não conforme.

**Classificação do risco:** Crítica.

**Recomendações:**

- Aplicar o princípio do menor privilégio nas políticas IAM.
- Bloquear o acesso público desnecessário aos buckets S3.
- Habilitar o AWS CloudTrail.
- Implementar monitoramento dos recursos utilizando serviços como AWS CloudWatch.
- Realizar revisões periódicas das permissões e configurações.

---

## 6.5. Backup e recuperação de dados

**Objetivo:** Verificar se existem mecanismos adequados para proteger e recuperar informações corporativas.

**Procedimentos realizados:**

- Verificação da existência de rotinas de backup.
- Avaliação da frequência dos backups.
- Verificação da existência de cópias externas.
- Avaliação dos procedimentos de recuperação.

**Evidências simuladas:**

1. A empresa realiza backups semanais.
2. Não existe documentação formal do processo de recuperação.
3. Não são realizados testes periódicos de restauração.
4. Os backups não possuem uma política documentada de proteção contra alterações ou exclusão indevida.

**Resultado:** Parcialmente conforme.

**Classificação do risco:** Alta.

**Recomendações:**

- Implementar backups automatizados.
- Estabelecer políticas de retenção.
- Manter cópias isoladas ou imutáveis.
- Realizar testes periódicos de restauração.
- Definir os objetivos de recuperação RTO e RPO.

---

## 6.6. Monitoramento e gerenciamento de logs

**Objetivo:** Avaliar a capacidade de identificar atividades suspeitas e possíveis incidentes de segurança.

**Procedimentos realizados:**

- Verificação da existência de logs.
- Avaliação da centralização dos registros.
- Verificação de alertas de segurança.
- Análise dos procedimentos de resposta a incidentes.

**Evidências simuladas:**

Foram identificadas as seguintes deficiências:

1. Os registros de eventos estão distribuídos entre diferentes sistemas.
2. Não existe uma solução SIEM implementada.
3. Não existem alertas centralizados para tentativas suspeitas de autenticação.
4. A empresa não possui um procedimento formal de resposta a incidentes.

**Resultado:** Não conforme.

**Classificação do risco:** Alta.

**Recomendações:**

- Implementar uma solução SIEM.
- Centralizar os logs dos servidores, endpoints e dispositivos de rede.
- Criar alertas para atividades suspeitas.
- Definir procedimentos de investigação e escalonamento.
- Estabelecer um plano de resposta a incidentes.

---

## 6.7. Governança e políticas de segurança

**Objetivo:** Verificar a existência de políticas e procedimentos relacionados à segurança da informação.

**Procedimentos realizados:**

- Verificação da política de segurança da informação.
- Avaliação dos procedimentos internos.
- Análise dos processos de conscientização.
- Verificação da existência de gestão de riscos.

**Evidências simuladas:**

1. A empresa possui uma política de segurança desatualizada.
2. Não existe treinamento periódico de conscientização em segurança.
3. Não existe processo formal de avaliação de riscos.
4. Não há documentação adequada sobre responsabilidades relacionadas à segurança.

**Resultado:** Parcialmente conforme.

**Classificação do risco:** Média.

**Recomendações:**

- Atualizar a política de segurança da informação.
- Implementar treinamentos periódicos.
- Criar um processo formal de gestão de riscos.
- Definir responsabilidades e procedimentos de segurança.
- Estabelecer revisões periódicas das políticas.

---

## 6.8. Proteção de dados e conformidade com a LGPD

**Objetivo:** Avaliar os controles relacionados à proteção de dados pessoais.

**Procedimentos realizados:**

- Verificação dos mecanismos de controle de acesso.
- Avaliação da proteção dos dados armazenados.
- Análise dos procedimentos de retenção.
- Verificação da existência de processos relacionados aos direitos dos titulares.

**Evidências simuladas:**

1. Não existe inventário completo dos dados pessoais tratados.
2. Não existe documentação atualizada sobre o ciclo de vida dos dados.
3. Não há procedimento formal documentado para atendimento às solicitações dos titulares.
4. Não existe processo estruturado de avaliação de riscos de privacidade.

**Resultado:** Parcialmente conforme.

**Classificação do risco:** Alta.

**Recomendações:**

- Criar um inventário de dados pessoais.
- Documentar as atividades de tratamento.
- Implementar controles de acesso e proteção de dados.
- Estabelecer procedimentos para atendimento aos direitos dos titulares.
- Avaliar a necessidade de elaboração de Relatórios de Impacto à Proteção de Dados Pessoais (RIPD), conforme o contexto do tratamento.

---

# 7. Resumo dos Resultados

Após a avaliação dos oito domínios, foram identificadas as seguintes não conformidades:

| Domínio | Resultado | Risco |
|---|---|---|
| Controle de acesso | Não conforme | Alta |
| Segurança de endpoints | Parcialmente conforme | Alta |
| Segurança de rede | Não conforme | Crítica |
| Segurança em Cloud | Não conforme | Crítica |
| Backup | Parcialmente conforme | Alta |
| Monitoramento e logs | Não conforme | Alta |
| Governança | Parcialmente conforme | Média |
| Proteção de dados | Parcialmente conforme | Alta |

### 7.1. Indicadores da auditoria

| Indicador | Resultado |
|---|---:|
| Domínios avaliados | 8 |
| Domínios conformes | 0 |
| Domínios parcialmente conformes | 5 |
| Domínios não conformes | 3 |
| Não conformidades críticas | 2 |
| Não conformidades altas | 5 |
| Não conformidades médias | 1 |

**Conclusão dos indicadores:** A empresa apresenta deficiências relevantes em seus controles de segurança, principalmente em infraestrutura de rede, ambiente Cloud, gerenciamento de acessos e monitoramento.

---

# 8. Plano de Ação

Com base nos problemas identificados, foi elaborado o seguinte plano de ação:

| ID | Problema | Ação corretiva | Prioridade | Prazo sugerido |
|---|---|---|---|---|
| A01 | Firewall permissivo | Revisar e restringir regras de firewall | Crítica | 7 dias |
| A02 | Bucket S3 público | Revisar permissões e bloquear acesso público desnecessário | Crítica | Imediato |
| A03 | Permissões IAM excessivas | Aplicar menor privilégio | Alta | 15 dias |
| A04 | Contas de ex-funcionários | Desativar contas e revisar acessos | Alta | Imediato |
| A05 | Ausência de MFA | Implementar autenticação multifator | Alta | 15 dias |
| A06 | Endpoints desatualizados | Implementar política de atualização | Alta | 30 dias |
| A07 | Logs descentralizados | Implementar centralização de logs | Alta | 45 dias |
| A08 | Backup sem testes | Implementar testes de restauração | Alta | 30 dias |
| A09 | Política desatualizada | Revisar política de segurança | Média | 60 dias |
| A10 | Falta de treinamento | Implementar conscientização em segurança | Média | 60 dias |

*Os prazos são estimativas fictícias para fins educacionais.*

---

# 9. Conclusão da Auditoria

Com base nos procedimentos realizados, conclui-se que a TechSolutions Tecnologia Ltda. apresenta deficiências importantes em seus controles de segurança da informação.

Os principais riscos identificados estão relacionados à exposição indevida de recursos na nuvem, configurações inadequadas de firewall, gerenciamento deficiente de acessos e ausência de monitoramento centralizado.

Essas condições podem facilitar ataques cibernéticos, comprometimento de contas, vazamento de informações e interrupção de serviços.

Recomenda-se que a empresa priorize a correção das vulnerabilidades críticas, implemente mecanismos de monitoramento e fortaleça seus processos de governança e gestão de riscos.

Após a implementação das medidas corretivas, recomenda-se realizar uma nova auditoria para verificar a efetividade dos controles implementados.

**Parecer final:** O ambiente avaliado necessita de melhorias significativas nos controles de segurança da informação. A implementação do plano de ação é recomendada para reduzir a exposição aos riscos identificados.

---

# 10. Referências

- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
- [CIS Critical Security Controls](https://www.cisecurity.org/controls)
- [Lei Geral de Proteção de Dados – LGPD](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)
- [AWS Security Documentation](https://docs.aws.amazon.com/security/)

---

# 11. Aviso

Este documento foi desenvolvido exclusivamente para fins educacionais e demonstração de conhecimentos em auditoria de cibersegurança.

A empresa, os cenários, as evidências, os resultados e as não conformidades apresentados são fictícios.

O documento não representa uma auditoria oficial, certificação ou avaliação de conformidade realizada em uma organização real.
