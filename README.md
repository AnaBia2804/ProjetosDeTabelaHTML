# 📊 Tabela de Cadastro em HTML

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge">
</p>

Este é um projeto prático e inicial focado no estudo de **estruturação de dados tabulares**. O objetivo foi compreender o funcionamento das tags nativas do HTML para a criação de tabelas organizadas.

---

## 🚀 Funcionalidades

* **Visualização de Dados:** Exibição clara de informações cadastrais básicas (Nome, Idade e Profissão).
* **Organização Semântica:** Uso correto das divisões de cabeçalho (`<thead>`) e corpo da tabela (`<tbody>`).
* **Mesclagem de Células:** Aplicação de `colspan` para criar um título unificado no topo da tabela.

---

## 🛠️ Detalhes Técnicos

Abaixo estão os principais componentes e atributos utilizados no desenvolvimento da página:

| Elemento/Atributo | Função no Código | Status Atual (Boas Práticas) |
| :--- | :--- | :--- |
| `colspan="3"` | Faz a célula "Cadastro" ocupar o espaço de 3 colunas. | **Recomendado** (Uso estrutural) |
| `bgcolor` | Define as cores de fundo (vermelho, verde e prata). | *Depreciado* (Substituir por CSS) |
| `align="center"` | Centraliza os textos do título e das linhas. | *Depreciado* (Substituir por CSS) |
| `border="1"` | Cria as linhas divisórias da tabela. | *Depreciado* (Substituir por CSS) |

---

## 📂 Estrutura do Arquivo

O arquivo `index.html` foi estruturado seguindo esta lógica:

```html
├── index.html
    ├── <head>          └── <body>          ├── <h1>        ├── <hr>        └── <table>     ├── <thead> └── <tbody> ```

---

## 🔧 Como Executar o Projeto

Por ser um projeto feito em HTML puro, ele roda direto no seu navegador sem a necessidade de instalar nada:

1. Baixe o arquivo `index.html` ou clone este repositório.
2. Navegue até a pasta onde o arquivo foi salvo.
3. Dê um **duplo clique** no arquivo `index.html`.
4. A página abrirá automaticamente no seu navegador padrão.

---

## 💡 Próximas Melhorias (Roadmap)

Para evoluir este código para os padrões modernos do desenvolvimento web, os próximos passos são:

- [ ] **Migrar para CSS:** Remover todos os atributos `bgcolor`, `align` e `border` e controlá-los via folha de estilo externa (`style.css`).
- [ ] **Responsividade:** Adicionar regras de CSS para que a tabela não quebre em telas de celulares.
- [ ] **Estilização Moderna:** Substituir as cores fortes por uma paleta de cores mais suave e fontes personalizadas.

---

## 📋 Informações do Projeto

Versão Atual: 1.0
Data de Criação: 04/05/2026

---

## 👤 Autor

Desenvolvido pela Ana Beatriz (AnaBia2804).

GitHub:Usuário [AnaBia2804]
