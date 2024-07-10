# Relatório de Encerramento do Projeto SWIFTPIX

## 1. Introdução

Este documento visa fornecer uma análise detalhada e comparativa entre o planejamento inicial e a execução final do projeto SWIFTPIX. Serão avaliados diversos componentes como o Backlog, as Histórias de Usuário, Custos, Qualidade e Riscos associados, com o objetivo de elucidar o progresso e as realizações do projeto, bem como identificar áreas de melhoria.

## 2. Backlog

### 2.1 Planejadas

As histórias de usuário iniciais do projeto incluíam funcionalidades essenciais para gerenciamento de contas e transações via PIX, assim como operações específicas de geolocalização e notificações.

#### Gerenciamento de Contas
- [US01 - Gerenciar Minha Conta](#)
- [US02 - Gerenciar Minhas Transações PIX](#)

#### Transações e Notificações
- [US03 - Realizar Transações PIX Utilizando a Geolocalização](#)
- [US04 - Receber Notificações](#)

### 2.2 Realizadas

#### Executado com Sucesso
- [US01 - Gerenciar Minha Conta](#)
  - Todas as funcionalidades planejadas foram implementadas com sucesso, incluindo a gestão de informações pessoais e segurança da conta.
- [US02 - Gerenciar Minhas Transações PIX](#)
  - Implementação completa das funcionalidades de chave PIX e histórico de transações.

#### Parcialmente Implementadas
- [US03 - Realizar Transações PIX Utilizando a Geolocalização](#)
  - A funcionalidade de transações por aproximação não foi implementada devido a limitações de acesso ao hardware necessário.
- [US04 - Receber Notificações](#)
  - Notificações de alteração de conta foram implementadas, porém a funcionalidade de notificação de cotação da moeda atual não foi concluída devido à falta de uma biblioteca adequada.

### 2.3 Análise

A implementação atingiu 70% das funcionalidades planejadas. As restrições tecnológicas e a ausência de ferramentas adequadas no mercado impactaram o desenvolvimento de funcionalidades específicas, como transferências por aproximação e notificações precisas de cotação de moeda.

## 3. Custos

Os custos do projeto foram mantidos dentro do orçamento inicialmente proposto, com exceção dos gastos extras incorridos na tentativa de solucionar as limitações tecnológicas encontradas.

## 4. Qualidade

### Planejado
Era esperado que todos os componentes do sistema atingissem uma cobertura de teste de pelo menos 80%.

### Executado
- **Frontend**: 89,1%
- **Backend (Serviço de Usuários e Transações)**: 91,7% e 93,9% respectivamente

## 5. Riscos

Diversos riscos foram identificados e administrados ao longo do projeto, incluindo desafios de comunicação e sincronização entre equipes, bem como a adaptação a novas ferramentas tecnológicas. Os riscos de dependência de hardware e software de terceiros foram os mais impactantes, resultando em atrasos e redefinições de escopo em determinadas áreas.

## 6. Próximos Passos

Para avançar, o projeto SWIFTPIX necessitará de várias ações estratégicas, incluindo:

- **Avaliação Detalhada das Funcionalidades Não Implementadas**: Identificar soluções alternativas viáveis para as funcionalidades que não foram implementadas devido a limitações tecnológicas.

- **Continuação do Desenvolvimento das Funcionalidades Pendentes**: Ajustar o plano de projeto conforme necessário para completar o desenvolvimento das funcionalidades restantes.

- **Revisão e Fortalecimento das Estratégias de Mitigação de Riscos**: Especialmente aquelas relacionadas à dependência tecnológica, garantindo que o projeto possa adaptar-se a mudanças no ambiente tecnológico sem grandes perturbações.

- **Preparação para Integração com a API do Banco Central**: Notavelmente, o SWIFTPIX já possui endpoints desenvolvidos que facilitarão a futura conexão com a API de PIX do Banco Central. Isso representa um passo significativo em direção à plena operacionalidade do sistema em conformidade com os padrões regulatórios e técnicos exigidos para transações PIX. A integração planejada aumentará a funcionalidade do sistema e ampliará suas capacidades de serviço, oferecendo uma base sólida para expansões futuras.

## Conclusão

O projeto SWIFTPIX, apesar dos desafios encontrados, conseguiu implementar a maioria das funcionalidades planejadas, demonstrando a eficácia e a resiliência da equipe de desenvolvimento. O aprendizado obtido será crucial para o sucesso contínuo e aprimoramento do projeto, especialmente com a antecipação da integração com a API do Banco Central, o que alinha o SWIFTPIX com as inovações mais recentes no campo de transações financeiras.

## Histórico de versão
| Data | Versão | Descrição | Autor(es) |
| ---- | ---- | ---- | ---- |
| 10/07/2024 | 1.0 | Criação do Documento | Júlia Farias Sousa |