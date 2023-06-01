# Plano de Teste Serverest Back-End

**Serverest**

*Versão 2.26.11*


## 1 - Introdução

Este documento descreve os requisitos a testar, os  tipos de testes definidos para cada iteração, os recursos de software a serem empregados e o cronograma dos testes ao longo do projeto. As seções referentes aos requisitos, recursos e cronograma servem para permitir ao gerente do projeto acompanhar a evolução dos testes.

Com esse documento, você deve:
- Identificar informações de projeto existentes e os componentes de software que devem ser testados.
- Listar os Requisitos a testar.
- Recomendar e descrever as estratégias de teste a serem empregadas.
- Identificar os recursos necessários e prover uma estimativa dos esforços de teste.
- Listar os elementos resultantes do projeto de testes.

Também é possível apresentar aqui o programa que será testado.

## 2 - Requisitos a Testar

Esta seção deve conter os casos de uso e requisitos não funcionais identificados como objetos dos testes ao longo do desenvolvimento do projeto.
Como, em geral, os requisitos a testar são obtidos diretamente dos requisitos do sistema, esta seção é concebida como opcional. Assim sendo, sempre que novos requisitos a testar, que não constem como requisitos do sistema, forem identificados ou, simplesmente, por questões de organização e clareza, esta seção deve ser preenchida.
Dependendo das informações disponíveis, essa seção pode começar a ser preenchida já nas primeiras iterações do ciclo de vida a partir do documento de requisitos.

Caso seja necessário, liste aqui os requisitos a testar subdivididos em casos de uso e requisitos não-funcionais.

### Casos de uso:

Identificador do caso de uso | Nome do caso de uso
-----------------------------|---------------------
 CT01                        |Listagem de usuários;
 CT02                        |Cadastro de usuários;
 CT03                        |Login;
 CT04                        |Buscar usuário por ID;
 CT05                        |Editar usuário;
 CT06                        |Deletar usuário;
 CT07                        |Cadastrar produto;
 CT08                        |Listar produtos;
 CT09                        |Buscar produto por ID;
 CT10                        |Editar produto;
 CT11                        |Deletar produto;
 CT12                        |Cadastrar carrinho;
 CT13                        |Listar carrinhos;
 CT14                        |Listar carrinhos;
 CT15                        |Listar carrinhos;
 CT16                        |Deletar cancelando;


### 3 - Ferramenta de teste

| Ferramenta           | Descrição                                               |
|----------------------|---------------------------------------------------------|
| Google Docs          | Para criação do documento                               |
| Microsoft Edge       | Pré-realização dos testes manuais                       |
| Microsoft Teams      | Para as comunicações                                    |
| E-mail 365           | Para as formalizações por e-mail                        |
| Visual Studio Code   | IDE para a criação do código da automação de testes     |
| Cypress              | Framework para a automação do back-end                  |
| JavaScript           | Linguagem de programação para realizar a automação de testes |
| Postman              | Ferramenta para interagir com as rotas de API da aplicação |
| GitHub               | Para versionamento do código da automação               |
| Jira Software        | Para gerenciamento dos testes                           |
| Canva                | Para criação do mapa mental                             |


### 4 - Cronograma
| Dia da Semana | Atividade 1                     | Atividade 2                     |
|---------------|-------------------------------|-------------------------------|
| Segunda-feira | Finalizar planejamento de testes       |                               |
| Terça-feira   | Finalizar planejamento de testes       | Iniciar testes e relatório manual       |
| Quarta-feira  | Iniciar testes e relatório manual       | Iniciar desenvolvimento da automação       |
| Quinta-feira  | Iniciar desenvolvimento da automação       | Começar a gerar relatórios       |
| Sexta-feira   | Começar a gerar relatórios       |     Finalizar os relatorios                          |

### 5 - Como rodar e gerar relatórios
Para rodar o cypress e gerar os relatórios, você deve:
 - clonar o repositório
    ```
    git clone https://github.com/Pedrofd2k/Cy-Serverest.git
    ```
 - Instalar as dependências
    ```
    npm install
    ```
 - Para rodar a interface visual
    ```
    npm run cy
    ```
 - Para rodar os testes
    ```
    npm run cy:run
    ```
 - Para gerar relatórios json
    ```
    npm run cy:json
    ```
 - Para gerar relatório html
    ```
    npm run cy:html
    ```
