<<<<<<< HEAD
# Awesome-Product-Customization

=======
<div align="center">

<img src="./assets/banner.svg" alt="Awesome Product Customization Banner" width="100%" />

# 🎨 Awesome Product Customization 🛍️
### ✨ Top Product Options, 3D Configurators & Personalization Ecosystem 🚀

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://awesome.re/badge.svg" alt="Awesome" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Product-Customization"><img src="https://img.shields.io/badge/Open--Source%20Repos-Curated-blue.svg" alt="Curated Open-Source" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License: MIT" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Product-Customization/blob/main/README.md#how-to-contribute"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 🌟 A curated directory of production-grade SaaS products, 3D product configurators, and open-source GitHub projects for **Product Customization**, **Product Options**, **Custom Fields**, and **Visual Personalization Workflows** across Shopify, WooCommerce, PrestaShop, VTEX, and headless architectures.

📅 *Last updated: October 2026.*

</div>

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS / Hosted Platforms](#️-saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
  - [🕹️ Frameworks & 3D Web Configurators](#️-frameworks--3d-web-configurators)
  - [🏢 ERP & Platform-Specific Modules](#-erp--platform-specific-modules)
  - [🛒 WooCommerce Extensions & Plugins](#-woocommerce-extensions--plugins)
  - [⚙️ Headless Libraries & Native Toolkits](#️-headless-libraries--native-toolkits)
- [⭐ Star History](#-star-history)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global product customization and configurator software market is valued at approximately **$1.28 billion to $1.5 billion** (scaling toward **$5.14+ billion by 2030** when paired with broader AI-driven dynamic personalization and CPQ engines at a 15–23% CAGR), embedded within a massive **$100B+** mass-customization and on-demand print/manufacturing ecosystem. 📈

Market dynamics remain **moderately fragmented and platform-asymmetric rather than winner-take-all**: native platform constraints (such as Shopify's historical 3-option/100-variant limit) created a resilient long tail of specialized third-party app developers and boutique visual CPQ tools, though roll-up aggregators (e.g., Shop Circle acquiring Bold and HulkApps tools) and platform-level API evolutions are steadily driving consolidation at the enterprise tier. 🌐

---

## ☁️ SaaS / Hosted Platforms

Below is a curated comparison of leading hosted SaaS product customization platforms, sorted by estimated parent company scale (revenue/valuation descending). 🏆

| Product | Developer / Parent Company | Company Scale (Revenue / Valuation) | Starting Tier Pricing | Free Tier / Trial Limit | Key Capabilities & Architecture |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Shopify Line-Item Properties](https://help.shopify.com/en/manual/online-store/themes/customizing-themes)** | Shopify Inc. (NYSE: SHOP) | ~$12.18B TTM Revenue / ~$215B–$224B Market Cap | $0/mo (Included in Shopify plans starting at $39/mo) | Free forever on any active Shopify store (zero extra app fees) | Core native form properties (`properties[...]`) stored directly on order line items; basic text/file fields without conditional logic or upcharges. |
| **[Bold Product Options](https://apps.shopify.com/product-options)** | Shop Circle (acquired from Bold Commerce) | ~$43M–$45M ARR / ~$305M+ Total Capital Raised | $14.99/mo (Basic Plan) | 14-day free trial on live stores; free indefinitely on Shopify Partner development stores | Custom option sets, text inputs, radio buttons, file uploads; $39.99/mo tier unlocks conditional logic and price upcharges. |
| **[Hulk Product Options](https://apps.shopify.com/hulk-product-options)** | HulkApps / Shop Circle | ~$11.6M–$19.1M ARR (Parent acquired / aggregated) | $10.00/mo (Basic Plan) | 7-day free trial; free access restricted to Shopify Partner development stores | 12+ input types, color/image swatches, file uploads, formula-based options, and Shopify B2B catalog support. |
| **[Infinite Options](https://apps.shopify.com/custom-options)** | ShopPad Inc. | Privately held SaaS (~$5M–$10M est. ARR; $500K Seed) | $12.99/mo (Essential Plan) | 14-day free trial across all features | Unlimited options, dropdowns, radio buttons, conditional visibility, number inputs, and product bundling. |
| **[Kickflip](https://gokickflip.com/)** | Kickflip (formerly MyCustomizer) | ~$2.3M ARR / Early VC-backed (~$50K+ seed) | $59.00/mo (Base plan) | 14-day free trial (no credit card required upfront) | Real-time multi-component visual configurator, full-page/modal embeds, live color/texture mapping, and translation support. |
| **[Zepto Product Personalizer](https://apps.shopify.com/product-personalizer)** | Zepto Apps | Bootstrapped SaaS (~$1M–$3M est. ARR) | $9.99/mo (Starter Plan) | 15-day free trial (no permanent free tier on live stores) | Live visual preview on canvas/product images, 22+ option inputs, layer-based graphics, and font selection. |
| **[Variant Option Product Options](https://apps.shopify.com/variant-option-product-options)** | Relentless Apps | Bootstrapped SaaS (~$500K–$1.5M est. ARR) | $9.99/mo (Basic Plan) | Free forever plan strictly limited to 1 product; 14-day free trial on paid plans | Unlimited options on 1 product for free; paid tier unlocks unlimited products, conditional logic, and add-on pricing. |
| **[Customify](https://apps.shopify.com/customify)** | Customify | Bootstrapped SaaS (~$300K–$800K est. ARR) | $10.00/mo (Lite Plan) | Free forever tier limited to 3 custom products, 3 paid custom orders/mo, and 256MB file storage (14-day trial on paid tiers) | Drag-and-drop web-to-print personalizer, custom artwork/photo uploads, and print-ready vector/raster exports. |
| **[King Product Options](https://apps.shopify.com/king-product-options)** | YMQ | Bootstrapped SaaS (~$200K–$600K est. ARR) | $0.00/mo (Free Core App) | Free forever with unlimited products and unlimited options | Free tier includes swatches, file upload fields, text inputs, option templates, and conditional display rules. |

---

## 💻 Open-Source GitHub Projects

Open-source product customization repositories sorted descending by GitHub Stars_Count. Each entry links to the official repository and includes an interactive social Stars_Badge linking directly to the repo's stargazers. 🌟

### 🕹️ Frameworks & 3D Web Configurators

- **[threejs-3d-room-designer](https://github.com/CodyMQ/threejs-3d-room-designer)** [![GitHub_Stars](https://img.shields.io/github/stars/CodyMQ/threejs-3d-room-designer?style=social&color=white)](https://github.com/CodyMQ/threejs-3d-room-designer/stargazers)  
  *Stack: React.js, Three.js, WebGL*  
  Comprehensive browser-based 3D room planner and modular product configurator. Demonstrates real-time texture mapping, dynamic material swaps, spatial dimension scaling, and 3D scene customization for home goods and interior fixtures. 🛋️

- **[Industry-Product-Configurator](https://github.com/Unity-Technologies/Industry-Product-Configurator)** [![GitHub_Stars](https://img.shields.io/github/stars/Unity-Technologies/Industry-Product-Configurator?style=social&color=white)](https://github.com/Unity-Technologies/Industry-Product-Configurator/stargazers)  
  *Stack: Unity, C#, WebGL / Multi-platform*  
  Lightweight industrial product configurator framework authored by Unity Technologies. Supports visibility toggling, material variants, camera preset transitions, and transform animations for complex mechanical, automotive, and industrial products. 🚗

- **[Product-Configurator (React-Three)](https://github.com/Khushi-Singh25/Product-Configurator)** [![GitHub_Stars](https://img.shields.io/github/stars/Khushi-Singh25/Product-Configurator?style=social&color=white)](https://github.com/Khushi-Singh25/Product-Configurator/stargazers)  
  *Stack: React, Vite, Three.js*  
  Headless 3D product customization web app loading glTF/GLB models dynamically. Allows end users to alter part colors, textures, and finishes with live 360-degree interactive preview. 👟

---

### 🏢 ERP & Platform-Specific Modules

- **[OCA/product-configurator](https://github.com/OCA/product-configurator)** [![GitHub_Stars](https://img.shields.io/github/stars/OCA/product-configurator?style=social&color=white)](https://github.com/OCA/product-configurator/stargazers)  
  *Stack: Python, Odoo ERP*  
  Enterprise-grade Odoo dynamic product configurator maintained by the Odoo Community Association (OCA). Handles complex multi-level attribute dependencies, dynamic bill-of-materials (BOM) generation, and real-time sales price calculation. 📦

- **[customizr](https://github.com/carolineschnapp/customizr)** [![GitHub_Stars](https://img.shields.io/github/stars/carolineschnapp/customizr?style=social&color=white)](https://github.com/carolineschnapp/customizr/stargazers)  
  *Stack: JavaScript, Liquid, Shopify Theme Architecture*  
  Pioneering open-source Shopify customization module designed by Caroline Schnapp. Demonstrates headless line-item properties injection, dynamic custom form elements, and file upload handlers for custom engraving and bespoke order details. 🛍️

- **[vtex-apps/product-customizer](https://github.com/vtex-apps/product-customizer)** [![GitHub_Stars](https://img.shields.io/github/stars/vtex-apps/product-customizer?style=social&color=white)](https://github.com/vtex-apps/product-customizer/stargazers)  
  *Stack: TypeScript, React, VTEX IO*  
  Official VTEX IO storefront product customizer app. Renders dynamic assembly options, attachment items, text personalization fields, and complex add-on services directly integrated into VTEX checkout. 🔌

---

### 🛒 WooCommerce Extensions & Plugins

- **[woocommerce-product-customizer](https://github.com/marcusig/woocommerce-product-customizer)** [![GitHub_Stars](https://img.shields.io/github/stars/marcusig/woocommerce-product-customizer?style=social&color=white)](https://github.com/marcusig/woocommerce-product-customizer/stargazers)  
  *Stack: PHP, WordPress, WooCommerce*  
  WooCommerce product configurator and visual customization engine allowing shoppers to configure physical goods with real-time live preview layers prior to cart addition. 🎨

- **[snelgraveren-product-designer](https://github.com/temmink/snelgraveren-product-designer)** [![GitHub_Stars](https://img.shields.io/github/stars/temmink/snelgraveren-product-designer?style=social&color=white)](https://github.com/temmink/snelgraveren-product-designer/stargazers)  
  *Stack: PHP, JavaScript, Canvas, WooCommerce*  
  Drag-and-drop web-to-print and laser-engraving designer for WooCommerce. Supports custom SVG text pathing, bitmap photo uploads, bounding-box constraints, and print-ready export. 🖨️

- **[Aldono (plogins-addons)](https://github.com/wppoland/plogins-addons)** [![GitHub_Stars](https://img.shields.io/github/stars/wppoland/plogins-addons?style=social&color=white)](https://github.com/wppoland/plogins-addons/stargazers)  
  *Stack: PHP, WordPress / WooCommerce*  
  Lightweight open-source product options plugin for WooCommerce. Adds 7 input field types (text, textarea, number, date, checkbox, select, radio), per-option price adjustment, character limits, and zero custom database table overhead. 🔧

- **[Swatch (plogins-swatch)](https://github.com/wppoland/plogins-swatch)** [![GitHub_Stars](https://img.shields.io/github/stars/wppoland/plogins-swatch?style=social&color=white)](https://github.com/wppoland/plogins-swatch/stargazers)  
  *Stack: PHP, JavaScript, CSS*  
  Lightweight, accessible variation swatches plugin replacing traditional HTML `<select>` variation dropdowns with responsive color swatches and button pickers. Zero external dependencies and native WooCommerce form integration. 🎯

---

### ⚙️ Headless Libraries & Native Toolkits

- **[product-variants-core](https://www.npmjs.com/package/product-variants-core)**  
  *Stack: TypeScript / Node.js*  
  Type-safe JavaScript/TypeScript core library for headless CPQ and variant logic. Generates valid variant permutations, enforces JSON conditional constraint rules (e.g., mutually exclusive options), and computes dynamic price modifiers. 🧩

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Product-Customization&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Product-Customization&type=date&legend=top-left)

---

## 💖 Support & Sponsorship

Thank you so much for exploring and using this repository! 🙏 If you find this curated directory useful for your ecommerce store, client projects, or technical research, please consider supporting the project:

- ⭐ **Star this repository** to help others discover it
- 🍴 **Fork it** and contribute new tools or updates
- 📢 **Share it** with fellow merchants, architects, and theme developers
- ☕ **Buy me a coffee / sponsor ongoing maintenance**: Support via the [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007)

Every contribution and star is deeply appreciated! 🌟

---

## 🤝 How to Contribute

Contributions to expand this curated list are welcome! 🚀

1. Fork the repository.
2. Add your SaaS product or open-source repository into the appropriate section.
3. For open-source entries, ensure you include:
   - Name and direct GitHub link
   - Social Stars_Badge linking to `/stargazers`
   - Primary tech stack and 1–2 factual description sentences
4. For SaaS entries, supply accurate pricing and transparent free-tier/trial terms.
5. Submit a Pull Request with a concise summary of additions.

---

## ⚠️ Disclaimer

- This repository is a community-maintained curated educational directory and does not constitute commercial endorsement.
- All product names, trademarks, and registered trademarks are property of their respective owners.
- Security note: Production customization engines handling uploaded files and personalized user input must enforce strict file format whitelisting, antivirus/malware scanning, and PII protection compliance (GDPR/CCPA).
>>>>>>> 798d6816c39672008f19c03c4012fe507b8e1738
# Awesome-Product-Customization
**Top Product Customization (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Product Options, Variant Expansion, File Uploads & Personalization Workflows*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Product Customization**. These tools enable merchants to offer personalized products—engraving, monograms, file uploads, conditional option fields, and variant expansion—from fully managed Shopify apps with conditional logic and live previews to open-source frameworks and developer references that give teams control over customization data and workflows.

**Examples** include Shopify Line-Item Properties, Bold Product Options, Infinite Options, Hulk Product Options, Zepto Product Personalizer, Variant Option Product Options, Customify, Kickflip, King Product Options, and TailorKit (the category leaders and developer tools in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, product personalization, and open customization infrastructure. **Critical note**: True open-source Shopify product customization apps—production-ready with conditional logic, file uploads, and live previews—do not exist. The projects below are **customizer frontends**, **developer SDKs**, or **MCP integrations** that require you to build or operate the backend. For merchants wanting a working app, commercial options remain the practical path.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Shopify Line-Item Properties](https://shopify.dev/docs/storefronts/themes/architecture/properties)** (**Native**)
  **Built-in customization data attachment** for cart lines and orders. Supports text inputs, dropdowns, checkboxes, and simple file references, attached to the line item and visible in the admin and order data . **Pricing**: Free with Shopify. **Free tier**: Yes. **Best for**: merchants needing basic text or simple selections without advanced workflows—**not suitable for multi-file uploads, validation, or conditional logic** .

- **[SC Product Options (formerly Bold)](https://apps.shopify.com/product-options)**
  **The most established Shopify product options app** (founded 2012), now operated by Shop Circle. **Pricing**: **Free** developer edition; **Basic** $14.99/month (unlimited options, file uploads); **Advanced** $39.99/month (conditional logic, pricing add-ons, cart editing, color samples) . **Free tier**: Developer stores only. **Best for**: merchants wanting a proven, feature-rich options app with a long track record—**note**: reviews report post-acquisition support and sync issues .

- **[Infinite Options](https://apps.shopify.com/custom-options)** (ShopPad)
  **Flexible product options app** with text boxes, dropdowns, checkboxes, swatches, conditional logic, and add-on pricing. **Pricing**: **Essential** $12.99/month . **Free tier**: None. **Best for**: merchants wanting a straightforward options app at a low monthly cost.

- **[Hulk Product Options](https://apps.shopify.com/product-options-4)**
  **Tiered options app** with 12–20+ option types, file uploads, and conditional logic (Advanced+). **Pricing**: **Basic** $10/month (12 option types, no conditional logic); **Advanced** $20/month (20 types, conditional logic, cart editing); **Enterprise** $49.90/month (inventory/SKU management, formula options, POS) . **Free tier**: Development stores only. **Best for**: merchants wanting granular tier options with predictable pricing—**conditional logic requires Advanced** .

- **[Zepto Product Personalizer](https://apps.shopify.com/product-personalizer)**
  **Visual personalization app with live preview** and 1,400+ reviews averaging 4.9. Installed on ~8,354 stores . **Pricing**: Quote-only; tiered by features. **Free tier**: None. **Best for**: merchants selling personalized products needing live visual previews (names, images, themes)—**strong support reputation** .

- **[Variant Option Product Options](https://apps.shopify.com/variant-option-product-options)** (Relentless Apps)
  **Variant expansion and options app** installed on ~26,700 stores, rated 4.6 . **Pricing**: Quote-only; tiered. **Free tier**: None. **Best for**: merchants hitting Shopify's option limits and needing variant add-ons without rebuilding products.

- **[Customify](https://apps.shopify.com/customify)**
  **Custom product builder** installed on ~1,761 stores, rated 4.4 . **Pricing**: Quote-only. **Free tier**: None. **Best for**: merchants wanting a product builder interface for configurable products.

- **[Kickflip](https://gokickflip.com/)**
  **Product customizer with visual design tools**. Integrates via Shopify App Embed to replace the product page with a customizer or add a "Customize" button . **Pricing**: Quote-only. **Free tier**: None. **Best for**: merchants selling designed products (apparel, print) needing an interactive design canvas.

- **[King Product Options](https://apps.shopify.com/king-product-options)** (Ymq)
  **High-install options app** on ~43,929 stores, rated 4.7—but installs declined 40% year-over-year . **Pricing**: Quote-only. **Free tier**: None. **Best for**: merchants wanting an established options app with broad adoption—**investigate the declining install trend before committing**.

- **[TailorKit](https://tailorkit.com/)** (**Developer Tool**)
  **Product customization framework** with template management, layer control, and Shopify integration. **Open-source MCP server** (MIT) connects AI assistants to the TailorKit API for natural-language template management . **Pricing**: Framework/SaaS pricing; MCP server free (MIT). **Free tier**: MCP server is open-source. **Best for**: developers wanting to build personalization experiences with AI-assisted template management.

## Open-Source GitHub Projects

- **[TailorKit MCP](https://github.com/sellersmith/tailorkit-mcp)**
  **Open-source MCP server for product customization templates** (MIT) — **the most directly relevant open-source tool for AI-driven product customization management**. **Features**: Connects Claude and other AI assistants to the TailorKit API; tools include `get_list_templates`, `get_detail_template`, `create_template`, and `get_list_layers_of_template`; enables natural-language management of customizable product templates and layers . **Tech stack**: Node.js, TypeScript. **Deploy**: npm (`@sellersmith/tailorkit-mcp`) or from GitHub . **Trade-off**: **Requires TailorKit API access and account**—it is an integration layer, not a standalone customizer. No frontend, no file upload handling, no Shopify storefront integration on its own. **Best for**: developers already using TailorKit wanting AI-assisted template management workflows.

- **[pastel-charms](https://github.com/noorfatma160207-dotcom/pastel-charms)**
  **Interactive SVG bracelet customizer** (license per repo) — **a working reference for visual product customization with real-time preview**. **Features**: Real-time SVG rendering of beads and letter beads as users type; 7 color palettes and 3 letter styles; spacers and charms; **dynamic price engine** updating in real time; persistent cart via localStorage; WhatsApp order generation . **Tech stack**: HTML5, CSS3, Vanilla JavaScript, SVG. **Deploy**: Static hosting (open `index.html` or `python -m http.server`) . **Trade-off**: **Static demo for handmade bracelets**—no backend, no payment processing, no Shopify integration. It is a **visual customizer reference**, not a platform. **Best for**: developers wanting a working example of SVG-based live product preview and price calculation.

- **[t-shirt-customizer](https://github.com/jaimin0609/t-shirt-customizer)**
  **Full-stack T-shirt customization application** (MIT) — **a complete reference for design-on-product workflows**. **Features**: Text, image, and design customization; **3D preview** via Three.js; user authentication; cart and checkout; admin panel for products and orders . **Tech stack**: React, Vite, Three.js, Node.js, Express, Sequelize, MySQL/PostgreSQL, JWT. **Deploy**: Self-hosted (backend + frontend) . **Trade-off**: **Standalone application, not a Shopify app**—no Shopify integration, no metafield handling, no order data mapping to Shopify line items. **Best for**: developers building a standalone custom merchandise platform, or wanting a reference for 3D product preview.

- **[Crex](https://github.com/albykennady/Crex)**
  **Merchandise customization platform with canvas editing** (license per repo) — **a Firebase-backed design tool reference**. **Features**: Fabric.js canvas for logos and graphics; real-time preview; saved projects; cart and order management; Firebase Auth, Firestore, and Storage . **Tech stack**: HTML5, JavaScript, Fabric.js, Firebase. **Deploy**: Static hosting (open `index.html` via Live Server) . **Trade-off**: **Internal-use platform**—no Shopify integration, no payment processing, no production hardening. **Best for**: developers wanting a reference for Fabric.js-based product design canvases.

- **[WooCommerce Products Designer](https://github.com/common-repository/woocommerce-products-designer)**
  **WooCommerce product design plugin** (GPLv2) — **the most mature open-source customizer for WooCommerce**. **Features**: Web-to-print design tool for t-shirts, mugs, cards, and more; clipart libraries, text and image editors, multiple output formats; WPML compatible. **Pro features**: templates, design saving, SVG/PDF outputs, print-ready files with bleed zones, custom pricing rules . **Tech stack**: PHP (WordPress/WooCommerce). **Deploy**: WordPress plugin. **Trade-off**: **WooCommerce-specific**—not usable on Shopify. Pro features require paid upgrade. **Best for**: WooCommerce merchants wanting a self-hosted product designer plugin.

### Additional Strong Open-Source Options

- **Shopify Hydrogen `getProductOptions`** — Official Hydrogen utility for handling product options and variants (including 2,000+ variant support) . **Note**: Developer utility, not a customizer—handles option display and selection, not file uploads or personalization fields . **Best for**: Hydrogen developers building custom storefronts needing robust option handling.
- **shopify-mcp** — MCP server for Shopify Admin API (MIT, 31 tools) including `manage-product-options` and `manage-product-variants` . **Note**: API automation tool, not a customer-facing customizer—enables AI assistants to create and modify product options programmatically . **Best for**: developers wanting to automate product option management via AI assistants.

**Frameworks for building custom systems**: Combine **pastel-charms** as a reference for SVG preview logic with **t-shirt-customizer** for 3D rendering and full-stack patterns, **TailorKit MCP** for AI-assisted template management if using TailorKit, and **WooCommerce Products Designer** for WooCommerce deployments—creating a customization stack. **None of these provide a turnkey Shopify product options app** with conditional logic, file uploads, and order data mapping—those require commercial apps or custom Shopify app development.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Product customization platforms handling customer-uploaded files and personalization data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate file validation and storage security.
- **The "Shopify app" vs. "developer framework/SDK" vs. "standalone customizer reference" distinction is critical.** **SC Product Options, Infinite Options, Hulk, Zepto, Variant Option, Customify, Kickflip, and King** are **Shopify apps**—they install into a store and work with Shopify's cart and order data. **TailorKit MCP** is a **developer integration**—it requires TailorKit API access and does not render a customizer UI. **pastel-charms, t-shirt-customizer, and Crex** are **standalone references**—they demonstrate customization patterns but have no Shopify integration. **WooCommerce Products Designer** is **WooCommerce-specific**. **No open-source project provides a production-ready Shopify product options app.**
- **Shopify's native line-item properties are limited.** They handle small text fields well but are **not a file-management system**—multiple uploads, validation, conditional fields, and DPI/dimension enforcement are not supported . For anything beyond simple text, an app is the practical path.
- **Conditional logic is a paid-tier feature across all apps.** Infinite Options includes it on Essential . Hulk requires Advanced ($20/month) . SC Product Options requires Advanced ($39.99/month) . **Do not expect conditional workflows on free or basic tiers.**
- **Zepto's support reputation is notably strong**, with reviews consistently praising 24/7 responsiveness and custom fixes . **King Product Options has broad adoption but declining installs** (-40% YoY)—investigate before committing .
- **TailorKit MCP is the most interesting open-source project in this space** for developers wanting AI-assisted template management, but it is an integration layer, not a customizer . **pastel-charms is the best working reference for live visual preview** with dynamic pricing .
- **Pricing opacity varies.** Infinite Options publishes $12.99/month . Hulk publishes tiered pricing ($10–$49.90) . SC Product Options publishes tiers ($14.99–$39.99) . Zepto, Variant Option, Customify, Kickflip, and King require sales contact. **Validate with direct vendor conversations against your option complexity and order volume.**
- Self-hosted open-source solutions require proper setup, file storage security, and ongoing maintenance. **Customer-uploaded files can contain sensitive content**—ensure your deployment includes file validation, storage access controls, and compliance with your organization's security standards before accepting uploads.

---

**Made for developers, merchants, and organizations building transparent product customization solutions.**
Let's make Product Customization more open, data-driven, and merchant-friendly.
