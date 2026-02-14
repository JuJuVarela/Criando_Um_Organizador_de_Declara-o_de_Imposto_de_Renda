# 📊 Formulário de Envio de Dados para Imposto de Renda no Excel

Este projeto foi desenvolvido como parte de um desafio da **DIO (Digital Innovation One)**. O objetivo é criar uma ferramenta robusta e organizada no Excel para centralizar todas as informações necessárias para a declaração anual de IRPF, facilitando a vida do contribuinte e evitando a correria de última hora.

---

## 🚀 Funcionalidades do Projeto

* **Menu de Navegação:** Botões interativos para transitar entre as abas sem usar as guias inferiores.
* **Validação de Dados:** Menus suspensos para categorias, garantindo que os dados sigam um padrão.
* **Interface Amigável:** Design limpo, sem linhas de grade.

---

## 🛠️ Passo a Passo da Execução

### 1. Planejamento da Estrutura
O arquivo foi dividido em 4 pilares principais:
* **Home:** Resumo visual e botões de acesso.
* **Rendimentos:** Registro de salários, pró-labore e Freelance.
* **Bens e Direitos:** Controle de saldo bancário.

### 2. Configuração do Layout
Para transformar a planilha em uma "ferramenta/app":
1.  Fui em **Exibir** e desmarquei as **Linhas de Grade**.
2.  Criei um cabeçalho fixo com o nome do projeto.
3.  Utilizei formas (Retângulos arredondados) para criar os botões de menu.

### 3. Implementação da Validação de Dados
Para evitar erros de digitação:
1.  Selecionei as células de categoria.
2.  Acesse guia **Dados** > **Validação de Dados**.
3.  Configurei como **Lista** e inseri as opções.

### 4. Criação de Links e Navegação
1.  Clique com o botão direito nos botões criados > **Link**.
2.  Selecionei "Colocar neste documento" e escolhi a aba correspondente.
3.  Adicionei um link externo para o meu Linkedin.

### 5. Fórmulas Utilizadas
Para consolidar os valores, utilizei a função `SOMA`, permitindo somar apenas os valores de rendimentos específicos.
> ` =SOMA(D11;D16;D21) `

---

## 🧠 Aprendizados Adquiridos

Durante o desafio, pude aprimorar:
* **Organização de Dados:** A importância de padronizar entradas para gerar relatórios precisos.
* **UX no Excel:** Como tornar uma ferramenta técnica acessível para usuários leigos através de design e navegação.
* **Documentação Técnica:** A prática de registrar o "como" e o "porquê" das soluções adotadas.

---

## 📂 Como utilizar
1. Baixe o arquivo `.xlsx` deste repositório.
2. Abra no Microsoft Excel (recomendado 2016 ou superior).
3. Utilize o Menu Inicial para navegar entre as categorias e preencher seus dados.

---
Desenvolvido por [JulianaVarela] | [(https://www.linkedin.com/in/juliana-vieira-varela-4107613a)]
