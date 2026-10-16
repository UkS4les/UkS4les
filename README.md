<p align="center">
  <img src="header.svg" width="100%" alt="Lucas Sales Vicente — Analista de Redes · Segurança da Informação · Design">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/lucas-sales-vicente-067987426/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:svicentelucas@gmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
  <a href="https://calenia.com.br/"><img src="https://img.shields.io/badge/calenia.com.br-0B0F14?style=for-the-badge&logo=googlechrome&logoColor=1DDB8B" alt="Calenia"></a>
  <a href="https://brachah.com.br/"><img src="https://img.shields.io/badge/brachah.com.br-0B0F14?style=for-the-badge&logo=googlechrome&logoColor=1DDB8B" alt="Brachah"></a>
</p>

## Sobre mim

Cuido de redes, servidores, CFTV, controle de acesso e portaria inteligente como **Analista de Redes e Comunicação de Dados** desde Agosto de 2021. Antes da infraestrutura, foram cerca de 10 deles como designer e web designer em gráfica e editora. Daí vem o que eu busco: tecnologia que protege **e** que qualquer pessoa consegue usar.

- **Construindo** o **H7X**, uma camada de defesa de rede acessível para empresas sem analista de segurança
- **Sócio** do **[Calenia](https://calenia.com.br/)**, sistema de gestão para salões de beleza
- **Estudando** o último semestre de **Tecnólogo em Segurança da Informação** (Universidade Positivo) e *Redes de Computadores* (Tanenbaum), rumo a uma certificação de redes
- **Antes disso**, cursei **Direito** até o 8º período e fui mediador/conciliador extrajudicial no projeto Conciliere (Faculdade Positivo + PROCON Londrina)

## Em destaque: H7X Cyber Defense

![status](https://img.shields.io/badge/status-em%20testes-orange?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Orange Pi](https://img.shields.io/badge/Orange%20Pi-FF8C00?style=flat-square)
![licença](https://img.shields.io/badge/Community-MIT-lightgrey?style=flat-square)

Defesa ativa posicionada **antes do firewall**: mais uma camada de proteção entre a internet e a rede.

```mermaid
flowchart LR
    A([Internet]) --> B{{H7X}} --> C[Firewall] --> D[Rede interna]
    classDef h7x fill:#1DDB8B,stroke:#1DDB8B,color:#0B0F14,font-weight:bold
    class B h7x
```

O H7X reúne **mais de 130 ferramentas** e protocolos de segurança já consagrados, empacotados para rodar em **Docker** ou em **hardware de baixo custo**, fazendo o papel de um analista de segurança para quem não tem um. A versão **Community** foi pensada para ser aberta à comunidade.

- **Origem:** nasceu na faculdade como um sentinela de rede IoT com ESP32 e display; virou containers depois da experiência configurando o UmbrelOS
- **Na prática:** testado em ambiente corporativo real e usado em um projeto ODS com tema de economia sustentável
- **Próxima fase:** versão para empresas de pequeno a grande porte, com preço fixo
- **Repositórios:** H7X Cyber Defense Community (Python, licença MIT), H7X Cloud (Python) e a landing page do projeto, ainda privados

<!-- Quando publicar os repositórios do H7X, troque os nomes acima pelos links -->

## Outros projetos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://calenia.com.br/">Calenia</a></h3>
      <img src="https://img.shields.io/badge/status-no%20ar-brightgreen?style=flat-square" alt="no ar">
      <p>Gestão para salões de beleza: agenda da equipe com lista de espera, histórico de clientes, <b>confirmações e lembretes automáticos por WhatsApp</b>, financeiro, relatórios e estoque. Roda no navegador, no computador ou no celular.</p>
      <p>Sou sócio e fiz o site. Também criei logotipo, marca e site da <a href="https://brachah.com.br/">Brachah</a>, clínica de podologia e estética em Londrina que usa o sistema.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/UkS4les/MTG-Meta">MTG Meta</a></h3>
      <img src="https://img.shields.io/badge/status-em%20desenvolvimento-blue?style=flat-square" alt="em desenvolvimento">
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
      <img src="https://img.shields.io/badge/licen%C3%A7a-MIT-lightgrey?style=flat-square" alt="MIT">
      <p>Open source para Magic: The Gathering que mostra <b>o meta por formato</b> (Standard, Pioneer, Modern e Pauper, em janelas de 7, 14 e 30 dias) e <b>quais decks você já consegue montar</b>, cruzando sua coleção, de papel ou do Arena, com os arquétipos dos torneios do Magic Online.</p>
      <p>Histórico de partidas e taxa de vitória pelo log do Arena. Next.js + Postgres embutido (PGlite), sobe com <code>docker compose up</code>; 102 testes e CI.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Forja</h3>
      <img src="https://img.shields.io/badge/status-em%20desenvolvimento-blue?style=flat-square" alt="em desenvolvimento">
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/licen%C3%A7a-AGPL--3.0-lightgrey?style=flat-square" alt="AGPL-3.0">
      <img src="https://img.shields.io/badge/reposit%C3%B3rio-privado-555555?style=flat-square" alt="repositório privado">
      <p>Jogo social para conectar profissionais de TI, web e design: uma <b>cidadela medieval cyberpunk</b> em visual isométrico, onde cada pessoa monta a sua loja e troca serviços, ajuda e networking. Desafios e eventos periódicos destacam quem se esforça.</p>
    </td>
    <td width="50%" valign="top">
      <h3>TuxGG</h3>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
      <img src="https://img.shields.io/badge/reposit%C3%B3rio-privado-555555?style=flat-square" alt="repositório privado">
      <p>Comunidade gamer focada em <b>Linux, jogos, programação e tecnologia</b>, conectando jogadores e desenvolvedores num ambiente acolhedor e colaborativo.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/UkS4les/XIso-Debian-Extrator-de-iso-xbox">XIso Extrator</a></h3>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
      <p>Extrator de imagens XDVDFS (Xbox original e Xbox 360) para Linux, alternativa ao ExtractXISO do Windows. Detecta o layout da imagem, reconstrói a árvore de diretórios e tem interface gráfica (Tkinter) e linha de comando. Só Python, sem dependências externas.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Certificações e cursos</h3>
      <img src="https://img.shields.io/badge/IBSEC-Fundamentos%20em%20Redes-1DDB8B?style=flat-square" alt="IBSEC — Fundamentos em Redes"><br>
      <img src="https://img.shields.io/badge/Cisco%20NetAcad-Introdu%C3%A7%C3%A3o%20%C3%A0%20Ciberseguran%C3%A7a-049FD9?style=flat-square&logo=cisco&logoColor=white" alt="Cisco Networking Academy — Introdução à Cibersegurança"><br>
      <img src="https://img.shields.io/badge/Cisco%20NetAcad-Linux%20Unhatched-049FD9?style=flat-square&logo=cisco&logoColor=white" alt="Cisco Networking Academy — Linux Unhatched">
      <p>Cursos de <b>Hacker Ético com Kali Linux</b> e <b>Perícia Forense Computacional</b> (40 h).</p>
      <!-- Se tiver o link do Credly ou da página de validação, envolva cada selo com <a href="LINK">...</a> -->
    </td>
  </tr>
</table>

## Ferramentas

<table>
  <tr>
    <td><b>Infra e segurança</b></td>
    <td>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
      <img src="https://img.shields.io/badge/Windows%20Server-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows Server">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
      <img src="https://img.shields.io/badge/Firewalls-30363D?style=flat-square" alt="Firewalls">
      <img src="https://img.shields.io/badge/Virtualiza%C3%A7%C3%A3o-30363D?style=flat-square" alt="Virtualização">
      <img src="https://img.shields.io/badge/Ethical%20Hacking-30363D?style=flat-square" alt="Ethical Hacking">
      <img src="https://img.shields.io/badge/CFTV-30363D?style=flat-square" alt="CFTV">
      <img src="https://img.shields.io/badge/Controle%20de%20Acesso-30363D?style=flat-square" alt="Controle de Acesso">
    </td>
  </tr>
  <tr>
    <td><b>Desenvolvimento</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
    </td>
  </tr>
  <tr>
    <td><b>Hardware e IoT</b></td>
    <td>
      <img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
      <img src="https://img.shields.io/badge/ESP32%20%2F%20ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32 / ESP8266">
      <img src="https://img.shields.io/badge/M5StickC-1A1A1A?style=flat-square" alt="M5StickC">
      <img src="https://img.shields.io/badge/Orange%20Pi-FF8C00?style=flat-square" alt="Orange Pi">
    </td>
  </tr>
  <tr>
    <td><b>Design</b></td>
    <td>
      <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white" alt="Photoshop">
      <img src="https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=black" alt="Illustrator">
      <img src="https://img.shields.io/badge/CorelDRAW-000000?style=flat-square&logo=coreldraw&logoColor=white" alt="CorelDRAW">
      <img src="https://img.shields.io/badge/Web%20Design-30363D?style=flat-square" alt="Web Design">
      <img src="https://img.shields.io/badge/Design%20Gr%C3%A1fico-30363D?style=flat-square" alt="Design Gráfico">
    </td>
  </tr>
</table>
