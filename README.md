<!DOCTYPE html>
<html lang="hi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AQUELIO™ | Ultra-Premium Aravalli Mineral Water</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Luxury Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700;900&family=Plus+Jakarta+Sans:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    
    <style>
        .font-royal { font-family: 'Cinzel', serif; }
        .font-body { font-family: 'Plus Jakarta Sans', sans-serif; }
        
        /* Custom Background Overlay Gradient */
        .hero-bg {
            background: linear-gradient(180deg, rgba(3, 10, 26, 0.75) 0%, rgba(5, 19, 43, 0.85) 60%, rgba(3, 10, 26, 0.98) 100%),
                        url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1920&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .story-bg {
            background: linear-gradient(135deg, rgba(15, 23, 42, 0.92) 0%, rgba(30, 27, 75, 0.88) 100%),
                        url('https://images.unsplash.com/photo-1599661046827-dacff0c0f09a?q=80&w=1920&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .customize-bg {
            background: linear-gradient(180deg, rgba(2, 6, 23, 0.9) 0%, rgba(15, 23, 42, 0.95) 100%),
                        url('https://images.unsplash.com/photo-1519741497674-611481863552?q=80&w=1920&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
        }

        /* Glassmorphism Cards */
        .glass-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(220, 175, 90, 0.25);
        }

        .glass-card-hover:hover {
            background: rgba(255, 255, 255, 0.09);
            border-color: rgba(245, 190, 80, 0.7);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.5), 0 0 20px rgba(224, 172, 80, 0.2);
            transform: translateY(-5px);
        }

        .gold-text-gradient {
            background: linear-gradient(135deg, #fff 0%, #ecd399 50%, #c49a45 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .cyan-glow {
            text-shadow: 0 0 20px rgba(56, 189, 248, 0.6);
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 font-body antialiased selection:bg-amber-500 selection:text-slate-950">

    <!-- Top Luxury Strip -->
    <div class="bg-slate-950 text-amber-300 text-xs py-2.5 px-4 border-b border-amber-500/20">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center text-center gap-2 font-semibold">
            <span class="tracking-widest uppercase text-[11px]"><i class="fa-solid fa-crown text-amber-400 mr-1.5"></i> Rajasthan's Most Royal Packaged Drinking Water</span>
            <div class="flex items-center space-x-6">
                <span class="text-slate-300"><i class="fa-solid fa-phone text-amber-400 mr-1.5"></i> Order Line: <strong class="text-white">+91 9351156730</strong></span>
                <span class="hidden md:inline text-emerald-400"><i class="fa-solid fa-circle text-[8px] mr-1"></i> Live Express Delivery</span>
            </div>
        </div>
    </div>

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-50 bg-slate-950/80 backdrop-blur-xl border-b border-white/10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 py-4 flex items-center justify-between">
            
            <a href="#home" class="flex items-center space-x-3 group">
                <div class="w-11 h-11 bg-gradient-to-tr from-amber-600 via-sky-500 to-amber-300 p-[1px] rounded-2xl shadow-lg shadow-sky-500/10">
                    <div class="w-full h-full bg-slate-950 rounded-2xl flex items-center justify-center">
                        <i class="fa-solid fa-mountain text-amber-400 text-xl group-hover:scale-110 transition"></i>
                    </div>
                </div>
                <div>
                    <span class="text-2xl font-royal font-black tracking-widest text-white block leading-none">AQUELIO<span class="text-amber-400">™</span></span>
                    <span class="text-[9px] text-sky-400 font-bold tracking-[0.25em] uppercase block mt-1">Aravalli Mineral Water</span>
                </div>
            </a>

            <!-- Nav Links -->
            <nav class="hidden md:flex items-center space-x-9 text-xs font-bold tracking-widest uppercase text-slate-300">
                <a href="#home" class="hover:text-amber-400 transition">होम (Home)</a>
                <a href="#story" class="hover:text-amber-400 transition">शाही कहानी (Story)</a>
                <a href="#products" class="hover:text-amber-400 transition">उत्पाद (Products)</a>
                <a href="#customize" class="hover:text-amber-400 transition">Custom Label</a>
                <a href="#contact" class="hover:text-amber-400 transition">संपर्क (Contact)</a>
            </nav>

            <!-- Order Button -->
            <a href="https://wa.me/919351156730?text=Hi%20Aquelio,%20I%20want%20to%20place%20an%20order" target="_blank" 
               class="bg-gradient-to-r from-amber-500 via-amber-400 to-yellow-500 hover:from-amber-400 hover:to-amber-300 text-slate-950 font-black px-6 py-3 rounded-full text-xs shadow-lg shadow-amber-500/20 flex items-center space-x-2 transition transform hover:scale-105 uppercase tracking-wider">
                <i class="fa-brands fa-whatsapp text-base"></i>
                <span>व्हाट्सएप ऑर्डर</span>
            </a>
        </div>
    </header>

    <!-- HERO SECTION WITH HD BACKGROUND -->
    <section id="home" class="hero-bg min-h-screen flex items-center justify-center relative px-4 py-20 overflow-hidden">
        
        <!-- Ambient Glow Elements -->
        <div class="absolute top-1/4 left-10 w-96 h-96 bg-sky-500/10 rounded-full blur-3xl pointer-events-none"></div>
        <div class="absolute bottom-10 right-10 w-96 h-96 bg-amber-500/10 rounded-full blur-3xl pointer-events-none"></div>

        <div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12 items-center relative z-10">
            
            <div class="lg:col-span-7 space-y-8 text-center lg:text-left">
                <div class="inline-flex items-center space-x-2 bg-slate-900/80 border border-amber-400/40 text-amber-300 text-xs font-bold px-5 py-2 rounded-full backdrop-blur-md uppercase tracking-widest shadow-xl">
                    <i class="fa-solid fa-droplet text-sky-400 animate-pulse"></i>
                    <span>अरावली की गहराइयों की शुद्धता</span>
                </div>

                <h1 class="text-4xl sm:text-6xl xl:text-7xl font-royal font-black tracking-tight leading-tight">
                    Purity from Aravallis, <br>
                    <span class="gold-text-gradient">Royalty of Rajasthan</span>
                </h1>

                <p class="text-slate-300 text-base sm:text-lg max-w-2xl leading-relaxed font-light">
                    राजस्थान की वीर धरा और प्राचीन अरावली पर्वतमाला की छांव में तैयार, AQUELIO आपके परिवार और अतिथियों के लिए पेश करता है 100% शुद्ध, मिनरल-युक्त एवं 8-स्तरीय प्यूरीफाइड प्रीमियम ड्रिंकिंग वाटर।
                </p>

                <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-2">
                    <a href="#products" class="bg-gradient-to-r from-amber-500 to-amber-600 hover:from-amber-400 hover:to-amber-500 text-slate-950 font-extrabold px-9 py-4 rounded-2xl shadow-2xl shadow-amber-500/30 transition transform hover:-translate-y-1 text-sm uppercase tracking-wider">
                        उत्पाद देखें (View Range)
                    </a>
                    <a href="#story" class="glass-card hover:bg-white/10 text-white font-bold px-8 py-4 rounded-2xl border border-white/20 transition text-sm uppercase tracking-wider backdrop-blur-md">
                        हमारी कहानी पढ़ें
                    </a>
                </div>

                <!-- Trust Badges -->
                <div class="grid grid-cols-3 gap-4 pt-8 border-t border-white/10">
                    <div class="glass-card p-4 rounded-2xl text-center">
                        <i class="fa-solid fa-shield-halved text-amber-400 text-2xl mb-1"></i>
                        <p class="text-xs font-bold text-slate-200">ISO 9001:2015</p>
                        <p class="text-[10px] text-slate-400">प्रमाणित शुद्धता</p>
                    </div>
                    <div class="glass-card p-4 rounded-2xl text-center">
                        <i class="fa-solid fa-filter text-sky-400 text-2xl mb-1"></i>
                        <p class="text-xs font-bold text-slate-200">8-Stage Purified</p>
                        <p class="text-[10px] text-slate-400">RO + UV + Ozone</p>
                    </div>
                    <div class="glass-card p-4 rounded-2xl text-center">
                        <i class="fa-solid fa-gem text-amber-400 text-2xl mb-1"></i>
                        <p class="text-xs font-bold text-slate-200">100% Minerals</p>
                        <p class="text-[10px] text-slate-400">कैल्शियम & मैग्नीशियम</p>
                    </div>
                </div>
            </div>

            <!-- Visual Showcase Card -->
            <div class="lg:col-span-5">
                <div class="glass-card p-8 sm:p-10 rounded-3xl relative shadow-2xl overflow-hidden border border-amber-500/30">
                    <div class="absolute -right-10 -top-10 w-40 h-40 bg-amber-500/20 rounded-full blur-2xl"></div>
                    
                    <div class="text-center space-y-6">
                        <div class="w-24 h-24 mx-auto bg-gradient-to-tr from-amber-500/20 to-sky-500/20 border border-amber-400/40 rounded-3xl flex items-center justify-center text-amber-400 text-5xl shadow-inner">
                            <i class="fa-solid fa-wine-bottle"></i>
                        </div>

                        <h3 class="text-2xl font-royal font-bold text-white">AQUELIO Pure Gold Standard</h3>
                        <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">
                            हर एक बोतल में सुरक्षित है अरावली का ताज़ा अहसास। बीपीए-फ्री और 100% ऑटोमेटेड हाइजीनिक बॉटलिंग प्रोसेस।
                        </p>

                        <div class="space-y-3 text-left text-xs text-slate-200 bg-slate-950/60 p-4 rounded-2xl border border-white/5">
                            <div class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-emerald-400"></i><span>100% बैक्टीरिया एवं वायरस मुक्त पानी</span></div>
                            <div class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-emerald-400"></i><span>नेचुरल pH बैलेंस (7.5+) सेहत के लिए उत्तम</span></div>
                            <div class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-emerald-400"></i><span>शादियों और सम्मेलनों के लिए विशेष पैकेजिंग</span></div>
                        </div>

                        <a href="https://wa.me/919351156730" target="_blank" class="block w-full bg-emerald-500 hover:bg-emerald-400 text-slate-950 font-black py-3.5 rounded-xl text-xs uppercase tracking-widest transition shadow-lg">
                            <i class="fa-brands fa-whatsapp text-sm mr-2"></i> फोन पर तुरंत ऑर्डर करें
                        </a>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- INSPIRATIONAL STORY SECTION (HINDI & ENGLISH) -->
    <section id="story" class="story-bg py-24 px-4 border-t border-b border-white/10 relative">
        <div class="max-w-6xl mx-auto relative z-10">
            
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-3">
                <span class="text-amber-400 font-extrabold text-xs uppercase tracking-[0.3em] bg-amber-500/10 px-4 py-1.5 rounded-full border border-amber-400/30">
                    The Heritage Story
                </span>
                <h2 class="text-3xl sm:text-5xl font-royal font-extrabold text-white">हमारी प्रेरणा: अरावली और शाही विरासत</h2>
                <div class="w-32 h-1 bg-gradient-to-r from-transparent via-amber-400 to-transparent mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-10">
                
                <!-- Hindi Story Card -->
                <div class="glass-card p-8 sm:p-10 rounded-3xl border border-amber-500/30 space-y-4">
                    <div class="flex items-center justify-between border-b border-white/10 pb-4">
                        <span class="text-amber-400 font-royal font-bold text-lg"><i class="fa-solid fa-feather mr-2"></i> हिंदी संस्करण</span>
                        <span class="text-xs text-slate-400 uppercase tracking-widest">राजस्थान की गौरवगाथा</span>
                    </div>
                    
                    <h3 class="text-xl font-bold text-white leading-snug">अरावली की पावन धरा और राजस्थान का संकल्प</h3>
                    
                    <p class="text-slate-300 text-sm leading-relaxed">
                        राजस्थान की वीर और ऐतिहासिक भूमि, जहाँ हर कण में स्वाभिमान, त्याग और अतिथि सत्कार की महान परंपरा बसती है। इसी पावन धरा की गोद में फैली विश्व की प्राचीनतम <strong>अरावली पर्वतमालाएं (Aravalli Range)</strong> सदियों से कुदरती जल स्रोतों को अपने आंचल में सहेज कर रखती आई हैं। राजस्थान के कठिन मौसम में जल केवल एक प्यास बुझाने का साधन नहीं, बल्कि जीवन, सेहत और सम्मान का प्रतीक माना गया है।
                    </p>
                    
                    <p class="text-slate-300 text-sm leading-relaxed">
                        <strong>AQUELIO</strong> की नींव इसी सोच के साथ रखी गई कि अरावली की गहराइयों की शुद्धता और राजस्थान की शाही मेहमाननवाज़ी को हर घर तक पहुँचाया जाए। हम अत्याधुनिक <strong>8-स्तरीय प्यूरीफिकेशन (RO + UV + Ozonation)</strong> तकनीक और आवश्यक खनिजों के सही संतुलन के साथ पानी तैयार करते हैं। AQUELIO का हर एक घूंट आपको अरावली की ताजगी और राजस्थान के शाही सत्कार का अहसास कराता है।
                    </p>
                </div>

                <!-- English Story Card -->
                <div class="glass-card p-8 sm:p-10 rounded-3xl border border-amber-500/30 space-y-4">
                    <div class="flex items-center justify-between border-b border-white/10 pb-4">
                        <span class="text-amber-400 font-royal font-bold text-lg"><i class="fa-solid fa-globe mr-2"></i> English Story</span>
                        <span class="text-xs text-slate-400 uppercase tracking-widest">Legacy of Royalty</span>
                    </div>

                    <h3 class="text-xl font-bold text-white leading-snug">The Legend of Aravalli & Rajasthani Purity</h3>

                    <p class="text-slate-300 text-sm leading-relaxed">
                        Rajasthan is a land defined by royal heritage, majestic forts, and timeless culture. Standing tall at its core is the ancient <strong>Aravalli Mountain Range</strong>, one of the world's oldest geological wonders, preserving natural water sanctuaries for generations. In the heart of Rajasthan, water is revered not just as a natural resource, but as a sacred symbol of hospitality and pure care.
                    </p>

                    <p class="text-slate-300 text-sm leading-relaxed">
                        Inspired by the untouched purity of the Aravalli hills and the regal spirit of Rajasthan, <strong>AQUELIO</strong> was founded to deliver 100% safe, pristine, and mineral-enriched drinking water. Combining state-of-the-art <strong>8-Stage Ultra-Purification</strong> with essential natural minerals (Calcium & Magnesium), AQUELIO ensures that every drop embodies mountain freshness and royal perfection.
                    </p>
                </div>

            </div>

        </div>
    </section>

    <!-- PRODUCTS SECTION (STRICTLY 4 SIZES - NO DUPLICATES) -->
    <section id="products" class="py-24 px-4 bg-slate-950 relative">
        <div class="max-w-7xl mx-auto">
            
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-3">
                <span class="text-sky-400 font-extrabold text-xs uppercase tracking-[0.3em] bg-sky-500/10 px-4 py-1.5 rounded-full border border-sky-400/30">
                    Premium Product Collection
                </span>
                <h2 class="text-3xl sm:text-5xl font-royal font-extrabold text-white">हमारे उत्पाद (Our Products)</h2>
                <p class="text-slate-400 text-sm">आपकी हर ज़रूरत के लिए 4 सही और प्रीमियम साइज में उपलब्ध</p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                
                <!-- 200 ml -->
                <div class="glass-card glass-card-hover rounded-3xl p-6 transition-all duration-300 flex flex-col justify-between group">
                    <div>
                        <div class="h-44 bg-gradient-to-b from-slate-900 to-slate-950 rounded-2xl flex items-center justify-center text-5xl text-amber-400 mb-6 border border-white/5 shadow-inner group-hover:scale-105 transition">
                            <i class="fa-solid fa-bottle-water"></i>
                        </div>
                        <span class="text-[10px] font-black text-amber-400 bg-amber-500/10 border border-amber-400/30 px-3 py-1 rounded-full uppercase tracking-wider">शादी & इवेंट स्पेशल</span>
                        <h3 class="text-2xl font-royal font-bold text-white mt-4">200 ml Bottle</h3>
                        <p class="text-slate-400 text-xs mt-2 leading-relaxed">शादी, पार्टी, सम्मेलनों और VIP मेहमानों को सर्व करने के लिए सबसे पसंदीदा और कॉम्पैक्ट साइज।</p>
                    </div>
                    <a href="https://wa.me/919351156730?text=I%20want%20to%20order%20200ml%20Bottles" target="_blank"
                       class="mt-8 w-full bg-slate-900 hover:bg-amber-500 hover:text-slate-950 border border-amber-500/40 text-amber-300 font-black py-3 rounded-xl text-center text-xs uppercase tracking-wider transition">
                        ऑर्डर करें (Order Now)
                    </a>
                </div>

                <!-- 500 ml -->
                <div class="glass-card glass-card-hover rounded-3xl p-6 transition-all duration-300 flex flex-col justify-between group">
                    <div>
                        <div class="h-44 bg-gradient-to-b from-slate-900 to-slate-950 rounded-2xl flex items-center justify-center text-5xl text-sky-400 mb-6 border border-white/5 shadow-inner group-hover:scale-105 transition">
                            <i class="fa-solid fa-flask"></i>
                        </div>
                        <span class="text-[10px] font-black text-sky-400 bg-sky-500/10 border border-sky-400/30 px-3 py-1 rounded-full uppercase tracking-wider">ट्रैवल & ऑफिस यूज़</span>
                        <h3 class="text-2xl font-royal font-bold text-white mt-4">500 ml Bottle</h3>
                        <p class="text-slate-400 text-xs mt-2 leading-relaxed">सफ़र, गाड़ियों, जिम और ऑफिस के दौरान ताजगी और सेहत का सही साथी।</p>
                    </div>
                    <a href="https://wa.me/919351156730?text=I%20want%20to%20order%20500ml%20Bottles" target="_blank"
                       class="mt-8 w-full bg-slate-900 hover:bg-amber-500 hover:text-slate-950 border border-amber-500/40 text-amber-300 font-black py-3 rounded-xl text-center text-xs uppercase tracking-wider transition">
                        ऑर्डर करें (Order Now)
                    </a>
                </div>

                <!-- 750 ml -->
                <div class="glass-card glass-card-hover rounded-3xl p-6 transition-all duration-300 flex flex-col justify-between group">
                    <div>
                        <div class="h-44 bg-gradient-to-b from-slate-900 to-slate-950 rounded-2xl flex items-center justify-center text-5xl text-emerald-400 mb-6 border border-white/5 shadow-inner group-hover:scale-105 transition">
                            <i class="fa-solid fa-glass-water"></i>
                        </div>
                        <span class="text-[10px] font-black text-emerald-400 bg-emerald-500/10 border border-emerald-400/30 px-3 py-1 rounded-full uppercase tracking-wider">शाही डाइनिंग & होटल</span>
                        <h3 class="text-2xl font-royal font-bold text-white mt-4">750 ml Bottle</h3>
                        <p class="text-slate-400 text-xs mt-2 leading-relaxed">होटल, रिसॉर्ट्स और लक्जरी डाइनिंग टेबल्स के लिए विशेष रूप से डिज़ाइन की गई प्रीमियम बोतल।</p>
                    </div>
                    <a href="https://wa.me/919351156730?text=I%20want%20to%20order%20750ml%20Bottles" target="_blank"
                       class="mt-8 w-full bg-slate-900 hover:bg-amber-500 hover:text-slate-950 border border-amber-500/40 text-amber-300 font-black py-3 rounded-xl text-center text-xs uppercase tracking-wider transition">
                        ऑर्डर करें (Order Now)
                    </a>
                </div>

                <!-- 1 Litre -->
                <div class="glass-card glass-card-hover rounded-3xl p-6 transition-all duration-300 flex flex-col justify-between group">
                    <div>
                        <div class="h-44 bg-gradient-to-b from-slate-900 to-slate-950 rounded-2xl flex items-center justify-center text-5xl text-purple-400 mb-6 border border-white/5 shadow-inner group-hover:scale-105 transition">
                            <i class="fa-solid fa-wine-bottle"></i>
                        </div>
                        <span class="text-[10px] font-black text-purple-400 bg-purple-500/10 border border-purple-400/30 px-3 py-1 rounded-full uppercase tracking-wider">फैमिली पैक</span>
                        <h3 class="text-2xl font-royal font-bold text-white mt-4">1 Litre Bottle</h3>
                        <p class="text-slate-400 text-xs mt-2 leading-relaxed">घर के दैनिक उपयोग और लंबी दूरी की यात्राओं के लिए 100% शुद्ध मिनरल वाटर।</p>
                    </div>
                    <a href="https://wa.me/919351156730?text=I%20want%20to%20order%201Litre%20Bottles" target="_blank"
                       class="mt-8 w-full bg-slate-900 hover:bg-amber-500 hover:text-slate-950 border border-amber-500/40 text-amber-300 font-black py-3 rounded-xl text-center text-xs uppercase tracking-wider transition">
                        ऑर्डर करें (Order Now)
                    </a>
                </div>

            </div>
        </div>
    </section>

    <!-- CUSTOMIZE LABEL & CONTACT SECTION WITH BACKGROUND -->
    <section id="customize" class="customize-bg py-24 px-4 border-t border-white/10 relative">
        <div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
            
            <div class="lg:col-span-6 space-y-6">
                <span class="bg-amber-500/20 border border-amber-400/40 text-amber-300 font-extrabold text-xs px-4 py-1.5 rounded-full uppercase tracking-widest">
                    Event & Corporate Branding
                </span>
                <h2 class="text-3xl sm:text-5xl font-royal font-black text-white leading-tight">
                    Customize Water Label <br>
                    <span class="gold-text-gradient">अपनी ब्रांडिंग का लेबल बनवाएं</span>
                </h2>
                <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                    शादी-विवाह (Weddings), जन्मदिन, कॉरपोरेट मीटिंग्स, होटल और रिसॉर्ट्स के लिए अपनी पसंद का डिज़ाइन, नाम और लोगो (Logo) पानी की बोतलों पर प्रिंट करवाएं।
                </p>

                <div class="grid grid-cols-2 gap-4 text-xs font-bold text-slate-200">
                    <div class="glass-card p-4 rounded-xl border border-white/10"><i class="fa-solid fa-heart text-amber-400 mr-2"></i> शादी-विवाह स्पेशल</div>
                    <div class="glass-card p-4 rounded-xl border border-white/10"><i class="fa-solid fa-building text-amber-400 mr-2"></i> कॉर्पोरेट ब्रांडिंग</div>
                    <div class="glass-card p-4 rounded-xl border border-white/10"><i class="fa-solid fa-hotel text-amber-400 mr-2"></i> होटल एवं रिसॉर्ट्स</div>
                    <div class="glass-card p-4 rounded-xl border border-white/10"><i class="fa-solid fa-crown text-amber-400 mr-2"></i> VIP इवेंट्स</div>
                </div>

                <a href="https://wa.me/919351156730?text=Hi,%20I%20want%20to%20Customize%20Water%20Label%20for%20my%20event" target="_blank"
                   class="inline-block bg-gradient-to-r from-amber-500 to-amber-600 hover:from-amber-400 hover:to-amber-500 text-slate-950 font-black px-9 py-4 rounded-2xl shadow-xl transition transform hover:scale-105 text-xs uppercase tracking-widest">
                    <i class="fa-solid fa-pen-ruler mr-2"></i> Custom लेबल का ऑर्डर दें
                </a>
            </div>

            <!-- Contact Box -->
            <div id="contact" class="lg:col-span-6">
                <div class="glass-card p-8 sm:p-10 rounded-3xl border border-amber-500/40 space-y-6 shadow-2xl">
                    <div class="text-center space-y-2 border-b border-white/10 pb-4">
                        <h3 class="text-2xl font-royal font-bold text-amber-400">संपर्क करें (Contact Details)</h3>
                        <p class="text-xs text-slate-400 uppercase tracking-widest">AQUELIO Helpline & Ordering Center</p>
                    </div>

                    <div class="space-y-4">
                        <a href="tel:+919351156730" class="flex items-center space-x-4 bg-slate-950/80 p-4 rounded-2xl border border-white/5 hover:border-amber-400/40 transition">
                            <div class="w-12 h-12 bg-amber-500/20 text-amber-400 rounded-xl flex items-center justify-center text-xl">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <p class="text-[10px] text-slate-400 font-bold uppercase tracking-wider">कॉल करें (Direct Call):</p>
                                <p class="text-lg font-bold text-white">+91 9351156730</p>
                            </div>
                        </a>

                        <a href="https://wa.me/919351156730" target="_blank" class="flex items-center space-x-4 bg-slate-950/80 p-4 rounded-2xl border border-white/5 hover:border-emerald-400/40 transition">
                            <div class="w-12 h-12 bg-emerald-500/20 text-emerald-400 rounded-xl flex items-center justify-center text-xl">
                                <i class="fa-brands fa-whatsapp"></i>
                            </div>
                            <div>
                                <p class="text-[10px] text-slate-400 font-bold uppercase tracking-wider">व्हाट्सएप सहायता (WhatsApp Order):</p>
                                <p class="text-lg font-bold text-white">+91 9351156730</p>
                            </div>
                        </a>

                        <div class="flex items-center space-x-4 bg-slate-950/80 p-4 rounded-2xl border border-white/5">
                            <div class="w-12 h-12 bg-sky-500/20 text-sky-400 rounded-xl flex items-center justify-center text-xl">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <p class="text-[10px] text-slate-400 font-bold uppercase tracking-wider">प्लांट लोकेशन:</p>
                                <p class="text-sm font-bold text-white">AQUELIO Packaged Water, Rajasthan, India</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-slate-950 text-slate-500 text-center py-8 text-xs border-t border-white/10 font-medium">
        <p>© 2026 AQUELIO™ Packaged Drinking Water. All Rights Reserved.</p>
        <p class="text-[10px] text-amber-500/70 mt-1 uppercase tracking-widest">अरावली की शुद्धता... राजस्थान का शाही गौरव</p>
    </footer>

</body>
</html>
