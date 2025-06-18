# INFINITY-BUSINESS-
Site base
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infinity Business - Soluções Estratégicas para seu Crescimento</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, #1e3a8a 0%, #2563eb 50%, #3b82f6 100%);
        }
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .animate-float {
            animation: float 6s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-800">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <span class="text-2xl font-bold text-blue-600">∞ Infinity Business</span>
                    </div>
                    <div class="hidden md:ml-10 md:flex md:space-x-8">
                        <a href="#home" class="border-blue-500 text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Home</a>
                        <a href="#services" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Serviços</a>
                        <a href="#about" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Sobre</a>
                        <a href="#contact" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Contato</a>
                    </div>
                </div>
                <div class="hidden md:ml-6 md:flex md:items-center">
                    <button class="bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-md text-sm font-medium transition duration-300">Fale Conosco</button>
                </div>
                <div class="-mr-2 flex items-center md:hidden">
                    <button type="button" id="mobile-menu-button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none">
                        <span class="sr-only">Open main menu</span>
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <div class="pt-2 pb-3 space-y-1">
                <a href="#home" class="bg-blue-50 border-blue-500 text-blue-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">Home</a>
                <a href="#services" class="border-transparent text-gray-600 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-800 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">Serviços</a>
                <a href="#about" class="border-transparent text-gray-600 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-800 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">Sobre</a>
                <a href="#contact" class="border-transparent text-gray-600 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-800 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">Contato</a>
                <div class="mt-4 pl-3">
                    <button class="bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-md text-sm font-medium transition duration-300 w-full">Fale Conosco</button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-gradient text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 md:py-32">
            <div class="md:flex items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-bold leading-tight mb-6">Impulsionando Seu Crescimento com Inovação</h1>
                    <p class="text-xl mb-8">Transformamos o potencial da sua empresa em resultados reais com soluções estratégicas em vendas, atendimento ao cliente e gestão.</p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <button class="bg-white text-blue-600 hover:bg-gray-100 px-6 py-3 rounded-md font-medium transition duration-300">Comece Agora</button>
                        <button class="border-2 border-white text-white hover:bg-white hover:text-blue-600 px-6 py-3 rounded-md font-medium transition duration-300">Saiba Mais</button>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Business Growth" class="rounded-lg shadow-2xl animate-float max-w-md w-full">
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Nossas Soluções Estratégicas</h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Oferecemos as ferramentas e estratégias que sua empresa precisa para crescer de forma sustentável e inovadora.</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Feature 1 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-md transition duration-300">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-chart-line text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Vendas Estratégicas</h3>
                    <p class="text-gray-600">Metodologias comprovadas para otimizar seu processo de vendas e aumentar sua receita de forma consistente.</p>
                </div>
                
                <!-- Feature 2 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-md transition duration-300">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-headset text-green-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Atendimento Excepcional</h3>
                    <p class="text-gray-600">Programas que fortalecem o relacionamento com seus clientes e constroem lealdade duradoura.</p>
                </div>
                
                <!-- Feature 3 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-md transition duration-300">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-cogs text-purple-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Gestão Inovadora</h3>
                    <p class="text-gray-600">Ferramentas e insights para uma administração eficiente e orientada ao crescimento sustentável.</p>
                </div>
                
                <!-- Feature 4 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-md transition duration-300">
                    <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-lightbulb text-red-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Foco em Inovação</h3>
                    <p class="text-gray-600">Adotamos as últimas tendências e tecnologias para manter sua empresa à frente no mercado.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="md:flex items-center gap-12">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Our Team" class="rounded-lg shadow-xl w-full">
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-3xl font-bold text-gray-900 mb-6">Sua Parceira Estratégica para Excelência e Expansão</h2>
                    <p class="text-gray-600 mb-6">A Infinity Business é especializada em desenvolver soluções completas, impulsionadas pela inovação, para levar seu negócio ao próximo nível. Entendemos que o sucesso de uma empresa reside na sinergia entre vendas eficazes, atendimento ao cliente de alta qualidade e uma gestão sólida e adaptável.</p>
                    
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <div class="w-6 h-6 bg-blue-100 rounded-full flex items-center justify-center">
                                    <i class="fas fa-check text-blue-600 text-xs"></i>
                                </div>
                            </div>
                            <p class="ml-3 text-gray-700"><span class="font-medium">Resultados Comprovados:</span> Nosso compromisso é com o seu crescimento sustentável e mensurável.</p>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <div class="w-6 h-6 bg-blue-100 rounded-full flex items-center justify-center">
                                    <i class="fas fa-check text-blue-600 text-xs"></i>
                                </div>
                            </div>
                            <p class="ml-3 text-gray-700"><span class="font-medium">Cultura de Inovação:</span> Estamos sempre um passo à frente, aplicando as mais recentes inovações do mercado.</p>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <div class="w-6 h-6 bg-blue-100 rounded-full flex items-center justify-center">
                                    <i class="fas fa-check text-blue-600 text-xs"></i>
                                </div>
                            </div>
                            <p class="ml-3 text-gray-700"><span class="font-medium">Parceria Dedicada:</span> Mais do que prestadores de serviço, somos parceiros comprometidos com seu sucesso.</p>
                        </div>
                    </div>
                    
                    <button class="mt-8 bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-md font-medium transition duration-300">Conheça Nossa História</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">O Que Nossos Clientes Dizem</h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Resultados reais de empresas que confiaram em nossas soluções.</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="text-yellow-400 mr-2">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 italic mb-6">"A Infinity Business revolucionou nosso processo de vendas. Em apenas 3 meses, aumentamos nossa receita em 40% com suas estratégias inovadoras."</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full bg-gray-300 overflow-hidden mr-4">
                            <img src="https://randomuser.me/api/portraits/women/43.jpg" alt="Client" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold">Ana Carolina Silva</h4>
                            <p class="text-gray-500 text-sm">CEO, TechSolutions</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="text-yellow-400 mr-2">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 italic mb-6">"O atendimento ao cliente da nossa empresa nunca foi tão bom. A Infinity nos ajudou a criar experiências memoráveis que fidelizaram nossos clientes."</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full bg-gray-300 overflow-hidden mr-4">
                            <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Client" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold">Ricardo Almeida</h4>
                            <p class="text-gray-500 text-sm">Diretor Comercial, VivaBem</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="text-yellow-400 mr-2">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 italic mb-6">"As soluções de gestão implementadas transformaram nossa operação. Reduzimos custos em 25% e aumentamos a produtividade em 35%."</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full bg-gray-300 overflow-hidden mr-4">
                            <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Client" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold">Fernanda Oliveira</h4>
                            <p class="text-gray-500 text-sm">Diretora de Operações, LogiFast</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20 bg-blue-600 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold mb-6">Pronto para impulsionar o crescimento da sua empresa?</h2>
            <p class="text-xl mb-8 max-w-3xl mx-auto">Na Infinity Business, oferecemos as soluções que você precisa em vendas, atendimento e gestão, com um foco inabalável em inovação.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <button class="bg-white text-blue-600 hover:bg-gray-100 px-8 py-4 rounded-md font-medium text-lg transition duration-300">Comece Agora</button>
                <button class="border-2 border-white text-white hover:bg-white hover:text-blue-600 px-8 py-4 rounded-md font-medium text-lg transition duration-300">Fale com um Especialista</button>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="md:flex gap-12">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h2 class="text-3xl font-bold text-gray-900 mb-6">Entre em Contato</h2>
                    <p class="text-gray-600 mb-8">Tem dúvidas ou quer saber mais sobre nossas soluções? Nossa equipe está pronta para ajudar você a alcançar seus objetivos de negócios.</p>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-map-marker-alt text-blue-600 text-xl"></i>
                            </div>
                            <div class="ml-4">
                                <h4 class="font-bold text-gray-900">Endereço</h4>
                                <p class="text-gray-600">Av. Paulista, 1000 - São Paulo, SP</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-phone-alt text-blue-600 text-xl"></i>
                            </div>
                            <div class="ml-4">
                                <h4 class="font-bold text-gray-900">Telefone</h4>
                                <p class="text-gray-600">(11) 9999-9999</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-envelope text-blue-600 text-xl"></i>
                            </div>
                            <div class="ml-4">
                                <h4 class="font-bold text-gray-900">Email</h4>
                                <p class="text-gray-600">contato@infinitybusiness.com</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="mt-10">
                        <h4 class="font-bold text-gray-900 mb-4">Siga-nos</h4>
                        <div class="flex space-x-4">
                            <a href="#" c
