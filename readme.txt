You can just take some pictures off our fb page and put them on the website if possible
add navbar link to ligth em up
add this into the clearview main page:   <!-- Cross-Promotion Section (Light em up MTL) -->
    <section class="py-16 bg-gray-900 relative overflow-hidden border-y border-brand-500/30">
        <!-- Background Pattern / Glow -->
        <div class="absolute inset-0 opacity-10">
            <svg class="h-full w-full" xmlns="http://www.w3.org/2000/svg">
                <defs>
                    <pattern id="grid-pattern-dark" width="40" height="40" patternUnits="userSpaceOnUse">
                        <path d="M0 40L40 0H20L0 20M40 40V20L20 40" stroke="#f59e0b" stroke-width="2" fill="none"/>
                    </pattern>
                </defs>
                <rect width="100%" height="100%" fill="url(#grid-pattern-dark)"/>
            </svg>
        </div>
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[800px] h-[400px] bg-lightem-500/20 rounded-full blur-[100px] pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 flex flex-col md:flex-row items-center justify-between gap-10">
            <div class="text-center md:text-left">
                <div class="inline-flex items-center gap-2 text-lightem-500 font-bold tracking-widest uppercase text-sm mb-3">
                    <i class="ph-fill ph-sparkle"></i> 
                    <span class="en">Sister Company</span><span class="fr">Compagnie Sœur</span>
                </div>
                <h3 class="text-3xl md:text-4xl font-extrabold text-white mb-4">
                    <span class="en">Looking for Custom Exterior Lighting?</span>
                    <span class="fr">Besoin d'Éclairage Extérieur Sur Mesure?</span>
                </h3>
                <p class="text-gray-300 text-lg max-w-2xl">
                    <span class="en">Transform your home at night with <strong>Light 'em up MTL</strong>. We specialize in professional holiday lighting, permanent architectural LEDs, and beautiful landscape lighting.</span>
                    <span class="fr">Transformez votre maison la nuit avec <strong>Light 'em up MTL</strong>. Nous sommes spécialisés dans l'éclairage des fêtes professionnel, les LED architecturales permanentes et l'éclairage paysager.</span>
                </p>
            </div>
            
            <div class="flex-shrink-0">
                <a href="lightemup.html" class="inline-flex items-center gap-3 py-4 px-8 bg-lightem-500 text-white font-bold rounded-xl hover:bg-lightem-600 transition-all duration-300 shadow-[0_0_20px_rgba(245,158,11,0.4)] hover:-translate-y-1">
                    <span class="en">Visit Light 'em up MTL</span><span class="fr">Visiter Light 'em up MTL</span>
                    <i class="ph-bold ph-arrow-up-right text-xl"></i>
                </a>
            </div>
        </div>
    </section>

add this into the inex page as well as it's a gallery

 <!-- Visual Gallery Divider -->
    <section id="gallery" class="py-20 border-y border-dark-border bg-dark-card relative overflow-hidden">
        <!-- Abstract glowing orbs -->
        <div class="absolute top-0 right-0 w-64 h-64 bg-brand-600 rounded-full mix-blend-screen filter blur-[100px] opacity-10"></div>
        <div class="absolute bottom-0 left-0 w-64 h-64 bg-brand-500 rounded-full mix-blend-screen filter blur-[100px] opacity-10"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-end mb-10">
                <div>
                    <h2 class="text-brand-500 font-bold tracking-widest uppercase text-sm mb-2">
                        <span class="en">Our Work</span><span class="fr">Notre Travail</span>
                    </h2>
                    <h3 class="text-3xl md:text-4xl font-serif text-white">
                        <span class="en">Recent Installations</span><span class="fr">Installations Récentes</span>
                    </h3>
                </div>
                <a href="#contact" class="hidden md:flex items-center gap-2 text-brand-400 hover:text-brand-300 font-bold transition-colors">
                    <span class="en">Ready to light up your home?</span><span class="fr">Prêt à illuminer votre maison?</span>
                    <i class="ph-bold ph-arrow-right"></i>
                </a>
            </div>

            <!-- CSS Grid Gallery -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 md:gap-6">
                <div class="col-span-2 md:col-span-2 row-span-2 rounded-2xl overflow-hidden group relative">
                    <img src="https://images.unsplash.com/photo-1576692155415-95f820a3c2ce?q=80&w=1000&auto=format&fit=crop" alt="Holiday House Lighting" class="w-full h-full object-cover aspect-square md:aspect-auto md:h-[500px] transform group-hover:scale-105 transition-transform duration-700">
                    <div class="absolute inset-0 bg-gradient-to-t from-dark-bg/90 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                        <span class="text-white font-bold text-lg"><span class="en">Custom Holiday Design</span><span class="fr">Design Fêtes sur Mesure</span></span>
                    </div>
                </div>
                <div class="col-span-1 rounded-2xl overflow-hidden group relative">
                    <img src="https://images.unsplash.com/photo-1543854589-497641258672?q=80&w=800&auto=format&fit=crop" alt="Landscape Lighting" class="w-full h-full object-cover aspect-square transform group-hover:scale-105 transition-transform duration-700">
                </div>
                <div class="col-span-1 rounded-2xl overflow-hidden group relative">
                    <img src="https://images.unsplash.com/photo-1605810731174-8b63483df2ea?q=80&w=800&auto=format&fit=crop" alt="Pathway Lights" class="w-full h-full object-cover aspect-square transform group-hover:scale-105 transition-transform duration-700">
                </div>
                <div class="col-span-2 md:col-span-2 rounded-2xl overflow-hidden group relative">
                    <img src="https://images.unsplash.com/photo-1513201099705-a9746e1e201f?q=80&w=1000&auto=format&fit=crop" alt="Permanent Architectural Lighting" class="w-full h-full object-cover aspect-[2/1] transform group-hover:scale-105 transition-transform duration-700">
                    <div class="absolute inset-0 bg-gradient-to-t from-dark-bg/90 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                        <span class="text-white font-bold text-lg"><span class="en">Architectural Accents</span><span class="fr">Accents Architecturaux</span></span>
                    </div>
                </div>
            </div>
        </div>
    </section>
