<div align="center">
  <h1>🙃 Stranger Things: Theme Switcher Experience</h1>
  
  <p>
    Landing Page imersiva que explora o conceito de <b>Dual Theming</b> (Light/Dark Mode) 
    e manipulação de áudio via JavaScript, inspirada na série Stranger Things.
  </p>

  <img src="https://img.shields.io/github/deployments/EderJuniorS/Landing-Page-no-Mundo-Invertido/github-pages?label=Deploy&style=flat-square&logo=github">
  <img src="https://img.shields.io/github/last-commit/EderJuniorS/Landing-Page-no-Mundo-Invertido?style=flat-square&color=red">
  
  <br><br>

  <a href="https://ederjuniors.github.io/Landing-Page-no-Mundo-Invertido/">
    <img src="https://img.shields.io/badge/🙃_Inverter_Mundo-Live_Experience-critical?style=for-the-badge" alt="Ver Demo">
  </a>
</div>

<br>

<div align="center">
  <table>
    <tr>
      <td align="center"><b>🌞 Mundo Normal</b></td>
      <td align="center"><b>🌑 Mundo Invertido</b></td>
    </tr>
    <tr>
      <td><img src="assets/images/projeto_pronto/mundo-normal.png" width="400px"></td>
      <td><img src="assets/images/projeto_pronto/mundo-invertido.png" width="400px"></td>
    </tr>
  </table>
</div>

<br>

## 📋 Sobre o Projeto

Este projeto foi desenvolvido durante o bootcamp **Ri Happy - Front-end do Zero (DIO)**. O desafio técnico foi transcender uma landing page estática, implementando interatividade completa que altera não apenas o CSS, mas a atmosfera da aplicação.

O foco da engenharia foi criar um mecanismo robusto de troca de temas que sincroniza **variáveis CSS**, **imagens no DOM** e **trilhas de áudio** simultaneamente ao clique de um botão.

## 🚀 Engenharia & Funcionalidades

- **Dynamic Theme Switching:** Lógica JavaScript que alterna classes no elemento `body`, disparando mudanças globais de estilo (cores, fontes, backgrounds) instantaneamente.
- **Audio State Management:** Controle da API de Áudio do HTML5. O script verifica qual tema está ativo para pausar a trilha atual e iniciar a trilha correspondente (Mundo Real vs. Invertido) no ponto correto.
- **DOM Manipulation:** Troca dinâmica de assets de imagem (Logos e Personagens) baseada no estado da aplicação.
- **Responsive Layout:** Uso de Flexbox e Media Queries para garantir a imersão tanto em Desktop quanto Mobile.

## 🛠️ Tecnologias Utilizadas

- ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) **Estrutura Semântica:** Uso correto de tags de seção, áudio e inputs.
- ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3) **Estilização:**
    - **CSS Variables:** (Conceito implícito) Alteração de propriedades visuais em massa.
    - **Transitions:** Suavização da troca de tema para não ser abrupta.
    - **Custom Fonts:** Importação de tipografia temática.
- ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) **Core Logic:**
    - `classList.toggle()`: Para gerenciamento de estado visual.
    - `Audio()` Object: Para controle programático de mídia.
    - `Event Listeners`: Captura de interação do usuário.

## 📂 Estrutura do Projeto

```bash
/
├── assets/
│   ├── audio/           # Trilhas sonoras (musica.mp3)
│   ├── images/          # Assets gráficos (SVG/PNG) e Logos
│   └── video/           # Backgrounds dinâmicos (se houver)
├── css/
│   └── style.css        # Folha de estilos global e temas
├── js/
│   └── scripts.js       # Lógica de troca de mundo
├── index.html           # View Principal
└── README.md            # Documentação
```

## 🏁 Como Executar Localmente
Clone o repositório:

```bash
git clone https://github.com/EderJuniorS/Landing-Page-no-Mundo-Invertido.git
```

Abra o arquivo index.html no seu navegador.

Clique no botão "Inverter Mundos" e certifique-se de que o som está ativado.

<div align="center"> Desenvolvido por <a href="https://www.linkedin.com/in/ederjuniormatossilva">Éder Junior</a> durante o Bootcamp da DIO. </div>
