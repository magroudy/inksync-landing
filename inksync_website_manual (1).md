# inksync Website Revamp Manual

## Website Copy & Content

### Hero Section (Dark Background)
**Headline:** Financial-Trader-Level Intelligence for Your Inventory

**Subheadline:** Commercial teams and business owners get Bloomberg-style analytics for inventory decisions that directly impact working capital efficiency.

**CTA Button:** Book a Demo

### Problem Section
**Headline:** Every Team Has Their Platform... Except Commercial Teams

**Body Copy:** 
- **Sales Teams** have Salesforce to drive demand across many channels
- **OPS Teams** have ERPs to fulfill orders across complex supply chains  
- **Commercial Teams** only have Excel to analyze, optimize and trade +5,000 SKUs

**Bottom Line:** You're managing millions in inventory with spreadsheets while other teams have sophisticated platforms.

### Solution Section
**Headline:** An Inventory Intelligence Platform Built for Commercial Teams

**Body Copy:**
inksync treats your SKUs like tradable financial assets, providing the analytical sophistication that commercial teams need for inventory decisions.

**Four Core Capabilities:**

1. **Bloomberg-Style Analytics Dashboards**
   - Icon: Chart/Dashboard symbol
   - Real-time performance visibility across all SKUs

2. **Real-Time Margin & Cashflow Visibility**
   - Icon: Dollar/Analytics symbol
   - Track profitability by individual SKU

3. **Automated Cross-System Reconciliation**
   - Icon: Sync/Integration symbol  
   - Supplier reporting without manual work

4. **AI-Powered Optimization Recommendations**
   - Icon: Brain/Target symbol
   - Data-driven insights for better decisions

### Benefits Section
**Headline:** Like Hiring an Expert Data Science Team Working 24/7

**Three Key Outcomes:**
1. **Working Capital Efficiency**
   - Icon: Money/Growth arrow
   - Make inventory decisions that directly impact cash flow

2. **Financial-Trader-Level Sophistication**  
   - Icon: Analytics/Chart
   - Analytical capabilities previously unavailable to commercial teams

3. **No System Replacements**
   - Icon: Plug/Integration
   - Works with your existing infrastructure

### How It Works Section
**Headline:** From Excel to Bloomberg in Minutes

**Three Steps:**
1. **Connect Your Data**
   - Export from your existing systems
   
2. **See Your Trading Dashboard**
   - Bloomberg-style SKU intelligence
   
3. **Make Intelligent Decisions**
   - AI recommendations for optimization

### CTA Section
**Headline:** Ready for Financial-Trader-Level Inventory Intelligence?

**Body:** Join commercial teams and business owners who treat their SKUs like tradable financial assets.

**CTA Button:** Book a Demo

### Footer
- Logo: inksync
- Tagline: "The Bloomberg Terminal for Commercial Teams"
- Demo button link

---

## Cursor AI Implementation Steps

### Step 1: Project Setup
```bash
# Create new React project
npx create-react-app inksync-landing
cd inksync-landing
npm install tailwindcss styled-components lucide-react
```

### Step 2: Design System Prompt
"Create a landing page with these design specifications:
- Dark hero section #1a2025 background) like Bloomberg terminal
- Light sections #f8f9fa) for contrast
- Primary color: #06a6bf (terminal green)
- Secondary color: #fefefeec
- Font: Inter or similar modern sans-serif
- Minimal, clean design inspired by Whoop website
- Mobile-responsive
- Simple animations on scroll"

### Step 3: Component Structure
"Build these components in order:
1. Header with logo and demo CTA
2. Hero section with dark background
3. Problem section with stats
4. Solution section with 3 modules
5. Benefits section with 3 key points  
6. How it works (3 steps)
7. Final CTA section
8. Footer"

### Step 4: Content Integration
"Use this exact copy: [paste website copy above]
- Hero: Dark section with terminal aesthetic
- All other sections: Light background with subtle shadows
- Icons: Use Lucide React icons, simple and minimal
- Typography: Large headings, readable body text
- Spacing: Generous whitespace between sections"

### Step 5: Interactive Elements
"Add these interactions:
- Smooth scroll between sections
- Fade-in animations for sections on scroll
- Hover effects on demo buttons
- Terminal-style cursor blink in hero headline
- Demo button links to external Calendly URL"

### Step 6: Responsiveness
"Ensure mobile-first responsive design:
- Stack modules/benefits vertically on mobile
- Adjust font sizes for mobile readability
- Maintain dark/light section contrast
- Keep demo buttons prominent on all screen sizes"

### Step 7: Performance & Deployment
"Optimize for:
- Fast loading times
- Clean, semantic HTML
- Accessible color contrast
- SEO meta tags for 'Bloomberg terminal for commercial teams'
- Ready for GitHub Pages deployment"

### Step 8: Final Polish
"Add these finishing touches:
- Subtle box shadows on light sections
- Terminal green accent color for CTAs
- Clean transitions between dark/light sections
- Professional but approachable visual hierarchy
- Remove any intimidating or complex language"

## Key Design Principles

**Color Palette:**
- Dark sections: #1a2025 (prototype background)
- Light sections: #f8f9fa (clean white-gray)
- Primary accent: #06a6bf (prototype teal)
- Text on dark: #fefefeec (prototype white)
- Text on light: #2d3748 (dark gray)
- Secondary text dark: #999FA5 (prototype gray)
- Borders/accents: #424445 (prototype border gray)

**Typography Scale:**
- Hero headline: 3xl/4xl
- Section headlines: 2xl/3xl
- Body text: lg
- Button text: md

**Spacing:**
- Section padding: py-16 lg:py-24
- Container max-width: 1200px
- Component spacing: mb-8 lg:mb-12

**Animation Guidelines:**
- Subtle fade-ins on scroll
- Terminal cursor blink effect
- Smooth hover transitions
- No distracting movements

## Conversion Optimization

**Demo Button Placement:**
1. Header (always visible)
2. Hero section (primary CTA)
3. Final CTA section (secondary)

**Trust Signals:**
- Bloomberg comparison (credibility)
- Specific benefit percentages
- "No IT projects" (removes barriers)
- Simple 3-step process

**Messaging Hierarchy:**
1. What we are (Bloomberg for commercial teams)
2. Why you need it (stop trading blind)
3. How it works (simple 3 modules)
4. What you get (specific benefits)
5. How to start (book demo)