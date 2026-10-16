# Seletor de personagens GTA

Uma página web simples para apresentar e selecionar personagens do universo GTA. Ao escolher um personagem, a página atualiza o nome, a imagem e a cor do nome.

## Personagens disponíveis

- **Lucia** — rosa (`#ff3cac`)
- **Jason** — azul (`#00b2c9`)
- **CJ** — verde (`#7ed37e`)

Os textos da página permanecem visíveis durante a seleção.

## Como executar

Não é necessário instalar dependências nem compilar o projeto. Abra `index.html` em um navegador. Para desenvolvimento, também é possível servir a pasta com qualquer servidor HTTP local.

## Estrutura do projeto

```text
.
├── index.html       # Estrutura da página e opções de personagens
├── script.js        # Atualização do personagem selecionado
├── styles.css       # Estilos e layout
└── img/
    ├── background.jpg
    ├── background1.jpg
    ├── background2.jpg
    ├── cj.png
    ├── jason.png
    └── lucia.png
```

O fundo atualmente usado pela página é `img/background1.jpg`. As fontes Bangers e Inter são carregadas do Google Fonts quando há conexão com a internet.
