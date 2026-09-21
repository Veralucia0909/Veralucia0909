# ⚡ Olá mundo, sou a Vera Lúcia!

### Desenvolvedora Front-end | React · JavaScript · PWA mobile-first

*De painéis elétricos a linhas de código, transformando resolução de problemas em software.*

<a href="https://veralucia-portfolio.vercel.app" target="_blank">
  <img src="https://img.shields.io/badge/Portf%C3%B3lio-FF4088?style=for-the-badge&logo=vercel&logoColor=white" />
</a>
<a href="./curriculo-vera-lucia.pdf" target="_blank">
  <img src="https://img.shields.io/badge/Curr%C3%ADculo%20(PDF)-2D3748?style=for-the-badge&logo=readdotcv&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/verapaulalima" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:limaveralucia2018@gmail.com">
  <img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

---

## 💻 Sobre mim

Sou desenvolvedora front-end e estudante de Desenvolvimento de Sistemas no SENAI/SC. Antes do código, passei mais de 7 anos em manutenção elétrica, eletromecânica e automação industrial diagnosticando falhas sob pressão, em equipamento que não podia parar.

Levo esse mesmo raciocínio investigativo para o software: pesquiso, testo e entrego. Foi assim que identifiquei um gargalo no fluxo de documentos da imobiliária onde trabalho, propus uma solução e coloquei o **AssinaDoc** no ar sistema que hoje é usado todos os dias por pessoas reais.

Trabalho principalmente com **React, JavaScript (ES6+), HTML5 e CSS3**, com foco em **PWA mobile-first**: aplicações instaláveis, que funcionam offline e são pensadas para o celular antes do desktop.

---

## 🛠️ Stack que utilizo

**Front-end**

<img src="https://skillicons.dev/icons?i=react,js,html,css,vite,tailwind,ts" height="42" />

**Back-end**

<img src="https://skillicons.dev/icons?i=nodejs,express,python,prisma" height="42" />

**Banco de dados**

<img src="https://skillicons.dev/icons?i=postgres,mysql,supabase,firebase" height="42" />

**Ferramentas**

<img src="https://skillicons.dev/icons?i=git,github,vercel,postman,figma,vscode" height="42" />

> React, JavaScript, HTML, CSS, Vite, Supabase, Firebase, Git e Vercel são o que uso no dia a dia dos meus projetos. TypeScript, Node.js, Express, Prisma e PostgreSQL estou aprofundando agora nos projetos de back-end do curso.

---

## 🚀 Projetos

### 📄 AssinaDoc — Assinatura digital de documentos via WhatsApp
*em produção, cliente real*

**Stack:** JavaScript (ES6+) · HTML5 · CSS3 · Supabase (Postgres + Edge Functions) · APIs REST/JSON · Vercel

- Identifiquei o gargalo no fluxo de documentos da imobiliária onde trabalho e propus, desenvolvi e coloquei no ar a solução — do levantamento do problema ao deploy.
- Envio do documento pelo WhatsApp, assinatura no celular com o dedo e devolução do PDF assinado, eliminando deslocamentos de inquilinos e proprietários.
- Modelagem das tabelas, autenticação e regras de acesso no Supabase, com controle de status de cada documento.
- Segurança tratada no servidor: senhas em Edge Functions (nenhum segredo no código do site), PDFs em bucket privado com link temporário de 15 minutos, sessão com validade e bloqueio contra tentativa automática de senha.
- Consentimento LGPD registrado antes da assinatura.
- Sistema em uso real: evolução e correção de bugs contínuas a partir do feedback de quem usa todos os dias.

