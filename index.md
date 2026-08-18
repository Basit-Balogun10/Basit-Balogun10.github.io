---
title: Home
permalink: /
---

# Basit Balogun

Software engineer, making myself a noob again on purpose - chip design, verification, firmware, learned live on stream. [A little more on why I'm actually doing this →](/about/)

<div class="social-links">
  <a href="mailto:basitbalogun10@gmail.com">Email</a>
  <a href="https://github.com/Basit-Balogun10">GitHub</a>
  <a href="https://www.twitch.tv/basitbalogun10">Twitch</a>
  <a href="https://www.youtube.com/@basitbalogun10">YouTube</a>
  <a href="https://linkedin.com/in/basit-balogun">LinkedIn</a>
  <a href="https://x.com/Basit_Balogun10">X</a>
</div>

I basically stream that process and the things I'm building live, and whenever something's actually finished it turns into a [write-up](/blog/) (and hopefully a walkthrough on YouTube as well). [Here's what I'm actually building →](/roadmap/)

<details class="resume-toggle">
<summary>Here's some highlights about myself <span class="chevron">›</span></summary>
<div class="resume-content" markdown="1">

## Professional experience

**Software Engineering Intern → Software Engineer**, Matt Young Media (MYM) - *Apr 2023 – Feb 2024*

- Developed and shipped key features and bug fixes for a leads generation tool, reducing pre-launch crashes by over 20%.
- Was instrumental in transitioning a large frontend codebase from JavaScript to TypeScript, significantly boosting code reliability and maintainability.
- Deep integration with LinkedIn APIs on the backend to extract user data, automate connection requests, and analyze engagement patterns for lead generation and content optimization.
- Implemented AI-powered features for content creation and personalization, enabling public figures and sales professionals to create high-converting posts and messages.

**Web Developer**, Synergy Network International - *Mar 2021 – Jan 2022*

## Open source contributions

**PostHog** (open source all-in-one developer platform)

- **Feature ownership (i18n)**: Took the initiative to architect the end-to-end implementation of internationalization for Surveys - enabling global customers to manage a single survey across multiple languages, eliminating the need to create duplicate surveys and manually merge response data (issue #42154).
- **Backend & architecture**: Designed a hybrid storage schema to ensure data integrity - mapped question translations inline to support reordering, while keeping global fields at the root level (#45096, merged as #47934).
- **Frontend & SDK**: Built the translation panel/feature with input validation into the Surveys creation editor (#45281, merged as #52949), and drafted the client-side language detection logic and survey translations rendering for the JS SDK (#3004, merged as #3488).

**PostHog/code** (desktop AI coding agent)

- **Cross-platform reliability**: Fixed a Windows-specific binary path resolution bug in the agent runtime, and resolved a sidebar layout issue affecting task navigation.
- **Session management**: Shipped model-selection persistence, ensuring the agent retains the selected model across mid-task changes.
- **Keyboard navigation**: Designed and demoed keyboard navigation and a jump-to-message picker for long conversations - the implementation was later recreated and merged by a maintainer, who credited the design directly in the PR.

**Lightdash** (open source BI tool)

- **Communication & planning**: Authored a detailed implementation plan for a highly-requested "Cancel Query" feature, facilitating the technical discussion with maintainers to break the work into manageable PRs.
- **Backend**: `feat: allow email configuration without authentication`
- **Frontend/UX**: `feat: allow tab and enter to navigate/apply categories`
- **Testing**: `test: create pivot table on explore`

**Other contributions**

- **GitHub Docs**: Fixed duplicated steps in the Octernships application guide.
- **Apify**: Fixed a critical destructuring import for EventEmitter in `apify-shared-js`.
- **HackSoftware**: Corrected issues in the Django Styleguide and Google OAuth examples.

## Projects

**Farmceries** - React Native, TypeScript, Express.js, Redis, NativeWind · *Jan 2024 – Present*

- As the sole engineer, led the end-to-end technical development of an award-winning cross-platform mobile e-commerce app addressing socio-economic challenges for farmers, vendors, and consumers.
- Single-handedly executed the complete product development lifecycle from conceptualization to production-ready state - market research, UI/UX design from sketches, full-stack development, and backend architecture.
- Built a scalable Node.js/Express.js backend with Redis caching and session management, and developed the React Native frontend with NativeWind styling.
- Took ownership of product strategy and customer-centric design, resulting in a user-friendly interface that generated significant pre-launch interest and waitlist growth.
- Wore multiple hats (engineer, designer, product strategist) while collaborating effectively with non-technical team members.

**"Fuse" - Cloud-Native Platform** - Microservices, AWS, Kubernetes, Terraform, Docker, Ansible, ELK Stack, PagerDuty *(contract, private repo)*

- After delivering the web application, architected and implemented a complete, production-grade cloud-native ecosystem on AWS for a multi-service application, automating the entire infrastructure and deployment lifecycle from scratch.
- Built a CI/CD pipeline with GitHub Actions, featuring dynamic image tagging, automated environment creation/teardown for PRs, semantic versioning, and integrated security scanning.

**Secure UART Peripheral** (AI-HDL 2026) - Verilog, Cocotb, Yosys, OpenLANE

- Repository: [github.com/Basit-Balogun10/team-farmceries-AI-HDL-2026](https://github.com/Basit-Balogun10/team-farmceries-AI-HDL-2026/tree/basit-dp-1)
- Designed and implemented a complete UART serial communication system with 4 configurable baud rates and a memory-mapped register interface for a RISC-V CPU.
- Integrated an AES-128 hardware encryption engine directly into the datapath, achieving successful synthesis (~98k cells) using Yosys.
- Developed comprehensive testbenches using Python and Cocotb to verify cryptographic transformations and serial data transmission.

## Hackathon achievements

**Winner - ISQED Agentic AI Design Verification Challenge 2026**

- Won the ISQED Agentic AI Design Verification Challenge 2026.
- Proof: [LinkedIn post](https://lnkd.in/p/dXHPDn9V)

**2nd Place Winner - GTCO Squad Hackathon 2.0** *(March 2025)*

- Engineered the full integration of the Squad payment provider into the Farmceries mobile app, culminating in a powerful live demo that secured a 2nd place victory.
- Proof: Winning Moment (Instagram)

**5th Place Finalist - Cavista Hackathon "Pulse"** *(March 2025)*

- Demonstrated extreme resilience by pivoting from a mobile build blocked by a critical bug to rapidly prototype a new "Uber for Healthcare" web app in under 2 hours, securing a top 5 finish.
- Links: Live App | Demo Video | GitHub

**Round 2 Qualifier - Nigeria MATLAB Coding Challenge** *(November 2024)*

- Developed a "Crop Planner App" using MATLAB to help farmers optimize planting sessions, advancing to the Top 10 finalist round in a nationwide competition.
- Links: App Pitch Deck | Certificate | Code Submission

**Top 10 Finalist - Pipeops Hackops Hackathon** *(June 2024)*

- Successfully navigated a critical submission failure under pressure, ensuring the team's project was evaluated and advanced to the Top 10 finalists from over 100 entries.

**Global Summit Finalist - Hult Prize Challenge ("Farmceries")** *(April 2024)*

- Propelled the Farmceries project onto the world stage by securing a spot as a Global Summit Finalist, selected from thousands of international applications.
- Proof: Summit Invitation Letter

**3rd Place Winner - Cavista Hackathon ("HealthAlt")** *(April 2024)*

- Won 3rd place by building a full-stack, AI-powered health app in under 24 hours that suggests food alternatives and connects users with vendors.
- Links: Live App | Demo Video | GitHub | Devpost

**1st Place Winner - FSI Innovation Challenge ("Farmceries")** *(January 2024)*

- As the sole engineer, built the winning MVP for Farmceries in React Native on my first attempt with the framework in a professional setting, securing 1st place in my debut hackathon.
- Proof: News Feature (Google Search)

## Testimonials

> "Basit was an absolute pleasure to work with. His remarkable work ethic was not only matched by his skill level but also by his ability and willingness to assist those around him. Basit would be a valuable addition to any team."
> - Charles Leighton, Solutions Engineer, LucidLink

> "His eagerness to constantly develop himself and nurture his knowledge have taken him from being an ordinary LeetCode problem-solver to mastering several technologies... He is, indeed, a four-leaf clover for whomever is lucky enough to have him in their team."
> - German Cousillas Martinez, Former IT Director, Synergy Network International

> "Basit helped create a website for my football coaching company. I was amazed by the standard and the quality... Basit is a great communicator and does exactly what you ask of him. I fully recommend anybody to try Basit and his quality work."
> - James Makanjuola, Head/Founder, Titans Chelmsford

## Education

**Bachelor of Science, Electrical and Electronics Engineering**
University of Lagos

</div>
</details>
