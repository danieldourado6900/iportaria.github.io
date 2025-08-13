<!DOCTYPE ahtml>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iPortaria - Portaria Remota</title>
    <!-- Inclui a biblioteca Tailwind CSS para estilização rápida e responsiva -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Estilos personalizados para o degradê do botão */
        .btn-gradient {
            background-image: linear-gradient(to right, #0F62FE, #2D5BFF);
            transition: all 0.3s ease;
        }
        .btn-gradient:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(45, 91, 255, 0.4);
        }
        .section-separator {
            border-top: 1px solid rgba(229, 231, 235, 0.5);
            margin-top: 4rem;
            margin-bottom: 4rem;
        }
        /* Estilo para ícones SVG */
        .icon {
            color: #0F62FE;
            width: 24px;
            height: 24px;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Seção de Cabeçalho (Hero) -->
    <header class="bg-white shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- AQUI: Por favor, substitua a URL abaixo pela URL direta da sua logomarca. -->
            <a href="#" class="text-2xl font-bold text-gray-900">
                <img src="https://placehold.co/150x50/cccccc/000000?text=Sua+Logo" alt="Logo da iPortaria - sua segurança conectada" class="h-10">
            </a>
            <nav class="hidden md:flex space-x-8">
                <a href="#servicos" class="text-gray-600 hover:text-gray-900 transition-colors duration-200">Serviços</a>
                <a href="#app" class="text-gray-600 hover:text-gray-900 transition-colors duration-200">Aplicativo</a>
                <a href="#sobre" class="text-gray-600 hover:text-gray-900 transition-colors duration-200">Sobre Nós</a>
                <a href="#contato" class="text-gray-600 hover:text-gray-900 transition-colors duration-200">Contato</a>
            </nav>
            <a href="#contato" class="hidden md:inline-block bg-indigo-600 text-white font-semibold py-2 px-6 rounded-full hover:bg-indigo-700 transition-colors duration-200">
                Fale Conosco
            </a>
        </div>
    </header>

    <!-- Seção Principal com Título e Chamada para Ação -->
    <main>
        <section class="py-20 md:py-32 bg-indigo-50 text-center">
            <div class="max-w-4xl mx-auto px-4">
                <h1 class="text-4xl md:text-6xl font-extrabold text-gray-900 leading-tight">
                    Segurança e Inovação para o seu Condomínio
                </h1>
                <p class="mt-4 text-lg md:text-xl text-gray-600 max-w-2xl mx-auto">
                    A Portaria Remota é a solução inteligente que reduz custos, aumenta a segurança e moderniza a gestão do seu prédio.
                </p>
                <div class="mt-8 flex justify-center space-x-4">
                    <a href="#contato" class="btn-gradient text-white font-semibold py-3 px-8 rounded-full shadow-lg">
                        Peça um Orçamento Grátis
                    </a>
                    <a href="#servicos" class="bg-white text-indigo-600 font-semibold py-3 px-8 rounded-full border border-indigo-600 hover:bg-indigo-100 transition-colors duration-200">
                        Nossos Serviços
                    </a>
                </div>
            </div>
        </section>

        <!-- Seção de Serviços -->
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <section id="servicos" class="py-16 md:py-20 text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Nossos Serviços de Ponta</h2>
                <p class="mt-4 text-gray-600 max-w-2xl mx-auto">
                    Oferecemos uma solução completa de segurança, controle e conveniência para o seu patrimônio.
                </p>
                <div class="mt-12 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Cartão de Serviço 1 -->
                    <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300">
                        <div class="mb-4">
                             <svg class="icon mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900">Monitoramento 24h</h3>
                        <p class="mt-2 text-gray-600">
                            Equipe especializada disponível 24 horas por dia, 7 dias por semana, para garantir a segurança de todos.
                        </p>
                    </div>
                    <!-- Cartão de Serviço 2 -->
                    <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300">
                         <div class="mb-4">
                             <svg class="icon mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.066 12.066 0 001.25 12c.005 3.528 1.947 6.84 4.885 8.448"></path>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900">Controle de Acesso</h3>
                        <p class="mt-2 text-gray-600">
                            Tecnologia de ponta para o controle de entrada e saída, com biometria, tags e câmeras inteligentes.
                        </p>
                    </div>
                    <!-- Cartão de Serviço 3 -->
                    <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300">
                         <div class="mb-4">
                             <svg class="icon mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900">Redução de Custos</h3>
                        <p class="mt-2 text-gray-600">
                            Economia de até 50% nas despesas condominiais sem comprometer a qualidade ou a segurança.
                        </p>
                    </div>
                </div>
            </section>
        </div>
        
        <div class="section-separator max-w-7xl mx-auto"></div>

        <!-- Nova Seção: Download do App -->
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <section id="app" class="py-16 md:py-20 text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Baixe nosso aplicativo!</h2>
                <p class="mt-4 text-gray-600 max-w-2xl mx-auto">
                    Tenha o controle total na palma da sua mão. Com o nosso aplicativo, você pode gerenciar tudo de forma fácil e segura.
                </p>
                <div class="mt-8 flex flex-col sm:flex-row justify-center items-center space-y-4 sm:space-y-0 sm:space-x-8">
                    <!-- Botão Google Play Store -->
                    <a href="#" class="w-full sm:w-auto bg-gray-900 text-white font-semibold py-3 px-6 rounded-md shadow-lg flex items-center justify-center space-x-3 hover:bg-gray-700 transition-colors duration-200">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M7 2.115v19.77l15.115-9.885L7 2.115zM7.7 20.3L2.3 22.7l5.4-2.4c.1-.1.2-.2.2-.3v-1.6c-.1.2-.1.5-.1.8zM2 12c0 .4.2.8.5 1.1l3.5 2.1c.1.1.2.2.3.2V8.6c-.1.1-.1.2-.2.3l-3.5 2.1c-.3.3-.5.7-.5 1zM7.7 3.7L2.3 1.3l5.4 2.4c.1.1.2.2.2.3v1.6c-.1-.2-.1-.5-.1-.8z" />
                        </svg>
                        <span>Google Play</span>
                    </a>
                    <!-- Botão Apple App Store -->
                    <a href="#" class="w-full sm:w-auto bg-gray-900 text-white font-semibold py-3 px-6 rounded-md shadow-lg flex items-center justify-center space-x-3 hover:bg-gray-700 transition-colors duration-200">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M12 2c-3.132 0-5.714 2.364-5.714 5.286 0 1.29.544 2.476 1.464 3.32-.93.57-1.464 1.258-1.464 2.057 0 1.056.84 1.93 2.062 1.93s2.062-.874 2.062-1.93c0-.8-.534-1.488-1.464-2.057.92-.844 1.464-2.03 1.464-3.32 0-2.922-2.582-5.286-5.714-5.286zm0 18c-2.735 0-5-2.265-5-5s2.265-5 5-5 5 2.265 5 5-2.265 5-5 5zm0-8c-1.657 0-3 1.343-3 3s1.343 3 3 3 3-1.343 3-3-1.343-3-3-3z"/>
                        </svg>
                        <span>App Store</span>
                    </a>
                </div>
            </section>
        </div>

        <div class="section-separator max-w-7xl mx-auto"></div>
        
        <!-- Seção Sobre Nós -->
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <section id="sobre" class="py-16 md:py-20 text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">A Tecnologia que Transforma Vidas</h2>
                <p class="mt-4 text-gray-600 max-w-2xl mx-auto">
                    Somos uma empresa dedicada a oferecer o que há de mais moderno em portaria remota, com foco na segurança, eficiência e satisfação dos nossos clientes.
                </p>
            </section>
        </div>

        <div class="section-separator max-w-7xl mx-auto"></div>

        <!-- Seção de Contato -->
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <section id="contato" class="py-16 md:py-20 text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Fale Conosco</h2>
                <p class="mt-4 text-gray-600 max-w-2xl mx-auto">
                    Preencha o formulário abaixo para solicitar um orçamento. A mensagem será enviada diretamente pelo WhatsApp!
                </p>
                <div class="mt-12 max-w-lg mx-auto bg-white p-8 rounded-lg shadow-md">
                    <form id="contact-form" class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 text-left">Nome</label>
                            <input type="text" id="name" name="name" required class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500">
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 text-left">E-mail</label>
                            <input type="email" id="email" name="email" required class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500">
                        </div>
                         <!-- NOVO CAMPO: Adicionado o campo de telefone -->
                        <div>
                            <label for="phone" class="block text-sm font-medium text-gray-700 text-left">Telefone (opcional)</label>
                            <input type="tel" id="phone" name="phone" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500">
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 text-left">Mensagem</label>
                            <textarea id="message" name="message" rows="4" required class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500"></textarea>
                        </div>
                        <button type="submit" class="w-full btn-gradient text-white font-semibold py-2 px-4 rounded-md shadow-lg flex items-center justify-center space-x-2">
                             <!-- Ícone do WhatsApp (SVG) -->
                            <svg class="w-5 h-5 text-white" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                <path d="M12.039 2c-5.46 0-9.914 4.496-9.914 9.992 0 1.765.46 3.454 1.348 4.965l-1.348 4.995 5.12-1.318c1.478.8 3.12 1.258 4.804 1.258 5.456 0 9.914-4.496 9.914-9.993s-4.458-9.992-9.914-9.992zm3.626 13.918l-.208-.124c-.312-.187-.666-.312-1.042-.436-.376-.126-.646-.22-.924-.22-.278 0-.55.112-.81.332-.26.223-.496.67-.655.823-.157.153-.306.17-.565.112-.258-.06-.803-.298-1.536-.957-.566-.51-1.07-1.144-1.385-1.68-.316-.534-.035-.82.25-.86.284-.04.43-.13.567-.313.136-.182.164-.32.222-.445.056-.125.028-.236-.013-.346-.04-.112-.376-.905-.515-1.22-.14-.316-.285-.275-.496-.275-.108 0-.236.002-.38.002-.145 0-.376.04-.596.242-.222.2-.84.81-1.12 1.104-.28.293-.45.474-.45.92 0 .445.244.757.502 1.05.258.292.98.718 2.052 1.15.823.336 1.492.59 1.936.758.64.248 1.146.21 1.57.112.424-.1.884-.44 1.145-.758.262-.317.472-.516.666-.64.195-.125.39-.247.584-.11.196.14.924.96.924.986 0 .025.293.18.57.34.276.16.51.272.585.34.075.068.188.163.146.257-.04.093-.207.18-.328.25-.12.068-.266.155-.407.248-.142.093-.27.187-.39.29-.12.1-.21.2-.21.293 0 .094-.132.28-.132.553 0 .27.13.437.29.624.16.185.39.366.612.366.22 0 .428-.112.56-.237.133-.125.33-.29.47-.564.14-.274.52-.9.52-.9.186-.407.35-.615.545-.583.197.03.882.378 1.042.446.16.066.29.112.44.112.15 0 .346-.04.512-.132.164-.092.49-.247.78-.372.29-.126.54-.15.81-.15.27 0 1.25.138 1.41.22.16.084.223.11.223.238 0 .125-.11.642-.212.784-.102.14-.35.258-.57.336-.22.078-.51.15-.81.187-.3.037-.58.056-.78.056-.202 0-.27-.01-.39-.026z"/>
                            </svg>
                            <span>Enviar por WhatsApp</span>
                        </button>
                    </form>
                    <div id="success-message" class="mt-6 p-4 text-green-700 bg-green-100 rounded-md hidden">
                        Mensagem enviada com sucesso! Você será redirecionado para o WhatsApp.
                    </div>
                </div>
            </section>
        </div>
    </main>

    <!-- Rodapé -->
    <footer class="bg-gray-900 text-gray-300 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p>&copy; 2025 iPortaria. Todos os direitos reservados.</p>
            <div class="mt-4 space-x-4">
                <a href="#" class="text-gray-400 hover:text-white transition-colors duration-200">Facebook</a>
                <a href="#" class="text-gray-400 hover:text-white transition-colors duration-200">Instagram</a>
                <a href="#" class="text-gray-400 hover:text-white transition-colors duration-200">LinkedIn</a>
            </div>
        </div>
    </footer>

    <script>
        // Lógica para enviar mensagem do formulário via WhatsApp
        document.getElementById('contact-form').addEventListener('submit', function(event) {
            event.preventDefault();

            // Obter os valores do formulário
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const phone = document.getElementById('phone').value;
            const message = document.getElementById('message').value;
            
            // AQUI: Insira o seu número de WhatsApp com o código do país (ex: 5511999998888)
            const whatsappNumber = '5569984345184'; // Substitua por seu número real
            
            // Montar a mensagem com as informações do formulário
            const whatsappMessage = `Olá, iPortaria!%0A%0ARecebi uma mensagem através do site:%0A%0ANome: ${name}%0AE-mail: ${email}%0ATelefone: ${phone ? phone : 'Não informado'}%0A%0AMensagem: ${message}`;
            
            // Construir a URL do WhatsApp
            const whatsappUrl = `https://api.whatsapp.com/send?phone=${whatsappNumber}&text=${whatsappMessage}`;
            
            // Abrir o link do WhatsApp em uma nova aba
            window.open(whatsappUrl, '_blank');

            // Mostra a mensagem de sucesso e limpa o formulário
            document.getElementById('success-message').classList.remove('hidden');
            event.target.reset();
        });
    </script>
</body>
</html>
