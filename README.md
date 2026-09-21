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
- [🎯 Tipos de teste realizados na suíte](#-tipos-de-teste-realizados-na-suíte)

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

## 🎯 Tipos de teste realizados na suíte

A suíte de testes do qaFood é composta por todos os tipos de testes descritos abaixo:

| Tipo de Teste                    | O que valida                                                                                                                                                | Exemplos na suíte                                                                                                                                                                                                                                                                                       |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **End-to-End (E2E)**             | Valida jornadas completas atravessando diferentes páginas, componentes e fluxos da aplicação.                                                               | **0001** — acesso à página de eventos; **0011** — busca e visualização do evento “Buffalo Tom em São Paulo”; **0015** — acesso ao Google Maps e retorno ao evento; **0045** — estresse do carrossel → acesso ao evento → retorno à Home; **0057** — recuperação após busca inválida.                    |
| **Funcionais**                   | Verifica se funcionalidades e comportamentos previstos da aplicação funcionam corretamente.                                                                 | **0001–0004** — acesso à página de eventos; **0005–0012** — buscas por cidade, evento e local; **0013** — “Leia mais/Mostrar menos”; **0014–0019** — localização e Google Maps; **0020–0034** — páginas institucionais e links; **0041–0043** — controles do carrossel; **0069** — filtros e navegação. |
| **Regressão**                    | Garante que alterações ou novas funcionalidades não introduziram problemas em comportamentos anteriormente funcionais.                                      | **A suíte completa (0001–0070)** pode ser utilizada como suíte de regressão. Destacam-se os fluxos críticos **0001–0034**, navegação/carrossel **0041–0057** e integridade/acessibilidade **0061–0070**.                                                                                                |
| **Navegação**                    | Valida deslocamento entre páginas, seções, links, controles, carrossel e histórico do navegador.                                                            | **0001–0004** — navegação para Explorar Eventos; **0014–0019** — navegação entre evento, localização e Google Maps; **0020–0034** — navegação entre páginas institucionais; **0041–0045** — navegação no carrossel; **0048** — Back/Forward; **0055–0056** — links e múltiplas abas.                    |
| **Interface (UI)**               | Verifica a presença, interação e comportamento de elementos visuais e componentes da interface.                                                             | **0013** — expansão/recolhimento de conteúdo; **0026** — opções “App FasTix” e “Web”; **0041–0043** — botões do carrossel; **0051** — elementos da interface em diferentes resoluções; **0061–0062** — cards e imagens; **0070** — integridade do footer.                                               |
| **Responsividade**               | Avalia o comportamento da interface em diferentes dimensões e dispositivos.                                                                                 | **0051** — aplicação testada em **mobile, tablet e desktop ultrawide**, incluindo overflow, controles, cards, navegação, refresh e footer.                                                                                                                                                              |
| **Acessibilidade**               | Avalia navegação por teclado, gerenciamento de foco e interação sem depender exclusivamente do mouse.                                                       | **0052** — navegação utilizando teclado; **0067** — gerenciamento de foco; **0068** — navegação utilizando somente **TAB**.                                                                                                                                                                             |
| **Performance**                  | Avalia o tempo de resposta da aplicação diante das operações executadas.                                                                                    | **0059** — validação do **tempo de resposta da aplicação**.                                                                                                                                                                                                                                             |
| **Estabilidade**                 | Verifica se a aplicação permanece funcional após operações repetidas, prolongadas ou potencialmente disruptivas.                                            | **0046** — estabilidade da busca sob stress; **0049** — recuperação após refresh; **0050** — múltiplos refreshes; **0054** — estabilidade do carrossel; **0060** — scroll agressivo; **0064** — sessão longa; **0065** — múltiplos reloads; **0066** — interrupções inesperadas.                        |
| **Estresse (Stress)**            | Avalia o comportamento da aplicação quando submetida a uma quantidade ou frequência elevada de operações.                                                   | **0044** — 44 avanços + 44 retornos no carrossel; **0045** — stress do carrossel associado à jornada E2E; **0046** — busca sob stress; **0047** — duplo/múltiplos cliques; **0050** — refresh contínuo; **0054** — stress do carrossel; **0058** — entradas extremas.                                   |
| **Robustez**                     | Avalia a capacidade do sistema de lidar com entradas inesperadas, inválidas, extremas ou sequências incomuns de ações sem apresentar comportamento crítico. | **0035** — termo inexistente; **0036–0040** — caracteres especiais, números e combinações; **0046–0047** — operações repetidas/múltiplos cliques; **0057** — recuperação após busca sem resultados; **0058** — input extremo; **0066** — interrupção inesperada.                                        |
| **Validação de Dados**           | Verifica se dados inseridos, pesquisados, exibidos ou retornados pela aplicação são tratados e apresentados corretamente.                                   | **0005–0012** — busca por cidade, evento e local; **0035** — termo inexistente; **0036–0040** — caracteres especiais, números e combinações; **0057–0058** — buscas inválidas/extremas; **0061** — integridade dos dados dos cards; **0069** — filtros.                                                 |
| **Integridade**                  | Verifica se informações, componentes e conteúdos permanecem consistentes após diferentes interações.                                                        | **0053** — atualização correta dos conteúdos do carrossel; **0054** — integridade do carrossel após múltiplas operações; **0061** — integridade dos cards de eventos; **0062** — integridade das imagens; **0070** — integridade do footer.                                                             |
| **Compatibilidade de Navegação** | Avalia se diferentes formas de navegação e interação continuam funcionando corretamente em diferentes contextos de uso.                                     | **0048** — Back/Forward do navegador; **0051** — navegação em diferentes resoluções; **0052** — navegação por teclado; **0055** — links institucionais, aplicativos e redes sociais; **0056** — múltiplas abas internas e externas; **0067–0068** — navegação por foco/TAB.                             |
| **Monitoramento de Erros**       | Verifica a ocorrência de erros críticos durante a execução e a ausência de sinais de falha da aplicação.                                                    | **0039** — busca com caracteres especiais verificando ausência de `500` e `Error`; **0040** — combinação de números/caracteres verificando ausência de `500`, `Error` e `Exception`; **0063** — monitoramento do console para ausência de erros críticos.                                               |
| **Integridade Visual**           | Verifica se elementos visuais, imagens, componentes e estrutura visual permanecem íntegros após interações.                                                 | **0051** — elementos visuais em diferentes resoluções; **0054** — comportamento visual do carrossel; **0062** — integridade das imagens da página “Explorar Eventos”; **0070** — integridade visual do footer após múltiplas interações.                                                                |
| **Persistência de Estado**       | Verifica se o estado da aplicação é mantido ou recuperado adequadamente após navegação, reloads ou interrupções.                                            | **0049** — recuperação após refresh durante interação; **0050** — refresh durante interação contínua; **0057** — recuperação após busca inválida; **0065** — comportamento após múltiplos reloads; **0066** — recuperação após interrupções inesperadas.                                                |


---


## 🎯 Tipos de teste realizados na suíte

A suíte de testes do qaFood é composta por todos os tipos de testes descritos abaixo:


