
## Restaurante Quioto-Gohan

```md
# Landing Page de Restaurante

Este repositório contém o código-fonte de uma landing page para um restaurante, construída utilizando HTML, CSS, Bootstrap e JavaScript com jQuery.

## Visão Geral

A landing page tem como objetivo apresentar o restaurante, mostrando seções como "Sobre", "Eventos", "Contato" e outros detalhes relevantes, junto com a utilização de plugins para máscaras de formulários e validação.

## Tecnologias Utilizadas

- **HTML**: Estrutura do conteúdo.
- **CSS**: Estilos customizados.
- **Bootstrap**: Estilos e componentes responsivos.
- **JavaScript**: Funcionalidade da página.
- **jQuery**: Biblioteca JavaScript utilizada para simplificar a manipulação do DOM.
- **Plugins jQuery**:
  - `jquery.mask.min.js`: Utilizado para mascarar campos de formulário.
  - `jquery.validate.min.js`: Utilizado para validação de formulários.

## Estrutura de Pastas

```bash
.
├── Plugins
│   ├── jquery.mask.min.js
│   ├── jquery.validate.min.js
│   └── messages_pt_BR.js
├── img
│   ├── About
│   ├── Carousel
│   ├── Contacts
│   ├── Events
│   ├── Header-icons
│   ├── Menu
│   └── title icons
├── lib
│   ├── bootstrap.bundle.min.js
│   ├── bootstrap.min.css
├── Main.js
├── index.css
└── index.html
```

- **Plugins**: Contém os plugins JavaScript utilizados no projeto.
- **img**: Contém as imagens utilizadas na página.
- **lib**: Contém os arquivos de Bootstrap.
- **Main.js**: Script principal da aplicação.
- **index.css**: Estilos customizados da página.
- **index.html**: Estrutura HTML da página.

## Funcionalidades

1. **Mascaramento de Campos**: O plugin `jquery.mask.min.js` foi utilizado para aplicar máscaras a campos de entrada de dados, como telefone e CPF.
2. **Validação de Formulários**: O plugin `jquery.validate.min.js` é utilizado para validar os formulários, garantindo que os campos obrigatórios sejam preenchidos corretamente.
3. **Responsividade**: Com o uso de Bootstrap, a página se adapta a diferentes tamanhos de tela.

## Como Executar

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```
2. Abra o arquivo `index.html` em seu navegador.
