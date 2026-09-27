<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WM Strategix | Tax Advisory & Strategic Finance</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Inter & Plus Jakarta Sans -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Playfair+Display:ital,wght@0,600;1,400&display=swap" rel="stylesheet">
  
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              navy: '#090E1A',
              surface: '#0F172A',
              card: '#16223B',
              cardHover: '#1D2C4D',
              border: '#243456',
              gold: '#D4AF37',
              goldHover: '#B89628',
              goldLight: '#FDF6E2',
              cyanAccent: '#38BDF8',
              emeraldAccent: '#10B981'
            }
          },
          fontFamily: {
            sans: ['"Plus Jakarta Sans"', 'sans-serif'],
            serif: ['"Playfair Display"', 'serif'],
          }
        }
      }
    }
  </script>

  <style>
    /* Executive custom scrollbar */
    ::-webkit-scrollbar {
      width: 7px;
    }
    ::-webkit-scrollbar-track {
      background: #090E1A;
    }
    ::-webkit-scrollbar-thumb {
      background: #243456;
      border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #D4AF37;
    }

    .gold-gradient-text {
      background: linear-gradient(135deg, #FFF7DC 0%, #D4AF37 55%, #AA820A 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .badge-glow {
      box-shadow: 0 0 25px rgba(212, 175, 55, 0.12);
    }
  </style>
</head>

<body class="bg-brand-navy text-slate-100 font-sans selection:bg-brand-gold selection:text-brand-navy antialiased min-h-screen flex flex-col justify-between">

  <header class="fixed top-0 left-0 right-0 z-50 bg-brand-navy/95 backdrop-blur-md border-b border-brand-border/70 transition-all">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-20">
        
        <!-- Brand Logo Lockup & Top By-Name Tab -->
        <div class="flex items-center gap-4">
          <a href="#hero" class="flex items-center space-x-3 group">
            <div class="w-11 h-11 rounded-lg bg-gradient-to-br from-brand-gold via-amber-500 to-amber-700 flex items-center justify-center font-serif text-brand-navy font-bold text-xl shadow-lg shadow-brand-gold/20 group-hover:scale-105 transition-transform">
              WM
            </div>
            <div class="flex flex-col">
              <span class="text-xl font-extrabold tracking-tight text-white group-hover:text-brand-gold transition-colors">
                WM STRATEGIX
              </span>
              <span class="text-[10px] tracking-widest uppercase text-brand-gold font-semibold -mt-1">
                Tax Advisory &amp; Strategic Finance
              </span>
            </div>
          </a>

          <!-- Minimal Top By-Name Tab (Name & Member of ICAP) -->
          <div class="hidden lg:inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brand-surface/90 border border-brand-gold/30 text-xs">
            <span class="text-slate-400 font-medium">By</span>
            <span class="font-bold text-white tracking-wide">Wahib Maqbool, ACA</span>
            <span class="text-brand-gold/60 font-serif">&bull;</span>
            <span class="text-brand-gold font-medium text-[11px]">Member of ICAP</span>
          </div>
        </div>

        <!-- Desktop Navigation Links -->
        <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-slate-300">
          <a href="#services" class="hover:text-brand-gold transition-colors">Services</a>
          <a href="#differentiation" class="hover:text-brand-gold transition-colors">Why WM Strategix</a>
          <a href="#diagnostic" class="hover:text-brand-gold transition-colors">Scope Diagnostic</a>
          <a href="#faq" class="hover:text-brand-gold transition-colors">FAQ</a>
        </nav>

        <!-- CTA & Quick Connect Buttons -->
        <div class="hidden md:flex items-center space-x-4">
          <a href="https://wa.me/?text=Hello%20WM%20Strategix,%20I%20would%20like%20to%20inquire%20about%20your%20tax%20and%20financial%20advisory%20services." target="_blank" rel="noopener noreferrer" class="text-xs uppercase font-bold tracking-wider text-slate-300 hover:text-emerald-400 flex items-center gap-1.5 transition-colors">
            <svg class="w-4 h-4 text-emerald-400" fill="currentColor" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/></svg>
            Quick WhatsApp
          </a>
          <a href="#consultation" class="bg-gradient-to-r from-brand-gold to-amber-500 text-brand-navy font-bold text-xs uppercase tracking-wider px-5 py-2.5 rounded-lg shadow-md hover:brightness-110 active:scale-95 transition-all">
            Book Consultation
          </a>
        </div>

        <!-- Mobile Menu Toggle Button -->
        <button id="mobile-menu-btn" class="md:hidden p-2 text-slate-300 hover:text-white focus:outline-none" aria-label="Toggle navigation">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
        </button>
      </div>
    </div>

    <!-- Mobile Dropdown Menu -->
    <div id="mobile-menu" class="hidden md:hidden bg-brand-surface border-b border-brand-border px-6 py-6 space-y-4">
      <!-- Mobile Top By-Name Tab -->
      <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-brand-card border border-brand-gold/30 text-xs">
        <span class="text-slate-400">By</span>
        <span class="font-bold text-white">Wahib Maqbool, ACA</span>
        <span class="text-brand-gold/60">&bull;</span>
        <span class="text-brand-gold text-[11px] font-medium">Member of ICAP</span>
      </div>
      <a href="#services" class="block text-slate-200 hover:text-brand-gold text-base py-1">Services</a>
      <a href="#differentiation" class="block text-slate-200 hover:text-brand-gold text-base py-1">Why WM Strategix</a>
      <a href="#diagnostic" class="block text-slate-200 hover:text-brand-gold text-base py-1">Scope Diagnostic</a>
      <a href="#faq" class="block text-slate-200 hover:text-brand-gold text-base py-1">FAQ</a>
      <div class="pt-4 border-t border-brand-border flex flex-col space-y-3">
        <a href="#consultation" class="text-center bg-brand-gold text-brand-navy font-bold text-sm uppercase tracking-wider py-3 rounded-lg">
          Book Consultation
        </a>
      </div>
    </div>
  </header>

  <section id="hero" class="relative pt-36 pb-20 md:pt-48 md:pb-28 overflow-hidden">
    <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[700px] h-[380px] bg-brand-gold/10 rounded-full blur-[140px] pointer-events-none"></div>
    <div class="absolute -top-10 right-0 w-96 h-96 bg-brand-cyanAccent/5 rounded-full blur-[120px] pointer-events-none"></div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
      <div class="text-center max-w-3xl mx-auto">
        
        <!-- Pillar Tag Badge -->
        <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-brand-card border border-brand-gold/40 text-brand-gold text-xs font-semibold uppercase tracking-wider mb-6 badge-glow">
          <span class="w-2 h-2 rounded-full bg-brand-gold animate-pulse"></span>
          Strategic Advisory &bull; Precision Tax &bull; Virtual CFO
        </div>

        <!-- Main Headline -->
        <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight text-white leading-[1.15] mb-6">
          Strategic Financial Leadership &amp; <span class="gold-gradient-text font-serif italic font-normal">Flawless</span> Tax Execution
        </h1>

        <!-- Subheadline with updated zero-surprise guarantee -->
        <p class="text-lg sm:text-xl text-slate-300 font-normal leading-relaxed mb-10">
          WM Strategix empowers growing companies and executive leaders with predictive Virtual CFO intelligence and rigorous statutory tax governance—ensuring <strong class="text-white font-semibold">no surprises from the tax side</strong>, no last-minute liabilities, and absolute audit peace of mind.
        </p>

        <!-- CTA Action Buttons -->
        <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
          <a href="#consultation" class="w-full sm:w-auto px-8 py-3.5 rounded-lg bg-gradient-to-r from-brand-gold to-amber-500 text-brand-navy font-bold text-sm uppercase tracking-wider shadow-lg shadow-brand-gold/20 hover:scale-105 transition-all text-center">
            Schedule Discovery Call
          </a>
          <a href="#services" class="w-full sm:w-auto px-8 py-3.5 rounded-lg bg-brand-card/90 border border-brand-border text-slate-200 font-semibold text-sm hover:border-brand-gold hover:text-white transition-all text-center">
            Explore Advisory Pillars
          </a>
        </div>

        <!-- Value Badges Strip with explicit Zero-Surprise Tax Governance -->
        <div class="mt-16 grid grid-cols-2 md:grid-cols-4 gap-4 max-w-5xl mx-auto text-left">
          
          <!-- Badge 1: Zero-Surprise Tax Governance -->
          <div class="p-4 rounded-xl bg-brand-surface/80 border border-brand-border hover:border-brand-gold/60 transition-all group">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-lg bg-brand-navy flex items-center justify-center text-brand-gold text-lg font-bold border border-brand-border group-hover:border-brand-gold/40">
                🛡️
              </div>
              <div>
                <div class="text-[11px] uppercase tracking-wider text-brand-gold font-bold">Tax Certainty</div>
                <div class="text-sm font-bold text-white">Zero-Surprise Governance</div>
              </div>
            </div>
            <p class="text-[11px] text-slate-400 mt-2 leading-tight">
              No hidden liabilities or year-end shocks. Continuous forecasting &amp; compliance calendars.
            </p>
          </div>

          <!-- Badge 2: Predictive Financial Intelligence -->
          <div class="p-4 rounded-xl bg-brand-surface/80 border border-brand-border hover:border-brand-gold/60 transition-all group">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-lg bg-brand-navy flex items-center justify-center text-brand-gold text-lg font-bold border border-brand-border group-hover:border-brand-gold/40">
                📈
              </div>
              <div>
                <div class="text-[11px] uppercase tracking-wider text-slate-400 font-semibold">Intelligence</div>
                <div class="text-sm font-bold text-white">Predictive Modeling</div>
              </div>
            </div>
            <p class="text-[11px] text-slate-400 mt-2 leading-tight">
              Dynamic 3-statement forecasts, runway planning, and KPI cockpit metrics.
            </p>
          </div>

          <!-- Badge 3: Cloud & ERP Architecture -->
          <div class="p-4 rounded-xl bg-brand-surface/80 border border-brand-border hover:border-brand-gold/60 transition-all group">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-lg bg-brand-navy flex items-center justify-center text-brand-gold text-lg font-bold border border-brand-border group-hover:border-brand-gold/40">
                ⚙️
              </div>
              <div>
                <div class="text-[11px] uppercase tracking-wider text-slate-400 font-semibold">Cloud Ready</div>
                <div class="text-sm font-bold text-white">QuickBooks &amp; Odoo</div>
              </div>
            </div>
            <p class="text-[11px] text-slate-400 mt-2 leading-tight">
              Standard operating procedures (SOPs) and automated ledger reconciliations.
            </p>
          </div>

          <!-- Badge 4: Chartered Rigor -->
          <div class="p-4 rounded-xl bg-brand-surface/80 border border-brand-border hover:border-brand-gold/60 transition-all group">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-lg bg-brand-navy flex items-center justify-center text-brand-gold text-lg font-bold border border-brand-border group-hover:border-brand-gold/40">
                🎓
              </div>
              <div>
                <div class="text-[11px] uppercase tracking-wider text-slate-400 font-semibold">Standard</div>
                <div class="text-sm font-bold text-white">Chartered Standards</div>
              </div>
            </div>
            <p class="text-[11px] text-slate-400 mt-2 leading-tight">
              Rigorous Big-4 grade technical discipline with boutique advisory agility.
            </p>
          </div>

        </div>

      </div>
    </div>
  </section>

  <section id="services" class="py-20 bg-brand-surface border-y border-brand-border/60 relative">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="text-center max-w-2xl mx-auto mb-16">
        <h2 class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Our Two Core Pillars</h2>
        <p class="text-3xl font-extrabold text-white tracking-tight sm:text-4xl">
          Complete Financial Mastery &amp; Tax Certainty
        </p>
        <p class="mt-4 text-slate-300 text-sm sm:text-base">
          We separate high-stakes statutory compliance from forward-looking Virtual CFO intelligence so your business runs compliant today and prepared for tomorrow.
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
        
        <!-- Pillar 1: Precision Tax -->
        <div class="rounded-2xl bg-brand-card border border-brand-border p-8 hover:border-brand-gold/50 transition-all duration-300 relative group flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between mb-4">
              <span class="text-xs font-extrabold tracking-widest uppercase px-3 py-1 rounded bg-amber-500/10 text-brand-gold border border-brand-gold/20">
                Pillar I
              </span>
              <span class="text-2xl">🏛️</span>
            </div>

            <h3 class="text-2xl font-bold text-white mb-2 group-hover:text-brand-gold transition-colors">
              Precision Tax
            </h3>
            
            <!-- Prominent No Surprise Highlight Banner -->
            <div class="my-4 p-3.5 rounded-xl bg-brand-navy border border-brand-gold/30 flex items-start gap-3">
              <span class="text-brand-gold text-base mt-0.5">🛡️</span>
              <div>
                <div class="text-xs font-bold text-brand-gold uppercase tracking-wider">No Surprises From The Tax Side</div>
                <p class="text-xs text-slate-300 mt-0.5">
                  Predictable liabilities, proactive filing schedules, and zero audit shocks. We model your statutory liabilities in real-time before deadlines hit.
                </p>
              </div>
            </div>

            <ul class="space-y-4 my-6">
              <li class="flex items-start gap-3">
                <span class="w-5 h-5 rounded-full bg-brand-gold/20 text-brand-gold flex items-center justify-center text-xs mt-0.5 font-bold">✓</span>
                <div>
                  <h4 class="text-sm font-semibold text-white">Corporate &amp; Business Statutory Returns</h4>
                  <p class="text-xs text-slate-400">Preparation and filing of corporate income tax returns, monthly sales tax, and withholding reconciliations.</p>
                </div>
              </li>
              <li class="flex items-start gap-3">
                <span class="w-5 h-5 rounded-full bg-brand-gold/20 text-brand-gold flex items-center justify-center text-xs mt-0.5 font-bold">✓</span>
                <div>
                  <h4 class="text-sm font-semibold text-white">Audit Representation &amp; Notice Defense</h4>
                  <p class="text-xs text-slate-400">Direct, authoritative handling of revenue authority notices, assessments, and contentious compliance scrutiny.</p>
                </div>
              </li>
              <li class="flex items-start gap-3">
                <span class="w-5 h-5 rounded-full bg-brand-gold/20 text-brand-gold flex items-center justify-center text-xs mt-0.5 font-bold">✓</span>
                <div>
                  <h4 class="text-sm font-semibold text-white">Transaction Structuring &amp; Withholding Tax</h4>
                  <p class="text-xs text-slate-400">Structuring commercial contracts, cross-border payments, and entity structures to legally minimize tax drag.</p>
                </div>
              </li>
              <li class="flex items-start gap-3">
                <span class="w-5 h-5 rounded-full bg-brand-gold/20 text-brand-gold flex items-center justify-center text-xs mt-0.5 font-bold">✓</span>
                <div>
                  <h4 class="text-sm font-semibold text-white">Executive &amp; High-Net-Worth Advisory</h4>
                  <p class="text-xs text-slate-400">Personal wealth statements, salary structuring, and multi-asset compliance for founders and executives.</p>
                </div>
              </li>
            </ul>
          </div>

          <a href="#consultation" onclick="preselectService('Precision Tax')" class="w-full text-center py-3 rounded-lg bg-brand-navy border border-brand-border text-xs uppercase font-bold tracking-wider text-slate-200 hover:border-brand-gold hover:text-brand-gold transition-colors">
            Inquire For Precision Tax &rarr;
          </a>
        </div>

        <!-- Pillar 2: Financial Clarity -->
        <div class="rounded-2xl bg-brand-card border border-brand-border p-8 hover:border-brand-gold/50 transition-all duration-300 relative group flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between mb-4">
              <span class="text-xs font-extrabold tracking-widest uppercase px-3 py-1 rounded bg-sky-500/10 text-sky-300 border border-sky-400/20">
                Pillar II
              </span>
              <span class="text-2xl">📊</span>
            </div>

            <h3 class="text-2xl font-bold text-white mb-2 group-hover:text-sky-300 transition-colors">
              Financial Clarity
            </h3>

            <!-- Strategic Clarity Highlight Banner -->
            <div class="my-4 p-3.5 rounded-xl bg-brand-navy border border-sky-400/30 flex items-start gap-3">
              <span class="text-sky-400 text-base mt-0.5">💡</span>
              <div>
                <div class="text-xs font-bold text-sky-300 uppercase tracking-wider">Predictive Visibility &amp; Executive Oversight</div>
                <p class="text-xs text-slate-300 mt-0.5">
                  Translating fragmented ledger numbers into forward-looking runway forecasts, unit economics, and board-ready dashboards.
                </p>
              </div>
            </div>

            <ul class="space-y-4 my-6">
              <li class="flex items-start gap-3">
                <span class="w-5 h-5 rounded-full bg-sky-400/20 text-sky-300 flex items-center justify-center text-xs mt-0.5 font-bold">✓</span>
                <div>
                  <h4 class="text-sm font-semibold text-white">Virtual CFO Advisory Retainers</h4>
                  <p class="text-xs text-slate-400">Strategic partnership for founders: managing working capital, monthly reviews, and strategic capital allocation.</p>
                </div>
              </li>
              <li class="flex items-start gap-3">
                <span class="w-5 h-5 rounded-full bg-sky-400/20 text-sky-300 flex items-center justify-center text-xs mt-0.5 font-bold">✓</span>
                <div>
                  <h4 class="text-sm font-semibold text-white">Dynamic 3-Statement Financial Modeling</h4>
                  <p class="text-xs text-slate-400">Institutional-grade forecasting models tested for debt financing, investor seed/growth rounds, and valuations.</p>
                </div>
              </li>
              <li class="flex items-start gap-3">
                <span class="w-5 h-5 rounded-full bg-sky-400/20 text-sky-300 flex items-center justify-center text-xs mt-0.5 font-bold">✓</span>
                <div>
                  <h4 class="text-sm font-semibold text-white">Cloud Accounting &amp; ERP Architecture</h4>
                  <p class="text-xs text-slate-400">Clean setup, reconciliation workflows, and robust SOPs for QuickBooks Online and Odoo ERP systems.</p>
                </div>
              </li>
              <li class="flex items-start gap-3">
                <span class="w-5 h-5 rounded-full bg-sky-400/20 text-sky-300 flex items-center justify-center text-xs mt-0.5 font-bold">✓</span>
                <div>
                  <h4 class="text-sm font-semibold text-white">Executive Management Dashboards</h4>
                  <p class="text-xs text-slate-400">Concise monthly flash reports showing gross margins, customer acquisition cost, and cash runway projections.</p>
                </div>
              </li>
            </ul>
          </div>

          <a href="#consultation" onclick="preselectService('Financial Clarity')" class="w-full text-center py-3 rounded-lg bg-brand-navy border border-brand-border text-xs uppercase font-bold tracking-wider text-slate-200 hover:border-sky-400 hover:text-sky-300 transition-colors">
            Inquire For Financial Clarity &rarr;
          </a>
        </div>

      </div>

    </div>
  </section>

  <section id="differentiation" class="py-20 relative">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="text-center max-w-2xl mx-auto mb-14">
        <h2 class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">The WM Strategix Advantage</h2>
        <p class="text-3xl font-extrabold text-white tracking-tight sm:text-4xl">
          Why Modern Enterprises Choose Us Over Traditional Firms
        </p>
        <p class="mt-3 text-slate-400 text-sm">
          We do not simply record what has already happened; we partner with you to engineer your fiscal future and eliminate regulatory surprises.
        </p>
      </div>

      <!-- Comparison Matrix Table -->
      <div class="overflow-x-auto">
        <div class="min-w-[680px] bg-brand-surface rounded-2xl border border-brand-border overflow-hidden shadow-2xl">
          <div class="grid grid-cols-12 bg-brand-navy border-b border-brand-border text-xs uppercase font-bold tracking-wider py-4 px-6">
            <div class="col-span-4 text-slate-400">Core Strategic Dimension</div>
            <div class="col-span-4 text-rose-300/80">Traditional Accounting Firms</div>
            <div class="col-span-4 text-brand-gold flex items-center gap-1.5">
              <span>★</span> WM STRATEGIX ADVANTAGE
            </div>
          </div>

          <!-- Row 1: Explicit Tax Surprise Contrast -->
          <div class="grid grid-cols-12 border-b border-brand-border/60 py-5 px-6 items-center hover:bg-brand-card/40 transition-colors">
            <div class="col-span-4 pr-4">
              <span class="font-bold text-white text-sm block">Tax Compliance &amp; Certainty</span>
              <span class="text-xs text-slate-400">Handling liabilities &amp; audits</span>
            </div>
            <div class="col-span-4 pr-4 text-xs text-slate-400">
              <span class="inline-block px-2 py-0.5 rounded bg-rose-500/10 text-rose-300 font-semibold mb-1">Reactive Filing &amp; Year-End Shocks</span>
              <p>Scrambles at filing deadlines. Unanticipated tax liabilities, penalty notices, and audit panic.</p>
            </div>
            <div class="col-span-4 text-xs text-slate-200">
              <span class="inline-block px-2 py-0.5 rounded bg-brand-gold/10 text-brand-gold font-bold mb-1">Zero-Surprise Proactive Modeling</span>
              <p>No surprises from the tax side. Liabilities are forecasted, deductions planned, and filings audit-proofed in advance.</p>
            </div>
          </div>

          <!-- Row 2: Perspective & Reporting -->
          <div class="grid grid-cols-12 border-b border-brand-border/60 py-5 px-6 items-center hover:bg-brand-card/40 transition-colors">
            <div class="col-span-4 pr-4">
              <span class="font-bold text-white text-sm block">Perspective &amp; Decision Support</span>
              <span class="text-xs text-slate-400">How your figures are used</span>
            </div>
            <div class="col-span-4 pr-4 text-xs text-slate-400">
              <span class="inline-block px-2 py-0.5 rounded bg-rose-500/10 text-rose-300 font-medium mb-1">Rearview-Mirror Bookkeeping</span>
              <p>Reports what was spent months after the period closes. No predictive foresight for executive planning.</p>
            </div>
            <div class="col-span-4 text-xs text-slate-200">
              <span class="inline-block px-2 py-0.5 rounded bg-brand-gold/10 text-brand-gold font-semibold mb-1">Predictive Cash Intelligence</span>
              <p>Dynamic cash models, runway simulations, and forward-looking KPI metrics built for executive steering.</p>
            </div>
          </div>

          <!-- Row 3: Service Architecture -->
          <div class="grid grid-cols-12 border-b border-brand-border/60 py-5 px-6 items-center hover:bg-brand-card/40 transition-colors">
            <div class="col-span-4 pr-4">
              <span class="font-bold text-white text-sm block">Service Architecture</span>
              <span class="text-xs text-slate-400">Internal communication</span>
            </div>
            <div class="col-span-4 pr-4 text-xs text-slate-400">
              <span class="inline-block px-2 py-0.5 rounded bg-rose-500/10 text-rose-300 font-medium mb-1">Disconnected Silos</span>
              <p>Bookkeeper and annual tax filer do not talk. Operational oversights create compliance liabilities.</p>
            </div>
            <div class="col-span-4 text-xs text-slate-200">
              <span class="inline-block px-2 py-0.5 rounded bg-brand-gold/10 text-brand-gold font-semibold mb-1">Unified CFO &amp; Tax Engine</span>
              <p>Daily ledger hygiene directly feeds into management dashboards and proactive statutory tax strategies.</p>
            </div>
          </div>

          <!-- Row 4: Talent Execution -->
          <div class="grid grid-cols-12 py-5 px-6 items-center hover:bg-brand-card/40 transition-colors">
            <div class="col-span-4 pr-4">
              <span class="font-bold text-white text-sm block">Talent &amp; Technology Stack</span>
              <span class="text-xs text-slate-400">Oversight and software</span>
            </div>
            <div class="col-span-4 pr-4 text-xs text-slate-400">
              <span class="inline-block px-2 py-0.5 rounded bg-rose-500/10 text-rose-300 font-medium mb-1">Junior Delegation &amp; Broken Sheets</span>
              <p>Handed off to interns or entry-level staff; trapped in manual spreadsheets and slow email chains.</p>
            </div>
            <div class="col-span-4 text-xs text-slate-200">
              <span class="inline-block px-2 py-0.5 rounded bg-brand-gold/10 text-brand-gold font-semibold mb-1">Senior Chartered Guidance &amp; Cloud ERP</span>
              <p>Direct chartered leadership paired with modern QuickBooks and Odoo cloud automated integrations.</p>
            </div>
          </div>

        </div>
      </div>

    </div>
  </section>

  <section id="diagnostic" class="py-20 bg-brand-surface border-t border-brand-border/60">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="text-center mb-12">
        <span class="text-xs font-bold uppercase tracking-widest text-brand-gold">Interactive Tool</span>
        <h2 class="text-3xl font-extrabold text-white tracking-tight mt-1">
          Financial &amp; Tax Scope Diagnostic
        </h2>
        <p class="text-sm text-slate-300 mt-2">
          Select your business scale and primary operational bottleneck to receive a recommended advisory roadmap.
        </p>
      </div>

      <!-- Diagnostic Card Widget -->
      <div class="bg-brand-card border border-brand-border rounded-2xl p-6 sm:p-10 shadow-xl">
        <div class="space-y-8">
          
          <!-- Step 1: Business Scale -->
          <div>
            <label class="block text-xs font-bold uppercase tracking-wider text-slate-300 mb-3">
              1. Business Stage &amp; Structure
            </label>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-3" id="stage-buttons">
              <button type="button" onclick="setDiagnostic('stage', 'startup', this)" class="stage-opt p-3.5 rounded-xl border border-brand-gold bg-brand-gold/10 text-left transition-all active:scale-95">
                <div class="text-sm font-bold text-white">Startup / Solopreneur</div>
                <div class="text-[11px] text-slate-400 mt-0.5">Pre-revenue up to $10k/mo</div>
              </button>
              <button type="button" onclick="setDiagnostic('stage', 'growth', this)" class="stage-opt p-3.5 rounded-xl border border-brand-border bg-brand-navy/60 hover:border-brand-gold text-left transition-all active:scale-95">
                <div class="text-sm font-bold text-white">Growing SME</div>
                <div class="text-[11px] text-slate-400 mt-0.5">$10k - $100k/mo revenue</div>
              </button>
              <button type="button" onclick="setDiagnostic('stage', 'corporate', this)" class="stage-opt p-3.5 rounded-xl border border-brand-border bg-brand-navy/60 hover:border-brand-gold text-left transition-all active:scale-95">
                <div class="text-sm font-bold text-white">Established Enterprise</div>
                <div class="text-[11px] text-slate-400 mt-0.5">$100k+/mo or multi-entity</div>
              </button>
            </div>
          </div>

          <!-- Step 2: Primary Challenge -->
          <div>
            <label class="block text-xs font-bold uppercase tracking-wider text-slate-300 mb-3">
              2. Primary Priority or Challenge
            </label>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3" id="challenge-buttons">
              <button type="button" onclick="setDiagnostic('challenge', 'tax', this)" class="chal-opt p-3.5 rounded-xl border border-brand-gold bg-brand-gold/10 text-left transition-all active:scale-95">
                <div class="text-sm font-bold text-white">Zero-Surprise Tax Compliance</div>
                <div class="text-[11px] text-slate-400 mt-0.5">Eliminate audit shocks, statutory filings</div>
              </button>
              <button type="button" onclick="setDiagnostic('challenge', 'cfo', this)" class="chal-opt p-3.5 rounded-xl border border-brand-border bg-brand-navy/60 hover:border-brand-gold text-left transition-all active:scale-95">
                <div class="text-sm font-bold text-white">Virtual CFO &amp; Cash Visibility</div>
                <div class="text-[11px] text-slate-400 mt-0.5">Cash flow steering, runway &amp; KPI dashboards</div>
              </button>
              <button type="button" onclick="setDiagnostic('challenge', 'fundraise', this)" class="chal-opt p-3.5 rounded-xl border border-brand-border bg-brand-navy/60 hover:border-brand-gold text-left transition-all active:scale-95">
                <div class="text-sm font-bold text-white">Financial Model for Investors</div>
                <div class="text-[11px] text-slate-400 mt-0.5">3-Statement model, debt financing deck</div>
              </button>
              <button type="button" onclick="setDiagnostic('challenge', 'erp', this)" class="chal-opt p-3.5 rounded-xl border border-brand-border bg-brand-navy/60 hover:border-brand-gold text-left transition-all active:scale-95">
                <div class="text-sm font-bold text-white">Clean Up ERP &amp; Bookkeeping</div>
                <div class="text-[11px] text-slate-400 mt-0.5">Fix messy ledgers, configure QuickBooks / Odoo</div>
              </button>
            </div>
          </div>

          <!-- Dynamic Output Recommendation Box -->
          <div id="diagnostic-output" class="p-5 rounded-xl bg-brand-navy border border-brand-gold/40 flex flex-col sm:flex-row items-center justify-between gap-5">
            <div>
              <span class="text-[10px] uppercase font-bold tracking-widest text-brand-gold">Recommended Service Plan</span>
              <h3 id="rec-title" class="text-lg font-bold text-white mt-0.5">Startup Precision Tax &amp; Zero-Surprise Setup</h3>
              <p id="rec-desc" class="text-xs text-slate-300 mt-1 max-w-lg">
                Statutory registration, initial deduction audits, and withholding tax optimization setup to ensure no surprise bills.
              </p>
            </div>
            <a href="#consultation" id="rec-cta-btn" class="w-full sm:w-auto px-6 py-2.5 rounded-lg bg-brand-gold text-brand-navy font-bold text-xs uppercase tracking-wider hover:brightness-110 whitespace-nowrap text-center transition-all">
              Claim Diagnostic Slot
            </a>
          </div>

        </div>
      </div>

    </div>
  </section>

  <section id="consultation" class="py-20 relative">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="text-center mb-12">
        <span class="text-xs font-bold uppercase tracking-widest text-brand-gold">Direct Engagement</span>
        <h2 class="text-3xl font-extrabold text-white tracking-tight mt-1">
          Schedule a Confidential Consultation
        </h2>
        <p class="text-sm text-slate-300 mt-2 max-w-xl mx-auto">
          Share your requirements. We will analyze your tax &amp; financial posture and respond within 24 hours with an actionable briefing.
        </p>
      </div>

      <div class="bg-brand-surface border border-brand-border rounded-2xl p-6 sm:p-10 shadow-2xl">
        
        <form id="consultation-form" onsubmit="handleFormSubmit(event)" class="space-y-6">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
            <div>
              <label for="client-name" class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Full Name *</label>
              <input type="text" id="client-name" required placeholder="Wahib or Corporate Contact" class="w-full bg-brand-navy border border-brand-border rounded-lg px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-brand-gold transition-colors">
            </div>

            <div>
              <label for="client-email" class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Work Email Address *</label>
              <input type="email" id="client-email" required placeholder="contact@company.com" class="w-full bg-brand-navy border border-brand-border rounded-lg px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-brand-gold transition-colors">
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
            <div>
              <label for="client-phone" class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Phone / WhatsApp Number</label>
              <input type="tel" id="client-phone" placeholder="+92 300 0000000" class="w-full bg-brand-navy border border-brand-border rounded-lg px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-brand-gold transition-colors">
            </div>

            <div>
              <label for="client-service" class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Primary Advisory Area *</label>
              <select id="client-service" class="w-full bg-brand-navy border border-brand-border rounded-lg px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-gold transition-colors">
                <option value="Precision Tax">Precision Tax (Zero-Surprise Compliance &amp; Filings)</option>
                <option value="Financial Clarity">Financial Clarity (Virtual CFO, Models)</option>
                <option value="Full Retainer">Integrated CFO &amp; Tax Retainer</option>
                <option value="ERP Setup">ERP &amp; Cloud Accounting (QuickBooks/Odoo)</option>
              </select>
            </div>
          </div>

          <div>
            <label for="client-message" class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Key Challenges or Desired Outcomes</label>
            <textarea id="client-message" rows="4" placeholder="Briefly describe your current revenue stage, tax jurisdiction, or upcoming financial modeling deadlines..." class="w-full bg-brand-navy border border-brand-border rounded-lg px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-brand-gold transition-colors"></textarea>
          </div>

          <div class="flex flex-col sm:flex-row items-center justify-between gap-4 pt-2">
            <div class="text-xs text-slate-400 flex items-center gap-1.5">
              <span>🔒</span> 100% Confidentiality &bull; Non-Disclosure Standard
            </div>
            
            <button type="submit" id="submit-btn" class="w-full sm:w-auto px-8 py-3.5 rounded-lg bg-gradient-to-r from-brand-gold to-amber-500 text-brand-navy font-bold text-xs uppercase tracking-wider shadow-lg shadow-brand-gold/20 hover:scale-105 active:scale-95 transition-all">
              Request Discovery Session
            </button>
          </div>
        </form>

        <!-- Dynamic Success Message Alert -->
        <div id="form-success-banner" class="hidden mt-6 p-5 rounded-xl bg-emerald-950/70 border border-emerald-500/40 text-emerald-200 text-sm">
          <div class="flex items-center gap-2 font-bold text-emerald-400 mb-1">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/></svg>
            Inquiry Successfully Transmitted
          </div>
          <p id="success-summary" class="text-xs leading-relaxed text-slate-300">
            Thank you. Your diagnostic request has been logged. A senior WM Strategix advisor will review your parameters and follow up shortly.
          </p>
        </div>

      </div>

    </div>
  </section>

  <section id="faq" class="py-16 bg-brand-surface border-t border-brand-border/60">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="text-center mb-12">
        <h2 class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-1">Client Inquiries</h2>
        <p class="text-2xl font-bold text-white tracking-tight sm:text-3xl">
          Frequently Asked Questions
        </p>
      </div>

      <div class="space-y-4">
        
        <div class="rounded-xl border border-brand-border bg-brand-card overflow-hidden">
          <button onclick="toggleFaq('faq-0')" class="w-full px-6 py-4 text-left font-semibold text-sm text-white flex justify-between items-center hover:text-brand-gold transition-colors">
            <span>What do you mean by &ldquo;No Surprises from the Tax Side&rdquo;?</span>
            <span id="faq-0-icon" class="text-brand-gold text-lg font-bold">+</span>
          </button>
          <div id="faq-0" class="hidden px-6 pb-5 text-xs text-slate-300 leading-relaxed border-t border-brand-border/40 pt-3">
            Traditional accountants wait until tax filing month to calculate what you owe, leading to sudden cash crunches and surprise liabilities. At WM Strategix, we forecast your tax position continuously throughout the fiscal year. You always know your exact statutory obligations ahead of time, with deductions planned and paperwork audit-ready.
          </div>
        </div>

        <div class="rounded-xl border border-brand-border bg-brand-card overflow-hidden">
          <button onclick="toggleFaq('faq-1')" class="w-full px-6 py-4 text-left font-semibold text-sm text-white flex justify-between items-center hover:text-brand-gold transition-colors">
            <span>How does a Virtual CFO differ from a traditional accountant?</span>
            <span id="faq-1-icon" class="text-brand-gold text-lg font-bold">+</span>
          </button>
          <div id="faq-1" class="hidden px-6 pb-5 text-xs text-slate-300 leading-relaxed border-t border-brand-border/40 pt-3">
            A traditional accountant looks backwards—recording historical transactions and categorizing receipts. A Virtual CFO from WM Strategix acts as your high-level strategic advisor, building 3-statement forecast models, managing cash flow runway, presenting to investors, and setting strategic metrics.
          </div>
        </div>

        <div class="rounded-xl border border-brand-border bg-brand-card overflow-hidden">
          <button onclick="toggleFaq('faq-2')" class="w-full px-6 py-4 text-left font-semibold text-sm text-white flex justify-between items-center hover:text-brand-gold transition-colors">
            <span>Can you assist with multi-jurisdiction or remote company taxes?</span>
            <span id="faq-2-icon" class="text-brand-gold text-lg font-bold">+</span>
          </button>
          <div id="faq-2" class="hidden px-6 pb-5 text-xs text-slate-300 leading-relaxed border-t border-brand-border/40 pt-3">
            Yes. We structure cross-border withholding tax positions, advise on international contractor compliance, and align financial statements with international frameworks (IFRS and US GAAP).
          </div>
        </div>

        <div class="rounded-xl border border-brand-border bg-brand-card overflow-hidden">
          <button onclick="toggleFaq('faq-3')" class="w-full px-6 py-4 text-left font-semibold text-sm text-white flex justify-between items-center hover:text-brand-gold transition-colors">
            <span>Which accounting platforms and ERPs do you support?</span>
            <span id="faq-3-icon" class="text-brand-gold text-lg font-bold">+</span>
          </button>
          <div id="faq-3" class="hidden px-6 pb-5 text-xs text-slate-300 leading-relaxed border-t border-brand-border/40 pt-3">
            We specialize in QuickBooks Online, Odoo ERP, and Xero. We assist with end-to-end chart of accounts setup, multi-currency sync, and standard operating procedures (SOPs) for internal finance teams.
          </div>
        </div>

        <div class="rounded-xl border border-brand-border bg-brand-card overflow-hidden">
          <button onclick="toggleFaq('faq-4')" class="w-full px-6 py-4 text-left font-semibold text-sm text-white flex justify-between items-center hover:text-brand-gold transition-colors">
            <span>How are advisory fees structured?</span>
            <span id="faq-4-icon" class="text-brand-gold text-lg font-bold">+</span>
          </button>
          <div id="faq-4" class="hidden px-6 pb-5 text-xs text-slate-300 leading-relaxed border-t border-brand-border/40 pt-3">
            We offer transparent, fixed-scope monthly retainers for Virtual CFO and ongoing tax governance, as well as defined milestone packages for financial models, tax health audits, and ERP migrations. No surprise billing.
          </div>
        </div>

      </div>

    </div>
  </section>

  <footer class="bg-brand-navy border-t border-brand-border/80 pt-16 pb-12">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <!-- Lead Magnet Bar -->
      <div class="mb-14 p-6 sm:p-8 rounded-2xl bg-gradient-to-r from-brand-card to-brand-surface border border-brand-gold/30 flex flex-col md:flex-row items-center justify-between gap-6">
        <div>
          <span class="text-[11px] font-bold text-brand-gold uppercase tracking-wider">Free Executive Resource</span>
          <h3 class="text-xl font-bold text-white mt-1">Year-End Corporate Tax &amp; Financial Close Checklist</h3>
          <p class="text-xs text-slate-300 mt-1 max-w-xl">
            A 20-point audit checklist covering balance sheet reconciliations, withholding liabilities, and statutory zero-surprise tax prep.
          </p>
        </div>
        <button onclick="downloadChecklist()" class="px-6 py-3 rounded-lg bg-brand-gold text-brand-navy font-bold text-xs uppercase tracking-wider hover:brightness-110 active:scale-95 transition-all whitespace-nowrap">
          Download Checklist
        </button>
      </div>

      <!-- Links & Brand Details -->
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8 pb-12 border-b border-brand-border/60">
        <div class="md:col-span-2">
          <div class="flex items-center space-x-3 mb-3">
            <div class="w-8 h-8 rounded bg-brand-gold flex items-center justify-center font-serif text-brand-navy font-bold text-sm">
              WM
            </div>
            <span class="text-lg font-bold text-white">WM STRATEGIX</span>
          </div>
          <p class="text-xs font-semibold text-brand-gold mb-2">
            Founded &amp; Led by Wahib Maqbool, ACA (Member of ICAP)
          </p>
          <p class="text-xs text-slate-400 max-w-sm leading-relaxed">
            Tax Advisory &amp; Strategic Finance. Providing growing businesses with Virtual CFO advisory, robust predictive financial modeling, and precision tax compliance under strict chartered accounting governance.
          </p>
        </div>

        <div>
          <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-3">Core Pillars</h4>
          <ul class="space-y-2 text-xs text-slate-400">
            <li><a href="#services" class="hover:text-brand-gold transition-colors">Precision Tax</a></li>
            <li><a href="#services" class="hover:text-brand-gold transition-colors">Virtual CFO Retainers</a></li>
            <li><a href="#services" class="hover:text-brand-gold transition-colors">Financial Modeling</a></li>
            <li><a href="#services" class="hover:text-brand-gold transition-colors">ERP &amp; QuickBooks SOPs</a></li>
          </ul>
        </div>

        <div>
          <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-3">Principal &amp; Practice</h4>
          <ul class="space-y-2 text-xs text-slate-400">
            <li>Principal: <span class="text-slate-200">Wahib Maqbool, ACA</span></li>
            <li>Credential: <span class="text-slate-200">Member of ICAP</span></li>
            <li>Direct: <span class="text-slate-200">advisory@wmstrategix.com</span></li>
            <li>Location: Lahore &amp; Global Remote Advisory</li>
            <li><a href="#consultation" class="text-brand-gold hover:underline">Book Discovery Call &rarr;</a></li>
          </ul>
        </div>
      </div>

      <!-- Copyright Notice -->
      <div class="pt-8 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-500 gap-4">
        <p>&copy; <span id="current-year">2026</span> WM Strategix &bull; Led by Wahib Maqbool, ACA (Member of ICAP). All rights reserved.</p>
        <div class="flex space-x-6">
          <span class="hover:text-slate-400 cursor-pointer">Confidentiality Policy</span>
          <span class="hover:text-slate-400 cursor-pointer">Engagement Terms</span>
          <span class="hover:text-slate-400 cursor-pointer">Chartered Ethics</span>
        </div>
      </div>

    </div>
  </footer>

  <!-- Floating WhatsApp Action Button -->
  <a href="https://wa.me/?text=Hello%20WM%20Strategix,%20I%20would%20like%20to%20inquire%20about%20your%20tax%20and%20financial%20advisory%20services." target="_blank" rel="noopener noreferrer" class="fixed bottom-6 left-6 z-40 bg-emerald-500 hover:bg-emerald-600 text-white p-3.5 rounded-full shadow-2xl transition-all transform hover:scale-110 flex items-center justify-center gap-2 group" title="Chat on WhatsApp">
    <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/></svg>
    <span class="max-w-0 overflow-hidden whitespace-nowrap group-hover:max-w-xs transition-all duration-300 text-xs font-bold uppercase tracking-wider pr-1">Chat With Advisor</span>
  </a>

  <!-- Notification Toast -->
  <div id="toast" class="fixed bottom-6 right-6 z-50 transform translate-y-24 opacity-0 transition-all duration-300 bg-brand-card border border-brand-gold text-slate-100 text-xs px-5 py-3 rounded-xl shadow-2xl flex items-center gap-3">
    <span class="text-brand-gold">✓</span>
    <span id="toast-msg">Action Completed</span>
  </div>

  <script>
    // Update Copyright Year dynamically
    document.getElementById('current-year').textContent = new Date().getFullYear();

    // Mobile Navigation Toggle
    const mobileBtn = document.getElementById('mobile-menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    mobileBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    // Close mobile menu on link click
    document.querySelectorAll('#mobile-menu a').forEach(link => {
      link.addEventListener('click', () => {
        mobileMenu.classList.add('hidden');
      });
    });

    // FAQ Accordion Toggle
    function toggleFaq(id) {
      const el = document.getElementById(id);
      const icon = document.getElementById(id + '-icon');
      const isHidden = el.classList.contains('hidden');
      
      ['faq-0', 'faq-1', 'faq-2', 'faq-3', 'faq-4'].forEach(fId => {
        const item = document.getElementById(fId);
        const itemIcon = document.getElementById(fId + '-icon');
        if(item) item.classList.add('hidden');
        if(itemIcon) itemIcon.textContent = '+';
      });

      if (isHidden) {
        el.classList.remove('hidden');
        icon.textContent = '−';
      }
    }

    // Diagnostic Tool State & Logic
    let currentStage = 'startup';
    let currentChallenge = 'tax';

    const diagnosticMatrix = {
      'startup': {
        'tax': {
          title: "Startup Precision Tax & Zero-Surprise Setup",
          desc: "Clean setup of tax filings, preliminary withholding optimization, and registration compliance to ensure zero surprise tax bills.",
          serviceSelect: "Precision Tax"
        },
        'cfo': {
          title: "Early-Stage Runway & Cash Flow Model",
          desc: "Burn-rate calculation, cash flow roadmap, and lightweight monthly review to extend your operating runway.",
          serviceSelect: "Financial Clarity"
        },
        'fundraise': {
          title: "Seed / Pre-Series Pitch Financial Model",
          desc: "Standard 3-statement model with unit economics, assumptions table, and investor-ready summaries.",
          serviceSelect: "Financial Clarity"
        },
        'erp': {
          title: "Clean Cloud Setup (QuickBooks / Wave)",
          desc: "Initial chart of accounts, bank feed rules, and automated invoicing setup.",
          serviceSelect: "ERP Setup"
        }
      },
      'growth': {
        'tax': {
          title: "Corporate Tax Governance & Zero-Surprise Calendar",
          desc: "Proactive statutory reviews, deduction maximization, and sales tax / withholding reconciliation with zero year-end liabilities.",
          serviceSelect: "Precision Tax"
        },
        'cfo': {
          title: "Monthly Virtual CFO Growth Retainer",
          desc: "Bi-weekly strategy sessions, custom KPI dashboard, working capital tracking, and executive performance reviews.",
          serviceSelect: "Full Retainer"
        },
        'fundraise': {
          title: "Enterprise 3-Statement Dynamic Model",
          desc: "Multi-scenario stress testing, debt service capacity models, and valuation prep.",
          serviceSelect: "Financial Clarity"
        },
        'erp': {
          title: "ERP Migration & SOP Architecture (Odoo / QBO)",
          desc: "Complete cleanup of legacy ledger errors, inventory / bill sync, and finance SOP formulation.",
          serviceSelect: "ERP Setup"
        }
      },
      'corporate': {
        'tax': {
          title: "Comprehensive Tax Structuring & Audit Defense",
          desc: "Group entity optimization, cross-border treaty review, and dedicated revenue authority representation with guaranteed defense preparedness.",
          serviceSelect: "Precision Tax"
        },
        'cfo': {
          title: "Executive Fractional CFO Advisory Suite",
          desc: "Board-level presence, capital allocation strategy, M&A prep, and enterprise performance steering.",
          serviceSelect: "Full Retainer"
        },
        'fundraise': {
          title: "Institutional Financial Model & Due Diligence Deck",
          desc: "Audited-grade dynamic financial models built to withstand private equity and institutional debt scrutiny.",
          serviceSelect: "Financial Clarity"
        },
        'erp': {
          title: "Odoo Enterprise Systems & Internal Controls Audit",
          desc: "Full segregation of duties, multi-currency architecture, and automated statutory reporting pipelines.",
          serviceSelect: "ERP Setup"
        }
      }
    };

    function setDiagnostic(type, value, btn) {
      if (type === 'stage') {
        currentStage = value;
        document.querySelectorAll('.stage-opt').forEach(el => {
          el.classList.remove('border-brand-gold', 'bg-brand-gold/10');
          el.classList.add('border-brand-border', 'bg-brand-navy/60');
        });
        btn.classList.add('border-brand-gold', 'bg-brand-gold/10');
        btn.classList.remove('border-brand-border', 'bg-brand-navy/60');
      } else if (type === 'challenge') {
        currentChallenge = value;
        document.querySelectorAll('.chal-opt').forEach(el => {
          el.classList.remove('border-brand-gold', 'bg-brand-gold/10');
          el.classList.add('border-brand-border', 'bg-brand-navy/60');
        });
        btn.classList.add('border-brand-gold', 'bg-brand-gold/10');
        btn.classList.remove('border-brand-border', 'bg-brand-navy/60');
      }

      const recommendation = diagnosticMatrix[currentStage][currentChallenge];
      document.getElementById('rec-title').textContent = recommendation.title;
      document.getElementById('rec-desc').textContent = recommendation.desc;
    }

    // Pre-select service dropdown when user clicks a card
    function preselectService(serviceName) {
      const select = document.getElementById('client-service');
      for (let i = 0; i < select.options.length; i++) {
        if (select.options[i].text.includes(serviceName)) {
          select.selectedIndex = i;
          break;
        }
      }
    }

    // Form Submission Handling
    function handleFormSubmit(event) {
      event.preventDefault();
      
      const name = document.getElementById('client-name').value;
      const service = document.getElementById('client-service').value;

      const submitBtn = document.getElementById('submit-btn');
      submitBtn.disabled = true;
      submitBtn.textContent = "Processing...";

      setTimeout(() => {
        submitBtn.disabled = false;
        submitBtn.textContent = "Request Discovery Session";
        
        const successBanner = document.getElementById('form-success-banner');
        const summary = document.getElementById('success-summary');
        
        summary.innerHTML = `Thank you, <strong>${name}</strong>. Your consultation request for <strong>${service}</strong> has been logged. We will prepare your preliminary assessment and reach out promptly.`;
        
        successBanner.classList.remove('hidden');
        showToast("Consultation inquiry registered successfully");
        document.getElementById('consultation-form').reset();
      }, 700);
    }

    // Trigger Checklist Download
    function downloadChecklist() {
      const checklistText = `WM STRATEGIX - YEAR-END TAX & FINANCIAL CLOSE CHECKLIST\nZero-Surprise Compliance & Strategic Close Guidelines\n\n1. Reconcile all bank, credit card, and payment gateway balances against the general ledger.\n2. Review accounts receivable aging report; flag >90 days balances for bad debt reserves.\n3. Reconcile monthly sales tax/VAT filed against audited P&L gross receipts.\n4. Verify vendor Tax IDs (NTN/FTIN) and withholdings before final annual returns.\n5. Audit capital expenditure and fixed asset additions against statutory depreciation rates.\n6. Confirm debt loan schedules against bank balances (principal vs interest expense).\n7. Formulate preliminary 3-statement forecast for upcoming quarters.\n8. Verify compliance with statutory filing deadlines to avoid penalties and notices.\n\nFor advisory support: advisory@wmstrategix.com`;
      
      const blob = new Blob([checklistText], { type: 'text/plain' });
      const anchor = document.createElement('a');
      anchor.href = URL.createObjectURL(blob);
      anchor.download = 'WM_Strategix_Year_End_Checklist.txt';
      document.body.appendChild(anchor);
      anchor.click();
      document.body.removeChild(anchor);

      showToast("Checklist downloaded to your device");
    }

    // Toast Utility
    function showToast(message) {
      const toast = document.getElementById('toast');
      const toastMsg = document.getElementById('toast-msg');
      toastMsg.textContent = message;
      toast.classList.remove('translate-y-24', 'opacity-0');
      toast.classList.add('translate-y-0', 'opacity-100');
      
      setTimeout(() => {
        toast.classList.remove('translate-y-0', 'opacity-100');
        toast.classList.add('translate-y-24', 'opacity-0');
      }, 3500);
    }
  </script>
</body>
</html>
