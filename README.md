# Awesome-Demand-Side-Platform-DSP
# Awesome-Demand-Side-Platform-DSP

## Top Demand-Side Platform (DSP)

**Curated List of SaaS Products & Open-Source GitHub Projects**



*Focused on Programmatic Advertising, Real-Time Bidding (RTB), Media Buying & Campaign Optimization*



**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Demand-Side Platforms (DSPs)**. These tools enable advertisers and agencies to buy digital ad inventory programmatically across exchanges using real-time bidding, audience targeting, and campaign optimization.



**Examples** include Adobe Advertising Cloud, Google Display & Video 360, The Trade Desk, Amazon DSP, Criteo, Basis Technologies, MediaMath, Amobee, Yahoo DSP, and Viant (the category leaders).



**Open-source emphasis**: Full-featured commercial DSPs dominate the market due to the complexity of real-time bidding, inventory access, fraud prevention, and scale. However, several open-source **RTB bidder engines**, frameworks, and partial DSP platforms exist — including **RTBkit**, **vanilla-rtb**, **OpenDSP**, **Zhuque**, and related projects. These provide building blocks for custom or self-hosted programmatic solutions. This section is expanded around available open options.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Demand-Side Platform (DSP) market is estimated at approximately $48 billion to $52 billion in 2026, expanding at an annual growth rate of roughly 19% to 24% propelled by Connected TV (CTV), retail media, and programmatic real-time bidding (RTB). The sector exhibits a barbell structure—concentrated at the top where the top 5 platforms command roughly 47% of total market share, yet moderately fragmented across regional and specialized verticals with over 100+ active DSP players globally.

## SaaS/Hosted Platforms

