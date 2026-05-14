# The Computational Architecture of Free Culture Tabletop Roleplaying Games: A Curated List and Analytical Directory

## Table of Contents

- [The Computational Architecture of Free Culture Tabletop Roleplaying Games: A Curated List and Analytical Directory](#the-computational-architecture-of-free-culture-tabletop-roleplaying-games-a-curated-list-and-analytical-directory)
  - [Table of Contents](#table-of-contents)
  - [The Intersection of Open Source Software and Tabletop Game Design](#the-intersection-of-open-source-software-and-tabletop-game-design)
  - [The Legal Ontology of TTRPG Licensing](#the-legal-ontology-of-ttrpg-licensing)
    - [The Fallacy of the Open Game License and the ORC Alternative](#the-fallacy-of-the-open-game-license-and-the-orc-alternative)
    - [The Taxonomy of Truly Free Licenses](#the-taxonomy-of-truly-free-licenses)
    - [The Exclusionary Nature of Non-Commercial Clauses](#the-exclusionary-nature-of-non-commercial-clauses)
  - [The Technological Architecture of TTRPG Repositories](#the-technological-architecture-of-ttrpg-repositories)
    - [Plain Text and the Markdown Paradigm](#plain-text-and-the-markdown-paradigm)
    - [Continuous Integration and Automated Rendering](#continuous-integration-and-automated-rendering)
    - [Complex Compilation via LaTeX and Automation Scripts](#complex-compilation-via-latex-and-automation-scripts)
  - [Curated Directory of Free Culture TTRPGs](#curated-directory-of-free-culture-ttrpgs)
    - [Narrative Frameworks and PBTA Implementations](#narrative-frameworks-and-pbta-implementations)
      - [Aspirant](#aspirant)
      - [Reclaimers](#reclaimers)
      - [LTTS](#ltts)
      - [Charge](#charge)
      - [Lady Blackbird](#lady-blackbird)
    - [Old School Renaissance (OSR) and Rules-Lite Engines](#old-school-renaissance-osr-and-rules-lite-engines)
      - [Basic Fantasy Role-Playing Game (BFRPG)](#basic-fantasy-role-playing-game-bfrpg)
      - [Cairn](#cairn)
      - [BIND (BIND is Not D\&D)](#bind-bind-is-not-dd)
      - [Pocket Quest (Open Adventure)](#pocket-quest-open-adventure)
      - [Chronicles](#chronicles)
    - [**Universal Systems and Agnostic Frameworks**](#universal-systems-and-agnostic-frameworks)
      - [Quest (The Adventure Guild)](#quest-the-adventure-guild)
      - [Freeform Universal (FU)](#freeform-universal-fu)
      - [Agora](#agora)
      - [Open Lore](#open-lore)
      - [1w6](#1w6)
      - [Additional Open Frameworks](#additional-open-frameworks)
  - [Build Artifacts](#build-artifacts)
    - [Aspirant: The Advent Edition](#aspirant-the-advent-edition)
    - [BIND: Print-Optimized LaTeX Compilation](#bind-print-optimized-latex-compilation)
    - [Cairn: Multi-Format Digital Deployment](#cairn-multi-format-digital-deployment)
    - [Basic Fantasy RPG: Core Rules 4th Edition](#basic-fantasy-rpg-core-rules-4th-edition)
    - [Charge: System Reference Document Outputs](#charge-system-reference-document-outputs)
    - [Reclaimers: Static Site Renderings](#reclaimers-static-site-renderings)
  - [Synthesizing the Future of Open Tabletop Systems](#synthesizing-the-future-of-open-tabletop-systems)
      - [Bibliography](#bibliography)


## The Intersection of Open Source Software and Tabletop Game Design

The foundational architecture of tabletop roleplaying games (TTRPGs) has historically relied on a proprietary, closed-source model of intellectual property. Under this traditional paradigm, publishers distribute finalized, static documents—typically physical books or digitally locked portable document formats (PDFs)—retaining absolute centralized control over mechanical systems, setting lore, and derivative works. However, the contemporary landscape of game design is undergoing a profound structural metamorphosis, heavily influenced by the methodologies of open-source software engineering. This transformation treats the foundational rules of a game not as immutable, copyrighted literature, but as dynamic, collaborative "source code" capable of being iterated upon, forked, and deployed by decentralized communities of contributors.

This shift necessitates a departure from standard publishing formats in favor of repository-driven development. By hosting game texts on platforms such as GitHub, GitLab, and Codeberg, progressive game designers apply version control, issue tracking, and continuous integration pipelines to narrative and mechanical frameworks. In this ecosystem, plain text formats like Markdown, HTML, and LaTeX serve as the raw source code, while formatted PDFs and web pages act as the compiled binaries.1 The fusion of software development culture with tabletop gaming has given rise to the "Free Culture TTRPG," a movement defined by irrevocable, universally permissive licensing that actively encourages modification, redistribution, and commercial adaptation without restrictive corporate oversight.

The following report functions as an exhaustive, analytical "Curated List"—a curated directory of tabletop roleplaying games that adhere strictly to true free culture licenses. It deconstructs the legal frameworks that govern game licensing, critiques the inadequacies of industry-standard licenses, and explores the technological pipelines used to render games from plain text. Ultimately, this document provides a rigorously vetted repository of games whose source code is directly accessible, culminating in a dedicated section for compiled build artifacts.

## The Legal Ontology of TTRPG Licensing

The legal mechanisms governing tabletop roleplaying games are uniquely complex due to the inherent difficulty of copyrighting abstract game mechanics. While the specific expression of a rule (the literal text) is protected under copyright law, the underlying mathematical probabilities, dice algorithms, and abstract procedures are generally not. To navigate this ambiguity and foster community creation while protecting core assets, the industry has historically relied on bespoke licensing agreements. However, a rigorous examination of these licenses reveals significant philosophical and legal disparities between corporate open-gaming licenses and genuine free culture frameworks.

### The Fallacy of the Open Game License and the ORC Alternative

For over two decades, the tabletop industry was functionally monopolized by the Open Game License (OGL), introduced in the year 2000\. The OGL allowed independent creators to utilize specific mechanical frameworks—colloquially known as the System Reference Document (SRD)—in exchange for perpetually licensing their own mechanical contributions back to the commons. However, the OGL contained critical structural flaws from the perspective of free culture.2 Foremost among these was the concept of "Product Identity," a restrictive legal clause allowing publishers to arbitrarily cordon off vast swathes of content—including names, locations, storylines, thematic elements, and specialized mechanics—making them strictly off-limits for reproduction, modification, or distribution by third parties.3

Furthermore, the legal fragility of the OGL was starkly exposed during the licensing crisis of 2023, wherein attempts were made by corporate entities to revoke or retroactively alter the fundamental terms of the OGL 1.0a, a document long assumed by the community to be permanent and irrevocable.4 This event precipitated a massive migration away from legacy corporate licenses. Yet, the industry's primary, highly publicized response—the Open RPG Creative (ORC) license—failed to align with true open-source philosophy.

The ORC license, while widely praised within commercial publishing circles, operates fundamentally as a protective instrument for corporate intellectual property rather than a catalyst for unrestricted cultural freedom.5 Much like its predecessor, the ORC license requires creators to strictly bifurcate their works into "open" mechanical systems and "closed" proprietary elements.5 It is specifically engineered to shield the brand identities, trademarks, and narrative assets of major publishers, ensuring that the core profit drivers of their franchises remain legally walled off from the community.5 From a strict open-source software perspective, this mandatory segregation of mechanics and narrative runs contrary to the ethos of total creative accessibility. Consequently, neither the OGL nor the ORC meets the stringent criteria required for inclusion in a truly free and open culture directory.

### The Taxonomy of Truly Free Licenses

To qualify as a genuine part of the free culture ecosystem, a tabletop roleplaying game must be distributed under a license that guarantees the user's irrevocable right to copy, modify, distribute, and commercialize the work without arbitrary restrictions on thematic or mechanical integration. The licenses that satisfy these rigorous standards fall into four primary categories:

| License Designation | Operational Mechanism | Cultural Implication |
| :---- | :---- | :---- |
| **Creative Commons Zero (CC0)** | Functions as a complete waiver of copyright, releasing the work into the public domain.8 | Eliminates all exclusive rights. Allows anyone to utilize, hack, remix, and sell the game without any obligation to provide attribution.10 |
| **Creative Commons Attribution (CC-BY)** | Grants absolute freedom to adapt, rewrite, and commercially exploit the text, provided explicit credit is given to the original authors.8 | Represents the baseline of standard open publishing, favored by designers fostering maximum interoperability while maintaining historical authorship.9 |
| **Creative Commons Attribution-ShareAlike (CC-BY-SA)** | Mandates that any derivative works built upon the original material must also be released under the identical license.8 | The "viral" copyleft standard. Ensures the digital commons perpetually expands, as proprietary enclosure of mechanics in subsequent iterations is legally barred.9 |
| **GNU General Public License (GPL)** | Requires that anyone distributing a modified version must also provide direct access to the underlying editable source code.2 | Enforces absolute parity between the rules text and the source files (Markdown, LaTeX), originating directly from software engineering ethics.2 |

### The Exclusionary Nature of Non-Commercial Clauses

A critical distinction must be made regarding licenses that incorporate a Non-Commercial (NC) restriction, such as CC-BY-NC or CC-BY-NC-SA. While these licenses are popular among independent designers who wish to prevent corporate exploitation of their labor, they are explicitly rejected by foundational open-source institutions because they restrict how the user may deploy the software or text. Within the parameters of an exhaustive free culture directory, NC clauses act as a definitive poison pill.

This restriction actively disqualifies several highly prominent and beloved tabletop roleplaying games from true open-source categorization. For instance, the critically acclaimed *Ironsworn* and its science-fiction derivative *Starforged* possess robust, highly advanced open repository infrastructures. The community has meticulously organized the rulesets into a machine-readable JSON schema within the datasworn repository on GitHub.14 These repositories provide programmable access to hundreds of oracle tables, assets, and game moves, featuring typings for C\#, Go, Java, Python, Ruby, and Rust.14 However, the underlying text and imagery of the *Ironsworn* system are inextricably bound by the CC-BY-NC-SA 4.0 license.14 Because independent writers cannot legally utilize this data for commercial tabletop projects, *Ironsworn* fails the strict criteria of free culture.

Similarly, the paranormal mercenary game *FIST: Ultra Edition* maintains a vibrant hacker community and provides open layouts and mechanical SRDs on GitHub.10 It features an "Intelligence Matrix" repository of tables and assets for tactical operations.18 Yet, the core material is explicitly bound by the CC-BY-NC-SA 4.0 license, strictly prohibiting commercial use by downstream designers.18 Consequently, systems employing NC clauses have been analytically reviewed to understand market trends but deliberately purged from the curated directory below to ensure absolute compliance with open software methodologies.

## The Technological Architecture of TTRPG Repositories

The transition from traditional physical publishing to open-source repository management requires a fundamental shift in how tabletop roleplaying games are authored, formatted, and compiled. To facilitate collaborative, decentralized development, the semantic content of the game must be cleanly separated from its typographic presentation.

### Plain Text and the Markdown Paradigm

The overwhelming majority of open-source TTRPGs utilize Markdown as their foundational source code. Markdown serves as a lightweight markup language that provides a highly legible, uncompiled reading experience while remaining easily parseable by advanced computational tools.1 By storing the game in plain text formats within Git-based repositories (GitHub, GitLab), designers invite the community to submit pull requests to correct typographical errors, balance mechanical formulas, or append new rulesets directly into the master branch.1

This plain text architecture allows for deep integration with local knowledge management systems. Repositories are frequently optimized for software like Obsidian, a powerful, offline note-taking application that natively processes interconnected Markdown files through bidirectional linking.1 Game masters can clone a repository directly to their local machine and immediately manipulate the game's mechanics, creating a customized, interconnected wiki of rules and lore without relying on external servers or proprietary virtual tabletops.1

### Continuous Integration and Automated Rendering

The true power of the repository-driven game design model lies in its capacity for automation. Advanced open-source TTRPG projects utilize Continuous Integration and Continuous Deployment (CI/CD) pipelines, such as GitHub Actions, to bridge the gap between plain text source code and user-facing presentation.

When a contributor pushes an update to a repository's Markdown files, automated scripts trigger in the cloud. These pipelines utilize static site generators—such as Jekyll, Hugo, mdBook, or MkDocs—to instantaneously convert the Markdown into beautifully styled, responsive HTML web pages.21 This ensures that the online rulebook is never out of sync with the underlying source code.1 Specialized styling frameworks actively support this ecosystem; for instance, the Torillic theme for MkDocs provides cascading style sheets (CSS) specifically engineered to mimic the visual aesthetics of professional, traditional fantasy sourcebooks while retaining the agility of raw HTML, itself released under CC0.25

### Complex Compilation via LaTeX and Automation Scripts

While Markdown is ubiquitous for web deployment, games that demand rigorous, print-ready typesetting frequently turn to LaTeX. LaTeX is a sophisticated typesetting system traditionally used in mathematics and academic publishing, but its capacity for programmatic layout makes it an exceptionally powerful tool for open-source TTRPGs.27 A game written in LaTeX is structurally indistinguishable from software source code; it relies on complex macros and class definitions to automatically generate tables of contents, index cross-references, and multi-column layouts.28

Additionally, robust repositories employ advanced scripting languages like Ruby, Python, or Shell to execute automated data processing tasks. Shell scripts are routinely utilized to automate the generation of interconnected lists and asset compilations during the build process, seamlessly transforming disparate text files into unified artifacts.23 Python and Ruby are frequently used to parse narrative Markdown text and extract raw statistical data into JSON format for integration with digital tools.29

## Curated Directory of Free Culture TTRPGs

The following section constitutes the exhaustive, curated directory—the "Curated List"—of tabletop roleplaying games that adhere strictly to the parameters of free culture. Every entry in this directory is licensed under a non-restrictive, fully open framework (CC0, CC-BY, CC-BY-SA, or GPL). Furthermore, every entry shuns the OGL and ORC licenses, and the raw source code of each game is directly accessible via a public version-control repository.

### Narrative Frameworks and PBTA Implementations

This category focuses on games that prioritize collaborative storytelling, partial success mechanics, and fiction-first resolution systems, often drawing inspiration from the "Powered by the Apocalypse" (PBtA) engine or the "Forged in the Dark" framework.

#### Aspirant

*Aspirant* represents a massive collaborative endeavor designed around the thematic pillars of adventure, expertise, and shared world-building. Functioning as a hybrid system, it draws heavy mechanical inspiration from classic high-fantasy RPGs and PBtA frameworks.1 The game mechanics emphasize cooperative storytelling, where participants actively co-create the fantasy world they are exploring. The ruleset includes complex subsystems for character progression, magical frameworks, crafting matrices, and detailed combat applications regarding stress, awareness, and specialized actions.30

The technological backend of *Aspirant* is a masterclass in modern open-source deployment. The entirety of the game's rules text is housed within a dedicated Game directory formatted entirely in Markdown.1 This design choice deliberately invites the community to fork the project and adapt the ruleset. Furthermore, the repository is configured to interact with Obsidian, utilizing local Markdown linking for seamless navigation.1 To handle public distribution, the project utilizes GitHub Actions; the moment a pull request containing a rules update is merged into the master branch, the CI/CD pipeline automatically recompiles the Markdown and deploys it directly to the live website.1

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Narrative Fantasy / Collaborative Worldbuilding |
| **License** | Creative Commons Attribution-ShareAlike 4.0 (CC-BY-SA 4.0) |
| **Source Format** | Markdown / Shell / Python / HTML |
| **Repository** | ([https://github.com/bombasticSlacks/Aspirant](https://github.com/bombasticSlacks/Aspirant)) |

#### Reclaimers

Developed by the same engineering and design collaborative responsible for *Aspirant*, *Reclaimers* pivots mechanically and thematically into the realm of science-fiction horror.23 The game's narrative philosophy is stark, summarized as "a game about violence and control," tasking players with confronting individuals on the worst day of their lives and attempting to salvage the situation.23

Structurally, *Reclaimers* mirrors the highly efficient repository architecture of its fantasy counterpart. The repository features extensive shell scripting (lists\_build.sh) to automate complex repository tasks, composed of 74% Shell and 26% HTML code.23 The ruleset, provided entirely in Markdown within the Game folder, is explicitly optimized for local rendering via the Obsidian note-taking environment, evidenced by the inclusion of a .obsidian configuration directory within the source tree.23 The project adheres strictly to the CC-BY-SA 4.0 license, functioning as a viral copyleft mechanism that forces any subsequent hacks to remain public.23

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Sci-Fi Horror / Tactical Intervention |
| **License** | Creative Commons Attribution-ShareAlike 4.0 (CC-BY-SA 4.0) |
| **Source Format** | Markdown / HTML / Shell |
| **Repository** | ([https://github.com/bombasticSlacks/Reclaimers](https://github.com/bombasticSlacks/Reclaimers)) |

#### LTTS

Further expanding the portfolio of open-source PBtA implementations, *LTTS* operates as a dedicated science-fiction exploration roleplaying game.31 Hosted within the same organizational ecosystem as *Aspirant* and *Reclaimers*, the system utilizes identical open-source repository structures to facilitate community-driven sci-fi storytelling.31 Released under CC-BY-SA 4.0, it mandates that all space-faring adaptations and mechanical expansions derived from its core remain perpetually free and open to the public.31

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | PBtA Sci-Fi Exploration |
| **License** | Creative Commons Attribution-ShareAlike 4.0 (CC-BY-SA 4.0) |
| **Source Format** | Markdown |
| **Repository** | ([https://github.com/bombasticSlacks/LTTS](https://github.com/bombasticSlacks/LTTS)) |

#### Charge

*Charge* is an extraordinary entry designed by Fari RPGs, offering a free, open, and generic role-playing engine. It utilizes a rapid dice resolution mechanic heavily inspired by "Forged in the Dark" systems but introduces a novel framework designed to maximize player engagement.11 *Charge* is built with internal "dials," allowing game masters to seamlessly adjust the tone of the game from grim realism to larger-than-life cinematic adventure without rewriting the core mechanics.11

The System Reference Document for *Charge* is hosted on GitHub and is released under the exceptionally permissive Creative Commons Attribution 4.0 (CC-BY 4.0) license.10 This specifically allows third-party creators to design, publish, and monetize "Powered by Charge" games, requiring nothing more than basic attribution to the original designer and the foundational text of *Blades in the Dark*.11 The availability of the SRD in uncompiled formats makes it a prime candidate for immediate cloning and hacking.

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Generic Narrative Engine / Forged in the Dark Derivative |
| **License** | Creative Commons Attribution 4.0 (CC-BY 4.0) |
| **Source Format** | Markdown / Plain Text |
| **Repository** | ([https://github.com/Tabyltop/CC-SRD](https://github.com/Tabyltop/CC-SRD)) (Converted Formats) / Fari RPGs |

#### Lady Blackbird

*Lady Blackbird* is widely regarded as a masterpiece of self-contained narrative game design. Operating as a tight, pre-generated scenario with baked-in rules, it has spawned an entire subgenre of structural hacks.10 The mechanics rely on a simple dice pool system driven by character traits and "keys" that directly reward roleplaying with mechanical progression. The core mechanics have been released under a Creative Commons license, cementing its status as a foundational text in open narrative design.10

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Steampunk / Pre-generated Narrative Scenario |
| **License** | Creative Commons (CC) |
| **Source Format** | Plain Text / Repository Archives |
| **Repository** | Various GitHub Mirrors (e.g., [Zireael07/awesome-tabletop-rpgs](https://github.com/Zireael07/awesome-tabletop-rpgs)) |

### Old School Renaissance (OSR) and Rules-Lite Engines

The Old School Renaissance emphasizes high lethality, procedural exploration, and rapid resolution mechanics, often reverse-engineering the frameworks of the earliest tabletop RPGs. These systems are highly modular, making them ideal candidates for open-source iteration.

#### Basic Fantasy Role-Playing Game (BFRPG)

The *Basic Fantasy Role-Playing Game* is a cornerstone of the OSR movement, dedicated to modernizing the mechanical frameworks of late 1970s and early 1980s fantasy gaming.33 The system is intentionally rules-light, featuring classic archetypes (fighters, clerics, magic-users) and ascending armor class mechanics, prioritizing rapid rulings over complex computational math at the table.33

Historically, *BFRPG* operated under the Open Game License. However, following the industry-wide destabilization of the OGL in 2023, the developers executed a monumental legal pivot.35 The release of the 4th Edition marked a complete transition to the Creative Commons Attribution-ShareAlike 4.0 (CC-BY-SA 4.0) license, permanently severing ties with corporate-controlled legal frameworks.33 The System Reference Document for the game is hosted publicly on GitHub within the Solomoriah/BFRPG\_SRD repository.36 The textual content is formatted in meticulously styled HTML (comprising 98.9% of the code) and CSS (bfrpg.css, comprising 1.1%), rendering the core rules instantly accessible and deeply parseable by third-party virtual tabletops and character generation software.36

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Old School Renaissance (OSR) Fantasy |
| **License** | Creative Commons Attribution-ShareAlike 4.0 (CC-BY-SA 4.0) |
| **Source Format** | HTML / CSS |
| **Repository** | ([https://github.com/Solomoriah/BFRPG\_SRD](https://github.com/Solomoriah/BFRPG_SRD)) |

#### Cairn

*Cairn* has established itself as a foundational text in the modern, open-source tabletop renaissance. Designed as an adventure game concerning hardened explorers navigating a dark, monstrous wood, the system is classless, highly lethal, and relentlessly "fiction-first".29 Player character progression occurs organically through environmental interaction and in-game decisions rather than mechanical leveling, ensuring that the narrative dictates the mechanics, not the inverse.38

The repository infrastructure for *Cairn* is immense, boasting over 4,200 commits and demonstrating a highly active, decentralized development community.29 The GitHub repository acts as the master archive, holding the Markdown files for the core rules (adventures.md, barebones.md, first-edition.md), bestiaries, and localization translations.29 Furthermore, the repository is highly computational, composed of Python (69.6%), TeX (10.9%), JavaScript, Shell, and HTML.29 It features automated Ruby scripts (generate\_monster\_json.rb) designed to dynamically parse the game's textual bestiary into structured JSON data formats.29 Under the CC-BY-SA 4.0 license, *Cairn* has spawned an entire ecosystem of compatible hacks and third-party modules, all legally bound to remain as open and accessible as the original text.10

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Fiction-First Dark Fantasy / Classless Exploration |
| **License** | Creative Commons Attribution-ShareAlike 4.0 (CC-BY-SA 4.0) |
| **Source Format** | Markdown / HTML / Ruby / Python / TeX |
| **Repository** | [https://github.com/yochaigal/cairn](https://github.com/yochaigal/cairn) |

#### BIND (BIND is Not D\&D)

*BIND* is an open-source, grunge-fantasy roleplaying game that represents a rare and fascinating implementation of pure software licensing within the tabletop sphere. The game focuses heavily on immediate problem-solving, eschewing lengthy character backstories and lore dumps in favor of fast-paced, highly lethal combat resolution.40 Mechanics are resolved via a streamlined 2d6 engine, wherein players roll two six-sided dice, add their attributes and skills, and attempt to surpass a target "Tie Number" (TN).28 Combat is highly optimized; a single roll dictates both attack and defense, ensuring that conflicts rarely last more than two rounds.28

What distinguishes *BIND* is its absolute commitment to open-source software purity. The game is licensed under the GNU General Public License version 3 (GPLv3), a strict copyleft software license that grants players the right to copy, modify, and resell the work, provided they distribute the raw source files alongside any final product.10 The author explicitly states that the game relies on its open-source nature to negate the need for "house rules," as anyone can fundamentally rewrite the source files.28 Hosted on GitLab, the source repository is an intricate web of text and formatting directives designed to be computationally compiled using LaTeX.2

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Grunge-Fantasy / Streamlined 2d6 Mechanics |
| **License** | GNU General Public License v3 (GPLv3) |
| **Source Format** | LaTeX / Plain Text |
| **Repository** | [https://gitlab.com/bindrpg/core](https://gitlab.com/bindrpg/core) |

#### Pocket Quest (Open Adventure)

Derived from the broader *Open Adventure* engine, *Pocket Quest* is an exercise in extreme mechanical condensation. The system is engineered to function as a complete, rules-lite fantasy and science-fiction roleplaying game that occupies only a single, double-sided sheet of paper.41 Despite its minimal footprint, the game supports long-term campaign play, featuring specialized rules for dungeon crawling, weaponry, varied magic typologies, and Game Master guidelines.41 As a subset of the *Open Adventure* ecosystem, the source text is hosted deep within the project's GitHub directory structure, distributed under a CC-BY-SA license to ensure continuous open iteration.41

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Rules-Lite OSR / Fantasy & Sci-Fi |
| **License** | Creative Commons Attribution-ShareAlike (CC-BY-SA) |
| **Source Format** | Plain Text / Markdown |
| **Repository** | [https://github.com/openadventure/Open-Adventure](https://github.com/openadventure/Open-Adventure) |

#### Chronicles

*Chronicles* stands as a pristine example of Markdown-first development in roleplaying games. It is a completely open-source RPG whose foundational base is written exclusively in plain text Markdown, allowing it to seamlessly interface with modern publishing pipelines.2 This architecture permits the ruleset to be computationally pushed out to various formats—including EPUB, HTML, and PDF—without manual typesetting interference, guaranteeing that the source code remains universally editable by anyone with a text editor.2

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Universal Open Roleplaying |
| **License** | Open Source (Creative Commons) |
| **Source Format** | Markdown |
| **Repository** | Indexed via [https://github.com/19-84/chronicon](https://github.com/19-84/chronicon) |

### **Universal Systems and Agnostic Frameworks**

These games provide structural scaffolding designed to be applied to any genre or narrative setting, functioning as pure mathematical engines or conceptual world-building tools.

#### Quest (The Adventure Guild)

*Quest* operates as a streamlined, highly accessible fantasy roleplaying game that has embraced the open-source philosophy through its Creator's Resource and SRD.10 The rules emphasize approachability, stripping away dense mathematical modifiers in favor of a single d20 resolution mechanic focused on narrative outcomes. The system has been released under the Creative Commons Attribution 4.0 (CC-BY) license, explicitly encouraging independent creators to hack the game, create new roles, design custom abilities, and commercially sell their modifications.10 *Quest* is further supported by *Quest Bound*, a free and open-source computational engine for creating digital TTRPGs, hosting its own source code on GitHub under a strong copyleft license.43

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Accessible Fantasy / Digital Engine Support |
| **License** | Creative Commons Attribution (CC-BY 4.0) |
| **Source Format** | Markdown / Source Code |
| **Repository** | [https://github.com/curtmorgan3/quest-bound](https://github.com/curtmorgan3/quest-bound) |

#### Freeform Universal (FU)

*Freeform Universal* (and its subsequent *FU 2 beta*) represents one of the foundational texts of the modern freeform movement.10 Rather than relying on rigid statistical attributes, the system uses narrative descriptors to build dice pools, yielding outcomes that inherently drive the fiction forward (e.g., "Yes, and...", "No, but..."). The system has spawned countless derivatives due to its highly permissive CC licensing, making it a critical asset for designers looking to build qualitative, rather than quantitative, engines.10

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Narrative Freeform / Descriptor-Based Resolution |
| **License** | Creative Commons (CC) |
| **Source Format** | Plain Text |
| **Repository** | Indexed via [Zireael07/awesome-tabletop-rpgs](https://github.com/Zireael07/awesome-tabletop-rpgs) |

#### Agora

*Agora* distinguishes itself by shifting the mechanical focus away from tactical combat and heavily toward sociological and narrative friction. It is an intricate game concerning deep, complex characters striving to enact ideological change upon their respective worlds.24 The mechanics reflect this psychological depth, utilizing systems to track "Endurance stress" (Fatigue) and "Resolve stress" (Burnout), forcing players to manage the internal deterioration of their characters as they confront external societal pressures.24

The game's repository is explicitly engineered as an Obsidian Vault, leveraging Markdown to create a non-linear, interconnected hyper-document.24 The author has implemented a nuanced licensing strategy: the core System Reference Document is released under CC-BY 4.0, allowing extensive commercial freedom provided attribution is given, while specific sub-articles and mechanical components within the repository are explicitly dedicated to the public domain under CC0, requiring no credit whatsoever.24

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Sociological Narrative / Psychological Stress |
| **License** | Creative Commons Attribution 4.0 (CC-BY 4.0) / CC0 |
| **Source Format** | Markdown (Obsidian Vault) |
| **Repository** | ([https://github.com/Seraaron/agora](https://github.com/Seraaron/agora)) |

#### Open Lore

Rather than providing strict dice resolution mechanics, *Open Lore* functions as an open-source cosmological framework and world-building matrix designed to interface with any ruleset.21 It offers a highly variable "existential spark" architecture capable of representing diverse genres ranging from pre-medieval fantasy and cyberpunk to weird westerns and space exploration.21

The repository structure reflects its encyclopedic nature, utilizing Markdown in conjunction with mdBook—a command-line utility written in Rust specifically designed to create heavily structured, easily navigable online books from raw Markdown files.21 To maximize its utility as a universal foundation for third-party designers, the entire text and cosmology of *Open Lore* have been released into the public domain under the CC0 license, entirely eradicating the concept of copyright from the setting.21

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Universal Cosmology / Agnostic World-building |
| **License** | Creative Commons Zero 1.0 Universal (CC0 1.0) |
| **Source Format** | Markdown (mdBook) |
| **Repository** | [https://github.com/JenniferPylko/openlore](https://github.com/JenniferPylko/openlore) |

#### 1w6

The *1w6* system presents a highly modular, universal ruleset driven entirely by six-sided dice mechanics.10 What makes the system an object of deep technical fascination is its integration with advanced computational programming environments. The engine relies heavily on Guile Scheme Wisp, an experimental programming syntax used to create low-ceremony embedded languages.44 This unique confluence of tabletop mechanics and functional programming paradigms allows designers to programmatically generate dialogue-focused games with minimal overhead.44 Reflecting its deep ties to traditional software development communities, the entire *1w6* ruleset is licensed under the strict copyleft requirements of the GPL.10

| Specification | Details |
| :---- | :---- |
| **Subject Focus** | Universal d6 Mechanics / Programmatic Dialogue |
| **License** | GNU General Public License (GPL) |
| **Source Format** | Guile Scheme Wisp / Plain Text |
| **Repository** | [https://hg.sr.ht/\~arnebab/ews](https://hg.sr.ht/~arnebab/ews) |

#### Additional Open Frameworks

The directory of completely open-source, non-NC mechanics hosted natively in text formats extends deeply into specific niche designs:

* **The Resistance Toolbox**: The generic system powering critically acclaimed games like *Spire* and *Heart*, released under CC-BY to allow broad commercial hacking.10  
* **Siren RPG**: An open-source 3d6 system published under a CC license, designed for universal adaptability.10  
* **One Roll Engine (ORE)**: An innovative system based on rolling a pool of ten-sided dice and finding matching sets (height and width) to determine both success and impact simultaneously, released under CC.10

## Build Artifacts

In software engineering, compiling raw source code (such as C++ or Rust) produces an executable binary file meant for end-user deployment. The open-source TTRPG methodology mirrors this exact computational process. While the raw mechanics and text of a game live in version-controlled repositories as Markdown, HTML, or LaTeX (the "source code"), the average player requires a heavily formatted, aesthetically optimized document to utilize at the physical gaming table. These end-user files—rendered PDFs, EPUBs, and compiled web assets—are the "Build Artifacts" of the tabletop world.

The automated pipelines and manual typesetting procedures utilized by the games in the aforementioned directory yield the following finalized build artifacts, which represent the culmination of the open-source pipeline:

### Aspirant: The Advent Edition

While the raw Markdown of *Aspirant* constantly evolves within its master branch, the developers capture specific, stable iterations of the ruleset and compile them into formatted PDFs.45 The resulting build artifact, titled the *Advent Edition*, is a heavily stylized, 64-to-72 page digital book featuring unique layout designs, playflow samples, and fully realized character classes.46 These PDFs are distributed directly to consumers via storefronts like Itch.io and digital reward fulfillment systems, demonstrating how CC-BY-SA 4.0 source code can be packaged into premium, monetized digital artifacts without violating the open license.45

### BIND: Print-Optimized LaTeX Compilation

Because *BIND* is structurally written using LaTeX, the build process explicitly generates highly optimized, typographical artifacts designed specifically for physical printing rather than screen reading.28 The author specifically notes that reading a two-column, blinding-white PDF on a monitor will induce a headache, urging users to compile the books and take them to a local print shop.28 The repository provides multiple distinct compiled artifacts through its automated typesetting, including the comprehensive 85-page *Core Rules*, the *Goblin Hole* introductory module (complete with tear-out pre-generated character sheets), and the *Book of Judgement* setting guide.28

### Cairn: Multi-Format Digital Deployment

The *Cairn* repository produces an impressive array of compiled artifacts to serve diverse user requirements.39 Utilizing specialized layout software integrated with its text files, the Markdown source is transformed into several digital manifestations. The repository's build outputs include standard reading PDFs (12 MB), specialized booklet-formatted PDFs designed for DIY zine printing (12 MB), raw Affinity Publisher (.afpub) layout files (14 MB) for extreme structural modification by graphic designers, and interactive, form-fillable character sheets.39 This multi-artifact approach ensures maximum utility across digital and physical play spaces.

### Basic Fantasy RPG: Core Rules 4th Edition

The HTML and CSS source codes of the *Basic Fantasy RPG* SRD are routinely compiled into massive, 208-page, print-ready PDFs.47 Following the shift to the CC-BY-SA 4.0 license, the 4th Edition artifacts are made universally available as zero-cost downloads directly from the project's web infrastructure.33 Furthermore, they are heavily distributed through major digital marketplaces like DriveThruRPG in both standard and alternate cover variations, showcasing how open HTML code can be transformed into a commercially viable, 208-page hardback artifact.33

### Charge: System Reference Document Outputs

The *Charge* RPG SRD represents a dual-artifact approach. The raw Markdown files are compiled into comprehensive digital documents that are freely distributed across platforms like Itch.io, available in multiple localizations including English, French, and Spanish.32 These artifacts feature all the rules of the *Charge* RPG alongside insightful designer notes, functioning not just as a rulebook, but as an instructional manual teaching downstream designers how to utilize the open text to compile their own independent "Powered by Charge" games.32

### Reclaimers: Static Site Renderings

Unlike projects that prioritize PDF generation, the primary build artifact for *Reclaimers* is its automated, interactive web portal.23 The GitHub Actions CI/CD pipeline compiles the .obsidian formatted Markdown into an interconnected, highly responsive static HTML site. This web-based artifact acts as the definitive, player-facing rulebook, ensuring that consumers are always interacting with the latest, computationally verified version of the game's mechanics, completely circumventing the need for static PDFs.23

## Synthesizing the Future of Open Tabletop Systems

The structural analysis of open-source tabletop roleplaying games reveals a profound paradigm shift in how interactive narratives and probability engines are authored. By categorically rejecting restrictive corporate models like the Open Game License and the ORC license in favor of pure free culture frameworks (CC0, CC-BY, CC-BY-SA, and GPL), a new class of designers has effectively decentralized the tabletop industry. Furthermore, the explicit rejection of Non-Commercial clauses guarantees that this intellectual property remains an active, functioning part of the global economic commons, free from artificial enclosure.

By treating textual rulesets as computational source code, the games curated in this directory demonstrate the immense power of repository-driven design. The deployment of Markdown formatting, Git version control, LaTeX compilation, and automated CI/CD pipelines has eradicated the historical friction of traditional publishing. Consequently, the boundary between the game designer and the player has been computationally dissolved, giving rise to an ecosystem where every participant possesses the legal and technological authority to alter, recompile, and redistribute the very fabric of the games they play.

#### Bibliography

1. bombasticSlacks/Aspirant: A fantasy TTRPG \- GitHub, accesso eseguito il giorno maggio 14, 2026, [https://github.com/bombasticSlacks/Aspirant](https://github.com/bombasticSlacks/Aspirant)  
2. Open Source RPGs \- BIND RPG, accesso eseguito il giorno maggio 14, 2026, [https://bindrpg.gitlab.io/blog/foss\_list/](https://bindrpg.gitlab.io/blog/foss_list/)  
3. Are there any complete and usable, open source, community built, TTRPGs? : r/rpg \- Reddit, accesso eseguito il giorno maggio 14, 2026, [https://www.reddit.com/r/rpg/comments/19386g4/are\_there\_any\_complete\_and\_usable\_open\_source/](https://www.reddit.com/r/rpg/comments/19386g4/are_there_any_complete_and_usable_open_source/)  
4. Beyond OGL – what are the options? \- Melestrua's Musings, accesso eseguito il giorno maggio 14, 2026, [https://melestrua.net/2023/01/14/beyond-ogl-what-are-the-options/](https://melestrua.net/2023/01/14/beyond-ogl-what-are-the-options/)  
5. What TTRPGs or TTRPG systems have something like an open gaming license (OGL)? : r/rpg \- Reddit, accesso eseguito il giorno maggio 14, 2026, [https://www.reddit.com/r/rpg/comments/1k4jfq6/what\_ttrpgs\_or\_ttrpg\_systems\_have\_something\_like/](https://www.reddit.com/r/rpg/comments/1k4jfq6/what_ttrpgs_or_ttrpg_systems_have_something_like/)  
6. Why is the ORC Necessary/ Highly Praised When There Is Already Creative Commons? : r/rpg \- Reddit, accesso eseguito il giorno maggio 14, 2026, [https://www.reddit.com/r/rpg/comments/10csbs8/why\_is\_the\_orc\_necessary\_highly\_praised\_when/](https://www.reddit.com/r/rpg/comments/10csbs8/why_is_the_orc_necessary_highly_praised_when/)  
7. What Open Gaming license would people in the tabletop RPG community recommend these days? : r/RPGdesign \- Reddit, accesso eseguito il giorno maggio 14, 2026, [https://www.reddit.com/r/RPGdesign/comments/1i0qw6d/what\_open\_gaming\_license\_would\_people\_in\_the/](https://www.reddit.com/r/RPGdesign/comments/1i0qw6d/what_open_gaming_license_would_people_in_the/)  
8. Open Source TTRPG Resources \- Thought Punks, accesso eseguito il giorno maggio 14, 2026, [https://thoughtpunks.com/open-source-ttrpg-resources/](https://thoughtpunks.com/open-source-ttrpg-resources/)  
9. Forever Open Source 2024 \- Itch.io, accesso eseguito il giorno maggio 14, 2026, [https://itch.io/jam/forever-open-source-2024](https://itch.io/jam/forever-open-source-2024)  
10. Zireael07/awesome-tabletop-rpgs: Awesome list of free and/or open source tabletop RPGs, accesso eseguito il giorno maggio 14, 2026, [https://github.com/Zireael07/awesome-tabletop-rpgs](https://github.com/Zireael07/awesome-tabletop-rpgs)  
11. Charge RPG by Fari RPGs, accesso eseguito il giorno maggio 14, 2026, [https://farirpgs.itch.io/charge-rpg](https://farirpgs.itch.io/charge-rpg)  
12. Forever Open Source 2025 \- Itch.io, accesso eseguito il giorno maggio 14, 2026, [https://itch.io/jam/forever-open-source-2025](https://itch.io/jam/forever-open-source-2025)  
13. BIND \- OGC Library, accesso eseguito il giorno maggio 14, 2026, [https://ogc.rpglibrary.org/index.php?title=BIND](https://ogc.rpglibrary.org/index.php?title=BIND)  
14. rsek/datasworn: The successor to the original Datasworn ... \- GitHub, accesso eseguito il giorno maggio 14, 2026, [https://github.com/rsek/datasworn](https://github.com/rsek/datasworn)  
15. GitHub \- rsek/dataforged: Official content and rules data for the Ironsworn: Starforged tabletop role-playing game, formatted as JSON for use in community tools. Includes JSON schemas and a Javascript/Typescript API., accesso eseguito il giorno maggio 14, 2026, [https://github.com/rsek/dataforged](https://github.com/rsek/dataforged)  
16. GitHub \- scottbenton/Iron-Link: An online app for playing the Ironsworn family of games, either solo or with a group, accesso eseguito il giorno maggio 14, 2026, [https://github.com/scottbenton/Iron-Link](https://github.com/scottbenton/Iron-Link)  
17. Ironsworn Starforged Rulebook \- Flip eBook Pages 1-50 \- AnyFlip, accesso eseguito il giorno maggio 14, 2026, [https://anyflip.com/krnil/qxmn/basic](https://anyflip.com/krnil/qxmn/basic)  
18. FIST: Ultra Edition by CLAYMORE \- itch.io, accesso eseguito il giorno maggio 14, 2026, [https://claymorerpgs.itch.io/fist](https://claymorerpgs.itch.io/fist)  
19. Sombroek Institute \- an antagonist faction for FIST by tonethiefgames, accesso eseguito il giorno maggio 14, 2026, [https://tonethiefgames.itch.io/sombroek-institute](https://tonethiefgames.itch.io/sombroek-institute)  
20. FIST: ULTRA EDITION Review – Paranormal Cold War Mercs | Cannibal Halfling Gaming, accesso eseguito il giorno maggio 14, 2026, [https://cannibalhalflinggaming.com/2023/09/18/fist-ultra-edition-review-paranormal-cold-war-mercs/](https://cannibalhalflinggaming.com/2023/09/18/fist-ultra-edition-review-paranormal-cold-war-mercs/)  
21. JenniferPylko/openlore: A CC0 multiverse for everyone \- GitHub, accesso eseguito il giorno maggio 14, 2026, [https://github.com/JenniferPylko/openlore](https://github.com/JenniferPylko/openlore)  
22. Do open source RPGs exist? Would there be any interest for that kind of thing? \- Reddit, accesso eseguito il giorno maggio 14, 2026, [https://www.reddit.com/r/rpg/comments/1gmiici/do\_open\_source\_rpgs\_exist\_would\_there\_be\_any/](https://www.reddit.com/r/rpg/comments/1gmiici/do_open_source_rpgs_exist_would_there_be_any/)  
23. bombasticSlacks/Reclaimers: A Sci-Fi Horror TTRPG · GitHub \- GitHub, accesso eseguito il giorno maggio 14, 2026, [https://github.com/bombasticSlacks/Reclaimers](https://github.com/bombasticSlacks/Reclaimers)  
24. GitHub \- Seraaron/agora: A free creative commons tabletop roleplaying game about playing deep and intricate characters who strive to change the worlds they live in to conform to their ideals., accesso eseguito il giorno maggio 14, 2026, [https://github.com/Seraaron/agora](https://github.com/Seraaron/agora)  
25. GitHub \- mkdocs/catalog: :trophy: A list of awesome MkDocs projects and plugins., accesso eseguito il giorno maggio 14, 2026, [https://github.com/mkdocs/catalog](https://github.com/mkdocs/catalog)  
26. GitHub \- TEParsons/torillic: A D\&D inspired theme for styling TTRPG notes and resources, accesso eseguito il giorno maggio 14, 2026, [https://github.com/TEParsons/torillic](https://github.com/TEParsons/torillic)  
27. creative commons · Topics \- GitLab, accesso eseguito il giorno maggio 14, 2026, [https://gitlab.com/explore/projects/topics/creative+commons](https://gitlab.com/explore/projects/topics/creative+commons)  
28. BIND / BindRPG \- Core Rulebook \- GitLab, accesso eseguito il giorno maggio 14, 2026, [https://gitlab.com/bindrpg/core](https://gitlab.com/bindrpg/core)  
29. yochaigal/cairn · GitHub \- GitHub, accesso eseguito il giorno maggio 14, 2026, [https://github.com/yochaigal/cairn](https://github.com/yochaigal/cairn)  
30. Aspirant RPG | Aspirant, accesso eseguito il giorno maggio 14, 2026, [https://aspirantrpg.com/](https://aspirantrpg.com/)  
31. GitHub \- bombasticSlacks/LTTS: A PBTA TTRPG game about Sci-Fi, accesso eseguito il giorno maggio 14, 2026, [https://github.com/bombasticSlacks/LTTS](https://github.com/bombasticSlacks/LTTS)  
32. Charge SRD by Fari RPGs, accesso eseguito il giorno maggio 14, 2026, [https://fari-rpgs.itch.io/charge-srd](https://fari-rpgs.itch.io/charge-srd)  
33. Basic Fantasy RPG Core Rules 4thEd \- DriveThruRPG, accesso eseguito il giorno maggio 14, 2026, [https://www.drivethrurpg.com/en/product/442921/basic-fantasy-rpg-core-rules-4thed](https://www.drivethrurpg.com/en/product/442921/basic-fantasy-rpg-core-rules-4thed)  
34. Basic Fantasy RPG seems to be missing from the OSR list. Not only can you get the game for free from their downloads section you can get printed books for just a tad over cost on Amazon. They have an active Facebook community and Discord. Developed under Creative Commons since 2006\. \- Reddit, accesso eseguito il giorno maggio 14, 2026, [https://www.reddit.com/r/rpg/comments/187j1th/basic\_fantasy\_rpg\_seems\_to\_be\_missing\_from\_the/](https://www.reddit.com/r/rpg/comments/187j1th/basic_fantasy_rpg_seems_to_be_missing_from_the/)  
35. Free to Download: Basic Fantasy RPG Core Rules 4e \- Geek Native, accesso eseguito il giorno maggio 14, 2026, [https://www.geeknative.com/159223/free-to-download-basic-fantasy-rpg-core-rules-4e/](https://www.geeknative.com/159223/free-to-download-basic-fantasy-rpg-core-rules-4e/)  
36. Solomoriah/BFRPG\_SRD: Basic Fantasy Role-Playing ... \- GitHub, accesso eseguito il giorno maggio 14, 2026, [https://github.com/Solomoriah/BFRPG\_SRD](https://github.com/Solomoriah/BFRPG_SRD)  
37. SRD \- Cairn RPG, accesso eseguito il giorno maggio 14, 2026, [https://cairnrpg.com/first-edition/cairn-srd/](https://cairnrpg.com/first-edition/cairn-srd/)  
38. Cairn RPG 2E: Warden's Guide | PDF \- Scribd, accesso eseguito il giorno maggio 14, 2026, [https://www.scribd.com/document/552324460/Cairn](https://www.scribd.com/document/552324460/Cairn)  
39. Cairn \- First Edition by Yochai Gal, accesso eseguito il giorno maggio 14, 2026, [https://yochaigal.itch.io/cairn](https://yochaigal.itch.io/cairn)  
40. BIND: Core Rules \- The Andonome Coterie \- DriveThruRPG, accesso eseguito il giorno maggio 14, 2026, [https://www.drivethrurpg.com/product/165299/BIND-Core-Rules?language=ensortdptoptopwywtrueptopwywtrue](https://www.drivethrurpg.com/product/165299/BIND-Core-Rules?language=ensortdptoptopwywtrueptopwywtrue)  
41. Pocket Quest \-- A one-page (duplex) rules-lite OSR fantasy/sci-fi RPG based off the Open Adventure game system \- Reddit, accesso eseguito il giorno maggio 14, 2026, [https://www.reddit.com/r/rpg/comments/2tis1p/pocket\_quest\_a\_onepage\_duplex\_ruleslite\_osr/](https://www.reddit.com/r/rpg/comments/2tis1p/pocket_quest_a_onepage_duplex_ruleslite_osr/)  
42. welcome, creators \- Quest, accesso eseguito il giorno maggio 14, 2026, [https://www.adventure.game/static/quest-creators-license-and-resource-72932d343a6d2f0af7a5804d9c0b2b46.pdf](https://www.adventure.game/static/quest-creators-license-and-resource-72932d343a6d2f0af7a5804d9c0b2b46.pdf)  
43. curtmorgan3/quest-bound: Free and Open Source Tabletop Game Engine \- GitHub, accesso eseguito il giorno maggio 14, 2026, [https://github.com/curtmorgan3/quest-bound](https://github.com/curtmorgan3/quest-bound)  
44. Light, accesso eseguito il giorno maggio 14, 2026, [https://www.draketo.de/book/export/html/195](https://www.draketo.de/book/export/html/195)  
45. NOW OUTDATED — Enclave: Advent Edition (PDF Copy) \- Etsy, accesso eseguito il giorno maggio 14, 2026, [https://www.etsy.com/listing/1695455978/now-outdated-enclave-advent-edition-pdf](https://www.etsy.com/listing/1695455978/now-outdated-enclave-advent-edition-pdf)  
46. ENCLAVE: Aspirant — The Narrative TTRPG with Infinite Depth \- Kickstarter, accesso eseguito il giorno maggio 14, 2026, [https://www.kickstarter.com/projects/robbylava/enclave-aspirant/description?comment=Q29tbWVudC00NTk0MTcwMA%3D%3D](https://www.kickstarter.com/projects/robbylava/enclave-aspirant/description?comment=Q29tbWVudC00NTk0MTcwMA%3D%3D)  
47. Basic Fantasy RPG 4th Edition (Hardback Alternate Cover) \- Lulu, accesso eseguito il giorno maggio 14, 2026, [https://www.lulu.com/shop/erik-wilson-and-chris-gonnerman/basic-fantasy-rpg-4th-edition-hardback-alternate-cover/hardcover/product-nvq2m78.html](https://www.lulu.com/shop/erik-wilson-and-chris-gonnerman/basic-fantasy-rpg-4th-edition-hardback-alternate-cover/hardcover/product-nvq2m78.html)  
48. Basic Fantasy RPG Core Rules 4thEd (Alternate Cover) \- The Basic, accesso eseguito il giorno maggio 14, 2026, [https://www.wargamevault.com/en/product/480067/Basic-Fantasy-RPG-Core-Rules-4thEd-Alternate-Cover?language=ptpto](https://www.wargamevault.com/en/product/480067/Basic-Fantasy-RPG-Core-Rules-4thEd-Alternate-Cover?language=ptpto)
