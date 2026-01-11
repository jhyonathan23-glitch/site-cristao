<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuando Dios Calla | eBook Espiritual</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
    <!-- Lucide Icons CDN -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .font-serif {
            font-family: 'Playfair Display', serif;
        }
        .bg-spiritual {
            background: linear-gradient(rgba(255, 255, 255, 0.9), rgba(255, 255, 255, 0.9)), url('https://images.unsplash.com/photo-1519681393784-d120267933ba?auto=format&fit=crop&q=80&w=2000');
            background-size: cover;
            background-attachment: fixed;
        }
        .bg-marble {
            background-color: #fcfcf9;
            background-image: radial-gradient(circle at 2px 2px, rgba(212, 175, 55, 0.05) 1px, transparent 0);
            background-size: 40px 40px;
        }
        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-out;
        }
        .faq-item.active .faq-answer {
            max-height: 500px;
        }
        .faq-item.active .chevron-icon {
            transform: rotate(180deg);
        }
        .chevron-icon {
            transition: transform 0.3s ease;
        }
        .btn-gold {
            background-color: #d4af37;
            transition: all 0.3s ease;
        }
        .btn-gold:hover {
            background-color: #c19b2e;
            transform: scale(1.05);
        }
        .btn-gold:active {
            transform: scale(0.95);
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fadeIn {
            animation: fadeIn 0.4s ease-out forwards;
        }
    </style>
</head>
<body class="bg-marble text-slate-800 antialiased selection:bg-[#d4af37]/30">

    <!-- Header -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md border-b border-white/20">
        <div class="max-w-6xl mx-auto px-4 h-16 flex items-center justify-between">
            <div class="font-serif italic font-bold text-xl text-slate-900">Cuando Dios Calla</div>
            <div class="flex gap-4 items-center">
                <button onclick="document.getElementById('testimonios').scrollIntoView()" class="hidden md:block text-slate-600 hover:text-[#d4af37] font-medium transition">
                    Testimonios
                </button>
                <button onclick="document.getElementById('pricing').scrollIntoView()" class="btn-gold text-white font-bold py-2 px-6 rounded-full text-sm shadow-lg flex items-center justify-center gap-2">
                    Acceder Ahora
                </button>
            </div>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="relative min-h-screen flex items-center justify-center pt-20 pb-16 px-4 bg-spiritual overflow-hidden">
            <div class="absolute inset-0 bg-gradient-to-b from-white/30 to-white/90 z-0"></div>
            <div class="relative z-10 max-w-5xl mx-auto text-center">
                <h1 class="text-4xl md:text-6xl font-serif font-bold text-slate-900 leading-tight mb-6">
                    ¿Por qué Dios guarda silencio cuando más lo necesitas?
                </h1>
                <p class="text-xl md:text-2xl text-slate-700 mb-10 max-w-3xl mx-auto font-light">
                    Este libro revela, con base bíblica, por qué el silencio de Dios no es abandono, sino parte del proceso espiritual.
                </p>
                
                <div class="flex justify-center mb-12">
                    <div class="relative group">
                        <div class="absolute -inset-1 bg-gradient-to-r from-[#d4af37] to-[#f3e5ab] rounded-lg blur opacity-25 group-hover:opacity-50 transition duration-1000"></div>
                        <img 
                          src="https://images.unsplash.com/photo-1544947950-fa07a98d237f?auto=format&fit=crop&q=80&w=800" 
                          alt="Ebook Mockup Bundle" 
                          class="relative rounded-lg shadow-2xl w-full max-w-md md:max-w-xl border-4 border-white"
                        />
                    </div>
                </div>

                <button onclick="document.getElementById('pricing').scrollIntoView()" class="btn-gold mx-auto text-white font-bold py-4 px-8 rounded-full shadow-lg flex items-center justify-center gap-2">
                    👉 Acceder ahora por solo $9,90
                </button>
            </div>
        </section>

        <!-- Symptoms Section -->
        <section class="py-20 px-4 bg-white">
            <div class="max-w-5xl mx-auto">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-serif font-bold mb-4 text-slate-800">Identifica tu proceso</h2>
                    <p class="text-lg max-w-2xl mx-auto text-slate-600">Si esto te está pasando, este libro es para ti:</p>
                </div>
                
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="bg-white p-8 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition-shadow">
                        <h3 class="text-xl font-bold mb-3 text-slate-800">Oras, pero no sientes respuestas</h3>
                        <p class="text-slate-600 leading-relaxed">Tus oraciones parecen no llegar a ningún lugar, y te preguntas si alguien está escuchando.</p>
                    </div>
                    <div class="bg-white p-8 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition-shadow">
                        <h3 class="text-xl font-bold mb-3 text-slate-800">Te preguntas si hiciste algo mal</h3>
                        <p class="text-slate-600 leading-relaxed">La culpa y la duda te hacen cuestionar cada paso que has dado en tu camino de fe.</p>
                    </div>
                    <div class="bg-white p-8 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition-shadow">
                        <h3 class="text-xl font-bold mb-3 text-slate-800">Sigues creyendo, aunque estés cansado</h3>
                        <p class="text-slate-600 leading-relaxed">Tu fe permanece, pero el cansancio espiritual es real y profundo.</p>
                    </div>
                    <div class="bg-white p-8 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition-shadow">
                        <h3 class="text-xl font-bold mb-3 text-slate-800">Sientes que Dios está lejos... pero no te rindes</h3>
                        <p class="text-slate-600 leading-relaxed">A pesar de la distancia que percibes, algo dentro de ti se niega a abandonar.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Core Message Section -->
        <section class="relative py-24 overflow-hidden">
            <div class="absolute inset-0 z-0">
                <img 
                  src="https://images.unsplash.com/photo-1504052434569-70ad5836ab65?auto=format&fit=crop&q=80&w=2000" 
                  class="w-full h-full object-cover grayscale opacity-10" 
                  alt="Background Bible" 
                />
            </div>
            <div class="relative z-10 max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-4xl md:text-5xl font-serif font-bold text-slate-900 leading-tight mb-6">
                        El silencio de <br/><span class="text-[#d4af37]">Dios también habla</span>
                    </h2>
                </div>
                <div class="text-lg text-slate-700 space-y-4">
                    <p>En la Biblia, muchos hombres y mujeres de fe pasaron por períodos de silencio antes de grandes transformaciones.</p>
                    <p class="font-semibold text-slate-900">Este libro te guía a comprender ese momento con claridad, paz y dirección espiritual.</p>
                </div>
            </div>
        </section>

        <!-- Benefits Section -->
        <section class="py-20 px-4 bg-slate-50">
            <div class="max-w-6xl mx-auto">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-serif font-bold mb-4 text-slate-800">Dentro de este libro descubrirás:</h2>
                </div>
                <div class="grid md:grid-cols-3 gap-6 mb-8">
                    <div class="bg-white p-8 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition-shadow flex flex-col items-center text-center">
                        <div class="mb-4 p-3 bg-yellow-50 rounded-full"><i data-lucide="calendar" class="text-[#d4af37]"></i></div>
                        <h3 class="text-xl font-bold mb-3">Por qué Dios guarda silencio</h3>
                        <p class="text-slate-600">Comprende las razones espirituales detrás del silencio divino y su propósito en tu vida.</p>
                    </div>
                    <div class="bg-white p-8 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition-shadow flex flex-col items-center text-center">
                        <div class="mb-4 p-3 bg-yellow-50 rounded-full"><i data-lucide="zap" class="text-[#d4af37]"></i></div>
                        <h3 class="text-xl font-bold mb-3">Qué hacer espiritualmente</h3>
                        <p class="text-slate-600">Acciones prácticas y espirituales para mantenerte firme durante la espera.</p>
                    </div>
                    <div class="bg-white p-8 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition-shadow flex flex-col items-center text-center">
                        <div class="mb-4 p-3 bg-yellow-50 rounded-full"><i data-lucide="heart" class="text-[#d4af37]"></i></div>
                        <h3 class="text-xl font-bold mb-3">Cómo fortalecer tu fe</h3>
                        <p class="text-slate-600">Herramientas bíblicas para cultivar una fe resiliente incluso en los momentos más difíciles.</p>
                    </div>
                </div>
                <div class="bg-white p-8 rounded-xl border border-slate-100 shadow-sm flex flex-col md:flex-row items-center gap-6 text-center md:text-left transition-shadow hover:shadow-md">
                    <div class="p-3 bg-yellow-50 rounded-full"><i data-lucide="lightbulb" class="text-[#d4af37]"></i></div>
                    <div>
                        <h3 class="text-xl font-bold mb-2">Reflexiones bíblicas claras y prácticas</h3>
                        <p class="text-slate-600">Enseñanzas directas que puedes aplicar inmediatamente en tu caminar espiritual.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Pricing Section -->
        <section id="pricing" class="py-20 px-4">
            <div class="max-w-4xl mx-auto bg-white rounded-3xl shadow-xl overflow-hidden border border-slate-100">
                <div class="p-8 md:p-12 text-center flex flex-col items-center">
                    <div class="inline-block px-6 py-2 bg-yellow-100 text-[#d4af37] font-serif font-bold rounded-full text-2xl mb-8 uppercase tracking-widest shadow-sm">
                        Libro digital (PDF)
                    </div>
                    
                    <div class="flex justify-center mb-10">
                        <img 
                          src="https://images.unsplash.com/photo-1544947950-fa07a98d237f?auto=format&fit=crop&q=80&w=800" 
                          alt="Device Mockup Bundle" 
                          class="w-full max-w-md shadow-2xl rounded-lg"
                        />
                    </div>

                    <h3 class="text-2xl font-bold mb-2">Acceso inmediato</h3>
                    <p class="text-slate-500 mb-8 italic">Lectura sencilla y profunda en cualquier lugar</p>
                    
                    <div class="h-px bg-slate-100 w-full mb-8"></div>
                    
                    <div class="mb-10 flex flex-col items-center">
                        <span class="text-red-600 line-through text-3xl font-bold mb-2 drop-shadow-sm">$29,90</span>
                        <span class="text-6xl md:text-7xl font-serif font-bold text-[#d4af37] tracking-tight">SOLO $9,90</span>
                    </div>

                    <button class="btn-gold text-white font-bold py-4 px-20 text-xl rounded-full shadow-2xl flex items-center justify-center gap-2">
                        👉 Quiero entender este proceso ahora
                    </button>
                </div>
            </div>
        </section>

        <!-- Trust Badges Section -->
        <section class="py-16 px-4 bg-white border-y border-slate-50">
            <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-12 text-center">
                <div class="flex flex-col items-center">
                    <i data-lucide="shield-check" class="w-12 h-12 text-[#d4af37] mb-4"></i>
                    <h4 class="font-bold mb-2">Pago seguro</h4>
                    <p class="text-slate-500 text-sm">Tu información está protegida con los más altos estándares de seguridad digital.</p>
                </div>
                <div class="flex flex-col items-center">
                    <i data-lucide="calendar" class="w-12 h-12 text-[#d4af37] mb-4"></i>
                    <h4 class="font-bold mb-2">Acceso inmediato</h4>
                    <p class="text-slate-500 text-sm">Recibe el libro en tu correo electrónico segundos después de completar tu compra.</p>
                </div>
                <div class="flex flex-col items-center">
                    <i data-lucide="smartphone" class="w-12 h-12 text-[#d4af37] mb-4"></i>
                    <h4 class="font-bold mb-2">Compra 100% digital</h4>
                    <p class="text-slate-500 text-sm">Lee en cualquier dispositivo: computadora, tablet o teléfono móvil.</p>
                </div>
            </div>
        </section>

        <!-- Target Audience Section -->
        <section class="py-20 px-4 bg-slate-50">
            <div class="max-w-5xl mx-auto">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-serif font-bold mb-4 text-slate-800">¿Es esto para ti?</h2>
                    <p class="text-lg max-w-2xl mx-auto text-slate-600">Este libro no es para todos. Es para quienes buscan respuestas sinceras.</p>
                </div>
                
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="bg-white p-8 rounded-xl border border-red-50 shadow-sm">
                        <div class="flex items-center gap-3 mb-6 text-red-500">
                            <i data-lucide="user-x" class="w-6 h-6"></i>
                            <h3 class="text-xl font-bold">Este libro NO es para ti si:</h3>
                        </div>
                        <ul class="space-y-4">
                            <li class="flex gap-3 text-slate-600"><span class="text-red-300">•</span> Buscas fórmulas mágicas o respuestas instantáneas</li>
                            <li class="flex gap-3 text-slate-600"><span class="text-red-300">•</span> Quieres teología compleja sin aplicación práctica</li>
                            <li class="flex gap-3 text-slate-600"><span class="text-red-300">•</span> No estás dispuesto a reflexionar profundamente</li>
                        </ul>
                    </div>

                    <div class="bg-white p-8 rounded-xl border border-green-50 shadow-lg">
                        <div class="flex items-center gap-3 mb-6 text-green-600">
                            <i data-lucide="user-check" class="w-6 h-6"></i>
                            <h3 class="text-xl font-bold">Este libro ES para ti si:</h3>
                        </div>
                        <ul class="space-y-4">
                            <li class="flex gap-3 text-slate-600"><span class="text-green-500 font-bold">✓</span> Buscas comprensión bíblica genuina</li>
                            <li class="flex gap-3 text-slate-600"><span class="text-green-500 font-bold">✓</span> Quieres fortalecer tu fe con fundamento</li>
                            <li class="flex gap-3 text-slate-600"><span class="text-green-500 font-bold">✓</span> Necesitas claridad espiritual en este momento</li>
                            <li class="flex gap-3 text-slate-600"><span class="text-green-500 font-bold">✓</span> Estás listo para crecer a través del proceso</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Bonus Section -->
        <section class="py-20 px-4 bg-white">
            <div class="max-w-5xl mx-auto">
                <div class="bg-slate-900 rounded-3xl p-8 md:p-16 text-white relative overflow-hidden">
                    <div class="absolute top-0 right-0 p-4 transform translate-x-1/4 -translate-y-1/4 opacity-10">
                        <i data-lucide="gift" class="w-64 h-64"></i>
                    </div>
                    
                    <div class="relative z-10 text-center">
                        <div class="flex items-center justify-center gap-2 mb-6 text-yellow-400">
                            <i data-lucide="gift" class="w-6 h-6"></i>
                            <span class="font-bold tracking-widest uppercase">BONO EXCLUSIVO</span>
                        </div>
                        
                        <h2 class="text-3xl md:text-5xl font-serif font-bold mb-8 uppercase">
                            SOBREVIVIR AL SILENCIO — 21 DÍAS
                        </h2>
                        
                        <div class="max-w-3xl mx-auto space-y-6 text-slate-300 text-lg mb-10 text-left md:text-center">
                            <p>No es un devocional común. Es un <strong class="text-white">proceso guiado</strong> para cuando orar duele y el silencio de Dios pesa.</p>
                            <p>En 21 días, el foco no es tener más fe, sino <strong class="text-white">no desistir</strong>. Cada día trae una oración y un paso simple para sustentar la fe.</p>
                            <p class="italic text-slate-400">Porque, a veces, la verdadera victoria espiritual no es entender todo de inmediato, sino sobrevivir sin abandonar a Dios.</p>
                        </div>

                        <div class="bg-white/10 p-6 rounded-2xl inline-block border border-white/20">
                            <p class="text-xl">
                                Este material podría venderse por hasta <span class="text-red-400 line-through">$19,90</span>, 
                                pero hoy es <span class="text-green-400 font-bold">Completamente GRATIS</span> para ti.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- FAQ Section -->
        <section class="py-20 px-4 bg-slate-50">
            <div class="max-w-4xl mx-auto">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-serif font-bold mb-4 text-slate-800">Preguntas Frecuentes</h2>
                </div>
                <div class="bg-white rounded-2xl p-6 md:p-10 shadow-sm" id="faq-container">
                    <!-- FAQ Items will be injected by JavaScript -->
                </div>
                <div class="mt-8 text-center text-slate-500">
                    ¿Aún tienes dudas? ¡No dudes en contactar a nuestro equipo de soporte!
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonios" class="py-24 px-4 bg-slate-50">
            <div class="max-w-6xl mx-auto">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-serif font-bold mb-4 text-slate-800">Testimonios de Fe</h2>
                    <p class="text-lg max-w-2xl mx-auto text-slate-600">Miles de personas han encontrado paz y dirección a través de estas enseñanzas.</p>
                </div>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6" id="testimonials-container">
                    <!-- Testimonials will be injected by JavaScript -->
                </div>
                
                <div class="mt-16 text-center">
                    <p class="text-slate-500 mb-8 max-w-xl mx-auto italic">
                        "Su testimonio es la prueba de que el silencio es solo el preámbulo de una gran victoria."
                    </p>
                    <button onclick="document.getElementById('pricing').scrollIntoView()" class="btn-gold mx-auto text-white font-bold py-4 px-8 rounded-full shadow-lg flex items-center justify-center gap-2">
                        Comienza tu transformación hoy
                    </button>
                </div>
            </div>
        </section>

        <!-- Guarantee Section -->
        <section class="py-20 px-4 bg-white">
            <div class="max-w-4xl mx-auto text-center border-2 border-[#d4af37]/20 rounded-3xl p-8 md:p-16 relative">
                <div class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-white px-4">
                    <i data-lucide="shield-check" class="w-16 h-16 text-[#d4af37]"></i>
                </div>
                <h2 class="text-3xl font-serif font-bold mb-6 mt-4">Garantía Incondicional de 7 Días</h2>
                <p class="text-xl text-slate-600 mb-8 italic">Lee con paz. Decide con tranquilidad.</p>
                
                <div class="space-y-6 text-slate-700 text-lg mb-10 text-left">
                    <p>Confiamos tanto en el contenido de este material que ofrecemos una <strong>Garantía Incondicional de 7 días</strong>.</p>
                    <p>👉 Si dentro de 7 días, por cualquier motivo, sientes que este eBook no te fue útil o no te trajo claridad espiritual, basta con solicitar el reembolso.</p>
                    <p>Devolvemos el <span class="bg-yellow-100 font-bold px-2 py-1">100% de tu dinero</span>. Sin preguntas. Sin complicaciones.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-sm">
                    <div class="p-4 bg-slate-50 rounded-xl">
                        <h5 class="font-bold mb-2">1. Solicitud</h5>
                        <p>Dentro de los 7 días posteriores a la compra.</p>
                    </div>
                    <div class="p-4 bg-slate-50 rounded-xl">
                        <h5 class="font-bold mb-2">2. Contacto</h5>
                        <p>Escríbenos al correo de soporte indicado.</p>
                    </div>
                    <div class="p-4 bg-slate-50 rounded-xl">
                        <h5 class="font-bold mb-2">3. Devolución</h5>
                        <p>El valor se devuelve según las reglas de pago.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Final CTA Section -->
        <section class="py-24 px-4 bg-[#fdfaf1] text-center">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-serif font-bold text-green-800 mb-6">No estás solo.</h2>
                <p class="text-2xl text-slate-800 mb-4 font-medium">Y el silencio de Dios no es el final de tu historia.</p>
                <p class="text-lg text-slate-600 mb-10 max-w-2xl mx-auto">
                    Miles de personas han pasado por este mismo proceso y han encontrado que el silencio era parte de su transformation. Ahora es tu momento de comprender y crecer.
                </p>
                <button onclick="document.getElementById('pricing').scrollIntoView()" class="btn-gold mx-auto text-lg px-12 bg-green-700 hover:bg-green-800 text-white font-bold py-4 rounded-full shadow-lg flex items-center justify-center gap-2 max-w-xs">
                    👉 Acceder ahora por $9,90
                </button>
                <div class="mt-8 flex flex-wrap justify-center gap-6 text-slate-500 text-sm">
                    <span class="flex items-center gap-1"><i data-lucide="check-circle-2" class="w-4 h-4"></i> Acceso inmediato</span>
                    <span class="flex items-center gap-1"><i data-lucide="shield-check" class="w-4 h-4"></i> Pago seguro</span>
                    <span class="flex items-center gap-1"><i data-lucide="smartphone" class="w-4 h-4"></i> Formato digital</span>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-white py-16 px-4 border-t border-slate-100">
        <div class="max-w-6xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-12">
                <div>
                    <h4 class="font-bold text-xl mb-6">Contacto & Soporte</h4>
                    <p class="text-slate-500 mb-4">¿Dudas, problemas con acceso o reembolso? Entre en contacto con nosotros:</p>
                    <a href="mailto:soporte@cuandodioscalla.com" class="flex items-center gap-2 text-[#d4af37] font-bold hover:underline">
                        <i data-lucide="mail" class="w-5 h-5"></i> soporte@cuandodioscalla.com
                    </a>
                </div>
                <div>
                    <h4 class="font-bold text-xl mb-6">Seguridad</h4>
                    <div class="space-y-4">
                        <div class="flex items-center gap-3 p-3 border border-slate-100 rounded-lg">
                            <i data-lucide="lock" class="text-green-500 w-5 h-5"></i>
                            <span class="text-sm text-slate-600 font-medium">Compra 100% segura</span>
                        </div>
                        <div class="flex items-center gap-3 p-3 border border-slate-100 rounded-lg">
                            <i data-lucide="zap" class="text-yellow-500 w-5 h-5"></i>
                            <span class="text-sm text-slate-600 font-medium">Acceso inmediato</span>
                        </div>
                    </div>
                </div>
                <div>
                    <h4 class="font-bold text-xl mb-6">Distribución Internacional</h4>
                    <p class="text-slate-500 text-sm">
                        Contenido disponible en español, con acceso liberado para diversos países.
                    </p>
                    <div class="mt-6 flex gap-4 text-xs font-bold text-slate-400 uppercase tracking-widest">
                        <a href="#" class="hover:text-slate-900 transition">Privacidad</a>
                        <a href="#" class="hover:text-slate-900 transition">Términos</a>
                        <a href="#" class="hover:text-slate-900 transition">Reembolso</a>
                    </div>
                </div>
            </div>
            <div class="text-center pt-8 border-t border-slate-50 text-slate-400 text-sm">
                <p>© 2026 – Todos los derechos reservados. La reproducción total o parcial de este material sin autorización está prohibida.</p>
            </div>
        </div>
    </footer>

    <script>
        // FAQ Data based on App.tsx
        const faqs = [
            { q: "¿Cómo voy a recibir el eBook después de la compra?", a: "Tan pronto como se confirme el pago, recibirás inmediatamente un correo electrónico con el enlace de acceso para descargar el eBook en PDF. Podrás leerlo en el celular, tablet o computadora, donde estés. Nada físico será enviado. Es rápido, práctico y seguro." },
            { q: "¿El acceso es inmediato?", a: "Sí. En la mayoría de los casos, el acceso se libera en pocos minutos después del pago. Si el pago es con tarjeta, generalmente es instantáneo." },
            { q: "¿Puedo comprar aunque viva en México, Colombia o Paraguay?", a: "Sí. El eBook fue creado en español y puede ser adquirido desde cualquier país. El pago es internacional y totalmente seguro." },
            { q: "¿En qué formato se entrega el eBook?", a: "El material se entrega en formato PDF, uno de los formatos más usados en el mundo. Puedes: leer offline, imprimir si lo deseas, y guardarlo para releer siempre que lo necesites." },
            { q: "¿Este eBook es realmente cristiano?", a: "Sí. El contenido es 100% cristiano, basado en: principios bíblicos, reflexiones espirituales profundas, y momentos reales de silencio de Dios que todo cristiano enfrenta. No es religión vacía. Es fe práctica para momentos de dolor, espera y confusión espiritual." },
            { q: "¿Este eBook es para mí aunque esté débil en la fe?", a: "Principalmente para ti. Este material fue creado para: quien ora y no siente respuesta, quien ama a Dios pero está cansado, quien siente que el cielo está en silencio. No es para cristianos perfectos. Es para cristianos heridos, confusos y perseverantes." },
            { q: "¿El pago es seguro?", a: "Totalmente seguro. Utilizamos plataformas de pago reconocidas internacionalmente, con encriptación y protección de datos. Tus datos no quedan expuestos." },
            { q: "¿Existe garantía?", a: "Sí. Si por cualquier motivo sientes que el contenido no te habló, puedes solicitar el reembolso dentro del plazo informado en la plataforma de pago (7 días). La fe no se fuerza. La claridad se entrega." },
            { q: "¿Este eBook puede realmente ayudarme espiritualmente?", a: "No sustituye a Dios. Pero puede ayudarte a entender el silencio, fortalecer tu fe y continuar caminando sin desistir. A veces, Dios no está en silencio. Él está trabajando en lo invisible." }
        ];

        // Testimonials Data based on App.tsx
        const testimonials = [
            {
                name: "Elena Rodríguez",
                role: "Líder de Jóvenes",
                image: "https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&q=80&w=200&h=200",
                content: "Pasé meses sintiendo que mis oraciones rebotaban en el techo. Este libro me enseñó que el silencio de Dios no es ausencia, sino una invitación a profundizar. Mi fe ha madurado de una forma que nunca imaginé.",
                rating: 5
            },
            {
                name: "Mateo Salazar",
                role: "Padre de Familia",
                image: "https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&q=80&w=200&h=200",
                content: "Después de perder mi empleo, el silencio divino me aterraba. 'Cuando Dios Calla' fue la guía bíblica que necesitaba para entender que Dios estaba trabajando en lo invisible mientras yo esperaba.",
                rating: 5
            },
            {
                name: "Lucía Méndez",
                role: "Misionera",
                image: "https://images.unsplash.com/photo-1438761681033-6461ffad8d80?auto=format&fit=crop&q=80&w=200&h=200",
                content: "Es un material esencial para todo cristiano. Me ayudó a sanar la frustración de no recibir respuestas inmediatas y a cultivar una paz que sobrepasa todo entendimiento en los momentos de desierto.",
                rating: 5
            },
            {
                name: "Javier Espinoza",
                role: "Estudiante de Teología",
                image: "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&q=80&w=200&h=200",
                content: "Lo que más me gustó fue el fundamento bíblico. No son solo palabras de aliento, sino una explicación profunda de cómo Dios se comunica a través del silencio. Transformó mi manera de orar.",
                rating: 5
            }
        ];

        // Render FAQ
        const faqContainer = document.getElementById('faq-container');
        faqContainer.innerHTML = faqs.map((faq, index) => `
            <div class="faq-item border-b border-slate-100 py-4">
                <button 
                    class="w-full flex justify-between items-center text-left py-2 hover:text-[#d4af37] transition"
                    onclick="toggleFaq(${index})"
                >
                    <span class="font-bold text-lg">${faq.q}</span>
                    <i data-lucide="chevron-down" class="w-5 h-5 chevron-icon"></i>
                </button>
                <div class="faq-answer text-slate-600 leading-relaxed animate-fadeIn">
                    <div class="pb-4 mt-2">
                        ${faq.a}
                    </div>
                </div>
            </div>
        `).join('');

        // Render Testimonials
        const testimonialsContainer = document.getElementById('testimonials-container');
        testimonialsContainer.innerHTML = testimonials.map(t => `
            <div class="bg-white p-8 rounded-2xl border border-slate-100 shadow-sm flex flex-col items-center text-center relative hover:border-[#d4af37]/50 transition-colors group">
                <div class="absolute top-4 right-4 text-[#d4af37]/20 group-hover:text-[#d4af37]/40 transition-colors">
                    <i data-lucide="quote" class="w-8 h-8 fill-current"></i>
                </div>
                
                <img 
                    src="${t.image}" 
                    alt="${t.name}" 
                    class="w-20 h-20 rounded-full object-cover mb-4 border-2 border-slate-50 p-1 bg-white shadow-sm"
                />
                
                <div class="flex gap-1 mb-4">
                    ${Array(t.rating).fill('<i data-lucide="star" class="w-4 h-4 fill-[#d4af37] text-[#d4af37]"></i>').join('')}
                </div>
                
                <p class="text-slate-600 italic mb-6 text-sm leading-relaxed">
                    "${t.content}"
                </p>
                
                <div class="mt-auto">
                    <h4 class="font-serif font-bold text-slate-900">${t.name}</h4>
                    <p class="text-xs text-[#d4af37] font-bold uppercase tracking-wider">${t.role}</p>
                </div>
            </div>
        `).join('');

        // Initialize Icons
        lucide.createIcons();

        // FAQ Toggle Function
        window.toggleFaq = function(index) {
            const items = document.querySelectorAll('.faq-item');
            const target = items[index];
            const isActive = target.classList.contains('active');
            
            // Close all others
            items.forEach(item => item.classList.remove('active'));
            
            // Toggle target
            if (!isActive) {
                target.classList.add('active');
            }
        };
    </script>
</body>
</html>