| Platform | Revenue / Valuation (Descending) | Description | Pricing Model & Starting Tier | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Amazon DSP](https://advertising.amazon.com/solutions/products/amazon-dsp)** | ~$2.0T+ Market Cap (~$638B Revenue) | Amazon's demand-side platform offering direct access to Amazon owned-and-operated inventory, audiences, and third-party exchanges. | CPM-based model with $0 minimum spend on self-serve direct access ($3,000–$5,000/mo recommended effective floor; managed-service tier requires $50,000/mo minimum commit). | No free tier or trial; requires funding working media spend (no sandbox trial credits). |
| **[Google Display & Video 360 (DV360)](https://marketingplatform.google.com/about/display-video-360/)** | ~$2.0T+ Market Cap (~$350B Revenue) | Google’s enterprise demand-side platform for cross-channel display, video, audio, and CTV with deep YouTube and Google ecosystem integration. | Percentage-of-media fee (~12%–15% take-rate); accessible via partner resellers starting at $2,000–$5,000/month media spend (direct Google enterprise contracts require six-figure annual commitments). | No free tier or trial; demo access is strictly available via sales-assisted walkthroughs. |
| **[Adobe Advertising Cloud](https://business.adobe.com/products/adobe-advertising-cloud.html)** | ~$150B–$200B Market Cap (~$21.5B Revenue) | Enterprise DSP natively integrated with Adobe Experience Cloud for cross-channel programmatic buying, audience activation, and attribution. | Enterprise software subscription plus tech fee percentage of media spend; starting commitments typically start at $10,000+/month ($100,000+/year contract). | No free tier or trial; platform evaluation is available only through scheduled enterprise guided demos. |
| **[The Trade Desk](https://www.thetradedesk.com/)** | ~$35B–$45B Market Cap (~$2.9B Revenue) | Premier independent DSP known for transparent auctions, CTV leadership, and omnichannel reach across the open internet. | Platform tech fee of ~15%–20% of gross media spend; direct enterprise seats require a minimum spend commit of $100,000/quarter ($33,000+/month) or via resellers at lower minimums. | No free tier or trial; live bidder infrastructure requires enterprise contract execution. |
| **[Yahoo DSP](https://www.yahooinc.com/advertising)** | ~$20B Valuation (~$7B Revenue) | Omnichannel DSP under Apollo Global Management providing access to Yahoo native inventory and global programmatic supply with identity graph solutions. | CPM/percentage-of-spend fee structure; accessible through self-serve and partner tiers with minimum spend starting at ~$2,500–$5,000/month. | No free tier or trial; live bidding requires active campaign funding and credit approval. |
| **[Criteo](https://www.criteo.com/)** | ~$1.5B–$2.0B Market Cap (~$1.9B Revenue) | Commerce-focused DSP and retail media platform specializing in dynamic product retargeting and open-web performance advertising. | Self-serve CPC/CPM model with no platform subscription fee; campaigns start at $0 minimum spend (promotional ad-credit matching offers require meeting an initial $500 spend threshold). | No free tier or trial; requires paying for clicks/impressions delivered (matched ad-credit promos offered periodically). |
| **[Viant](https://www.viantinc.com/)** | ~$800M–$1.0B Market Cap (~$344M Revenue) | People-based omnichannel DSP powered by ViantAI, focusing on household-level identity resolution and CTV advertising. | Choice of SaaS monthly subscription licensing fee starting around $2,500/month or percentage-of-media spend agreements tailored via custom master service contract. | No free tier or trial; interactive product demos provided upon qualified sales consultation. |
| **[Amobee](https://www.amobee.com/)** *(Nexxen)* | ~$500M Market Cap (~$380M Revenue) | Omnichannel and Connected TV DSP acquired by Nexxen (formerly Tremor International) for cross-screen data-driven planning and activation. | Dynamic CPM and programmatic tech-fee model starting at ~$5,000/month minimum media spend under Nexxen platform agreements. | No free tier or trial; prospective agency clients can request custom platform walkthroughs. |
| **[Basis Technologies](https://basis.com/)** | ~$155M Revenue (Private) | Comprehensive media automation platform unifying DSP capabilities with campaign planning, workflow management, and financial reconciliation. | All-inclusive tech fee bundled into working media spend (~10%–15% effective fee) with flexible entry terms ($0 strict contract minimum for independent agency seats). | No free tier or trial; offers a 1-day live interactive personalized demo upon onboarding request. |
| **[MediaMath](https://www.mediamath.com/)** *(Infillion)* | ~$100M Revenue (Private) | Pioneer programmatic DSP acquired and relaunched by Infillion, offering composable architecture, algorithmic bidding, and omnichannel DSP execution. | Modular tech fee pricing starting at ~10%–15% of media spend; custom contract tiers start with minimum monthly commitments of ~$3,000–$5,000. | No free tier or trial; live test seats require Infillion master services agreement onboarding. |

## Open-Source GitHub Projects

- **[RTBkit](https://github.com/rtbkit/rtbkit)**  

  Classic open-source software package for building and deploying a Real-Time Bidder for display advertising. One of the earliest and most referenced open DSP frameworks.



- **[vanilla-rtb](https://github.com/venediktov/vanilla-rtb)**  

  High-performance C++14 cross-platform bidder engine and application framework designed for low-latency RTB and DSP development.



- **[rapid-bidder](https://github.com/vanilla-rtb/rapid-bidder)**  

  Open-source model DSP application built on the vanilla-rtb stack, demonstrating real-time bidding and campaign handling.



- **[OpenDSP](https://github.com/javagossip/opendsp)**  

  Open-source mobile-focused DSP platform with built-in AdX integrations and a ready-to-use dashboard.



- **[Zhuque](https://github.com/javagossip/zhuque)**  

  Open-source all-in-one advertising platform that includes SSP, AdX, DSP, and DMP modules for building a complete programmatic stack.



- **[AdProX (ad_prox_dsp)](https://github.com/nayan9229/ad_prox_dsp)**  

  Feature-rich GoLang-based programmatic DSP supporting OpenRTB, VAST, native ads, HTML5 creatives, fraud detection, and real-time bidding.



- **[BlazeDSP](https://github.com/BlazeDSP/BlazeDSP)**  

  Open-source, cloud-powered Demand Side Platform designed with emphasis on low latency, scalability, and fault tolerance.



- **[OpenADX / related Ad Exchange projects](https://github.com/javagossip/open-adx)**  

  Open-source ad exchange components that can interoperate with custom DSPs for RTB workflows.



- **[Prebid](https://github.com/prebid)**  

  Widely adopted open-source header bidding and unified auction framework (Prebid.js, Prebid Server, Prebid Mobile). While primarily publisher-side, it is foundational to modern programmatic ecosystems.



- **[OpenRTB Libraries & Tools](https://github.com/)** (ecosystem)  

  Various open-source OpenRTB protocol implementations, serializers, and bidder starter kits in Java, Go, C++, and other languages that serve as building blocks for custom DSPs.



### Additional Strong Open-Source Options

- Bidder engines & frameworks: **RTBkit**, **vanilla-rtb**, **rapid-bidder**.

- Full or partial DSP platforms: **OpenDSP**, **Zhuque**, **AdProX**, **BlazeDSP**.

- Supporting open standards: **Prebid** ecosystem and OpenRTB libraries.

- Accepting that commercial DSPs (The Trade Desk, Google DV360, Amazon DSP, Adobe Advertising Cloud, Criteo, etc.) still dominate in inventory access, advanced optimization, fraud protection, identity graphs, reporting, and enterprise support. Open-source options are best suited for custom development, research, or specialized use cases rather than full replacement of major platforms.



**Frameworks for building custom systems**:  

Use **vanilla-rtb** or **RTBkit** as the core bidder engine → extend with campaign management and budget logic → integrate OpenRTB connectors → add reporting and fraud modules. Suitable for teams with strong engineering resources that need full control over bidding logic or wish to build specialized programmatic solutions.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Demand-Side Platforms involve real-time financial transactions, user data, and advertising regulations. Building or operating a DSP requires significant technical, legal, and compliance expertise (including privacy laws, brand safety, and anti-fraud measures). Open-source components provide transparency but do not replace the operational and inventory advantages of established commercial platforms. This list is not legal, financial, or technical advice.



---

**Made for ad-tech engineers, programmatic specialists, and open-source advocates.**



Let's keep programmatic advertising technology more transparent and accessible where practical.
