# Sistema de Gestão da Empresa Horizonte

## 1. Sobre o projeto

O Sistema de Gestão da Empresa Horizonte é um protótipo acadêmico desenvolvido para a empresa fictícia Horizonte Soluções.

Atualmente, a empresa organiza informações de clientes, produtos, pedidos e relatórios em anotações e planilhas separadas. Isso pode causar cadastros duplicados, informações inconsistentes e dificuldades para acompanhar as atividades.

O objetivo do projeto é criar páginas simples e organizadas para representar um sistema de gestão empresarial.

**Situação atual:** o projeto está em fase inicial, com a página inicial como primeira etapa do desenvolvimento.

## 2. Objetivo e funcionalidades previstas

O objetivo é desenvolver um protótipo visual de um sistema de gestão e aplicar os conhecimentos de Git e GitHub para controlar versões, organizar alterações e documentar o desenvolvimento.

As funcionalidades previstas são:

- **Painel inicial:** apresentar o sistema e permitir o acesso aos módulos.
- **Clientes:** apresentar um formulário ilustrativo e informações fictícias de clientes.
- **Produtos:** apresentar um formulário ilustrativo e uma lista de produtos fictícios.
- **Pedidos:** exibir informações de pedidos e seus respectivos status.
- **Relatórios:** apresentar indicadores ou tabelas com dados simulados.

Essas funcionalidades serão desenvolvidas progressivamente. Os formulários serão demonstrativos e não terão armazenamento real de dados, pois o projeto não exige banco de dados ou backend.

## 3. Tecnologias utilizadas

- **HTML5:** estrutura e conteúdo das páginas.
- **CSS3:** estilos, cores e organização visual.
- **Git:** controle de versões e registro das alterações.
- **GitHub:** hospedagem do repositório e gerenciamento do histórico do projeto.
- **Visual Studio Code (VS Code):** editor de código para o desenvolvimento.

### Requisitos para visualizar o projeto

- Um computador com navegador atualizado.
- Os arquivos do projeto disponíveis localmente.
- Visual Studio Code ou outro editor de código, caso seja necessário consultar ou editar os arquivos.

Não é necessário instalar banco de dados ou configurar um servidor backend.

## 4. Como obter e abrir o projeto

O repositório está disponível no GitHub:

**[Acessar o repositório gestao_horizonte](https://github.com/Antonygab077/gestao_horizonte)**

### Clonar o repositório

Abra o terminal e execute:

```bash
git clone https://github.com/Antonygab077/gestao_horizonte.git
```

Entre na pasta do projeto:

```bash
cd gestao_horizonte
```

### Abrir a página inicial

1. Abra a pasta do projeto no Visual Studio Code.
2. Localize o arquivo `index.html`.
3. Abra o arquivo em um navegador para visualizar a página inicial.
4. Conforme as demais páginas forem desenvolvidas, elas poderão ser acessadas pelos links de navegação correspondentes.

## 5. Estrutura de pastas e módulos

A estrutura abaixo representa a organização prevista para a versão completa. Os arquivos serão adicionados conforme o desenvolvimento avançar.

```text
gestao_horizonte/
├── index.html
├── clientes.html
├── produtos.html
├── pedidos.html
├── relatorios.html
├── css/
│   └── estilo.css
├── README.md
└── .gitignore
```

### Descrição dos arquivos

| Arquivo ou pasta | Finalidade |
|---|---|
| `index.html` | Página inicial do sistema. |
| `clientes.html` | Página prevista para o módulo de clientes. |
| `produtos.html` | Página prevista para o módulo de produtos. |
| `pedidos.html` | Página prevista para o módulo de pedidos. |
| `relatorios.html` | Página prevista para o módulo de relatórios. |
| `css/estilo.css` | Folha de estilos compartilhada pelas páginas. |
| `README.md` | Documentação do projeto. |
| `.gitignore` | Arquivo previsto para ignorar itens que não devem ser versionados. |

**Observação:** essa é a estrutura planejada, não uma confirmação de que todos os arquivos já existem.

## 6. Fluxo de branches do projeto

O Git será utilizado para registrar as alterações e o GitHub para armazenar o repositório, revisar mudanças e acompanhar as entregas.

O fluxo de trabalho previsto será:

- **`main`:** branch principal, destinada às versões estáveis.
- **`develop`:** branch para integrar as funcionalidades desenvolvidas.
- **Branches `feature/`:** destinadas à criação das páginas de funcionalidades.
- **Branches `fix/`:** destinadas à correção de problemas.

### Branches de trabalho previstas

| Branch | Objetivo |
|---|---|
| `feature/clientes` | Desenvolver a página de clientes. |
| `feature/produtos` | Desenvolver a página de produtos. |
| `feature/pedidos` | Desenvolver a página de pedidos. |
| `feature/relatorios` | Desenvolver a página de relatórios. |
| `fix/menu` | Corrigir um problema de navegação. |
| `fix/visual` | Corrigir um problema de apresentação visual. |

### Etapas do fluxo

1. Criar a branch `develop` a partir da organização inicial do projeto.
2. Criar cada branch de trabalho a partir da versão atualizada de `develop`.
3. Implementar a funcionalidade ou correção correspondente.
4. Registrar as alterações com commits descritivos.
5. Enviar a branch para o GitHub.
6. Abrir um Pull Request com destino à `develop`.
7. Revisar e integrar as alterações.
8. Após a validação, integrar a versão estável à `main`.
9. Criar uma tag e publicar uma release para cada entrega prevista.

Também serão realizados dois testes de conflito de merge: um conflito local e outro durante a integração de um Pull Request. As causas e soluções serão documentadas depois da realização dos testes.

**Situação atual:** as branches adicionais, os Pull Requests e os testes de conflitos ainda não foram realizados.

## 7. Situação atual e próximas entregas

O projeto está em fase inicial de desenvolvimento.

### Etapas realizadas ou iniciadas

- [x] Repositório individual informado para o projeto.
- [x] Página inicial (`index.html`) identificada como a primeira página do projeto.
- [ ] Confirmar a estrutura completa dos arquivos HTML e CSS.
- [ ] Criar e preencher este arquivo `README.md`.
- [ ] Criar e configurar o arquivo `.gitignore`.
- [ ] Criar a branch `develop`.
- [ ] Desenvolver as páginas de clientes, produtos, pedidos e relatórios.
- [ ] Criar as quatro branches de funcionalidades.
- [ ] Criar as duas branches de correção.
- [ ] Realizar commits significativos em cada etapa.
- [ ] Criar e revisar Pull Requests.
- [ ] Realizar e documentar os dois testes de conflitos de merge.
- [ ] Criar quatro tags de versão.
- [ ] Publicar quatro releases no GitHub.
- [ ] Conferir a navegação e os arquivos do projeto.
- [ ] Registrar evidências do desenvolvimento e revisar a documentação.

Os itens pendentes serão atualizados conforme forem concluídos. A conclusão de uma etapa deverá ser confirmada no repositório antes de ser marcada como realizada.

## 8. Histórico de versões e releases

O projeto ainda está em desenvolvimento e não possui releases publicadas.

O histórico abaixo apresenta uma proposta para organizar as futuras entregas. As versões e descrições deverão ser ajustadas de acordo com as alterações efetivamente realizadas.

| Versão planejada | Descrição | Situação |
|---|---|---|
| `v1.0.0` | Primeira entrega documentada do protótipo. | Planejada |
| `v1.1.0` | Evolução das páginas e dos módulos. | Planejada |
| `v1.2.0` | Correções e melhorias de navegação e apresentação. | Planejada |
| `v2.0.0` | Consolidação do protótipo e revisão final. | Planejada |

Essas versões são apenas uma sugestão de organização e ainda não foram publicadas.

**[Consultar as releases do projeto no GitHub](https://github.com/Antonygab077/gestao_horizonte/releases)**

Quando as releases forem criadas, esta seção deverá incluir os links e um resumo das mudanças de cada versão.

## 9. Responsável pelo projeto

- **Aluno:** Antony Gabriel de Oliviera Garcia
- **Turma:** 26-1N
- **Disciplina:** Git e GitHub
- **Data:** 22/10/2026
- **Repositório:** [gestao_horizonte](https://github.com/Antonygab077/gestao_horizonte)

## 10. Considerações finais

O Sistema de Gestão da Empresa Horizonte tem como finalidade representar uma solução visual para organizar informações empresariais fictícias e demonstrar os conhecimentos adquiridos durante as atividades de Git e GitHub.

O desenvolvimento será realizado por etapas, com registro das alterações, criação de branches, revisão por Pull Requests, testes de conflitos e publicação de releases.

Este README será atualizado ao longo do projeto para apresentar informações claras e compatíveis com o estado real do repositório.