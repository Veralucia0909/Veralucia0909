<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vera Lúcia - Portfólio</title>
    <!-- Tailwind CSS para estilização rápida -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- HEADER / TOPO COM A FOTO E NOME -->
    <header class="bg-cyan-700 text-white py-12 px-4 text-center shadow-md">
        <div class="max-w-4xl mx-auto flex flex-col items-center">
            <!-- Sua Foto -->
            <img src="LINK_DA_SUA_FOTO_AQUI" alt="Vera Lúcia" class="w-36 h-36 rounded-full object-cover border-4 border-white shadow-lg mb-4">
            
            <h1 class="text-3xl md:text-4xl font-bold">Vera Lúcia Paula de Lima</h1>
            <p class="text-cyan-100 text-lg mt-2">Desenvolvedora Front-end | React | TypeScript | Tailwind CSS</p>
            <p class="italic text-sm text-cyan-200 mt-1">"De painéis elétricos a linhas de código, transformando resolução de problemas em software."</p>
        </div>
    </header>

    <!-- FAIXA / CARROSSEL DE FERRAMENTAS -->
    <section class="bg-white py-6 shadow-sm border-b overflow-hidden">
        <div class="max-w-6xl mx-auto px-4 flex justify-center items-center flex-wrap gap-4">
            <img src="https://skillicons.dev/icons?i=react,ts,js,html,css,tailwind,vite,reactnative,nodejs,express,python,postgres,mysql,supabase,firebase,vercel,git,github,vscode,postman,figma,prisma,linux,windows" alt="Tecnologias" class="max-w-full h-auto">
        </div>
    </section>

    <!-- SEÇÃO SOBRE MIM -->
    <main class="max-w-4xl mx-auto px-6 py-12">
        <section class="bg-white p-8 rounded-xl shadow-md">
            <h2 class="text-2xl font-bold text-cyan-800 border-b-2 border-cyan-600 pb-2 mb-6">Sobre mim</h2>
            
            <div class="space-y-4 text-gray-700 leading-relaxed">
                <p>
                    Sou uma Desenvolvedora Front-end e estudante de Desenvolvimento de Sistemas no SENAI/SC, trazendo para a tecnologia uma sólida bagagem e experiência prévia em manutenção elétrica, eletromecânica e automação industrial. Em minha transição de carreira para a área de TI, uni a minha paixão por resolução de problemas complexos ao desenvolvimento de software moderno. Desde então, tenho me destacado na criação de aplicações web eficientes, responsivas e focadas na experiência do usuário.
                </p>
                <p>
                    Tenho experiência em tecnologias de front-end, como React, TypeScript, JavaScript, HTML5, CSS3, Tailwind CSS, além de trabalhar com Vite e bibliotecas para consumo de APIs com Axios. No ecossistema de desenvolvimento, também possuo conhecimentos em back-end com Node.js, Express, Python e manipulação de bancos de dados relacionais e em nuvem como PostgreSQL, MySQL, Supabase e Firebase, além de ferramentas como Git, GitHub, Postman, Prisma e Figma.
                </p>
                <p>
                    Sou apaixonada por aprender continuamente, otimizar processos e criar soluções que geram impacto real. Acredito que a combinação da minha vivência anterior em ambientes industriais com a agilidade do desenvolvimento web me proporciona uma visão analítica diferenciada na entrega de software de qualidade.
                </p>
            </div>
        </section>

        <!-- SEÇÃO DE EXPERIÊNCIAS E PROJETOS -->
        <section class="bg-white p-8 rounded-xl shadow-md mt-8">
            <h2 class="text-2xl font-bold text-cyan-800 border-b-2 border-cyan-600 pb-2 mb-6">Experiências & Projetos</h2>
            
            <div class="space-y-6">
                <div>
                    <h3 class="text-lg font-semibold text-gray-900">Projetos Práticos & Desenvolvimento Web | 2025 - Presente</h3>
                    <ul class="list-disc list-inside mt-2 space-y-1 text-gray-700">
                        <li><strong>AssinaDoc:</strong> Desenvolvimento de aplicação voltada para gerenciamento e facilitação de processos de assinatura de documentos com React e TypeScript.</li>
                        <li><strong>BusOnTime (Hackathon):</strong> Criação de solução voltada para otimização do tempo e acompanhamento de transporte público sob alta pressão de entrega.</li>
                        <li><strong>Investe Mais:</strong> Desenvolvimento de sistema completo com fluxo de registro, login de usuários e dashboards financeiros interativos.</li>
                    </ul>
                </div>
            </div>
        </section>
    </main>

    <!-- RODAPÉ -->
    <footer class="bg-gray-800 text-white text-center py-6 mt-12">
        <p>© 2026 Vera Lúcia Paula de Lima. Todos os direitos reservados.</p>
        <div class="flex justify-center gap-4 mt-3">
            <a href="mailto:limaveralucia2018@gmail.com" class="text-cyan-400 hover:underline">Gmail</a>
            <a href="https://www.linkedin.com/in/verapaulalima" target="_blank" class="text-cyan-400 hover:underline">LinkedIn</a>
        </div>
    </footer>

</body>
</html>
