### EM ATUALIZAÇÃO...

## 🤖 Automação Web CodeceptJS - Playwright - Node.js + JavaScript (FasTix)

<img width="1912" height="741" alt="image" src="https://github.com/user-attachments/assets/8dc7f870-7960-4e7a-99ba-97a38786b6df" />

A FasTix é uma plataforma de comercialização, distribuição e intermediação de ingressos, além de produtos e serviços associados ao mercado de entretenimento no Brasil. 

O projeto consiste na documentação Gherkin (linguagem para descrever o comportamento do software) e BDD (Behavior-Driven Development), em uma suíte de testes automatizados para o site FasTix (https://fastix.com.br), **baseada na versão de produção ativa publicada em julho de 2026:**


* **- Testes End-to-End (E2E)**
* **- Testes Funcionais**
* **- Testes de Regressão**
* **- Testes de Navegação**
* **- Testes de Interface (UI)**
* **- Testes de Responsividade**
* **- Testes de Acessibilidade**
* **- Testes de Performance**
* **- Testes de Estabilidade**
* **- Testes de Estresse**
* **- Testes de Robustez**
* **- Testes de Validação de Dados**
* **- Testes de Integridade**
* **- Testes de Compatibilidade de Navegação**
* **- Testes de Monitoramento de Erros**
* **- Testes de Integridade Visual**
* **- Testes de Persistência de Estado**


O site foi desenvolvido pela **empresa americana Web Solutions FL** (https://www.websolutionsfl.com/).

Todos os testes e a estrutura deste repositório foram desenvolvidos por **Diogo Amancio.**

---

  ## 📑 Índice

- [📱 Sobre o app](#-sobre-o-app)
- [🤖 Codecept](#-codeceptjs)
- [🏷️ Tecnologias utilizadas](#️-tecnologias-utilizadas)
- [⚙️ Estrutura da Suíte de Testes FasTix](#️-estrutura-da-suíte-de-testes-fastix)
- [🎯 Tipos de teste realizados na suíte](#-estratégia-e-cobertura-de-testes)

- ---

## 📱 Sobre o app

A FasTix é uma plataforma voltada à venda, distribuição e intermediação de ingressos, além de oferecer produtos e serviços relacionados ao setor de entretenimento no Brasil.

Atuando como uma ticketeira, a FasTix conecta o público aos organizadores de eventos, realiza a intermediação de ingressos e facilita a venda online de entradas para shows de música, festivais, cursos, palestras, exposições e eventos esportivos, independentemente do porte dos produtores de evento (pequeno, médio ou grande).

Também oferece tecnologia para produtores, com controle total para os organizadores realizarem a gestão de vendas e o controle de acesso do público no dia do evento (check-in).


---

## 🤖 CodeceptJS

O **CodeceptJS** utiliza recursos do ecossistema **Node.js e JavaScript**, dessa forma ele integra recursos do ecossistema **Node.js e JavaScript**, integrando o **Playwright** para a execução de testes automatizados em aplicações Web.

### Pré-requisitos para utilização no Windows
* **Node.js**
* **JavaScript**
* **CodeceptJS**
* **Playwright** para a execução de testes automatizados da aplicação Web da FasTix.

---

## 🏷️ Tecnologias utilizadas

![Web Testing](https://img.shields.io/badge/Web%20Testing-Automation-1E88E5?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Test%20Automation-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CodeceptJS](https://img.shields.io/badge/CodeceptJS-Test%20Automation-6C63FF?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright-Web%20Testing-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Testes Automatizados](https://img.shields.io/badge/Automated%20Testing-QA-1E88E5?style=for-the-badge)
![Test Scripts](https://img.shields.io/badge/Test%20Scripts-Automation-CB171E?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)
![Gherkin](https://img.shields.io/badge/Gherkin-BDD-5B5B5B?style=for-the-badge)

---

## ⚙️ Estrutura da Suíte de Testes FasTix

A suíte de testes da FasTix é **organizada em 6 Features composto por 586 testes.**

Dessa maneira, seguindo a jornada do usuário no site, desde o login, passando pela exploração de eventos, pelo acesso ao suporte e à ajuda, pela tela inicial, pela publicação de eventos, pela compra de ingressos e pela criação de uma conta.

| Feature                   |  Testes Automatizados |
| ------------------------- | ------: |
| Feature_Explorar Eventos            |      70 |
| Feature_Suporte e Ajuda            |      75 |
| Feature_Tela Inicial          |      164 |
| Feature_Publicar Eventos|      98 |
| Feature_Comprar Ingressos           |      127 |
| Feature_Criar Conta           |      52 |
| **Total**                 | **586** |


---

## 🎯 Estratégia e cobertura de testes

A suíte automatizada do FasTix foi estruturada para validar não apenas os fluxos funcionais da aplicação, mas também diferentes aspectos de qualidade, comportamento, resiliência e experiência de navegação.

**Os 70 cenários automatizados abaixo são todos os testes realizados na Feature Explorar Eventos.**

Todos os testes foram classificados considerando diferentes dimensões de teste. Essa abordagem evita tratar conceitos distintos como E2E, Regressão, Acessibilidade e Stress como se fossem categorias equivalentes.

### 📌 Dimensões de cobertura

| Dimensão                        | Categorias                                                                                  | Objetivo                                                                                              |
| ------------------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Escopo**                      | E2E                                                                                         | Validar jornadas completas atravessando diferentes páginas e componentes                              |
| **Objetivo funcional**          | Funcionais, Validação de Dados, Integridade                                                 | Verificar comportamentos esperados, dados apresentados e consistência das informações                 |
| **Qualidade da aplicação**      | UI, Responsividade, Acessibilidade, Performance, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais                                       |
| **Condição / técnica de teste** | Estresse, Compatibilidade de Navegação                                                      | Exercitar a aplicação sob condições repetitivas, intensivas ou diferentes formas de navegação         |
| **Resiliência**                 | Monitoramento de Erros, Recuperação de Estado                                               | Avaliar comportamento diante de erros, reloads, interrupções e operações inesperadas                  |
| **Finalidade de execução**      | Regressão                                                                                   | Reexecutar cenários existentes para identificar possíveis impactos causados por alterações no sistema |

---

## 🧪 Cobertura funcional e E2E

### Testes Funcionais

Validam se as funcionalidades disponíveis na aplicação apresentam o comportamento esperado.

**Exemplos:**

* **0001–0004:** acesso à página de eventos através de diferentes pontos da Home;
* **0005–0012:** pesquisa por eventos, cidades e locais;
* **0013:** expansão e recolhimento de conteúdo através de "Leia mais/Mostrar menos";
* **0014–0019:** navegação entre evento, localização e Google Maps;
* **0020–0034:** acesso e navegação pelas páginas institucionais;
* **0041–0043:** interação com os controles do carrossel;
* **0069:** filtragem e navegação.

### Testes End-to-End (E2E)

Validam jornadas completas envolvendo múltiplos componentes ou páginas da aplicação.

**Exemplos:**

* **0001:** Home → Explorar Eventos;
* **0011:** pesquisa → identificação do evento → acesso à página do evento;
* **0015:** página do evento → Google Maps → retorno ao fluxo do evento;
* **0045:** stress do carrossel → acesso ao evento → retorno à Home → nova interação;
* **0057:** pesquisa inválida → recuperação → pesquisa válida.

> **Observação:** E2E representa o **escopo da jornada**, e não uma categoria funcional isolada. Um mesmo cenário E2E também pode ser funcional, de navegação, de robustez ou de recuperação.

---

## 🧭 Testes de Navegação

Validam a movimentação do usuário entre páginas, componentes, links, histórico do navegador e diferentes pontos de acesso.

**Exemplos:**

* **0001–0004:** diferentes formas de acesso à página de eventos;
* **0014–0019:** navegação entre evento, localização e Google Maps;
* **0020–0034:** navegação entre páginas institucionais;
* **0041–0045:** navegação pelo carrossel;
* **0048:** utilização dos comandos Back e Forward do navegador;
* **0055–0056:** navegação através de links e múltiplas abas;
* **0067–0068:** navegação utilizando foco e teclado.

---

## 🖥️ Testes de Interface (UI)

Avaliam a presença, interação e comportamento dos principais componentes da interface.

**Exemplos:**

* **0013:** expansão/recolhimento de conteúdo;
* **0026:** validação das opções "Web" e "App FasTix";
* **0041–0043:** botões de navegação do carrossel;
* **0051:** componentes da interface em diferentes resoluções;
* **0061:** cards de eventos;
* **0062:** imagens;
* **0070:** integridade dos elementos do footer.

---

## 📱 Testes de Responsividade

Avaliam o comportamento da aplicação em diferentes dimensões de viewport.

O cenário **0051** realiza uma validação específica utilizando:

* **390 × 844 — Mobile**
* **768 × 1024 — Tablet**
* **2560 × 1440 — Desktop Ultrawide**

Durante a execução são avaliados elementos como:

* visibilidade de eventos;
* carrossel;
* navegação;
* overflow;
* componentes da interface;
* footer;
* acesso à página do evento;
* refresh;
* ausência de mensagens de erro.

---

## ♿ Testes de Acessibilidade

Avaliam a capacidade de interação com a aplicação utilizando mecanismos alternativos ao mouse.

**Exemplos:**

* **0052:** navegação utilizando teclado;
* **0067:** gerenciamento e comportamento do foco;
* **0068:** navegação utilizando exclusivamente TAB.

Os cenários verificam elementos como:

* foco;
* sequência de navegação;
* utilização de TAB;
* Shift + TAB;
* Enter;
* Space;
* interação com elementos da interface sem depender exclusivamente do mouse.

---

## ⚡ Testes de Performance

Avaliam o comportamento da aplicação em relação ao tempo de resposta durante operações específicas.

**Exemplo:**

* **0059:** validação relacionada ao tempo de resposta da aplicação.

> A suíte possui uma cobertura de performance **pontual**, não caracterizando uma estratégia completa de performance/load testing. Para um projeto futuro, poderiam ser adicionados testes específicos de carga, volume e throughput.

---

## 🔄 Testes de Estabilidade

Avaliam se a aplicação permanece funcional após repetição de operações, múltiplas interações, reloads ou períodos prolongados de utilização.

**Exemplos:**

* **0046:** estabilidade durante operações repetitivas;
* **0049:** recuperação após refresh;
* **0050:** múltiplos refreshes;
* **0054:** estabilidade do carrossel;
* **0060:** scroll agressivo;
* **0064:** sessão prolongada;
* **0065:** múltiplos reloads;
* **0066:** recuperação após interrupção inesperada.

---

## 🔥 Testes de Estresse (Stress Testing)

Submetem determinados componentes a operações repetitivas ou intensivas para verificar seu comportamento sob condições mais agressivas.

**Exemplos:**

* **0044:** múltiplos avanços e retornos do carrossel;
* **0045:** stress do carrossel associado a uma jornada E2E;
* **0046:** operações repetitivas;
* **0047:** múltiplas interações/cliques;
* **0050:** múltiplos refreshes;
* **0054:** operações repetitivas sobre o carrossel;
* **0058:** entradas extremas.

> **Importante:** esses cenários caracterizam stress/robustez de componentes da aplicação. Eles não devem ser apresentados como um teste formal de **load/performance**, pois não simulam múltiplos usuários ou carga concorrente de infraestrutura.

---

## 🛡️ Testes de Robustez

Avaliam a capacidade da aplicação de lidar com entradas inesperadas, inválidas, extremas ou sequências incomuns de interação.

**Exemplos:**

* **0035:** pesquisa por termo inexistente;
* **0036:** caracteres especiais;
* **0037:** caracteres especiais repetidos;
* **0038:** entradas numéricas;
* **0039–0040:** combinações de entradas para validação de comportamento;
* **0046–0047:** operações repetitivas;
* **0057:** recuperação após pesquisa inválida;
* **0058:** entrada extrema;
* **0066:** interrupção inesperada.

---

## 🔎 Testes de Validação de Dados

Verificam se os dados inseridos, pesquisados, retornados ou apresentados pela aplicação são tratados corretamente.

**Exemplos:**

* **0005–0012:** pesquisa por cidade, evento e local;
* **0035:** pesquisa sem resultado;
* **0036–0040:** caracteres especiais, números e combinações;
* **0057:** recuperação entre pesquisa inválida e válida;
* **0058:** entrada extrema;
* **0061:** validação dos dados exibidos nos cards;
* **0069:** filtros e resultados.

---

## 🔐 Testes de Integridade

Avaliam se os dados e componentes permanecem consistentes após diferentes operações.

**Exemplos:**

* **0053:** validação da alteração de estado do carrossel;
* **0054:** integridade do carrossel após múltiplas operações;
* **0061:** consistência dos dados dos cards;
* **0062:** integridade das imagens;
* **0070:** integridade do footer após múltiplas interações.

---

## 🌐 Testes de Compatibilidade de Navegação

Verificam se diferentes mecanismos de navegação continuam funcionando corretamente em diferentes contextos de interação.

**Exemplos:**

* **0048:** Back/Forward do navegador;
* **0051:** navegação em diferentes resoluções;
* **0052:** navegação por teclado;
* **0055:** links institucionais, aplicativos e redes sociais;
* **0056:** utilização de múltiplas abas;
* **0067–0068:** navegação por foco e teclado.

> Essa categoria representa **compatibilidade entre diferentes mecanismos de navegação**, e não compatibilidade entre diferentes browsers. A suíte atual não demonstra, pelos cenários analisados, uma estratégia completa de cross-browser testing.

---

## 🚨 Testes de Monitoramento de Erros

Monitoram sinais de falhas durante a execução e verificam a ausência de mensagens de erro conhecidas.

**Exemplos:**

* **0039:** ausência de `500` e `Error`;
* **0040:** ausência de `500`, `Error` e `Exception`;
* **0053–0054:** ausência de mensagens como `Application error`, `Internal Server Error` e `Unexpected error`;
* **0063:** monitoramento de erros no console.

---

## 🎨 Testes de Integridade Visual

Avaliam se elementos visuais permanecem íntegros após diferentes interações.

**Exemplos:**

* **0051:** elementos visuais em diferentes resoluções;
* **0054:** comportamento visual do carrossel após múltiplas operações;
* **0062:** validação da integridade das imagens;
* **0070:** integridade visual do footer.

---

## 🔄 Recuperação e Estado da Aplicação

Nos cenários analisados, existem testes relacionados à manutenção e recuperação do estado da aplicação após determinadas operações.

**Exemplos:**

* **0049:** recuperação após refresh;
* **0050:** comportamento após múltiplos refreshes;
* **0057:** recuperação após uma pesquisa inválida;
* **0065:** comportamento após múltiplos reloads;
* **0066:** recuperação após interrupção inesperada.

> **Precisão técnica:** esses cenários são melhor descritos como **testes de recuperação/resiliência e gerenciamento de estado**. Eles não comprovam, isoladamente, persistência de dados de negócio em banco, sessão ou armazenamento local.

---

# 🔁 Regressão

A **regressão não representa um conjunto separado de cenários**.

Os 70 cenários podem ser utilizados como uma **suíte de regressão automatizada**, especialmente após:

* novas funcionalidades;
* alterações de UI;
* alterações de navegação;
* correções de bugs;
* alterações no carrossel;
* alterações de responsividade;
* alterações de componentes;
* mudanças estruturais nas páginas.

A ideia é verificar se uma alteração introduzida no sistema provocou efeitos colaterais em comportamentos que anteriormente funcionavam.

### Exemplo de estratégia

```text
Alteração no sistema
        ↓
Execução dos testes relacionados
        ↓
Execução da suíte de regressão
        ↓
Comparação dos resultados
        ↓
Identificação de regressões
        ↓
RCA / Bug Report
```
---

# 📊 Matriz de cobertura da suíte

Para deixar o seu portfólio ainda mais profissional, eu incluiria uma matriz resumida:

| Dimensão                         | Cenários principais                              | Cobertura |
| -------------------------------- | ------------------------------------------------ | --------- |
| **E2E**                          | 0001, 0011, 0015, 0045, 0057                     | 🟢        |
| **Funcional**                    | 0001–0045, 0069                                  | 🟢        |
| **Regressão**                    | 0001–0070                                        | 🟢        |
| **Navegação**                    | 0001–0004, 0014–0034, 0041–0048, 0055–0056       | 🟢        |
| **UI**                           | 0013, 0026, 0041–0043, 0051, 0061–0062, 0070     | 🟢        |
| **Responsividade**               | 0051                                             | 🟢        |
| **Acessibilidade**               | 0052, 0067–0068                                  | 🟢        |
| **Performance**                  | 0059                                             | 🟡        |
| **Estabilidade**                 | 0046, 0049–0050, 0054, 0060, 0064–0066           | 🟢        |
| **Estresse**                     | 0044–0047, 0050, 0054, 0058                      | 🟢        |
| **Robustez**                     | 0035–0040, 0046–0050, 0057–0058, 0060, 0064–0066 | 🟢        |
| **Validação de Dados**           | 0005–0012, 0035–0040, 0057–0058, 0061, 0069      | 🟢        |
| **Integridade**                  | 0053–0054, 0061–0062, 0070                       | 🟢        |
| **Compatibilidade de Navegação** | 0048, 0051–0052, 0055–0056, 0067–0068            | 🟢        |
| **Monitoramento de Erros**       | 0039–0040, 0053–0054, 0063                       | 🟢        |
| **Integridade Visual**           | 0051, 0054, 0062, 0070                           | 🟢        |
| **Recuperação/Estado**           | 0049–0050, 0057, 0065–0066                       | 🟢        |

**Legenda:**
🟢 Cobertura claramente demonstrada pelos cenários analisados
🟡 Cobertura presente, porém pontual e passível de expansão

---





---



