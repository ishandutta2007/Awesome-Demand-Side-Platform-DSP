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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Adobe Advertising Cloud](https://business.adobe.com/products/adobe-advertising-cloud.html)**  

  Enterprise DSP integrated with Adobe Experience Cloud for cross-channel programmatic buying, audience targeting, and measurement.



- **[Google Display & Video 360 (DV360)](https://marketingplatform.google.com/about/display-video-360/)**  

  Google’s premium demand-side platform for display, video, audio, and connected TV advertising with deep YouTube and Google inventory access.



- **[The Trade Desk](https://www.thetradedesk.com/)**  

  Independent, leading DSP known for transparency, advanced targeting, and strong performance across digital channels including CTV.



- **[Amazon DSP](https://advertising.amazon.com/solutions/products/amazon-dsp)**  

  Amazon’s demand-side platform offering access to Amazon inventory and audiences plus third-party exchanges, ideal for retail and brand advertisers.



- **[Criteo](https://www.criteo.com/)**  

  Commerce-focused DSP specializing in retargeting, product recommendations, and performance advertising across retail media and open web.



- **[Basis Technologies](https://basis.com/)**  

  Workflow-centric platform combining DSP capabilities with campaign planning, trafficking, and omnichannel media execution.



- **[MediaMath](https://www.mediamath.com/)**  

  Established DSP offering advanced bidding, audience management, and marketing platform features for agencies and brands.



- **[Amobee](https://www.amobee.com/)**  

  Cross-screen DSP with strong capabilities in TV, digital, and data-driven planning and activation.



- **[Yahoo DSP](https://www.yahooinc.com/advertising)**  

  Yahoo’s demand-side platform providing access to Yahoo inventory and broader programmatic supply with targeting tools.



- **[Viant](https://www.viantinc.com/)**  

  People-based DSP focused on omnichannel advertising, identity, and household-level targeting.



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
