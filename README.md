### EM ATUALIZAÇÃO...

## 🤖 Automação Web CodeceptJS - Playwright - Node.js + JavaScript (FasTix)

<img width="1912" height="741" alt="image" src="https://github.com/user-attachments/assets/8dc7f870-7960-4e7a-99ba-97a38786b6df" />

A FasTix é uma plataforma de comercialização, distribuição e intermediação de ingressos, além de produtos e serviços associados ao mercado de entretenimento no Brasil. 

O projeto consiste na documentação Gherkin (linguagem para descrever o comportamento do software) e BDD (Behavior-Driven Development), em uma suíte de testes automatizados para o site FasTix (https://fastix.com.br), **baseada na versão de produção ativa publicada em julho de 2026:**

O site foi desenvolvido pela **empresa americana Web Solutions FL** (https://www.websolutionsfl.com/).

Todos os testes e a estrutura deste repositório foram desenvolvidos por **Diogo Amancio.**

---

#-como-executar-este-projeto

  ## 📑 Índice

- [📱 Sobre o app](#-sobre-o-app)
- [🤖 Codecept](#-codeceptjs)
- [🏷️ Tecnologias utilizadas](#️-tecnologias-utilizadas)
- [⚙️ Estrutura da Suíte de Testes FasTix](#️-estrutura-da-suíte-de-testes-fastix)
- [📝 Tipos de teste realizados na suíte](#-tipos-de-teste-realizados-na-suíte)
- [▶️ Como executar este projeto](#%EF%B8%8F-como-executar-este-projeto)
- [🧰 Ambiente e rotina diária](#-ambiente-e-rotina-diária)
- [✅ Uso](#-uso)
- [📁 Estrutura do repositório](#-estrutura-do-repositório)
- [🧭 A Jornada do usuário](#-a-jornada-do-usuário)
- [🎯 Estratégia e cobertura de Testes ](#-estratégia-e-cobertura-de-testes)
- [🔍 Feature Explorar Eventos ](#-feature-explorar-eventos)
- [🔍 Feature Suporte e Ajuda ](#-feature-suporte-e-ajuda)
- [🔍 Feature Tela Inicial ](#-feature-tela-inicial)



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
* **Playwright:Para a execução de testes automatizados da aplicação Web da FasTix.**

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

## 📝 Tipos de teste realizados na suíte

| Tipos de Testes |
| ------------------------- |
| Testes End-to-End (E2E) |
| Testes Funcionais |
| Testes de Regressão |
| Testes de Navegação |
| Testes de Interface (UI) |
| Testes de Responsividade |
| Testes de Acessibilidade |
| Testes de Performance |
| Testes de Estabilidade |
| Testes de Estresse |
| Testes de Robustez |
| Testes de Validação de Dados |
| Testes de Integridade |
| Testes de Compatibilidade de Navegação |
| Testes de Monitoramento de Erros |
| Testes de Integridade Visual |
| Testes de Persistência de Estado |
| **Total: 17 tipos de testes** |


---

## ▶️ Como executar este projeto 

Um resumo rápido para quem está clonando este repositório pela primeira vez. Para ver o passo a passo completo, consulte a seção **🧰 Ambiente e rotina diária** mais abaixo.

## 📌 Pré-requisitos

Configuração do ambiente com a instalação das seguintes tecnologias:

- **Node.js**  ([guia oficial de instalação](https://nodejs.org/learn/getting-started/an-introduction-to-the-npm-package-manager))
- **npm**
- **CodeceptJS**  ([guia oficial de instalação](https://codecept.io/installation/))
- **Playwright** ([guia oficial de instalação](https://playwright.dev/docs/intro))

## 📌 Passos

1. **Realizar o Download ZIP do projeto:**


<img width="565" height="495" alt="image" src="https://github.com/user-attachments/assets/2f573976-f5fc-4681-9681-cfe38c46cbe6" />

---

2. **Acessar a pasta Arquivos JavaScript (Testes Automatizados):**

<img width="512" height="75" alt="image" src="https://github.com/user-attachments/assets/381c1dfa-930c-487b-a173-1e1a1d6d8540" />


## 📌 Plano de Testes

Para garantir uma cobertura abrangente das funcionalidades da plataforma, o projeto foi dividido em seis Features, cada uma responsável por validar um conjunto específico de comportamentos do sistema.

Todos os cenários foram documentados utilizando a linguagem Gherkin, (por meio das palavras-chave Dado, Quando, Então e E) pensando na facilidade de comunicação para as equipes de desenvolvimento, qualidade (QA), produto e demais áreas envolvidas da FasTix.


1. **Acessar a pasta Plano de Testes:**

<img width="507" height="72" alt="image" src="https://github.com/user-attachments/assets/acc7b565-33c0-404d-92ba-4a62872f65c4" />

---

2. **Acessar o arquivo FasTix - Plano de Testes.docx:**

<img width="596" height="55" alt="image" src="https://github.com/user-attachments/assets/41cc0bbf-1210-4ab5-8918-bf120793e16a" />

---

3. **Consultar o Plano de Testes:**

<img width="1817" height="915" alt="image" src="https://github.com/user-attachments/assets/0623268e-849b-4e04-9a19-1e5cca74de99" />

---

## 📌 Bugs e Issues

Durante a execução dos testes automatizados foram identificados alguns comportamentos inesperados na plataforma.

Para documentar essas ocorrências foi elaborado um arquivo específico de Bugs e Issues, contendo as seguintes evidências de testes:

|Evidências                 |  
| ------------------------- | 
| Descrição detalhada de cada problema;            |     
| Passos para reprodução;         |     
| Resultado obtido;       |    
| Resultado esperado; |    
| Capturas de tela (screenshots);           |     
|Link para acesso de vídeos demonstrando os comportamentos encontrados          |     
|Propostas de melhoria para a plataforma         |     


Esse material auxilia na análise, priorização e correção das falhas identificadas, contribuindo para a evolução contínua da qualidade da plataforma.

1. **Acessar a pasta Bugs e Issues:**

<img width="507" height="57" alt="image" src="https://github.com/user-attachments/assets/28eaf619-5e42-423f-bbfb-18e625c82d78" />

---

2. **Acessar o arquivo FasTix - Bugs e Issues.docx:**

<img width="520" height="52" alt="image" src="https://github.com/user-attachments/assets/2f109dba-4ac1-4402-94d7-57959eacbab6" />

---

3. **Consultar o Bugs e Issues:**

<img width="1801" height="910" alt="image" src="https://github.com/user-attachments/assets/a4fc4703-d22f-4169-b7f4-5639a2eca8bb" />


---

## 🧰 Ambiente e rotina diária

O ambiente de testes combina:

### Pré-requisitos para utilização no Windows
* **Node.js**
* **JavaScript**
* **CodeceptJS**
* **Playwright:Para a execução de testes automatizados da aplicação Web da FasTix.**

## ⚙️ Configuração do Ambiente (Windows)

### Instalação do CodeceptJS com Playwright

### 📍 1. Instalar o Node.js

O CodeceptJS depende do Node.js para funcionar.

1. Acesse: https://nodejs.org/
2. Execute o instalador utilizando as configurações padrão.

### 📍 2. Verificar a instalação

```bash
node -v
```

Em seguida:

```bash
npm -v
```

> ⚠️ **Importante:** se ambos os comandos retornarem uma versão, a instalação foi concluída com sucesso.

### 📍 3. Criar o projeto

```bash
mkdir MeuProjeto
cd MeuProjeto
```

### 📍 4. Inicializar o projeto Node.js

```bash
npm init -y
```

Esse comando cria automaticamente o arquivo:

```text
package.json
```

### 📍 5. Instalar o CodeceptJS

```bash
npm install codeceptjs --save-dev
```

### 📍 6. Instalar o Playwright

Instale a biblioteca:

```bash
npm install playwright --save-dev
```

Depois instale os navegadores utilizados pelo Playwright:

```bash
npx playwright install
```

### 📍 7. Inicializar o CodeceptJS

```bash
npx codeceptjs init
```

### 📍 8. Configurar o assistente

| Pergunta | Resposta |
|----------|----------|
| **Where are your tests located?** | `./tests` |
| **What helpers do you want to use?** | `Playwright` |
| **Where is your application running?** | `https://fastix.com.br` *(ou a URL da aplicação)* |
| **Browser in which testing will be performed** | `chromium` |
| **Do you want to generate example tests?** | `Yes` |
| **Do you want to use TypeScript?** | `No` *(caso utilize JavaScript)* |

---

> ⚠️ **Importante:** a pasta `output/` armazena screenshots, vídeos e relatórios de falhas gerados automaticamente durante a execução dos testes — não deve ser versionada no repositório (adicione ao `.gitignore`).

### 📍 9. Criar um teste de exemplo

Crie o arquivo:

```text
tests/teste_inicial_test.js
```

```javascript
Feature("Teste Inicial");

Scenario("Abrir o Google", ({ I }) => {
  I.amOnPage("https://www.google.com");
  I.see("Google");
});
```

### 📍 10. Verificação final

Execute:

```bash
npx codeceptjs run
```

> ⚠️ **Importante:** se o teste for executado sem erros, o ambiente foi configurado corretamente.

---

## ✅ Uso

Após configurar o ambiente e instalar todas as dependências, utilize os comandos abaixo para executar os testes automatizados.

### 📍 Executar todos os testes automatizados

Executa todas as Features e todos os cenários de teste do projeto FasTix.

```bash
npx codeceptjs run
```

### 📍 Executar uma Feature específica

Executa todos os cenários pertencentes a uma Feature específica.

```bash
npx codeceptjs run --grep "nome_da_feature"
```

Exemplo:

```bash
npx codeceptjs run --grep "suporteeajuda"
```

Abaixo, segue a lista dos comandos para a execução de cada uma das seis Features específicas do projeto:

```bash
# 1 - Feature Explorar Eventos
npx codeceptjs run --grep "explorareventos"

# 2 - Feature Suporte e Ajuda
npx codeceptjs run --grep "suporteeajuda"

# 3 - Feature Tela Inicial
npx codeceptjs run --grep "telainicial"

# 4 - Feature Publicar Eventos
npx codeceptjs run --grep "publicareventos"

# 5 - Feature Comprar Ingressos
npx codeceptjs run --grep "compraringressos"

# 6 - Feature Criar Conta
npx codeceptjs run --grep "criarconta"
```

### 📍 Executar um cenário específico de uma Feature

Executa apenas um cenário de teste.

```bash
npx codeceptjs run --grep "nome_da_feature + número_do_cenário"
```

Exemplo:

```bash
npx codeceptjs run --grep "suporteeajuda33"
```

### 📍 Exibir cada passo da execução

```bash
npx codeceptjs run --steps
```

### 📍 Executar em modo detalhado

```bash
npx codeceptjs run --verbose
```

### 📍 Executar em modo detalhado exibindo todos os passos

```bash
npx codeceptjs run --steps --verbose
```

---

## 📁 Estrutura do repositório

```text
MeuProjeto/
├── tests/
│   └── example_test.js
├── output/
├── steps_file.js
├── codecept.conf.js
├── package.json
└── node_modules/
```


---

## 🧭 A Jornada do usuário

A suíte tem como objetivo automatizar e validar a jornada completa do usuário dentro da FasTix. Diferente de um fluxo estritamente linear, a plataforma atende dois perfis de usuário com caminhos próprios o comprador de ingressos e o produtor de eventos além de uma camada de suporte acessível a qualquer momento:

```text
Fluxo do Comprador:
Tela Inicial → Explorar Eventos → Criar Conta / Login → Comprar Ingressos → Pagamento e Confirmação
```

```text
Fluxo do Produtor:
Tela Inicial → Publicar Eventos → Login (Google / Apple / E-mail) → Gerenciamento de Eventos e Equipes
```

```text
Suporte e Ajuda: acessível a qualquer momento da jornada, funcionando como camada transversal de apoio ao usuário.
```

Os testes não validam apenas funcionalidades isoladas, mas também simulam comportamentos e situações próximas da utilização real de uma plataforma de venda de ingressos desde a descoberta de um evento na página inicial, passando pela pesquisa e seleção do evento certo, a criação de conta ou autenticação, a escolha e o pagamento dos ingressos, até a possibilidade de o mesmo usuário se tornar um produtor e publicar seus próprios eventos.

As informações a seguir apresentam a estrutura completa da suíte de testes da FasTix, organizada em seis Features que representam, em conjunto, a jornada do usuário na plataforma.

Cada Feature possui um conjunto de cenários que cobre desde o caminho feliz até casos de borda, testes de estresse, acessibilidade, performance e segurança, permitindo visualizar de forma clara o que é validado em cada etapa desde a descoberta do evento na Tela Inicial até a confirmação do pagamento na etapa de Comprar Ingressos, passando pelo suporte ao usuário e pela publicação de novos eventos por produtores.

---


## 🎯 Estratégia e cobertura de Testes 


A suíte automatizada do FasTix reúne 586 testes distribuídos em 6 Features, cobrindo toda a jornada do usuário na plataforma do primeiro acesso à compra de ingressos sob 17 dimensões de qualidade diferentes, não apenas validação funcional. 

A cobertura foi dimensionada por risco de negócio: as áreas com maior impacto em receita e alcance de usuários (Tela Inicial e Comprar Ingressos) concentram o maior volume de testes.

A FasTix é uma plataforma de venda, distribuição e intermediação de ingressos, atuando como ticketeira para produtores de eventos de todos os portes como shows, festivais, cursos, palestras, exposições e eventos esportivos. Além da venda ao público, oferece aos organizadores ferramentas de gestão de vendas e controle de acesso (check-in) no dia do evento. 

Esse escopo combina e-commerce, gestão de conteúdo publicado por terceiros e operação em tempo real, o que torna qualquer falha silenciosa potencialmente cara — seja em receita, confiança do produtor ou experiência do público na entrada do evento.

### Distribuição da cobertura

| Feature                     | Testes Automatizados | Papel na jornada |
| ---------------------------- | --------------------: | --- |
| Feature_Tela Inicial         |                   164 | Ponto de entrada, maior raio de impacto de qualquer instabilidade |
| Feature_Comprar Ingressos    |                   127 | Fluxo que gera receita diretamente |
| Feature_Publicar Eventos     |                    98 | Ferramenta de gestão para produtores |
| Feature_Suporte e Ajuda      |                    75 | Canal de contato, SEO e institucional |
| Feature_Explorar Eventos     |                    70 | Busca e navegação por carrossel de eventos divulgados na page|
| Feature_Criar Conta          |                    52 | Onboarding de novos usuários |
| **Total**                    |               **586** | — |

> ⚠️ **Importante:** A distribuição não é uniforme por decisão, não por lacuna: Tela Inicial e Comprar Ingressos concentram o maior volume porque representam, respectivamente, o ponto de contato de praticamente todo usuário e o fluxo com impacto financeiro direto — qualquer regressão ali tem o maior raio de dano possível ao negócio.

### Abordagem técnica

Cada Feature é testada sob um subconjunto relevante de 17 dimensões de qualidade:


| Tipos de Testes                            |
| ------------------------------------------ |
| Testes Funcionais                          |
| Testes End-to-End (E2E)                    |
| Testes de Navegação                        |
| Testes de Interface (UI)                   |
| Testes de Responsividade                   |
| Testes de Acessibilidade                   |
| Testes de Performance                      |
| Testes de Estabilidade                     |
| Testes de Estresse                         |
| Testes de Robustez                         |
| Testes de Validação de Dados               |
| Testes de Integridade                      |
| Testes de Compatibilidade de Navegação     |
| Testes de Monitoramento de Erros           |
| Testes de Contrato de Eventos de Analytics |
| Testes de SEO e Metadados                  |
| Testes de Segurança                        |
| **Total: 17 tipos de testes**              |


Todos os testes foram aplicados conforme o que cada parte da aplicação efetivamente arrisca quebrar, não como um checklist genérico repetido igualmente em toda a plataforma. 

Um fluxo de checkout demanda rigor em cálculo de valores e estabilidade sob múltiplas interações; uma página institucional de suporte demanda mais atenção a acessibilidade, SEO e integridade de links externos. 

Essa adaptação por contexto é o que diferencia uma suíte estruturada por risco de uma simples réplica de casos de teste entre páginas.

O conjunto completo funciona como base de regressão contínua: qualquer alteração na plataforma pode ser validada contra os 586 cenários existentes antes de chegar ao usuário final, ao produtor de evento ou à operação de check-in.

---

##  🔍 Feature Explorar Eventos


| Feature | 
| ------------------------- | 
| Feature_Explorar Eventos | 
| 0001 - Acessar a página de eventos (Botão: Explorar eventos) | |
| 0002 - Acessar a página de eventos (segunda opção de acesso via ícone fast-forward) | |
| 0003 - Acessar a página de eventos (Botão: Explorar eventos) e verificar a navegação por scroll | |
| 0004 - Acessar a página de eventos (segunda opção de acesso via ícone fast-forward) e verificar a navegação por scroll | |
| 0005 - Buscar uma cidade (São Paulo) no campo de pesquisa por evento (Botão: Explorar eventos) | |
| 0006 - Buscar uma cidade (São Paulo) no campo de pesquisa por evento (segunda opção de acesso via ícone fast-forward) | |
| 0007 - Buscar um evento (Buffalo Tom em São Paulo) no campo de pesquisa (Botão: Explorar eventos) | |
| 0008 - Buscar um evento (Buffalo Tom em São Paulo) no campo de pesquisa (segunda opção de acesso via ícone fast-forward) | |
| 0009 - Buscar um local (Fabrique Club) no campo de pesquisa (Botão: Explorar eventos) | |
| 0010 - Buscar um local (Cine Joia) no campo de pesquisa (segunda opção de acesso via ícone fast-forward) | |
| 0011 - Buscar um evento (Buffalo Tom em São Paulo) e visualizar suas informações no campo de pesquisa (Botão: Explorar eventos) | |
| 0012 - Buscar um evento (Buffalo Tom em São Paulo) no campo de pesquisa (segunda opção de acesso via ícone fast-forward) | |
| 0013 - Visualizar os campos 'Sobre o evento', clicar em 'Leia mais' e 'Mostrar menos' | |
| 0014 - Acessar o campo 'Localização' e abrir o endereço clicando em 'Abrir no Google Maps' | |
| 0015 - Acessar o endereço no Google Maps e retornar para a página do evento (Buffalo Tom em São Paulo) | |
| 0016 - Acessar o campo 'Localização', clicar em 'Ver mais' e acessar a página | |
| 0017 - Acessar a página 'Ver mais' e clicar no ícone abaixo do evento para retornar à página do evento | |
| 0018 - Acessar a página do evento (Buffalo Tom em São Paulo) e clicar no ícone do Google Maps ao lado do título 'Cine Joia' | |
| 0019 - Acessar a página do Google Maps, depois, retornar para a página do evento (Buffalo Tom em São Paulo) | |
| 0020 - Acessar a página de Política de Compra (via acesso superior da página) e verificar a navegação por scroll | |
| 0021 - Acessar a página de Termos de Uso (via acesso superior da página) e verificar a navegação por scroll | |
| 0022 - Acessar a página de Política de Compra (via acesso inferior da página) e verificar a navegação por scroll | |
| 0023 - Acessar a página de Termos de Uso (via acesso inferior da página) e verificar a navegação por scroll | |
| 0024 - Acessar a página de Meia-Entrada e verificar a navegação por scroll | |
| 0025 - Acessar a página de Guia Check-in e verificar a navegação por scroll | |
| 0026 - Acessar as opções 'App Fastix (Recomendado)' e 'Web' do 'Guia Check-in' | |
| 0027 - Acesso simultâneo entre os campos 'Meia Entrada', 'Política de Compra', 'Termos de Uso' | |
| 0028 - No campo 'Termos de Uso', acessar o tópico '2. Aceite dos Termos' e acessar o link 'Política de Compra' | |
| 0029 - No campo 'Termos de Uso', acessar o tópico '2. Aceite dos Termos' e acessar o link 'Política de Meia-entrada e ingressos Acessíveis' | |
| 0030 - No campo 'Termos de Uso', acessar o tópico '9. Operação, Isenções e Limitação de Responsabilidade' e acessar o link 'Política de Compra' | |
| 0031 - No campo 'Termos de Uso', acessar o tópico '13. Comunicações Eletrônicas' e acessar o link 'Política de Compra' | |
| 0032 - No campo 'Política de Compra', acessar o tópico '1. INTRODUÇÃO' e acessar o link 'Termos de Uso' | |
| 0033 - No campo 'Política de Compra', acessar o tópico '1. INTRODUÇÃO' e acessar o link 'Política de Meia-Entrada e Ingressos Acessíveis' | |
| 0034 - No campo 'Política de Compra', acessar o tópico '2. SUA CONTA E REGISTRO' e acessar o link 'Termos de Uso' | |
| 0035 - Validar campo de pesquisa por evento, local e cidade utilizando termo inexistente: 'Testando Fastix' | |
| 0036 - Validar campo de pesquisa por evento, local e cidade utilizando caracteres especiais | |
| 0037 - Validar o campo de pesquisa por evento, local e cidade utilizando 10 vezes cada caractere especial | |
| 0038 - Validar o campo de pesquisa por evento, local e cidade utilizando números | |
| 0039 - Validar o campo de pesquisa por evento, local e cidade com variações de caracteres especiais | |
| 0040 - Validar o campo de pesquisa por evento, local e cidade com combinação de números e caracteres especiais | |
| 0041 - Navegação entre eventos no carrossel utilizando o botão de controle por ícone (Botão voltar) | |
| 0042 - Navegação entre eventos no carrossel utilizando o botão de controle por ícone (Botão avançar) | |
| 0043 - Navegação entre eventos no carrossel utilizando os botões de voltar e avançar (10x voltar + 10x avançar) | |
| 0044 - Navegação de Stress no carrossel + acesso ao evento 'Buffalo Tom em São Paulo' | |
| 0045 - Navegação de stress no carrossel, acesso ao evento e retorno à home page | |
| 0046 - Validar estabilidade da busca sob stress | |
| 0047 - Validar comportamento do sistema sob duplo clique e múltiplos cliques consecutivos | |
| 0048 - Validar navegação utilizando back e forward do navegador | |
| 0049 - Validar recuperação da aplicação após refresh durante interação | |
| 0050 - Stress de refresh durante interação contínua | |
| 0051 - Validar responsividade da aplicação em dispositivos mobile, tablet e desktop ultrawide | |
| 0052 - Validar navegação utilizando apenas teclado | |
| 0053 - Validar atualização correta dos conteúdos do carrossel | |
| 0054 - Validar comportamento visual, navegação, estabilidade, integridade e stress do carrossel de eventos | |
| 0055 - Validar acessos simultâneos dos links institucionais, aplicativos e redes sociais no rodapé do evento | |
| 0056 - Validar abertura e navegação entre múltiplas abas externas e internas | |
| 0057 - Validar a recuperação do sistema após uma busca inválida e sem resultados | |
| 0058 - Input extremo: validar comportamento da busca com entradas extremas | |
| 0059 - Validar tempo de resposta da aplicação | |
| 0060 - Validar estabilidade da aplicação durante scroll agressivo | |
| 0061 - Validar integridade do conteúdo dinâmico dos cards de eventos | |
| 0062 - Validar a integridade das imagens da plataforma na página 'Explorar Eventos' | |
| 0063 - Validar ausência de erros críticos no console da aplicação | |
| 0064 - Validar estabilidade da aplicação durante sessão longa | |
| 0065 - Validar estabilidade da aplicação após múltiplos reloads consecutivos | |
| 0066 - Validar comportamento da página de explorar eventos após interrupções inesperadas | |
| 0067 - Validar gerenciamento correto de foco da aplicação na página de 'Explorar eventos' | |
| 0068 - Validar navegação utilizando apenas TAB na página 'Explorar Eventos' | |
| 0069 - Validar filtros e navegação da página 'Explorar Eventos' | |
| 0070 - Validar integridade do footer após múltiplas interações | |
| **Total** | **70** |

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

## 🔍 Feature Suporte e Ajuda

| Feature |
| ------------------------- |
| Feature_Suporte e Ajuda |
| 0001 - Acessar a página de Suporte e Ajuda pela página principal |
| 0002 - Acessar a página de Suporte e Ajuda e navegar até o footer |
| 0003 - Acessar o contato da Fastix via Instagram |
| 0004 - Acessar o contato da Fastix via Email (5 cliques consecutivos) |
| 0005 - Acessar o contato da Fastix via WhatsApp |
| 0006 - Preencher o formulário completo de contato |
| 0007 - Impedir envio da mensagem quando o campo "NOME" não é preenchido |
| 0008 - Impedir envio da mensagem quando o campo "EMAIL" não é preenchido |
| 0009 - Impedir envio da mensagem quando o campo "MENSAGEM" não é preenchido |
| 0010 - Impedir envio da mensagem quando nenhum campo é preenchido |
| 0011 - E-mail sem o @ — bloqueio do envio |
| 0012 - Aceitar e-mail com @, mas manter envio bloqueado sem validação humana |
| 0013 - Validar preenchimento de todos os campos com caracteres especiais |
| 0014 - Validar preenchimento individual dos campos com 10x cada caractere especial |
| 0015 - Clicar no card "Como solicitar reembolso?" |
| 0016 - Clicar nos cards "Como solicitar reembolso?" e "O que preciso levar no dia do evento?" |
| 0017 - Clicar nos cards reembolso, evento e "Como vender ingressos pela FasTix?" |
| 0018 - Clicar nos cards reembolso, evento, venda e "Onde compro ingresso sem taxa?" |
| 0019 - Clicar e acessar o botão iOS |
| 0020 - Clicar e acessar o botão Android |
| 0021 - Clicar e acessar o Guia Check-in |
| 0022 - Clicar e acessar os Termos e Condições de Uso |
| 0023 - Clicar e acessar a Política de Compra |
| 0024 - Clicar e acessar a Meia Entrada |
| 0025 - Clicar no ícone do LinkedIn na Central de Ajuda |
| 0026 - Clicar no ícone do Instagram na Central de Ajuda |
| 0027 - Clicar no ícone do X na Central de Ajuda |
| 0028 - Clicar no ícone de Email (Contato) na Central de Ajuda |
| 0029 - Clicar no link WebSolutionsFL na Central de Ajuda |
| 0030 - Navegação por teclado até o botão Suporte e Ajuda |
| 0031 - Validar acessibilidade e navegação via TAB em todos os campos do formulário |
| 0032 - Validação visual do foco na página de Suporte e Ajuda |
| 0033 - Garantir acesso e funcionalidade dos elementos do footer via navegação por TAB |
| 0034 - Persistência do formulário após scroll (stress test 10x) |
| 0035 - Validação de campos obrigatórios com espaços vazios |
| 0036 - Validação do limite máximo do campo Nome |
| 0037 - Validação do limite máximo do campo Mensagem (estabilidade) |
| 0038 - Validar limite máximo do campo Código do Pedido |
| 0039 - Validação do limite máximo do campo Email (estabilidade) |
| 0040 - Colagem de conteúdo no campo Mensagem do formulário |
| 0041 - Atualização (reload) da página durante preenchimento do formulário |
| 0042 - Validar estabilidade da aplicação durante navegação repetitiva (3x) |
| 0043 - Validar estabilidade sob navegação repetitiva com liberação de memória (20x) |
| 0044 - Validar estabilidade durante navegações repetitivas com monitoramento de console/rede (20x) |
| 0045 - Detecção de memory leak visual no fluxo de suporte (20x) |
| 0046 - Validar performance e estabilidade da navegação para a página de suporte (10 ciclos) |
| 0047 - Responsividade da página de suporte (Desktop, Laptop, Tablet, Mobile) |
| 0048 - Clique múltiplo nos botões de contato Instagram, Email e WhatsApp (10x) |
| 0049 - Estabilidade visual durante scroll contínuo (20x) |
| 0050 - Validar acessibilidade e integridade de todos os links da página |
| 0051 - Navegação para páginas externas com verificação de status HTTP |
| 0052 - Validar retorno correto ao utilizar o botão voltar do navegador (múltiplas páginas) |
| 0053 - Validar navegação e retorno correto das páginas do menu superior |
| 0054 - Validar navegação e retorno via botões Entrar, Criar Conta e Voltar |
| 0055 - Fluxo completo de navegação e retorno (navegador + menu + Entrar/Criar Conta) |
| 0056 - Validação de estabilidade após múltiplos acessos (5x) |
| 0057 - Validação de estabilidade após múltiplos acessos ao footer (5x, com liberação de memória) |
| 0058 - Validar stress de clique nos cards da página (5 loops × 4 cards) |
| 0059 - Validação visual do footer da página |
| 0060 - Validação visual do footer com responsividade (Desktop e Mobile) |
| 0061 - Observabilidade do console e falhas de rede |
| 0062 - Observabilidade realista de console, rede e UI |
| 0063 - Validar performance da página via Navigation Timing API |
| 0064 - Validação de Lazy loading do footer |
| 0065 - Validar estabilidade do formulário por execuções repetidas (Anti-Flaky, 3x) |
| 0066 - Teste anti-flaky do formulário com métricas de estabilidade e retries (5x) |
| 0067 - Validação de fallback sem imagens na página |
| 0068 - Validação de eventos no DataLayer |
| 0069 - Validação de contrato de eventos no dataLayer (schema e sequência) |
| 0070 - Validação de SEO title e meta description |
| 0071 - Validar SEO da página com keywords obrigatórias e opcionais |
| 0072 - Validação de OG tags |
| 0073 - Validar consistência das OG tags entre browser e crawler headless |
| 0074 - Garantir acessibilidade básica dos campos do formulário (label ou ARIA) |
| 0075 - Validar exposição de scripts e possíveis leaks de dados sensíveis no HTML |
| **Total** | **75** |

Assim como na Feature Explorar Eventos, todos os testes foram classificados considerando diferentes dimensões de teste, evitando tratar conceitos distintos (E2E, Regressão, Acessibilidade, Stress, SEO, Segurança) como categorias equivalentes.

### 📌 Dimensões de cobertura

| Dimensão | Categorias | Objetivo |
| --- | --- | --- |
| **Escopo** | E2E | Validar jornadas completas atravessando múltiplas páginas |
| **Objetivo funcional** | Funcionais, Validação de Dados, Integridade | Verificar comportamentos esperados, dados apresentados e consistência das informações |
| **Qualidade da aplicação** | UI, Responsividade, Acessibilidade, Performance, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais |
| **Condição / técnica de teste** | Estresse, Compatibilidade de Navegação | Exercitar a aplicação sob condições repetitivas, intensivas ou diferentes formas de navegação |
| **Resiliência** | Monitoramento de Erros, Recuperação de Estado | Avaliar comportamento diante de erros, reloads e interrupções |
| **Observabilidade e Contrato** | Analytics (dataLayer), SEO / Metadados | Verificar se dados de rastreamento e metadados de página seguem um contrato/schema esperado — dimensão específica desta feature, ausente na Explorar Eventos |
| **Segurança** | Exposição de dados sensíveis | Verificar ausência de vazamento de credenciais, tokens ou chaves no HTML/scripts renderizados — dimensão específica desta feature |
| **Finalidade de execução** | Regressão | Reexecutar cenários existentes para identificar impactos causados por alterações no sistema |

---

## 🧪 Cobertura funcional e E2E

### Testes Funcionais

Validam se as funcionalidades disponíveis na página apresentam o comportamento esperado.

**Exemplos:**

* **0001–0006:** acesso à página e aos canais de contato (Instagram, Email, WhatsApp), preenchimento completo do formulário;
* **0015–0018:** interação com os cards de ajuda ("Como solicitar reembolso?", "O que levar no dia do evento?", etc.);
* **0019–0024:** acesso a páginas institucionais (iOS, Android, Guia Check-in, Termos, Política de Compra, Meia Entrada);
* **0025–0029:** ícones e links do footer (LinkedIn, Instagram, X, Email, WebSolutionsFL);
* **0040:** colagem de conteúdo no campo Mensagem.

### Testes End-to-End (E2E)

Validam jornadas completas envolvendo múltiplos componentes ou páginas.

**Exemplos:**

* **0021–0024:** Suporte → página institucional específica;
* **0052–0055:** navegação para páginas externas/internas → retorno à página de Suporte, incluindo fluxos de Entrar e Criar Conta;
* **0073:** comparação entre a renderização vista pelo browser e a servida a um crawler headless — atravessa camada de frontend e de servidor.

> **Observação:** assim como na Feature Explorar Eventos, E2E representa o **escopo da jornada**, não uma categoria funcional isolada.

---

## 🧭 Testes de Navegação

**Exemplos:**

* **0001–0005:** diferentes formas de acesso à página e aos canais de contato;
* **0015–0029:** navegação por cards de ajuda, páginas institucionais e ícones do footer;
* **0052–0055:** botão voltar do navegador, menu superior, e botões Entrar/Criar Conta.

---

## 🖥️ Testes de Interface (UI)

**Exemplos:**

* **0015–0018:** overlays dos cards de ajuda;
* **0025–0029:** ícones de redes sociais e contato no footer;
* **0032:** indicação visual de foco;
* **0059–0060:** integridade visual do footer.

---

## 📱 Testes de Responsividade

**Exemplos:**

* **0047:** validação em 4 resoluções — Desktop (1920×1080), Laptop (1366×768), Tablet (768×1024), Mobile (375×667);
* **0060:** footer especificamente validado em Desktop (1280×720) e Mobile (375×812).

---

## ♿ Testes de Acessibilidade

**Exemplos:**

* **0030:** navegação via TAB até o link "Suporte e Ajuda";
* **0031:** navegação via TAB por todos os campos do formulário (fluxo único de até 80 tabs);
* **0032:** validação visual do indicador de foco (outline, box-shadow, ring);
* **0033:** acesso ao footer via TAB (até 120 tabs), validando que links possuem `href` funcional;
* **0074:** presença de `label`/`aria-label` nos campos do formulário.

---

## ⚡ Testes de Performance

**Exemplos:**

* **0046:** tempo de navegação por 10 ciclos, com limite de 3000ms por ciclo;
* **0063:** métricas via Navigation Timing API (`domContentLoaded`, `TTFB`, `responseTime`), com thresholds definidos;
* **0064:** comportamento de lazy loading do footer.

> Assim como na feature de referência, a cobertura de performance é **pontual**, focada em tempo de navegação e carregamento — não caracteriza uma estratégia completa de load/stress de infraestrutura.

---

## 🔄 Testes de Estabilidade

**Exemplos:**

* **0034:** persistência do formulário após 10 ciclos de scroll;
* **0041:** recuperação após reload duplo durante preenchimento;
* **0042–0043:** navegação repetitiva (3x e 20x);
* **0049:** scroll contínuo (20 ciclos);
* **0056–0057:** múltiplos acessos consecutivos (5x), incluindo variante com footer e liberação forçada de memória;
* **0065–0066:** testes anti-flaky do formulário, incluindo cálculo de taxa de flakiness (`flakinessRate`) com limite de 10%.

---

## 🔥 Testes de Estresse (Stress Testing)

**Exemplos:**

* **0004:** 5 cliques consecutivos no link de e-mail;
* **0014:** preenchimento com 10 repetições de cada caractere especial, em loop;
* **0034:** 10 ciclos de scroll com validação de persistência;
* **0043–0045:** 20 ciclos de navegação, com monitoramento de erros e detecção de memory leak visual;
* **0048:** 10 ciclos de clique simulado nos botões de contato (com neutralização de `href` para evitar navegação real);
* **0058:** 5 loops × 4 cards = 20 interações de clique.

> **Importante:** assim como na Explorar Eventos, esses cenários caracterizam stress/robustez de componentes da página — não simulam carga concorrente de múltiplos usuários nem substituem uma ferramenta dedicada de load testing.

---

## 🛡️ Testes de Robustez

**Exemplos:**

* **0007–0010:** bloqueio de envio com campos individualmente ou totalmente vazios;
* **0011–0012:** e-mail malformado (sem `@`) e e-mail válido sem validação humana (captcha);
* **0013–0014:** conjunto amplo de caracteres especiais (incluindo símbolos matemáticos, moedas, acentuação) em todos os campos;
* **0035:** campos preenchidos apenas com espaços em branco;
* **0036–0039:** limites máximos de caracteres por campo (Nome, Mensagem, Código do Pedido, Email), validando truncamento real via manipulação do `value` nativo do input;
* **0040:** colagem de conteúdo extenso;
* **0067:** comportamento da página com todas as imagens bloqueadas (fallback).

---

## 🔎 Testes de Validação de Dados

**Exemplos:**

* **0007–0014:** validação de campos obrigatórios e formato de e-mail;
* **0035–0039:** limites de caracteres e valor real armazenado em cada campo;
* **0050:** integridade dos `href` de 10 links distintos (Instagram, Email, WhatsApp, iOS, Android, LinkedIn, X/Twitter, WebSolutionsFL);
* **0069–0070:** schema de eventos do dataLayer e presença de metadados de SEO.

---

## 🔐 Testes de Integridade

**Exemplos:**

* **0045:** ausência de crescimento anormal do DOM entre ciclos (indício de memory leak);
* **0049:** variação controlada de elementos de UI durante scroll contínuo;
* **0050:** ausência de links vazios ou quebrados;
* **0059–0060:** integridade estrutural do footer (altura, largura, itens renderizados);
* **0064:** presença de links no footer após o carregamento progressivo (lazy loading).

---

## 🌐 Testes de Compatibilidade de Navegação

**Exemplos:**

* **0052:** botão voltar do navegador, testado contra 4 páginas institucionais distintas;
* **0053–0054:** navegação e retorno via menu superior e via botões Entrar/Criar Conta;
* **0055:** combinação de todos os mecanismos de navegação (voltar do navegador + menu + Entrar/Criar Conta) em um único fluxo.

> Assim como na feature de referência, essa categoria trata de **diferentes mecanismos de navegação** dentro do mesmo navegador — não caracteriza uma estratégia de teste cross-browser.

---

## 🚨 Testes de Monitoramento de Erros

**Exemplos:**

* **0044:** captura de erros de console, `pageerror` e falhas de rede durante 20 ciclos, com filtros para ruído conhecido (Cloudflare challenge, erro pré-existente de SSR `React #418`) e limite de 5 erros críticos;
* **0056–0057:** ausência de textos como "404", "500", "Application error" após múltiplos acessos;
* **0061–0062:** monitoramento dedicado de console e falhas de rede (`requestfailed`) em um fluxo único.

---

## 🎨 Testes de Integridade Visual

**Exemplos:**

* **0032:** indicador visual de foco;
* **0045:** estabilidade do número de elementos de UI entre ciclos;
* **0049:** variação de botões/inputs durante scroll contínuo;
* **0059–0060:** estrutura visual do footer, incluindo responsividade.

---

## 🔄 Recuperação e Estado da Aplicação

**Exemplos:**

* **0041:** recuperação do formulário após dois reloads consecutivos;
* **0065–0066:** testes anti-flaky com retry automático (até 2 tentativas por execução) e cálculo formal de taxa de flakiness.

> **Precisão técnica:** assim como destacado na feature de referência, esses cenários validam **recuperação/resiliência da interface**, não persistência de dados de negócio em backend — o formulário nunca é de fato submetido com sucesso em nenhum cenário desta suíte (o botão permanece desabilitado sem validação humana, cenário 0012).

---

## 📊 Observabilidade e Contrato (dimensão nova nesta feature)

Avaliam se eventos de rastreamento e metadados da página seguem um contrato/schema esperado — categoria não presente na Feature Explorar Eventos.

**Exemplos:**

* **0068:** presença de eventos no `dataLayer` relacionados a "Suporte"/"contact" após o clique;
* **0069:** validação de **schema completo** do evento `gtm.linkClick` (campos obrigatórios `gtm.elementText`, `gtm.elementUrl`, `gtm.triggers`), sequência esperada de eventos (`gtm.js` → `gtm.dom` → `gtm.load` → `gtm.linkClick` → `gtm.historyChange`), e ausência de eventos duplicados.

---

## 🔍 Testes de SEO e Metadados (dimensão nova nesta feature)

**Exemplos:**

* **0070:** presença e tamanho de `title` e `meta description` (limite de 160 caracteres);
* **0071:** presença de keywords obrigatórias (`fastix`) e opcionais (`ingressos`, `suporte`, `ajuda`), com cálculo de score percentual;
* **0072:** presença e tamanho mínimo de tags Open Graph (`og:title`, `og:description`, `og:url`);
* **0073:** **consistência entre o HTML servido ao navegador e o HTML servido a um crawler** (simulado com User-Agent do Googlebot) — verifica se a aplicação faz pré-renderização correta de metadados para SEO.

---

## 🔒 Testes de Segurança (dimensão nova nesta feature)

**Exemplo:**

* **0075:** varredura do HTML renderizado (na Home e na página de Suporte) em busca de padrões sensíveis (`api_key`, `secret`, `token`, `password`, `bearer`, `jwt`, entre outros) e de scripts inline suspeitos.

---

# 🔁 Regressão

A **regressão não representa um conjunto separado de cenários**.

Os 75 cenários podem ser utilizados como uma **suíte de regressão automatizada**, especialmente após:

* alterações no formulário de contato ou em suas validações;
* alterações nos cards da Central de Ajuda;
* alterações no footer ou em seus links;
* alterações de navegação entre Suporte e outras páginas do site;
* mudanças em tags de SEO/Open Graph;
* mudanças na configuração de eventos de Analytics (dataLayer);
* alterações estruturais na página que possam impactar acessibilidade.

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

| Dimensão | Cenários principais | Cobertura |
| --- | --- | --- |
| **E2E** | 0021–0024, 0052–0055, 0073 | 🟢 |
| **Funcional** | 0001–0029, 0040 | 🟢 |
| **Regressão** | 0001–0075 | 🟢 |
| **Navegação** | 0001–0029, 0052–0055 | 🟢 |
| **UI** | 0015–0018, 0025–0029, 0032, 0059–0060 | 🟢 |
| **Responsividade** | 0047, 0060 | 🟢 |
| **Acessibilidade** | 0030–0033, 0074 | 🟢 |
| **Performance** | 0046, 0063, 0064 | 🟡 |
| **Estabilidade** | 0034, 0037, 0041–0045, 0049, 0056–0057, 0065–0066 | 🟢 |
| **Estresse** | 0004, 0014, 0034, 0043–0045, 0048, 0058 | 🟢 |
| **Robustez** | 0007–0014, 0035–0040, 0067 | 🟢 |
| **Validação de Dados** | 0007–0014, 0035–0039, 0050, 0069–0070 | 🟢 |
| **Integridade** | 0045, 0049–0050, 0059–0060, 0064 | 🟢 |
| **Compatibilidade de Navegação** | 0052–0055 | 🟢 |
| **Monitoramento de Erros** | 0044, 0056–0057, 0061–0062 | 🟢 |
| **Integridade Visual** | 0032, 0045, 0049, 0059–0060 | 🟢 |
| **Recuperação/Estado** | 0041, 0065–0066 | 🟢 |
| **Observabilidade / Analytics** | 0068–0069 | 🟢 |
| **SEO / Metadados** | 0070–0073 | 🟢 |
| **Segurança** | 0075 | 🟡 |

**Legenda:**
🟢 Cobertura claramente demonstrada pelos cenários analisados
🟡 Cobertura presente, porém pontual e passível de expansão

---

## 🔍 Feature Tela Inicial

| Feature |
| ------------------------- |
| Feature_Tela Inicial |
| 0001 - Acessar "Explorar Eventos" |
| 0002 - Acessar "Publicar Eventos" |
| 0003 - Acessar "Suporte e Ajuda" |
| 0004 - Acessar botão de idioma |
| 0005 - Acessar o botão de idioma e clicar na opção Português |
| 0006 - Acessar o botão de idioma e clicar na opção Español |
| 0007 - Acessar o botão de idioma e clicar na opção English |
| 0008 - Acessar o botão de "Entrar" |
| 0009 - Acessar o botão de "Criar Conta" |
| 0010 - Acessar o botão de busca (Search / Command Palette ⌘K) |
| 0011 - Acessar o botão "Explorar eventos" |
| 0012 - Acessar o botão "Pesquisar evento, local..." |
| 0013 - Navegação no carrossel utilizando o botão de controle por ícone |
| 0014 - Navegação sequencial no carrossel com múltiplos cliques (10x) |
| 0015 - Navegação no carrossel com seleção de evento (THE WHITE BUFFALO em SÃO PAULO) |
| 0016 - Navegação sequencial no carrossel (esquerda 10x + direita 10x) |
| 0017 - Clicar no botão "Criar Conta" |
| 0018 - Clicar no botão "Publicar evento" |
| 0019 - Clicar em "Criar Conta" próximo ao título "Vendendo tickets online? Nós podemos ajudar" |
| 0020 - Clicar no botão iOS no footer |
| 0021 - Clicar no botão Android no footer |
| 0022 - Clicar no Guia Check-in no footer |
| 0023 - Clicar em Termos e Condições de Uso no footer |
| 0024 - Clicar em Política de Compra no footer |
| 0025 - Clicar em Meia Entrada no footer |
| 0026 - Clicar no ícone do LinkedIn no footer |
| 0027 - Clicar no ícone do Instagram no footer |
| 0028 - Clicar no ícone do Twitter no footer (ícone desatualizado) |
| 0029 - Clicar no ícone de Email no footer |
| 0030 - Clicar no link WebSolutionsFL no footer |
| 0031 - Validar que todos os links principais retornam status 200 (Broken Links) |
| 0032 - Validar abertura correta de links externos sem navegação real (Instagram) |
| 0033 - Validar alteração completa de idioma para English |
| 0034 - Validar alteração de idioma para English e comportamento após atualização da página |
| 0035 - Validar alteração completa de idioma para Español |
| 0036 - Validar acessibilidade e navegação via TAB nos elementos interativos e no footer |
| 0037 - Validar estrutura visual, landmarks e atributos principais da home |
| 0038 - Validar contraste visual mínimo dos componentes críticos |
| 0039 - Validar foco visível ao navegar via teclado |
| 0040 - Validar abertura do menu de idioma via ENTER |
| 0041 - Diagnosticar comportamento do atalho CTRL + K |
| 0042 - Validar comportamento funcional do atalho CTRL + K |
| 0043 - Validar estrutura principal, navegação e responsividade da Home (Desktop/Tablet/Mobile) |
| 0044 - Validar que o header não sofre quebra visual em diferentes resoluções |
| 0045 - Validar carregamento inicial da home em menos de 3 segundos |
| 0046 - Validar estabilidade do carrossel após 100 navegações consecutivas (esquerda + direita) |
| 0047 - Validar carregamento dinâmico de eventos durante scroll (Lazy Loading) |
| 0048 - Validar estabilidade do botão "Explorar Eventos" em execuções repetidas (10x, anti-flaky) |
| 0049 - Validar presença de título da página (SEO) |
| 0050 - Validar presença de meta description (SEO) |
| 0051 - Validar presença de atributo alt em imagens |
| 0052 - Validar ausência de informações sensíveis no frontend |
| 0053 - Validar ausência de informações sensíveis no frontend (variante com padrões nomeados) |
| 0054 - Validar ausência de erro interno exposto e exibição de mensagem amigável |
| 0055 - Validar padronização visual dos botões CTA |
| 0056 - Validar consistência dos links do footer |
| 0057 - Pesquisar evento existente |
| 0058 - Pesquisar evento inexistente |
| 0059 - Pesquisar utilizando caracteres especiais |
| 0060 - Validar debounce da busca |
| 0061 - Validar ausência de erros no console durante navegação |
| 0062 - Validar resposta da API de eventos |
| 0063 - Validar comportamento da interface sem carregamento de imagens |
| 0064 - Validar disparo de evento analytics ao clicar em Explorar Eventos |
| **Total** | **64** |

Assim como nas Features Explorar Eventos e Suporte e Ajuda, todos os testes foram classificados considerando diferentes dimensões de teste, evitando tratar conceitos distintos (E2E, Regressão, Acessibilidade, Stress, SEO, Segurança) como categorias equivalentes.

### 📌 Dimensões de cobertura

| Dimensão | Categorias | Objetivo |
| --- | --- | --- |
| **Escopo** | E2E | Validar jornadas completas atravessando múltiplas páginas a partir da Home |
| **Objetivo funcional** | Funcionais, Validação de Dados, Integridade | Verificar comportamentos esperados, dados apresentados e consistência das informações |
| **Qualidade da aplicação** | UI, Responsividade, Acessibilidade, Performance, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais |
| **Condição / técnica de teste** | Estresse, Compatibilidade de Navegação | Exercitar a aplicação sob condições repetitivas, intensivas ou diferentes mecanismos de interação |
| **Resiliência** | Monitoramento de Erros, Recuperação de Estado | Avaliar comportamento diante de erros, reloads e persistência de preferências |
| **Observabilidade e Contrato** | Analytics (dataLayer), SEO / Metadados | Verificar se dados de rastreamento e metadados de página seguem o esperado |
| **Segurança** | Exposição de dados sensíveis, mensagens de erro | Verificar ausência de vazamento de credenciais/tokens e de mensagens técnicas expostas ao usuário |
| **Finalidade de execução** | Regressão | Reexecutar cenários existentes para identificar impactos causados por alterações no sistema |

---

## 🧪 Cobertura funcional e E2E

### Testes Funcionais

**Exemplos:**

* **0001–0012:** acesso direto aos principais pontos de entrada da Home (Explorar Eventos, Publicar Eventos, Suporte e Ajuda, seletor de idioma, Entrar, Criar Conta, busca);
* **0017–0030:** cliques em CTAs e links institucionais/footer (iOS, Android, Guia Check-in, Termos, Política de Compra, Meia Entrada, redes sociais, WebSolutionsFL);
* **0040:** abertura do menu de idioma via tecla ENTER;
* **0057:** pesquisa e acesso a um evento existente.

### Testes End-to-End (E2E)

**Exemplos:**

* **0015:** navegação no carrossel → seleção do evento "THE WHITE BUFFALO em SÃO PAULO" → validação da URL de destino;
* **0020–0025:** Home → páginas institucionais via footer;
* **0057:** Home → busca → seleção do evento → página de detalhes;
* **0062:** validação da origem dos dados (API ou SSR) ao carregar a página de eventos — atravessa frontend e camada de rede;
* **0064:** clique em "Explorar Eventos" → navegação → validação do evento correspondente no dataLayer.

> **Observação:** assim como nas features de referência, E2E representa o **escopo da jornada**, não uma categoria funcional isolada.

---

## 🧭 Testes de Navegação

**Exemplos:**

* **0001–0012:** diferentes pontos de acesso a partir da Home;
* **0013–0016:** navegação entre eventos no carrossel (esquerda, direita, sequencial e combinada);
* **0017–0030:** navegação via CTAs e via links do footer;
* **0057–0058:** navegação decorrente da busca (evento encontrado ou não).

---

## 🖥️ Testes de Interface (UI)

**Exemplos:**

* **0013–0016:** resposta visual do carrossel aos cliques de navegação;
* **0020–0030:** ícones e botões do footer (redes sociais, apps, institucionais);
* **0055:** padronização visual entre os botões CTA "Explorar Eventos" e "Publicar Eventos" (cor, borda, tipografia);
* **0056:** consistência visual dos links do footer (cor, tamanho e peso de fonte).

---

## 📱 Testes de Responsividade

**Exemplos:**

* **0043:** validação híbrida da estrutura da Home em Desktop (1920×1080), Tablet (768×1024) e Mobile (375×812);
* **0044:** header validado especificamente contra quebra visual nas mesmas três resoluções.

---

## ♿ Testes de Acessibilidade

**Exemplos:**

* **0036:** navegação via TAB cobrindo desde o topo da página até todos os itens do footer (até 100 tabs por elemento-alvo);
* **0037:** presença de landmarks (`header`, `main`/`role="main"`, `footer`, `nav`) e atributos globais (`lang`, `title`, viewport);
* **0038:** contraste entre texto e fundo nos componentes críticos, incluindo validação de estado hover;
* **0039:** indicador visual de foco (outline/box-shadow) nos principais elementos interativos;
* **0040:** abertura do menu de idioma via ENTER, com validação das três opções disponíveis;
* **0051:** presença de atributo `alt` em todas as imagens da página.

---

## ⚡ Testes de Performance

**Exemplos:**

* **0045:** tempo total de carregamento da Home, com limite de 3000ms;
* **0060:** validação de debounce da busca — quantidade de requisições disparadas durante digitação contínua, com limite máximo aceitável.

> Assim como nas features de referência, a cobertura de performance é **pontual**, focada em tempo de carregamento e comportamento de digitação — não caracteriza uma estratégia completa de load testing.

---

## 🔄 Testes de Estabilidade

**Exemplos:**

* **0034:** persistência (ou não) do idioma selecionado após refresh, com verificação estrutural da página em ambos os cenários;
* **0046:** 200 interações consecutivas no carrossel (100 esquerda + 100 direita) com verificação de visibilidade a cada clique;
* **0047:** carregamento dinâmico de eventos durante scroll, monitorando header/body a cada ciclo;
* **0048:** execução repetida (10x) do clique em "Explorar Eventos" a partir da Home, validando navegação em todas as tentativas (anti-flaky);
* **0061:** monitoramento de console e rede durante um fluxo completo de navegação (Home → Eventos → voltar → busca → fechar busca).

---

## 🔥 Testes de Estresse (Stress Testing)

**Exemplos:**

* **0014:** 10 cliques consecutivos no botão esquerdo do carrossel;
* **0016:** 10 cliques à esquerda seguidos de 10 cliques à direita no carrossel;
* **0046:** 200 cliques consecutivos no carrossel (o cenário de maior volume da suíte).

> **Importante:** assim como nas features de referência, esses cenários caracterizam stress/robustez de componente de UI — não simulam carga concorrente de múltiplos usuários.

---

## 🛡️ Testes de Robustez

**Exemplos:**

* **0059:** pesquisa utilizando uma sequência extensa de caracteres especiais, validando que o campo e o modal de busca continuam funcionais e que nenhum erro interno é exposto;
* **0063:** comportamento completo da interface (navegação, footer, conteúdo) com todas as requisições de imagem bloqueadas.

---

## 🔎 Testes de Validação de Dados

**Exemplos:**

* **0031:** varredura de todos os links de header/footer, validando ausência de links quebrados e de respostas 404;
* **0032:** validação do `href` e do `target` do link do Instagram sem disparar navegação real;
* **0049–0051:** presença e validade de `title`, `meta description` e `alt` de imagens;
* **0056:** validação individual de `href`, visibilidade e estilo de cada link do footer.

---

## 🔐 Testes de Integridade

**Exemplos:**

* **0037:** integridade estrutural e semântica da Home (landmarks, atributos globais, elementos críticos);
* **0044:** integridade visual do header nas três resoluções testadas;
* **0056:** integridade de todos os links do footer (href válido, visível, com estilo dentro dos padrões esperados).

---

## 🚨 Testes de Monitoramento de Erros

**Exemplos:**

* **0037:** captura de erros de console durante um `page.reload()`;
* **0054:** verificação de ausência de mensagens técnicas (stack trace, exceptions, erros de banco) e presença de mensagem amigável ao acessar uma URL inexistente;
* **0061:** monitoramento dedicado de console (`error`) e de respostas de rede com status ≥ 500 durante um fluxo de navegação completo.

---

## 🎨 Testes de Integridade Visual

**Exemplos:**

* **0038:** diferenciação visual entre texto e fundo nos componentes críticos;
* **0044:** ausência de quebra visual do header entre resoluções;
* **0055:** consistência visual entre os botões CTA;
* **0056:** consistência visual dos links do footer (tamanho e peso de fonte dentro de valores permitidos).

---

## 🔄 Recuperação e Estado da Aplicação

**Exemplo:**

* **0034:** comportamento da aplicação após refresh com idioma alterado — o cenário aceita e documenta ambos os resultados possíveis (persistência ou retorno ao padrão PT-BR), tratando a ausência de persistência como comportamento atual conhecido da aplicação, não como falha automática do teste.

> **Precisão técnica:** diferente da Feature Suporte e Ajuda (onde a recuperação trata de resiliência de formulário), aqui a dimensão de recuperação está associada à **persistência de preferência de idioma** entre sessões/reloads.

---

## 📊 Observabilidade e Contrato

**Exemplo:**

* **0064:** validação da existência do `window.dataLayer`, seguida da checagem de que ao menos um evento relacionado ao clique em "Explorar Eventos" foi registrado após a navegação.

> Cobertura mais enxuta que a da Feature Suporte e Ajuda (que valida o schema completo do evento `gtm.linkClick`) — aqui a validação é de **presença do evento**, não de contrato detalhado de campos.

---

## 🔍 Testes de SEO e Metadados

**Exemplos:**

* **0049:** presença e conteúdo não vazio da tag `<title>`;
* **0050:** presença e conteúdo não vazio da `meta description`;
* **0051:** ausência de imagens sem atributo `alt` — tratado aqui como parte da cobertura de SEO/acessibilidade, listado separadamente da checagem de acessibilidade em 0036–0040.

---

## 🔒 Testes de Segurança

**Exemplos:**

* **0052–0053:** varredura do HTML renderizado em busca de padrões sensíveis (`api_key`, `secret`, `token`, `bearer`, `private_key`, `access_token`, `authorization`), com duas implementações independentes dos mesmos critérios;
* **0054:** acesso a uma URL inexistente, validando ausência de mensagens técnicas expostas (stack trace, exceptions, erros de SQL/banco) e presença de mensagem amigável ao usuário.

---

# 🔁 Regressão

A **regressão não representa um conjunto separado de cenários**.

Os 64 cenários podem ser utilizados como uma **suíte de regressão automatizada**, especialmente após:

* alterações nos CTAs, botões de navegação ou seletor de idioma da Home;
* alterações no carrossel de eventos (navegação, renderização, lazy loading);
* alterações no footer ou em seus links institucionais e de redes sociais;
* mudanças na lógica de busca (debounce, tratamento de caracteres especiais, mensagens de "nenhum resultado");
* mudanças em tags de SEO (title, meta description, alt de imagens);
* mudanças na configuração de eventos de Analytics (dataLayer);
* alterações estruturais na página que possam impactar acessibilidade ou responsividade.

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

| Dimensão | Cenários principais | Cobertura |
| --- | --- | --- |
| **E2E** | 0015, 0020–0025, 0057, 0062, 0064 | 🟢 |
| **Funcional** | 0001–0012, 0017–0030, 0040, 0057 | 🟢 |
| **Regressão** | 0001–0064 | 🟢 |
| **Navegação** | 0001–0030, 0057–0058 | 🟢 |
| **UI** | 0013–0016, 0020–0030, 0055–0056 | 🟢 |
| **Responsividade** | 0043–0044 | 🟡 |
| **Acessibilidade** | 0036–0040, 0051 | 🟢 |
| **Performance** | 0045, 0060 | 🟡 |
| **Estabilidade** | 0034, 0046–0048, 0061 | 🟢 |
| **Estresse** | 0014, 0016, 0046 | 🟢 |
| **Robustez** | 0059, 0063 | 🟡 |
| **Validação de Dados** | 0031–0032, 0049–0051, 0056 | 🟢 |
| **Integridade** | 0037, 0044, 0056 | 🟢 |
| **Compatibilidade de Navegação** | — | 🔴 |
| **Monitoramento de Erros** | 0037, 0054, 0061 | 🟢 |
| **Integridade Visual** | 0038, 0044, 0055–0056 | 🟢 |
| **Recuperação/Estado** | 0034 | 🟡 |
| **Observabilidade / Analytics** | 0064 | 🟡 |
| **SEO / Metadados** | 0049–0051 | 🟢 |
| **Segurança** | 0052–0054 | 🟢 |

**Legenda:**
🟢 Cobertura claramente demonstrada pelos cenários analisados
🟡 Cobertura presente, porém pontual e passível de expansão
🔴 Cobertura não observada nos cenários desta feature

> **Nota comparativa:** 

A ausência de cenários de **Compatibilidade de Navegação na Feature Tela Inicial** representa uma lacuna de cobertura, decorrente do escopo e das condições de teste. 

A suíte foi elaborada e executada exclusivamente em ambiente de produção, utilizando o Google Chrome. Não foram contemplados cenários específicos de histórico de navegação, como Back/Forward, retorno entre páginas e múltiplas navegações, nem testes Cross-Browser com Chrome, Edge, Firefox ou Safari.

Portanto, o GAP não caracteriza um defeito da aplicação, mas uma oportunidade de ampliação da cobertura de testes, distinguindo Compatibilidade de Navegação de Compatibilidade entre Navegadores (Cross-Browser).

---



