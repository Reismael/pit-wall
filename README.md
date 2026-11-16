
# 🏎️ PIT WALL | GP de São Paulo 2026

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![Responsivo](https://img.shields.io/badge/Design-Responsivo-E10600?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

## 📌 Sobre o Projeto

O **Pit Wall** é um projeto desenvolvido como atividade prática da disciplina de **Linguagem de Marcação (LIMA)**, do Curso Técnico em Desenvolvimento de Sistemas do SENAI.

O desafio consiste em reproduzir uma página inspirada no **Grande Prêmio de São Paulo de Fórmula 1**, realizado no Autódromo de Interlagos, utilizando exclusivamente HTML5 e CSS3.

O objetivo é aplicar os conhecimentos adquiridos em sala de aula, desenvolvendo uma interface moderna, organizada, responsiva e visualmente semelhante ao modelo fornecido pelos professores.

---

## 🎯 Objetivos da Atividade

- Desenvolver uma página web utilizando HTML5 e CSS3.
- Aplicar HTML semântico na estrutura do projeto.
- Utilizar Flexbox e CSS Grid na organização dos elementos.
- Trabalhar com variáveis CSS utilizando `:root`.
- Criar um layout responsivo para computadores e celulares.
- Utilizar imagens de fundo e gradientes.
- Construir cards, tabelas e formulários.
- Aplicar efeitos visuais com `hover` e `transition`.
- Reproduzir um layout a partir de uma referência visual.

---

## 🖥️ Funcionalidades e Seções

### 🏁 1. Página Principal (Hero)

A seção principal apresenta:

- Título do GP de São Paulo.
- Fotografia de um carro de Fórmula 1.
- Faixa vermelha diagonal.
- Informações do circuito de Interlagos.
- Botões de navegação.
- Efeito de zebra vermelha e branca inspirado nas pistas de corrida.

### 🏎️ 2. Grid de Pilotos

Apresentação de quatro pilotos em cards personalizados:

| Número | Piloto | Equipe |
|:---:|---|---|
| 16 | Charles Leclerc | Ferrari |
| 81 | Oscar Piastri | McLaren |
| 63 | George Russell | Mercedes |
| 5 | Gabriel Bortoleto | Audi |

Cada card apresenta a cor correspondente à equipe, o número do carro e um efeito de elevação ao passar o mouse.

### 🏆 3. Classificação

Tabela ilustrativa com informações sobre os pilotos:

- Posição no campeonato.
- Nome do piloto.
- Equipe.
- Número de vitórias.
- Diferença de pontos.
- Pontuação total.

A seção também apresenta campos visuais para busca de pilotos e seleção de equipes.

### 🎟️ 4. Ingressos

Área dedicada à apresentação dos setores e valores ilustrativos dos ingressos.

O formulário contém:

- Nome completo.
- E-mail.
- Seleção do setor.
- Data.
- Quantidade de ingressos.
- Perfil de rede social (opcional).
- Envio de fotografia.
- Mensagem para o piloto.

**Observação:** o formulário e os filtros são demonstrativos. Como a atividade utiliza somente HTML e CSS, não existe integração com banco de dados ou sistema real de reservas.

---

## 🛠️ Tecnologias Utilizadas

### HTML5

Utilizado para estruturar o conteúdo da página, incluindo:

- `header` — cabeçalho.
- `nav` — navegação.
- `main` — conteúdo principal.
- `section` — divisão de seções.
- `article` — cards dos pilotos.
- `table`, `thead` e `tbody` — classificação.
- `form`, `input` e `select` — formulário.
- `footer` — rodapé.

### CSS3

Utilizado para a estilização e responsividade, com:

- Variáveis CSS (`:root`).
- Flexbox (`display: flex`).
- CSS Grid (`display: grid`).
- Grid responsivo com `auto-fit` e `minmax()`.
- Media Queries (`@media`).
- Gradientes (`linear-gradient`).
- Zebra com `repeating-linear-gradient`.
- Recortes diagonais com `clip-path`.
- Pseudoelementos `::before` e `::after`.
- Efeitos `hover` e `transition`.

### Google Fonts

Foi utilizada a fonte **Titillium Web**, escolhida para reforçar a identidade visual esportiva da página.

---

## 📂 Estrutura do Projeto

```text
pit-wall/
│
├── index.html
│   └── Estrutura HTML da página
│
├── styles.css
│   └── Estilização e responsividade
│
└── img/
    └── piloto.jpg
        └── Imagem utilizada no Hero
```

---

## 📱 Responsividade

O projeto foi desenvolvido para se adaptar a diferentes tamanhos de tela.

**Desktop:**
- Menu de navegação completo.
- Hero com fotografia e faixa diagonal.
- Cards organizados em grid.
- Formulário dividido em duas colunas.

**Mobile:**
- Cabeçalho simplificado.
- Título adaptado à largura da tela.
- Cards distribuídos em duas colunas.
- Filtros organizados verticalmente.
- Tabela com rolagem horizontal.
- Formulário em coluna única.

A adaptação é realizada por meio de Media Queries CSS.

---

## 🚀 Como Executar

**1.** Baixe ou clone este repositório.

**2.** Abra a pasta do projeto no Visual Studio Code.

**3.** Verifique se a imagem `piloto.jpg` está dentro da pasta `img`.

**4.** Abra o arquivo `index.html` no navegador.

**5.** Para testar a responsividade, pressione `F12` e selecione o modo de visualização para dispositivos móveis.

Não é necessário instalar bibliotecas, frameworks ou dependências.

---

## 🎨 Identidade Visual

O projeto utiliza uma paleta inspirada no automobilismo:

| Cor | Código hexadecimal | Aplicação |
|---|---|---|
| Preto | `#0B0B0F` | Fundo principal |
| Vermelho | `#E10600` | Botões e destaques |
| Branco | `#F5F5F7` | Títulos e textos |
| Cinza | `#9696A5` | Textos secundários |
| Grafite | `#16161D` | Cards e formulários |

As equipes possuem cores próprias para facilitar a identificação visual dos pilotos.

---

## 📚 Aprendizados

Durante o desenvolvimento do Pit Wall, foram praticados conceitos importantes de desenvolvimento front-end, incluindo:

- Organização de código HTML e CSS.
- Separação entre estrutura e apresentação.
- Construção de layouts com Flexbox e Grid.
- Utilização de variáveis para padronização visual.
- Estilização de tabelas e formulários.
- Responsividade com Media Queries.
- Manipulação de imagens de fundo.
- Desenvolvimento de interfaces a partir de referências visuais.

---

## 🏫 Informações Acadêmicas

**Instituição:** SENAI A. Jacob Lafer — Santo André

**Curso:** Técnico em Desenvolvimento de Sistemas

**Disciplina:** Linguagem de Marcação (LIMA)

**Turma:** 1IE-DS

**Professores:** André Denani e Raul Lopes

**Atividade:** Desafio Pit Wall — GP de São Paulo

**Ano:** 2026

---

## 👨‍💻 Desenvolvedor

**Ismael Pereira dos Santos Reis**

Estudante do Curso Técnico em Desenvolvimento de Sistemas — SENAI Santo André.

---

## 📷 Créditos

Fotografia utilizada no projeto: **Jonathan Borba / Pexels**.

Os dados de pilotos, classificação, ingressos e valores apresentados na interface são ilustrativos e utilizados exclusivamente para fins educacionais.

---

## 📄 Finalidade

Este projeto foi desenvolvido exclusivamente para fins educacionais, como parte das atividades práticas da disciplina de Linguagem de Marcação.

**PIT WALL — GP DE SÃO PAULO 2026** 🏁
