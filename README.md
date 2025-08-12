# Traveler - Sua Agência de Viagem com Inteligência Artificial

O repositório da **Traveler** representa uma agência de viagens fictícia desenvolvida para oferecer uma experiência de usuário intuitiva com a integração de um **Assistente de Recomendação powered by IA (Gemini API)**.

## Funcionalidades Principais

*   **Página Inicial (Home):** Uma introdução aos serviços da agência, com destaque para os destinos mais populares.
*   **Lista de Viagens:** Detalhes sobre destinos turísticos, incluindo descrições, preços e atividades.
*   **Seguros:** Informações sobre os planos de seguro de viagem oferecidos.
*   **Orçamento:** Um formulário interativo para solicitar orçamentos personalizados de viagens e seguros.
*   **Contato:** Seção com informações de contato e um formulário para dúvidas e mensagens.
*   **Termos e Condições:** Documento com as políticas de uso do serviço.
*   **Design Responsivo:** O layout se adapta perfeitamente a diferentes tamanhos de tela (desktops, tablets e smartphones).
*   **Animações Suaves:** Utilização de `simple-anime.js` para adicionar transições e animações elegantes aos elementos da página.
*   **Assistente de Recomendação (IA):** Este assistente permite que o usuário faça perguntas sobre os destinos listados (Praia do Madeiro, Praia de Antunes, Porto de Galinhas) e receba recomendações personalizadas de pontos turísticos, restaurantes e atividades, utilizando a API Gemini (Google AI Studio).

## 🚀 Tecnologias Utilizadas

*   **HTML5:** Estrutura semântica e acessível.
*   **CSS3 (com BEM e variáveis CSS):** Estilização modular, responsiva e de fácil manutenção.
*   **JavaScript (ES6+):** Lógica interativa, manipulação do DOM e integração com APIs.
*   **Gemini API (Google AI Studio):** Para o assistente de recomendação inteligente.
*   **Showdown.js:** Biblioteca para converter Markdown em HTML, utilizada para formatar as respostas do assistente de IA.
*   **Simple Anime JS:** Pequena biblioteca para gerenciar animações baseadas em `data-attributes`.

## ⚙️ Como Rodar o Projeto Localmente

1.  **Configuração da API Key (para o Assistente de Recomendação):**
    Para utilizar o Assistente de Recomendação, você precisará de uma API Key do Google AI Studio (Gemini API).
    *   Crie uma conta no [Google AI Studio](https://aistudio.google.com/).
    *   Obtenha uma API Key e insira-a no campo "Informe a sua API KEY do Gemini" na seção "Assistente de Recomendação" na página de "Viagens".

## 🛣️ Estrutura do Projeto

```
traveler/
├── css/
│   ├── chat/
│   │   └── style.css          # Estilos do assistente de recomendação
│   ├── contato/
│   │   ├── contato.css        # Estilos da página de contato
│   │   └── lojas.css          # Estilos das lojas físicas
│   ├── global/
│   │   ├── footer.css         # Estilos do rodapé
│   │   ├── global.css         # Estilos globais (reset, tipografia base)
│   │   └── header.css         # Estilos do cabeçalho
│   ├── home/
│   │   ├── depoimento.css     # Estilos da seção de depoimento
│   │   ├── expertise.css      # Estilos da seção de expertise
│   │   ├── introducao.css     # Estilos da seção de introdução
│   │   └── parceiros.css      # Estilos da seção de parceiros
│   ├── orcamento/
│   │   └── orcamento.css      # Estilos da página de orçamento
│   ├── seguros/
│   │   ├── perguntas.css      # Estilos das perguntas frequentes
│   │   ├── seguros.css        # Estilos da página de seguros
│   │   └── vantagens.css     # Estilos das vantagens do seguro
│   ├── style.css              # Importa todos os outros arquivos CSS
│   ├── termos/
│   │   └── termos.css         # Estilos da página de termos e condições
│   ├── utilidades/
│   │   ├── animacao.css       # Estilos para animações
│   │   ├── componentes.css    # Estilos de componentes reutilizáveis (botões, etc.)
│   │   ├── cores.css          # Definição de variáveis de cores
│   │   └── tipografia.css     # Definição de classes de tipografia
│   ├── viagem/
│   │   ├── seguro.css         # Estilos da seção de seguro na página de viagem
│   │   └── viagem.css         # Estilos das páginas de detalhes de cada viagem
│   └── viagens/
│       ├── viagens-lista.css  # Estilos da lista de viagens na home
│       └── viagens.css        # Estilos da página principal de viagens
├── img/
│   ├── dec/                   # Imagens decorativas (SVGs)
│   ├── fotos/                 # Imagens de fotos de destinos, etc.
│   ├── icones/                # Ícones SVG
│   ├── parceiros/             # Logos dos parceiros (SVGs)
│   ├── redes/                 # Ícones de redes sociais (SVGs)
│   ├── viagens/               # Imagens para a lista de viagens
│   └── traveler.svg           # Logo principal
├── js/
│   ├── plugins/
│   │   └── simple-anime.js    # Plugin de animação
│   └── script.js              # Lógica JavaScript principal
├── contato.html
├── index.html
├── orcamento.html
├── seguros.html
├── termos.html
├── viagens.html
└── viagens/
    ├── antunes.html
    ├── madeiro.html
    └── porto.html
```

## ✒️ Autor

**Luiz Augusto Oliveira de Farias**
[LinkedIn](https://www.linkedin.com/in/luiz-augusto-oliveira/)
