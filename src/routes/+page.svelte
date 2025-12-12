<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[#050505] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-primary"></span>
                        <span class="text-white text-sm font-medium">Google Cloud Powered</span>
                        <span class="text-gray-400 text-sm">Australian Infrastructure</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Premium WordPress hosting. Australian pricing.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Enterprise-grade WordPress hosting powered by Google Cloud infrastructure. Built for Australian businesses who need blazing-fast performance without the enterprise price tag.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Start Free Trial
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            View Pricing
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Performance Metrics -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-sm font-semibold text-gray-700">Performance</div>
                                <div class="h-8 px-3 bg-green-100 rounded text-green-700 text-xs flex items-center justify-center font-bold">99.9% Uptime</div>
                            </div>
                            <div class="space-y-4">
                                <div class="bg-gradient-to-r from-green-50 to-blue-50 p-4 rounded-lg">
                                    <div class="text-xs text-gray-500 mb-1">Page Load Time</div>
                                    <div class="text-2xl font-bold text-gray-900">0.8s</div>
                                </div>
                                <div class="flex gap-2">
                                    <div class="flex-1 h-3 bg-green-400 rounded"></div>
                                    <div class="flex-1 h-3 bg-green-400 rounded"></div>
                                    <div class="flex-1 h-3 bg-green-400 rounded"></div>
                                    <div class="flex-1 h-3 bg-gray-200 rounded"></div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - WordPress Dashboard -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-[#23282d] p-4 flex items-center gap-3">
                                <svg class="w-8 h-8 text-white" viewBox="0 0 24 24" fill="currentColor">
                                    <path d="M12.158,12.786L9.46,20.625c0.806,0.237,1.657,0.366,2.54,0.366c1.047,0,2.051-0.181,2.986-0.511 c-0.024-0.038-0.046-0.079-0.065-0.124L12.158,12.786z M3.009,12c0,3.559,2.068,6.634,5.067,8.092L3.788,8.341 C3.289,9.459,3.009,10.696,3.009,12z M18.069,11.546c0-1.112-0.399-1.881-0.741-2.48c-0.456-0.741-0.883-1.368-0.883-2.109 c0-0.826,0.627-1.596,1.51-1.596c0.04,0,0.078,0.005,0.116,0.007C16.472,3.904,14.34,3.009,12,3.009 c-3.141,0-5.904,1.612-7.512,4.052c0.211,0.007,0.41,0.011,0.579,0.011c0.94,0,2.396-0.114,2.396-0.114 C7.947,6.93,8.004,7.642,7.52,7.699c0,0-0.487,0.057-1.029,0.085l3.274,9.739l1.968-5.901l-1.401-3.838 C9.848,7.756,9.389,7.699,9.389,7.699C8.904,7.67,8.961,6.93,9.446,6.958c0,0,1.484,0.114,2.368,0.114 c0.94,0,2.397-0.114,2.397-0.114c0.485-0.028,0.542,0.684,0.057,0.741c0,0-0.488,0.057-1.029,0.085l3.249,9.665l0.897-2.996 C17.841,13.284,18.069,12.316,18.069,11.546z M19.889,7.686c0.039,0.286,0.06,0.593,0.06,0.924c0,0.912-0.171,1.938-0.684,3.22 l-2.746,7.94c2.673-1.558,4.47-4.454,4.47-7.771C20.991,10.436,20.591,8.967,19.889,7.686z M12,22C6.486,22,2,17.514,2,12 C2,6.486,6.486,2,12,2c5.514,0,10,4.486,10,10C22,17.514,17.514,22,12,22z"/>
                                </svg>
                                <div class="text-white font-semibold">WordPress</div>
                            </div>
                            <div class="p-6 flex-grow space-y-3">
                                <div class="flex items-center gap-2 text-sm">
                                    <div class="w-3 h-3 rounded-full bg-green-500"></div>
                                    <span class="text-gray-600">All systems operational</span>
                                </div>
                                <div class="space-y-2">
                                    <div class="flex justify-between text-xs text-gray-500">
                                        <span>CPU Usage</span>
                                        <span>12%</span>
                                    </div>
                                    <div class="h-2 bg-gray-100 rounded-full overflow-hidden">
                                        <div class="h-full bg-primary w-[12%]"></div>
                                    </div>
                                </div>
                                <div class="space-y-2">
                                    <div class="flex justify-between text-xs text-gray-500">
                                        <span>Memory</span>
                                        <span>2.1 GB / 8 GB</span>
                                    </div>
                                    <div class="h-2 bg-gray-100 rounded-full overflow-hidden">
                                        <div class="h-full bg-blue-500 w-[26%]"></div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 - Security -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-sm font-semibold text-gray-700">Security</div>
                                <div class="h-8 px-3 bg-blue-100 rounded text-blue-700 text-xs flex items-center justify-center font-bold">Protected</div>
                            </div>
                            <div class="space-y-3">
                                <div class="flex items-center gap-3 p-3 bg-gray-50 rounded-lg">
                                    <svg class="w-5 h-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                    <span class="text-sm text-gray-700">SSL Certificate Active</span>
                                </div>
                                <div class="flex items-center gap-3 p-3 bg-gray-50 rounded-lg">
                                    <svg class="w-5 h-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                    <span class="text-sm text-gray-700">Daily Backups</span>
                                </div>
                                <div class="flex items-center gap-3 p-3 bg-gray-50 rounded-lg">
                                    <svg class="w-5 h-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                    <span class="text-sm text-gray-700">DDoS Protection</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by Australian businesses and agencies</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-50 grayscale">
                    <!-- WooCommerce -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <path d="M15,8 Q20,8 22,12 Q24,16 22,20 Q20,24 15,24 L8,24 L8,8 Z M30,8 L38,24 L42,8 L48,8 L48,24 L44,24 L44,12 L40,24 L36,24 L32,12 L32,24 L28,24 L28,8 Z"/>
                    </svg>
                    <!-- Elementor -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <rect x="10" y="8" width="4" height="16"/>
                        <rect x="16" y="8" width="12" height="4"/>
                        <rect x="16" y="14" width="8" height="4"/>
                        <rect x="16" y="20" width="12" height="4"/>
                        <text x="35" y="20" font-size="12" fill="currentColor">ELEMENTOR</text>
                    </svg>
                    <!-- Yoast -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <circle cx="15" cy="16" r="8"/>
                        <text x="28" y="20" font-size="14" font-weight="bold" fill="currentColor">YOAST</text>
                    </svg>
                    <!-- Gravity Forms -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <rect x="8" y="10" width="3" height="12" rx="1"/>
                        <rect x="13" y="8" width="3" height="14" rx="1"/>
                        <rect x="18" y="12" width="3" height="10" rx="1"/>
                        <text x="26" y="20" font-size="11" fill="currentColor">GRAVITY</text>
                    </svg>
                    <!-- ACF -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <text x="10" y="20" font-size="16" font-weight="bold" fill="currentColor">ACF</text>
                    </svg>
                </div>
            </div>
        </section>

        <!-- Google Cloud Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-primary font-mono text-xs tracking-[0.2em] uppercase mb-6">Google Cloud Infrastructure</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Enterprise performance.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Australian pricing.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Performance Card -->
                    <div class="bg-gradient-to-br from-[#4285F4] to-[#1a73e8] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Speed Indicator -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="text-white/60 text-xs uppercase tracking-wider font-medium mb-2">Page Load Speed</div>
                                <div class="text-white text-5xl font-bold mb-4">0.8s</div>
                                <div class="flex gap-1 mb-2">
                                    {#each [100, 85, 70, 55, 40, 25, 10] as height}
                                        <div class="flex-1 bg-white/30 rounded-t" style="height: {height}px"></div>
                                    {/each}
                                </div>
                                <div class="text-white/80 text-xs">Sydney Data Center</div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center text-green-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/></svg>
                                    </div>
                                    99.9% Uptime
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-blue-500/30 flex items-center justify-center text-blue-200">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M5 9V7a5 5 0 0110 0v2a2 2 0 012 2v5a2 2 0 01-2 2H5a2 2 0 01-2-2v-5a2 2 0 012-2zm8-2v2H7V7a3 3 0 016 0z" clip-rule="evenodd"/></svg>
                                    </div>
                                    SSL Included
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Built for Australian businesses.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Your customers expect fast, reliable websites. With Google Cloud's Sydney infrastructure, deliver lightning-fast load times without the enterprise price tag.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Everything You Need</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">WordPress hosting that just works.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">Without the complexity.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        See all features
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                                Lightning Performance
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Automatic Backups</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Security Shield</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Expert Support</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Staging Environment</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">CDN Included</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Lightning Performance" 
                            description="Blazing fast load times. Google Cloud's premium network and Sydney data centers ensure your WordPress site loads in under a second for Australian visitors."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Automatic Backups" 
                            description="Sleep soundly at night. Daily automated backups with one-click restore mean your site is always protected, no manual work required."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Security Shield" 
                            description="Enterprise-grade protection. Free SSL certificates, DDoS protection, and malware scanning keep your WordPress site secure 24/7."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Expert Support" 
                            description="Real humans, real fast. Australian-based WordPress experts available when you need them, with response times that actually matter."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Staging Environment" 
                            description="Test before you launch. Create perfect copies of your site to test updates, plugins, and changes before pushing to production."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="CDN Included" 
                            description="Global reach, local speed. Built-in content delivery network ensures fast load times for visitors worldwide, not just Australia."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Agency Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-blue-100 to-purple-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-blue-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Built for agencies managing multiple client sites — or businesses running a single mission-critical WordPress site.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        See pricing plans
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by Australian agencies and businesses. See what our customers say.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Testimonial Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-between">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-3 mb-6">
                                    <div class="w-12 h-12 rounded-full bg-[var(--color-primary)] flex items-center justify-center text-white font-bold text-lg">
                                        MD
                                    </div>
                                    <div>
                                        <div class="text-white font-semibold">Melbourne Digital</div>
                                        <div class="text-gray-400 text-sm">WordPress Agency</div>
                                    </div>
                                </div>
                                <h3 class="text-2xl font-bold text-white mb-4 max-w-md leading-relaxed">
                                    "We migrated 50+ client sites to South East Cloud. The speed improvement was immediate, and our clients noticed."
                                </h3>
                                <p class="text-gray-400 text-sm mb-6 max-w-md">
                                    After years with WP Engine, we switched to South East Cloud for the local infrastructure and pricing. Best decision we've made.
                                </p>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="flex items-center gap-3 mb-4">
                                        <div class="w-10 h-10 rounded-full bg-blue-500 flex items-center justify-center text-white font-bold">
                                            SC
                                        </div>
                                        <div>
                                            <div class="text-white font-semibold text-sm">Sydney Cafe Co</div>
                                            <div class="text-gray-400 text-xs">E-commerce</div>
                                        </div>
                                    </div>
                                    <p class="text-white text-sm leading-relaxed">
                                        "Our WooCommerce store has never been faster. Support team is incredible."
                                    </p>
                                </div>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors ml-auto">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-green-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="flex items-center gap-3 mb-4">
                                        <div class="w-10 h-10 rounded-full bg-green-500 flex items-center justify-center text-white font-bold">
                                            BW
                                        </div>
                                        <div>
                                            <div class="text-white font-semibold text-sm">Brisbane Web</div>
                                            <div class="text-gray-400 text-xs">Development Studio</div>
                                        </div>
                                    </div>
                                    <p class="text-white text-sm leading-relaxed">
                                        "Finally, enterprise hosting at prices that make sense for Australian businesses."
                                    </p>
                                </div>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors ml-auto">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-primary/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-primary-700/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Launch your WordPress site. <span class="text-primary">In minutes, not hours.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            One-click WordPress installation, automatic updates, and expert support. Everything you need to get online fast.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                            Start Free Trial
                            <kbd class="bg-black/30 px-1.5 py-0.5 rounded text-xs text-gray-400 font-mono">14 days</kbd>
                        </div>
                    </div>
                </div>

                <!-- Integrations -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        WooCommerce. Elementor. Gravity Forms.<br>
                        <span class="text-gray-400">All your favorite WordPress<br>plugins work perfectly.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        See compatible plugins
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['WooCommerce', 'Elementor', 'Yoast SEO', 'ACF', 'Gravity Forms', 'WPForms', 'Jetpack', 'Contact Form 7'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-semibold text-lg tracking-wide">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">WordPress tips and hosting insights.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-blue-100 to-purple-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <svg class="w-24 h-24 text-blue-600 opacity-50" viewBox="0 0 24 24" fill="currentColor">
                                    <path d="M12.158,12.786L9.46,20.625c0.806,0.237,1.657,0.366,2.54,0.366c1.047,0,2.051-0.181,2.986-0.511 c-0.024-0.038-0.046-0.079-0.065-0.124L12.158,12.786z M3.009,12c0,3.559,2.068,6.634,5.067,8.092L3.788,8.341 C3.289,9.459,3.009,10.696,3.009,12z M18.069,11.546c0-1.112-0.399-1.881-0.741-2.48c-0.456-0.741-0.883-1.368-0.883-2.109 c0-0.826,0.627-1.596,1.51-1.596c0.04,0,0.078,0.005,0.116,0.007C16.472,3.904,14.34,3.009,12,3.009 c-3.141,0-5.904,1.612-7.512,4.052c0.211,0.007,0.41,0.011,0.579,0.011c0.94,0,2.396-0.114,2.396-0.114 C7.947,6.93,8.004,7.642,7.52,7.699c0,0-0.487,0.057-1.029,0.085l3.274,9.739l1.968-5.901l-1.401-3.838 C9.848,7.756,9.389,7.699,9.389,7.699C8.904,7.67,8.961,6.93,9.446,6.958c0,0,1.484,0.114,2.368,0.114 c0.94,0,2.397-0.114,2.397-0.114c0.485-0.028,0.542,0.684,0.057,0.741c0,0-0.488,0.057-1.029,0.085l3.249,9.665l0.897-2.996 C17.841,13.284,18.069,12.316,18.069,11.546z M19.889,7.686c0.039,0.286,0.06,0.593,0.06,0.924c0,0.912-0.171,1.938-0.684,3.22 l-2.746,7.94c2.673-1.558,4.47-4.454,4.47-7.771C20.991,10.436,20.591,8.967,19.889,7.686z M12,22C6.486,22,2,17.514,2,12 C2,6.486,6.486,2,12,2c5.514,0,10,4.486,10,10C22,17.514,17.514,22,12,22z"/>
                                </svg>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Performance Guide</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-blue-600 transition-colors">How to speed up your WordPress site in 2024</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-primary/20 to-primary/10 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-primary/60 blur-xl opacity-80"></div>
                                    <div class="w-20 h-20 rounded-full bg-primary/80 blur-xl opacity-80"></div>
                                    <div class="w-12 h-12 rounded-full bg-primary-600/60 blur-xl opacity-80"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Hosting Guide</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-primary transition-colors">Why Australian businesses need local WordPress hosting</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