🔗 **[assinadocwhatsapp.com.br](https://www.assinadocwhatsapp.com.br/)** · *código privado (sistema de cliente)*

<!-- ▼ VÍDEO: arraste o arquivo assinadoc-demo.mp4 aqui na caixa de edição do README no GitHub.
     O GitHub sobe o arquivo e troca esta linha pelo link sozinho. Depois apague este comentário. ▼ -->

> **Demonstração (52s):** fluxo completo em modo demonstração — login, preenchimento, geração do link, assinatura, PDF assinado e painel de acompanhamento. Todos os dados do vídeo são fictícios.

---

### 🚌 BusOnTime Floripa — App PWA de mobilidade urbana
*2º lugar — Hackathon SENAI 2026*

**Stack:** React · Vite · Leaflet · MySQL · Service Workers

- MVP mobile-first construído do zero em equipe, em poucos dias de hackathon, com divisão de tarefas e versionamento no GitHub.
- Rastreamento de ônibus em tempo real com mapas interativos (Leaflet) e previsão de lotação apoiada em IA.
- Carteira digital com recarga via PIX, histórico de viagens e recarga automática por saldo mínimo.
- Linhas favoritas com alerta de chegada, central de notificações e tema claro/escuro.
- Funcionamento offline e instalação na tela inicial via Service Workers, pensando em quem espera o ônibus com conexão instável.

🔗 [busontime-floripa.vercel.app](https://busontime-floripa.vercel.app/) · [código no GitHub](https://github.com/Veralucia0909/busOnTime)

<!-- ▼ VÍDEO: arraste o arquivo busontime-demo.mp4 aqui. ▼ -->

> **Demonstração (54s):** dashboard com linhas favoritas, mapa em tempo real, carteira digital com recarga via PIX, histórico de viagens, notificações e troca de tema.

---

### ⚡ KitEnergia — PWA de leitura e gestão de energia
*projeto acadêmico*

**Stack:** React · Vite · JavaScript · PWA (Service Worker + Manifest) · LocalStorage · Vercel

- CRUD completo para leitura e acompanhamento do consumo de 12 unidades habitacionais.
- Emissão de fatura em PDF com demonstrativo de consumo e dashboard com total em kWh, tarifa aplicada e unidade de maior consumo.
- App instalável na tela inicial e com funcionamento offline pensado para quem faz a leitura em campo, onde nem sempre há sinal.

🔗 [kitenergia.vercel.app](https://kitenergia.vercel.app/) · [código no GitHub](https://github.com/Veralucia0909/KitEnergia)

<!-- ▼ VÍDEO: arraste o arquivo kitenergia-demo.mp4 aqui. ▼ -->

> **Demonstração (44s):** cadastro de leitura, acompanhamento do consumo e instalação do app na tela inicial.

---

### 🖥️ Painel de Comunidade — Desafio técnico HostGator / UniSENAI
*desafio técnico*

**Stack:** JavaScript (ES6+) · HTML5 · CSS3

- Aplicação web que processa um conjunto anonimizado de mensagens de uma comunidade de tecnologia e transforma os dados em um painel de acompanhamento.
- Tratamento e agregação dos dados no front-end, com visualização pensada para leitura rápida.

🔗 [desafio-hostgator-unisenai.vercel.app](https://desafio-hostgator-unisenai.vercel.app/) · [código no GitHub](https://github.com/Veralucia0909/desafio-hostgator-unisenai)

---

### 💰 Gestão Financeira — Aplicação web com Firebase
*projeto acadêmico em equipe — minha parte: autenticação*

**Stack:** JavaScript (ES6+) · HTML5 · CSS3 · Firebase Authentication · Vercel

- Desenvolvi o cadastro, o login e a recuperação de senha com Firebase Authentication, incluindo validação de formulário, tratamento de erros e a sessão que liga cada usuário aos seus próprios dados.
- A persistência das movimentações no Firestore e os gráficos ficaram a cargo de outro integrante da equipe.

🔗 [gestao-financeira-crud.vercel.app](https://gestao-financeira-crud.vercel.app/) · [código no GitHub](https://github.com/Veralucia0909/Gestao-Financeira)

---

## 📬 Vamos conversar?

Estou aberta a oportunidades como **Desenvolvedora Front-end Júnior**, em Florianópolis ou remoto.

- 🌐 **Portfólio:** [veralucia-portfolio.vercel.app](https://veralucia-portfolio.vercel.app)
- 📄 **Currículo em PDF:** [baixar aqui](./curriculo-vera-lucia.pdf)
- 💼 **LinkedIn:** [linkedin.com/in/verapaulalima](https://www.linkedin.com/in/verapaulalima)
- ✉️ **E-mail:** [limaveralucia2018@gmail.com](mailto:limaveralucia2018@gmail.com)

<div align="center">

<br/>

© 2026 Vera Lúcia Paula de Lima

</div>
