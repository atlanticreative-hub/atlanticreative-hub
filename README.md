<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AtlantiCreative Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7;
            color: #333;
        }
    </style>
</head>
<body>

    <!-- Cabeçalho -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <img src="https://placehold.co/40x40/7C6788/ffffff?text=AC" alt="Logo" class="rounded-lg">
                <span class="text-xl font-bold text-[#7C6788]">AtlantiCreative Hub</span>
            </div>
            <a href="#contato" class="px-4 py-2 bg-[#7C6788] text-white rounded-md hover:bg-[#6a597a] transition-colors">Contacte-nos</a>
        </nav>
    </header>

    <!-- Seção Principal -->
    <main>
        <section class="bg-[#F7E7C4] text-[#333] py-20">
            <div class="container mx-auto px-6 text-center">
                <h1 class="text-4xl md:text-5xl font-extrabold mb-4 leading-tight">Pensamos e crescemos juntos – da Madeira para o Mundo.</h1>
                <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto">
                    Apoio técnico, estratégico e formativo para o setor cultural, capacitando-o com ferramentas profissionais e oportunidades de circulação global.
                </p>
                <div class="flex flex-col md:flex-row justify-center space-y-4 md:space-y-0 md:space-x-4">
                    <a href="#servicos" class="px-8 py-3 bg-[#7C6788] text-white rounded-md text-lg font-semibold hover:bg-[#6a597a] transition-colors">Descubra os Serviços</a>
                </div>
            </div>
        </section>

        <!-- Seção de Serviços -->
        <section id="servicos" class="py-20 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-12 text-[#7C6788]">Os Nossos Serviços</h2>
                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Cartão de Agenciamento -->
                    <div class="bg-white p-8 rounded-lg shadow-lg border border-gray-200 hover:shadow-xl transition-shadow">
                        <div class="text-5xl mb-4 text-[#7C6788] text-center">
                            <!-- Ícone de Agenciamento -->
                            <svg class="h-12 w-12 text-[#7C6788] mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20v-2a3 3 0 013-3h3m-6 3a3 3 0 01-3-3V9a3 3 0 013-3h1a3 3 0 013 3v11m-9-9h1a3 3 0 013 3v11m-3-9V7a3 3 0 013-3h1a3 3 0 013 3v14m-10 1a1 1 0 01-1-1v-4a1 1 0 011-1h12a1 1 0 011 1v4a1 1 0 01-1 1h-12z" />
                            </svg>
                        </div>
                        <h3 class="text-2xl font-semibold text-center mb-4 text-[#333]">Agenciamento</h3>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Representação Artística e Apoio Profissional.</li>
                            <li>Acesso a uma rede de parceiros globais.</li>
                        </ul>
                    </div>
                    
                    <!-- Cartão de Gestão de Candidaturas -->
                    <div class="bg-white p-8 rounded-lg shadow-lg border border-gray-200 hover:shadow-xl transition-shadow">
                        <div class="text-5xl mb-4 text-[#7C6788] text-center">
                            <!-- Ícone de Candidaturas -->
                            <svg class="h-12 w-12 text-[#7C6788] mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m-5 3a2 2 0 01-2-2v-4a2 2 0 012-2h4a2 2 0 012 2v4a2 2 0 01-2 2h-4z" />
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 2a10 10 0 100 20 10 10 0 000-20z" />
                            </svg>
                        </div>
                        <h3 class="text-2xl font-semibold text-center mb-4 text-[#333]">Gestão de Candidaturas</h3>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Elaboração e revisão de candidaturas.</li>
                            <li>Apoio na submissão e gestão pós-submissão.</li>
                        </ul>
                    </div>

                    <!-- Cartão de Produção Cultural -->
                    <div class="bg-white p-8 rounded-lg shadow-lg border border-gray-200 hover:shadow-xl transition-shadow">
                        <div class="text-5xl mb-4 text-[#7C6788] text-center">
                            <!-- Ícone de Produção -->
                            <svg class="h-12 w-12 text-[#7C6788] mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                        </div>
                        <h3 class="text-2xl font-semibold text-center mb-4 text-[#333]">Produção Cultural</h3>
                        <ul class="list-disc list-inside space-y-2 text-gray-700">
                            <li>Criação de projetos culturais do conceito à implementação.</li>
                            <li>Criação de espetáculos inovadores.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Seção de Parcerias e Membros -->
        <section id="parcerias" class="py-20 bg-white">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-bold mb-12 text-[#7C6788]">Vantagens de ser Membro</h2>
                <div class="grid md:grid-cols-2 gap-8 items-center">
                    <div class="md:text-left">
                        <p class="text-xl mb-4">Ao aderir, terá acesso a uma rede de parceiros e a vantagens exclusivas:</p>
                        <ul class="list-disc list-inside text-left space-y-2 text-gray-700 max-w-md mx-auto md:mx-0">
                            <li>Desconto de 20% em todos os nossos serviços.</li>
                            <li>Acesso a uma rede mundial de residências artísticas.</li>
                            <li>Apoio à cooperação e circulação artística.</li>
                            <li>Quotas anuais flexíveis: artistas individuais (€100) e coletivos culturais (€250).</li>
                        </ul>
                    </div>
                    <div class="flex justify-center">
                        <img src="https://placehold.co/400x300/F7E7C4/7C6788?text=Rede+de+Membros" alt="Membros" class="rounded-lg shadow-lg">
                    </div>
                </div>
            </div>
        </section>

        <!-- Seção de Parceiros Oficiais -->
        <section id="parceiros-oficiais" class="py-20 bg-[#7C6788] text-white">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-12">Os Nossos Parceiros Oficiais</h2>
                <div class="grid md:grid-cols-4 gap-8">
                    <div class="bg-white text-[#7C6788] p-6 rounded-lg shadow-lg text-center font-bold">Associação Capote</div>
                    <div class="bg-white text-[#7C6788] p-6 rounded-lg shadow-lg text-center font-bold">Casa das Cenas</div>
                    <div class="bg-white text-[#7C6788] p-6 rounded-lg shadow-lg text-center font-bold">Prisma</div>
                    <div class="bg-white text-[#7C6788] p-6 rounded-lg shadow-lg text-center font-bold">Madeira Art Fest</div>
                </div>
            </div>
        </section>

        <!-- Seção de Contato -->
        <section id="contato" class="py-20 bg-[#F7E7C4]">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-bold mb-4 text-[#7C6788]">Pronto para transformar a sua carreira?</h2>
                <p class="text-lg text-gray-700 mb-8 max-w-xl mx-auto">
                    Entre em contacto connosco para saber como o AtlantiCreative Hub pode impulsionar o seu talento e levá-lo para o mundo.
                </p>
                <a href="mailto:ar7e.org@gmail.com" class="px-8 py-3 bg-[#7C6788] text-white rounded-md text-lg font-semibold hover:bg-[#6a597a] transition-colors">Enviar Email</a>
            </div>
        </section>
    </main>

    <!-- Rodapé -->
    <footer class="bg-[#333] text-white py-8">
        <div class="container mx-auto px-6 text-center text-sm">
            <p>&copy; 2024 AtlantiCreative Hub. Todos os direitos reservados.</p>
            <p class="mt-2">ar7e.org@gmail.com</p>
        </div>
    </footer>

</body>
</html>
