# 📊 Dashboard de Vendas - Xbox Game Pass (2024)

## 🔍 Seja Bem-vindo

Olá! Tudo bem?

Sem dúvida, existem ferramentas mais específicas — talvez até mais apropriadas — para a criação de dashboards.
Mas a satisfação que sinto ao construir soluções que respondem a perguntas de negócio **usando Excel** é indescritível.

Bom, vamos ao que interessa.

---

## 🎯 Objetivo do Projeto

O objetivo deste projeto é criar dashboards no Excel que respondam a perguntas estratégicas e exibam **métricas relacionadas às vendas de assinaturas** do serviço Xbox Game Pass e seus serviços empilhados (EA Play Season Pass e Minecraft Season Pass), com dados simulados para o ano de 2024.

> 📝 *Obs: Empilhamento de serviço* refere-se ao acúmulo de assinaturas complementares após a contratação do serviço principal.

---

## 📚 Contexto do Projeto

Este projeto foi desenvolvido para treinar técnicas de **organização, cálculo e visualização de dados** no Excel, reunindo tudo em **um único arquivo de trabalho com múltiplas dashboards** voltadas para diferentes setores (diretoria e equipe de vendas).

A proposta é que **um único ambiente no Excel** seja capaz de alimentar, calcular e apresentar visualizações diferentes, adaptadas às necessidades de **cada tipo de usuário**.

> Para estruturar o projeto, utilizei o método **ABCDE**, ensinado por **Felipe Aguir**, instrutor da **plataforma DIO**, no curso “Excel com IA” oferecido pelo **Banco Santander em parceria com a DIO**.

### 📁 Arquivos disponíveis

Você encontrará **duas versões** do mesmo projeto:

* **`[DASHBOARD_XBOX_FECHADO.xlsx](https://docs.google.com/spreadsheets/d/1ebXiV9OrIs9fR0dXmdAtKIrpR7oKffrb/edit?usp=sharing&ouid=116608752096568378233&rtpof=true&sd=true)**
  Versão simulada para uso final, com planilhas protegidas e interface controlada. É como se você estivesse acessando o arquivo sendo um **diretor** ou **membro da equipe de vendas**.

* **`* `[DASHBOARD_XBOX_ABERTO_EDITAVEL.xlsx](https://docs.google.com/spreadsheets/d/14Nau1Z4iVtH7-Q59b8quqp972PPAjCls/edit?usp=sharing&ouid=116608752096568378233&rtpof=true&sd=true)**
  Versão aberta para estudo, com todas as planilhas visíveis e desprotegidas. Ideal para aprendizado e exploração dos bastidores.

---

## 🧩 Estrutura das Planilhas

O arquivo contém **8 planilhas**, com a seguinte organização:

### `1 - ACESSÓRIOS`

Contém **cores, logos, imagens** e elementos visuais padronizados para manter a identidade visual das dashboards.

### `2 - BASE`

Base de dados fictícia com informações de **vendas de assinaturas do Xbox Game Pass e serviços empilhados** em 2024.

### `3 - CÁLCULOS`

Concentra todas as **fórmulas, tabelas dinâmicas, campos calculados** e demais elementos que alimentam as dashboards.

### `4 - DASH HOME`

Tela inicial onde o usuário:

* Escolhe sua **área/setor** (Diretoria, Equipe de Vendas, Analistas de Dados).
* Digita a **senha de acesso** correspondente.
* Após a validação, um **botão de acesso** é habilitado para redirecionamento à dashboard específica.

#### ✅ Áreas disponíveis:

* `DIREÇÃO`
* `EQUIPE DE VENDAS`
* `ANALISTAS DE DADOS` (em desenvolvimento)

#### 🔐 Senhas de acesso:

* `DIR01` → Diretoria
* `VEND_SUPER` → Equipe de Vendas

### `5 - DASH DIREÇÃO 1`

Dashboard com visão estratégica e indicadores principais para a **Diretoria**.

### `6 - DASH DIREÇÃO 2`

Dashboard complementar com informações mais detalhadas, acessada por botão/link a partir da anterior.

### `7 - DASH VENDAS`

Dashboard voltada à **Equipe de Vendas**, com foco em performance operacional.

> 🔒 As dashboards são isoladas: quem é da equipe de vendas não acessa os dados da diretoria, e vice-versa.

### `8 - EXTRA`

Contém **elementos auxiliares**, como tabelas, listas e recursos usados para validações de dados e funcionalidades extras.

---

## 🧠 Metodologia Utilizada

* Aplicação do **método ABCDE** para construção lógica.
* Separação clara em **camadas**: dados → cálculos → visualização.
* Uso de:

  * Validação de dados
  * Campos nomeados
  * Tabelas dinâmicas
  * Segmentações
  * Botões com links
  * Gráficos
  * Formatação condicional
  * Design visual padronizado

---

## 🚀 Como Usar

1. Baixe o arquivo desejado:

   * *`[DASHBOARD_XBOX_FECHADO.xlsx](https://docs.google.com/spreadsheets/d/1ebXiV9OrIs9fR0dXmdAtKIrpR7oKffrb/edit?usp=sharing&ouid=116608752096568378233&rtpof=true&sd=true)** para simulação de uso final.
   * `[DASHBOARD_XBOX_ABERTO_EDITAVEL.xlsx](https://docs.google.com/spreadsheets/d/14Nau1Z4iVtH7-Q59b8quqp972PPAjCls/edit?usp=sharing&ouid=116608752096568378233&rtpof=true&sd=true) para estudos e personalizações.
2. Abra o arquivo no Excel (recomendado: versão 2016 ou superior).
3. Acesse a planilha **DASH HOME**.
4. Selecione sua **área de atuação**.
5. Digite a **senha correspondente**.
6. Clique no botão habilitado para acessar sua dashboard personalizada.

7. Arquivo também foi disponibilizado via link através do Google Driver. Ao acessar possívelmente o arquivo abrirá no Google Sheets, mas sugiro que baixe o arquivo e utilize O Excel.

---

## 🔧 Melhorias Futuras

Pretendo futuramente atualizar meu projeto com:

* Navegação mais intuitiva.
* Gráficos com filtros e segmentações mais inteligentes.
* Interface ainda mais profissional.
* Adaptação para contextos reais em ambientes corporativos.

---

## 🤝 Contribua!

Fique à vontade para **baixar, estudar, personalizar ou melhorar** esse projeto.

Se quiser trocar ideias, me envie uma mensagem pelo LinkedIn:
🔗 [Fernando M. do Valle](https://www.linkedin.com/in/fernando-m-do-valle-b653a7349/)

---

📌 *Este projeto é simples, mas feito com carinho por alguém que acredita que o Excel pode ser uma ferramenta poderosa na tomada de decisão.*
