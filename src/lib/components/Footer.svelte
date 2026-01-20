<script>
    // Footer component
</script>

<footer class="bg-brand-dark text-white pt-32 pb-12 overflow-hidden relative font-sans">
    <div class="max-w-7xl mx-auto px-4 relative z-10">
        <div class="text-center mb-24">
             <span class="text-[10px] font-bold uppercase tracking-widest border border-white/20 px-3 py-1.5 rounded-full mb-8 inline-block">Strategy Sessions</span>
             <h2 class="text-5xl md:text-7xl font-serif-display mb-6">Get in leader,<br/> we're driving growth.</h2>
             <p class="text-gray-400 mb-10 max-w-lg mx-auto text-sm">Work directly with our expert team to create your AI visibility gameplan and automate your operations.</p>
             
             <div class="flex flex-col sm:flex-row justify-center gap-2 max-w-md mx-auto">
                 <input type="email" placeholder="Enter your work email" class="bg-white/5 border border-white/10 rounded-lg px-4 py-3 w-full text-white placeholder-gray-500 focus:outline-none focus:border-brand-green transition-colors" />
                 <button class="bg-brand-green hover:bg-brand-green-hover text-gray-900 px-6 py-3 rounded-lg font-bold whitespace-nowrap transition-colors flex items-center justify-center">
                     Book a Call
                     <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                 </button>
             </div>
        </div>

        <div class="grid md:grid-cols-4 gap-12 border-t border-white/10 pt-16">
            <div>
                <h3 class="font-bold mb-6">Frequently Asked Questions</h3>
            </div>
            <div class="md:col-span-3 space-y-6">
                {#each ['How is Speedrun different from a traditional SEO agency?', 'What is GEO and why does my business need it?', 'How long does a typical automation project take?', 'Do you provide ongoing support after delivery?', 'How does the 50/50 pricing structure work?'] as q}
                <div class="border-b border-white/10 pb-6 flex justify-between items-center cursor-pointer group">
                    <span class="text-lg font-light group-hover:text-primary-400 transition-colors">{q}</span>
                    <span class="text-2xl font-light">+</span>
                </div>
                {/each}
            </div>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-8 mt-24 text-sm text-gray-400">
            <div>
                <h4 class="text-white font-bold mb-4">Services</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">GEO Audits</a></li>
                    <li><a href="#" class="hover:text-white">n8n Automation</a></li>
                    <li><a href="#" class="hover:text-white">Workflow Design</a></li>
                    <li><a href="#" class="hover:text-white">AI Strategy</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">Markets</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Singapore</a></li>
                    <li><a href="#" class="hover:text-white">Philippines</a></li>
                    <li><a href="#" class="hover:text-white">Malaysia</a></li>
                    <li><a href="#" class="hover:text-white">Indonesia</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">Company</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">About Us</a></li>
                    <li><a href="#" class="hover:text-white">Speed Stories</a></li>
                    <li><a href="#" class="hover:text-white">Pricing</a></li>
                    <li><a href="#" class="hover:text-white">Contact</a></li>
                </ul>
            </div>
        </div>
        
        <div class="mt-32 text-center relative">
             <h1 class="text-[12rem] md:text-[16rem] font-bold tracking-tighter leading-none text-white select-none">speedrun</h1>
             <div class="absolute bottom-4 right-0 flex gap-4 text-[10px] text-gray-500 uppercase tracking-widest">
                 <a href="#">Privacy Policy</a>
                 <a href="#">Terms</a>
                 <a href="#">Contact</a>
             </div>
        </div>
    </div>
</footer>
