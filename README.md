# ParkControl — Site

Site institucional (landing page) do aplicativo **ParkControl**, um app Android para gestão
de estacionamentos de forma simples, rápida e **100% offline**.

🔗 **Site publicado:** `https://<seu-usuario>.github.io/parkcontrol-site/` *(após ativar o GitHub Pages)*

## Sobre o projeto

Este repositório contém **apenas o site** (landing page + política de privacidade) do app
ParkControl. O código-fonte do aplicativo Android fica em um repositório separado.

O site é construído com **HTML, CSS e JavaScript puros**, sem frameworks ou dependências de
build — basta abrir o `index.html` no navegador ou publicar via GitHub Pages.

## Estrutura do projeto

```
parkcontrol-site/
├── index.html           # Página principal (landing page)
├── privacy-policy.html  # Política de privacidade do app
├── style.css            # Estilos do site
├── script.js            # Interatividade (menu, FAQ, carrossel, lightbox, etc.)
└── assets/
    └── img/              # Ícone do app e capturas de tela
```

## Rodando localmente

Não há dependências nem build. Basta abrir o arquivo diretamente no navegador:

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

Ou sirva com qualquer servidor estático simples, por exemplo:

```bash
npx serve .
# ou
python -m http.server 8080
```

## Publicando no GitHub Pages

1. Faça o push deste repositório para o GitHub.
2. Vá em **Settings → Pages**.
3. Em **Source**, selecione a branch `main` e a pasta `/ (root)`.
4. Salve. O site ficará disponível em alguns instantes em:
   `https://<seu-usuario>.github.io/parkcontrol-site/`

## Tecnologias

- HTML5
- CSS3 (responsivo, sem frameworks)
- JavaScript (vanilla, sem bibliotecas externas)

## Licença e contato

Dúvidas sobre o app ou sobre a política de privacidade: `parkcontrol.sistema@gmail.com`

&copy; 2026 ParkControl. Todos os direitos reservados.

