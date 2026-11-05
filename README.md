# RSH Orders and Operations

Automação desenvolvida em **Microsoft Power Automate Desktop** para execução e tratamento de rotinas relacionadas a ordens e operações.

---

## Objetivo

O projeto automatiza atividades operacionais repetitivas, reduzindo intervenção manual e padronizando etapas de execução relacionadas ao processamento de ordens e operações.

A solução foi estruturada como **Desktop Flow** e posteriormente adicionada a uma **Power Platform Solution** para permitir exportação, migração e versionamento.

---

## Principais funcionalidades

- Automação de tarefas executadas em desktop
- Execução sequencial de etapas operacionais
- Tratamento de ordens e operações
- Interação com aplicações e interfaces locais
- Redução de atividades manuais
- Padronização da execução
- Suporte a rotinas recorrentes
- Estrutura preparada para ALM e controle de versão

---

## Arquitetura

A solução segue o fluxo:

**Processo operacional**  
↓  
**Power Automate Desktop**  
↓  
**Execução das ações automatizadas**  
↓  
**Sistemas e aplicações locais**  
↓  
**Processamento de ordens e operações**  
↓  
**Resultado da automação**

---

## Tecnologias

`Microsoft Power Automate Desktop` · `Power Automate` · `Power Platform` · `Desktop Flow` · `RPA` · `ALM` · `Solution`

---

## Estrutura do projeto

O repositório contém os arquivos extraídos da Solution utilizada no Power Platform.

```text
desktopflowbinaries/
├── ...
│
Workflows/
├── C_RSHOrdersAndOperations-*.json
│
[Content_Types].xml
customizations.xml
solution.xml
README.md
```

### Workflows

O diretório `Workflows` contém a definição principal do Desktop Flow.

### desktopflowbinaries

O diretório `desktopflowbinaries` contém os componentes e dependências utilizados pelo Power Automate Desktop, incluindo informações de manifesto, dependências, elementos de interface e recursos associados à automação.

### Arquivos da Solution

Os arquivos `solution.xml`, `customizations.xml` e `[Content_Types].xml` representam metadados e configurações da Power Platform Solution.

---

## Versionamento

O Desktop Flow foi incluído em uma **Power Platform Solution** e exportado como **Unmanaged Solution** para permitir controle de versão.

Fluxo utilizado:

**Power Automate Desktop → Solution → Export Unmanaged → Extração → GitHub**

Essa estrutura permite acompanhar alterações realizadas na automação e manter histórico técnico da solução.

---

## Segurança e confidencialidade

O projeto pode conter referências relacionadas a ambientes corporativos, como:

- nomes de sistemas
- caminhos de arquivos
- elementos de interface
- identificadores internos
- parâmetros de execução
- URLs e endereços de ambiente
- informações de conexão

Por esse motivo, o repositório deve permanecer privado até que todas as referências corporativas sejam revisadas e anonimizadas.

Credenciais, senhas, tokens e outros dados sensíveis nunca
