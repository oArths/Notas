## Objetivo do Projeto

Eliminar ou reduzir significativamente as restrições aplicadas ao número do WhatsApp, mantendo o mesmo número de atendimento e migrando a integração do CRM Strom para a WhatsApp Cloud API Oficial da Meta.

---

## Problemas Atuais

- Sincronização inconsistente entre o WhatsApp e o CRM.
- Limitação no volume de atendimentos simultâneos.
- Restrições temporárias aplicadas pelo WhatsApp.
- Desconexões recorrentes da integração via QR Code.
- Interrupções no atendimento.

---

## Fluxo Atual

```text
Facebook/Instagram Ads
        │
        ▼
     wa.me
        │
        ▼
WhatsApp Business App
        │
        ▼
Conexão via QR Code
        │
        ▼
IA do Strom
```

---

## Solução Proposta

Migrar a integração do WhatsApp Business App (QR Code) para a WhatsApp Cloud API Oficial da Meta, permitindo que o CRM Strom utilize a infraestrutura oficial da Meta para comunicação com os clientes.

Com essa mudança, espera-se:

- Redução significativa das restrições temporárias.
- Maior estabilidade da integração.
- Eliminação das desconexões via QR Code.
- Atendimento simultâneo de um maior número de clientes.
- Comunicação oficial entre o CRM e o WhatsApp.

---

## Acessos Necessários

- Conta da Meta (Business Manager) com permissões de administrador ou acesso concedido ao desenvolvedor.
- Número de telefone que será utilizado na WhatsApp Cloud API.
- Acesso administrativo ao CRM Strom.
- Disponibilidade do responsável pelo número para validar o código enviado pela Meta (SMS ou ligação).
- Definição de um horário de menor movimento para realização da migração.

---

## Custos Futuros

### Strom

- Plano compatível com integração da WhatsApp Cloud API.
- Mensalidade da integração oficial (caso aplicável).

Atualmente:

- Plano mínimo recomendado: **R$ 199,90**
- Integração oficial do WhatsApp: **R$ 49,90/mês**

### Meta

A Meta poderá cobrar pelo envio de determinados tipos de mensagens utilizando a WhatsApp Cloud API.

Como o fluxo atual consiste em clientes iniciando a conversa através dos anúncios (Click to WhatsApp), espera-se um custo muito baixo ou até inexistente na maior parte dos atendimentos.

Caso futuramente sejam realizadas campanhas de marketing ou mensagens iniciadas pela empresa, poderão existir cobranças conforme a tabela vigente da Meta.

---

## Premissas do Projeto

Este projeto contempla apenas a migração da integração do WhatsApp.

Não fazem parte deste escopo:

- Alterações na IA do Strom.
- Desenvolvimento de novas funcionalidades.
- Criação de novos fluxos de atendimento.
- Alterações em campanhas de anúncios.
- Integrações com outros sistemas.

---

## Pontos Imutáveis do Projeto

- Não alterar a forma como os leads chegam ao WhatsApp.
- Manter o mesmo número de telefone.
- Manter o CRM Strom.
- Manter o fluxo atual do bot, alterando apenas a forma de conexão com o WhatsApp.

---

## Entregáveis

- Criação e configuração do Meta Business Manager (caso necessário).
- Configuração da WhatsApp Cloud API.
- Migração do número atual.
- Configuração da integração oficial no CRM Strom.
- Configuração do bot na nova estrutura.
- Testes completos de envio e recebimento de mensagens.
- Homologação do funcionamento junto ao cliente.
- Documentação básica das configurações realizadas.
- Atualização do TimeSheet durante todo o projeto.

---

## Critérios de Aceite

O projeto será considerado concluído quando:

- O número estiver funcionando na WhatsApp Cloud API.
- O CRM Strom estiver conectado à API Oficial.
- A IA estiver respondendo normalmente.
- O cliente validar o funcionamento do fluxo completo de atendimento.

---

## Pontos de Atenção

- A utilização da API Oficial aumenta a confiabilidade da conta perante a Meta, porém continua sendo necessário seguir as políticas da plataforma para evitar restrições.
- Durante a migração, o WhatsApp poderá ficar indisponível.
- Após a migração, o número deixará de funcionar simultaneamente no WhatsApp Business App, passando a operar através da WhatsApp Cloud API.
- Esta proposta contempla apenas o escopo descrito neste documento.
- Solicitações de novas funcionalidades ou alterações após a aprovação do projeto serão orçadas separadamente.
- Esta proposta possui validade até **07/08/2026**.

---

## Custo do Projeto

O projeto será cobrado por hora.

**Valor da hora:** R$ 45,00

Estimativa de execução:

- Entre **8 e 12 horas** de trabalho.
- Previsão de conclusão: **1 a 2 dias úteis**.

---

## Cronograma

| Data | Atividade | Status |
|------|-----------|:------:|
| 27/07/2026 | Levantamento e definição do escopo | ✅ |
| — | Recebimento dos acessos necessários | ⏳ |
| — | Configuração do ambiente Meta | ⏳ |
| — | Migração para WhatsApp Cloud API | ⏳ |
| — | Configuração do CRM Strom | ⏳ |
| — | Testes e homologação | ⏳ |
| — | Entrega do projeto | ⏳ |

---

## Informações de Contato

**Desenvolvedor Responsável:** Arthur Ferreira

**E-mail:** arths.developer@gmail.com

**WhatsApp:** (11) 97667-0957

TimeSheet: [Link](https://docs.google.com/spreadsheets/d/12H8KzCxJMEp6-J2trXG_5MUcwLT62OyoZBtiTTcWOjs/edit?usp=sharing)