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
