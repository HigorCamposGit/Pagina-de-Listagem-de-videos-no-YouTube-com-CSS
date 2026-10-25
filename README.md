# Pagina-de-Listagem-de-videos-no-YouTube-com-CSS.

📺 Este projeto de Clone do YouTube - Projeto de CSS para o curso **[Formação CSS Web Developer](https://www.dio.me)** na plataforma **[DIO](https://www.dio.me)**.
Fiz uma versão versão desktop em tema escuro (eu prefiro tema escuro), desenvolvido como parte de um curso prático de desenvolvimento web para fixar conceitos fundamentais de estruturação `HTML5` e estilização avançada com `CSS3`, com foco especial em **Flexbox** e organização de layouts.

---

## 🚀 Tecnologias Utilizadas.

* **HTML5**: Estruturação semântica da página. Cabeçalho, menu lateral, área principal, grade de vídeos.
* **CSS3**: Estilização visual, escolhi cores do tema escuro oficial do YouTube (`#0f0f0f`), `tipografia` e efeitos de `hover`.
* **Flexbox**: Utilizado para o alinhamento de itens, distribuição de espaços no cabeçalho, barra de chips, categorias e nos cards de vídeo.
* **Google Material Icons**: Ícones oficiais utilizados na interface.

---

## 📂 Estrutura de Tags HTML5 Utilizadas.

Para garantir que o fique limpo, acessível e semântico, usadas tags do HTML5:

* `<header>`: Cabeçalho superior fixo contendo o menu, logo do YouTube e botões de busca, microfone e login.
* `<aside>`: Menu lateral de navegação, sidebar com as opções de início, shorts, inscrições e explorar.
* `<main>`: Contêiner principal que envolve o conteúdo dinâmico da página.
* `<section>`: Utilizada para agrupar blocos lógicos, como a barra de categorias `chips` e a grade de vídeos.
* `<article>`: Apresenta os card de vídeos individuais na grade.
* `<div>`: Utilizada como elemento genérico de apoio para estruturar e organizar os blocos internos de layout como avatares e detalhes dos vídeos.

---

## 🎨 Uso do Flexbox no Projeto.

O **Flexbox** foi a ferramenta principal de alinhamento e distribuição de layout neste projeto. Abaixo os pontos onde ele foi aplicado:

1. **Cabeçalho (`.header` e sub-blocos)**:
   * Organizado com `display: flex`, `align-items: center` e `justify-content: space-between` para separar  a logo à esquerda, a barra de busca centralizada e os botões de ação à direita.
2. **Barra de Chips / Categorias (`.chips-bar`)**:
   * Utiliza `display: flex` com rolagem horizontal (`overflow-x: auto`) para permitir que os botões de filtro se comportem de forma fluida em diferentes tamanhos de tela.
3. **Cards de Vídeo e Metadados (`.video-info`)**:
   * O bloco de informações abaixo de cada miniatura usa Flexbox para "alinhar o avatar circular do canal à esquerda", o título e as estatísticas do vídeo ocupando o espaço central, o botão de opções mais à direita.
4. **Alinhamentos Gerais**:
   * Uso de propriedades como `gap` para espaçamentos consistentes, `align-items` para centralização vertical e `flex-direction` para alternar colunas e linhas onde é necessário.

---

## 📷 Funcionalidades Visuais.

* **Tema Escuro Realista**: Cores baseadas na identidade visual atual do YouTube (`#0f0f0f` para o fundo e `#272727` para elementos interativos).
* **Grid de Vídeos Responsivo**: Organização visual limpa imitando a grade de recomendações da plataforma.
* **Badges e Detalhes**: Inclusão de marcadores de duração de vídeo e resoluções (como 4K e Ultra HD) nas miniaturas.

---

## ⚙️ Como Executar o Projeto.

1. Baixe ou clone este repositório para o seu computador.
2. Certifique-se de que os arquivos `index.html` e `style.css` estão na mesma pasta.
3. Dê um duplo clique no arquivo `index.html` para abri-lo em qualquer navegador web moderno (Firefox,Google Chrome, Edge, etc.).
---
## 🤝 Conecte-se comigo

Meu perfil do GitHub é: [HigorCamposGit](https://github.com/HigorCamposGit)
