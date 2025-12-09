<script>
    // Hero.svelte
    // Use Svelte for the hero to easily add future interactivity (e.g., animations)
</script>

<!-- HERO SECTION (Asymmetrical Grid) -->
<section class="grid grid-cols-1 md:grid-cols-12 min-h-[400px]">

    <!-- Orange Accent Block (Bauhaus Geometry) -->
    <div class="hidden md:block md:col-span-1 bg-bauhaus b-border-r flex flex-col justify-end pb-8 items-center">
        <div class="text-white writing-vertical text-xs font-mono tracking-widest transform -rotate-180"
            style="writing-mode: vertical-rl;">EST. 2025</div>
    </div>

    <!-- Content Block -->
    <div class="col-span-1 md:col-span-7 p-8 md:p-16 flex flex-col justify-center items-start">
        <span class="inline-block px-3 py-1 mb-6 text-xs font-bold tracking-widest uppercase border border-dark bg-offwhite shadow-[4px_4px_0px_0px_rgba(230,88,25,1)]">
            Full-Stack Developer
        </span>
        <p class="text-lg md:text-2xl leading-relaxed font-medium max-w-prose">
            <span class="text-bauhaus font-bold">Hey! I’m Ivan.</span><br>
            Full-stack dev who loves backend, frontend, security, and fintech. Currently leveling up from
            coder to builder.
        </p>
        <div class="mt-8 pt-8 border-t-2 border-dashed border-gray-300 w-full">
            <p class="text-gray-600">
                When I’m not shipping code, I’m either deep in a video game or messing around with my own
                game-dev projects.
            </p>
        </div>
    </div>

    <!-- Geometric Decorative Block / Contact CTA -->
    <div class="col-span-1 md:col-span-4 bg-dark text-offwhite flex flex-col justify-between p-8 md:b-border-l relative overflow-hidden">
        <!-- Decorative Geometric Shape -->
        <div class="absolute -top-12 -right-12 w-32 h-32 rounded-full border-4 border-bauhaus opacity-20">
        </div>
        <div class="absolute top-20 right-10 w-16 h-16 bg-offwhite opacity-10 rotate-45"></div>

        <div class="w-12 h-12 rounded-full bg-bauhaus mb-8 relative z-10"></div>

        <div class="space-y-6 relative z-10">
            <p class="text-xs font-mono text-bauhaus uppercase tracking-widest border-b border-gray-700 pb-2">
                Social Protocol</p>
            <ul class="space-y-4 text-lg">
                <li><a href="https://github.com/Nawy" target="_blank"
                        class="hover:text-bauhaus hover:translate-x-2 transition-all block">Github</a></li>
                <li><a href="https://linkedin.com/in/iermolaev" target="_blank"
                        class="hover:text-bauhaus hover:translate-x-2 transition-all block">LinkedIn</a>
                </li>
                <li><a href="https://twitter.com" target="_blank"
                        class="hover:text-bauhaus hover:translate-x-2 transition-all block">Twitter / X</a>
                </li>
                <li><a href="https://www.youtube.com/@ivan_ermolaev" target="_blank"
                        class="hover:text-bauhaus hover:translate-x-2 transition-all block">YouTube</a></li>
            </ul>
        </div>
    </div>
</section>
