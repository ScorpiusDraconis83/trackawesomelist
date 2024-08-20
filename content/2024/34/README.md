# Awesome List Updates on Aug 19 - Aug 25, 2024

16 awesome lists updated this week.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Ai Tools](/content/mahseema/awesome-ai-tools/week/README.md)

### Audio / AI Voice Cloning

*   [Descript Overdub](https://www.descript.com/overdub) - [Review](https://theresanai.com/descript-overdub) - Seamlessly integrates with Descript’s transcription and editing tools, ideal for content creators needing quick voiceovers.
*   [Respeecher](https://www.respeecher.com/) - [Review](https://theresanai.com/respeecher) -  A professional tool widely used in the entertainment industry to create emotion-rich, realistic voice clones.
*   [ElevenLabs](https://elevenlabs.io/) - [Review](https://theresanai.com/elevenlabs) - Known for ultra-realistic voice cloning and emotion modeling, setting a new standard in AI-driven voice synthesis.
*   [Murf AI](https://murf.ai/) - [Review](https://theresanai.com/murf) - User-friendly platform for quick, high-quality voiceovers, favored for commercial and marketing applications.
*   [iSpeech](https://www.ispeech.org/) - [Review](https://theresanai.com/ispeech) - A versatile solution for corporate applications with support for a wide array of languages and voices.
*   [Veritone Voice](https://www.veritone.com/solutions/voice/) - [Review](https://theresanai.com/veritone-voice) - Focuses on maintaining brand consistency with highly customizable voice cloning used in media and entertainment.
*   [Microsoft Azure Neural TTS](https://azure.microsoft.com/en-us/services/cognitive-services/text-to-speech/) - Review - Scalable and highly customizable, ideal for integration into enterprise applications.
*   [WellSaid Labs](https://www.wellsaidlabs.com/) - [Review](https://theresanai.com/wellsaid-labs) - Gaining traction for its natural-sounding voiceovers, particularly in corporate training and e-learning.
*   [Lovo.ai](https://www.lovo.ai/) - [Review](https://theresanai.com/lovo-ai) - A compelling choice for creative professionals, especially useful in ads and explainer videos.

## [2. Awesome Polars](/content/ddotta/awesome-polars/week/README.md)

### Libraries/Packages/Scripts / Python

*   [Narwhals (⭐304)](https://github.com/narwhals-dev/narwhals) - Python files that provides an extremely lightweight compatibility layer between Polars, Pandas, cuDF, and Modin by [@narwhals-dev](https://github.com/narwhals-dev).
*   [photoshoot (⭐2)](https://github.com/ngriffiths13/photoshoot) - A pytest plugin library for doing snapshot testing with Polars DataFrames by [@ngriffiths13](https://github.com/ngriffiths13).

## [3. Awesome Kotlin](/content/KotlinBy/awesome-kotlin/week/README.md)

### Libraries/Frameworks / Graphics

*   [GlimpseFramework/glimpse-framework (⭐16)](https://github.com/GlimpseFramework/glimpse-framework) - OpenGL made simple.

## [4. Awesome Acg](/content/soruly/awesome-acg/week/README.md)

### Downloaders

*   [waifuc (⭐236)](https://github.com/deepghs/waifuc) - Anime image data collector for training models. \[English]

### Image Processing

*   [imgutils (⭐154)](https://github.com/deepghs/imgutils) - Image processing library with various anime-style image processing models. \[English]

### Developer Groups

*   DeepGHS ([GitHub](https://github.com/deepghs) / [Hugging Face](https://huggingface.co/deepghs)) \[English]

## [5. Free for Dev](/content/ripienaar/free-for-dev/week/README.md)

### Other Free Resources

*   [MySQL Visual Explain](https://mysqlexplain.com) - Easy-to-understand and free MySQL EXPLAIN output visualizer to optimize slow queries.

## [6. Awesome Godot](/content/godotengine/awesome-godot/week/README.md)

### 3D / Godot 4.3

*   [OpenLiberty (⭐68)](https://github.com/FOSS-Supremacy/OpenLiberty) - An open-source reimplementation of Grand Theft Auto III on the Godot Engine.

## [7. Awesome Azure Openai Llm](/content/kimtth/awesome-azure-openai-llm/week/README.md)

### **Build an LLMs from scratch: picoGPT and lit-gpt** / **GPT series release date**

*   [Transformer Explainer](https://arxiv.org/pdf/2408.04619): an open-source interactive tool to learn about the inner workings of a Transformer model (GPT-2) [git](https://poloclub.github.io/transformer-explainer/) \[8 Aug 2024]

    <details>

    <summary>Expand</summary>

    *   Beam Search \[1977] in Transformers is an inference algorithm that maintains the `beam_size` most probable sequences until the end token appears or maximum sequence length is reached. If `beam_size` (k) is 1, it's a `Greedy Search`. If k equals the total vocabularies, it's an `Exhaustive Search`. [ref](https://huggingface.co/blog/constrained-beam-search) \[Mar 2022]

    #### Classification of Attention

    *   [ref](https://arize.com/blog-course/attention-mechanisms-in-machine-learning/): Must-Read Starter Guide to Mastering Attention Mechanisms in Machine Learning \[12 Jun 2023]

    1.  Encoder-Decoder Attention:

        1.  Soft Attention: assigns continuous weights to input elements, allowing the model to attend to multiple elements simultaneously. Used in neural machine translation.
        2.  Hard Attention: selects a subset of input elements to focus on while ignoring the rest. Used in image captioning.
        3.  Global Attention: focuses on all elements of the input sequence when computing attention weights. Captures long-range dependencies and global context.
        4.  Local Attention: focuses on a smaller, localized region of the input sequence when computing attention weights. Reduces computational complexity. Used in time series analysis.

    2.  Extended Forms of Attention: Only one Decoder component (only Input Sequence, no Target Sequence)

        1.  Self Attention: attends to different parts of the input sequence itself, rather than another sequence or modality. Captures long-range dependencies and contextual information. Used in transformer models.
        2.  Multi-head Self-Attention: performs self-attention multiple times in parallel, allowing the model to jointly attend to information from different representation subspaces.

        <!-- 1. Hierarchical Attention: attends to different levels of granularity in the input sequence, allowing the model to capture both local and global context. -->

    3.  Other Types of Attention:

        1.  Sparse Attention: reduces computation by focusing on a limited selection of similarity scores in a sequence, resulting in a sparse matrix. It includes implementations of “strided” and “fixed” attention. [ref](https://blog.research.google/2020/10/rethinking-attention-with-performers.html) \[23 Oct 2020]

        <!-- <img src="https://github.com/kimtth/awesome-azure-openai-llm/raw/main/files/rethinking-attention-with-performers.gif"/> -->

        1.  Cross-Attention: mixes two different embedding sequences, allowing the model to attend to information from both sequences. In a Transformer, when the information is passed from encoder to decoder that part is known as Cross Attention. [ref](https://vaclavkosar.com/ml/cross-attention-in-transformer-architecture) / [ref](https://sebastianraschka.com/blog/2023/self-attention-from-scratch.html) \[9 Feb 2023]

        2.  Sliding Window Attention (SWA): A technique used Longformer. It uses a fixed-size window of attention around each token, which allows the model to scale efficiently to long inputs. Each token attends to half the window size tokens on each side. [ref (⭐9.4k)](https://github.com/mistralai/mistral-src#sliding-window-to-speed-up-inference-and-reduce-memory-pressure)

    </details>

### **Agents: AutoGPT and Communicative Agents** / Agent Applications and Libraries

*   [SakanaAI AI-Scientist (⭐4.5k)](https://github.com/SakanaAI/AI-Scientist): Towards Fully Automated Open-Ended Scientific Discovery \[Aug 2024]

### **Caching** / **OSS Alternatives for OpenAI Code Interpreter (aka. Advanced Data Analytics)**

*   [Prompt caching with Claude](https://www.anthropic.com/news/prompt-caching): Reducing costs by up to 90% and latency by up to 85% for long prompts. \[15 Aug 2024]

### **LLMOps: Large Language Model Operations** / Math

*   [Azure ML Prompt flow](https://microsoft.github.io/promptflow/index.html): A set of LLMOps tools designed to facilitate the creation of LLM-based AI applications \[Sep 2023] > [How to Evaluate & Upgrade Model Versions in the Azure OpenAI Service](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/how-to-evaluate-amp-upgrade-model-versions-in-the-azure-openai/ba-p/4218880) \[14 Aug 2024]

## [8. Awesome Vue](/content/vuejs/awesome-vue/week/README.md)

### Resources / Podcasts

*   [DejaVue - The Vue podcast to remember](https://dejavue.fm/)

### Resources / Examples

*   [umo editor (⭐119)](https://github.com/umodoc/editor) - Umo Editor is an open-source document editor, based on Vue3 and Tiptap. Visit [Playground](https://demo.umodoc.com/editor?lang=en-US) for a fast experience.

### Projects Using Vue.js / Open Source

*   [Go-Vue-Chat-Starter (⭐3)](https://github.com/CoffeeeAtNight/Go-Vue-Chat-Starter) - A simple chat application starter project built with Vue.js and Go, featuring WebSocket communication, PrimeVue/PrimeFlex for the UI.

### Components & Libraries / UI Components

*   [navpress (⭐1)](https://github.com/aaronlamz/navpress) - NavPress is a CLI tool for generating static navigation websites. It allows you to quickly build a navigation site through a configuration file.
*   [vue-speedometer (⭐59)](https://github.com/palerdot/vue-speedometer) - Vue component for showing speedometer like gauge using d3.
*   [Vue-Player (⭐2)](https://github.com/display-design-studio/vue-player) - Lightweight, customizable, and easy-to-implement vue video player.
*   [vue3-select-component (⭐37)](https://github.com/TotomInc/vue3-select-component) - Vue 3 Select Component, single & multi-select, best-in-class DX support with TypeScript end-to-end typesafe, easy styling, slots and more \~4.4KB

### Components & Libraries / Scaffold

*   [mevn-boilerplate (⭐145)](https://github.com/mustafacagri/mevn-boilerplate) - ⭐️ the most comprehensive mevn stack boilerplate. ⭐️ mongodb - express - vue 3 (admin dashboard) - nodejs - nuxt 3 (client) boilerplate (pinia, tiptap, slug, vuetify and vuexy and more...) 🎉

## [9. Awesome Webaudio](/content/notthetup/awesome-webaudio/week/README.md)

### Resources / Tutorials

*   [audio-katas (⭐53)](https://github.com/survivejs/audio-katas) - A collection of self-guided katas during which you will build a DAW of your own while getting exposed to the key Web Audio APIs.

## [10. Awesome Vite](/content/vitejs/awesome-vite/week/README.md)

### Templates / React

*   [React Dapp Starter (⭐1)](https://github.com/Manta-Network/react-dapp-starter) - Enterprise-ready Web3 DApp starter with `TypeScript`, `TailwindCSS`, `Web3Modal`, `Wagmi`, `Shadcn UI`, `Zustand`, and `TanStack Query` for scalable decentralized applications.

### Framework-agnostic Plugins / Testing

*   [@poyro/vitest (⭐27)](https://github.com/poyro/poyro) - Test LLM integrations using Vitest.

### Framework-agnostic Plugins / Security

*   [vite-plugin-csp-guard (⭐1)](https://github.com/RockiRider/csp/tree/main/packages/vite-plugin-csp-guard) - Lets you configure a Content Security Policy to your project, supports all directives and hashing.

### WordPress / Community

*   [WordPlate (⭐2.1k)](https://github.com/vinkla/wordplate) - Starter app with Composer.

### TYPO3 CMS / Community

*   [vite-plugin-typo3 (⭐2)](https://github.com/s2b/vite-plugin-typo3) - Frontend integration for TYPO3 CMS.

## [11. Awesome Cl](/content/CodyReichert/awesome-cl/week/README.md)

### Parsing html / Isomorphic web frameworks

*   [cl-html5-parser (⭐55)](https://github.com/rotatef/cl-html5-parser) -  HTML5 parser for Common Lisp. GPL3.0.
    *   a port of the Python library html5lib.
    *   compared to Plump: Plump is a mix of an XML and an HTML parser and breaks on some HTML rules ([example (⭐119)](https://github.com/Shinmera/plump/issues/50]), while cl-html5-parser is a fully compliant HTML parser.

## [12. Awesome Rust](/content/rust-unofficial/awesome-rust/week/README.md)

### Libraries / Computation

*   Science
    *   [Axect/Peroxide (⭐486)](https://github.com/Axect/Peroxide) - Rust numeric library containing linear algebra, numerical analysis, statistics and machine learning tools in pure rust
    *   [cpmech/russell (⭐101)](https://github.com/cpmech/russell) - Rust Scientific Library for numerical mathematics, ordinary differential equations, special math functions, high-performance (sparse) linear algebra

### Libraries / Date and time

*   [arthurhenrique/rusti-cal (⭐52)](https://github.com/arthurhenrique/rusti-cal) \[[rusti-cal](https://crates.io/crates/rusti-cal)] - A cal(1) clone lightning-fast \~ more than 9999 years \~ Written in Rust.

## [13. Awesome Naming](/content/gruhn/awesome-naming/week/README.md)

### Tools, Applications, Libraries, Frameworks

*   [CockroachDB](https://web.archive.org/web/20150514123425/http://www.wired.co.uk/news/archive/2014-07/22/cockroachdb) - Database application, that is marketed as being so fault tolerant and resilient as a cockroach.

## [14. Awesome Angular](/content/PatrickJS/awesome-angular/week/README.md)

### AI / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [deep-chat (⭐1.4k)](https://github.com/OvidijusParsiunas/deep-chat) - Fully customizable AI chatbot component for your website.

### HTTP / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [angular-odata (⭐47)](https://github.com/diegomvh/angular-odata) - A fluent API for querying, creating, updating and deleting OData resources in Angular.

## [15. Awesome Sysadmin](/content/awesome-foss/awesome-sysadmin/week/README.md)

### Software / VPN

*   [Gluetun VPN client (⭐7.1k)](https://github.com/qdm12/gluetun) -  VPN client in a thin Docker container for multiple VPN providers, written in Go, and using OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in.  `MIT` `docker`

## [16. Awesome Zsh Plugins](/content/unixorn/awesome-zsh-plugins/week/README.md)

### Plugins / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [rose-pine-man (⭐3)](https://github.com/const-void/rose-pine-man) - Colorizes `man` pages.
*   [snr (⭐0)](https://github.com/raisedadead/zsh-snr) - Passes the selected output of the first command to the next.

### Completions / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [chezmoi (⭐0)](https://github.com/mass8326/zsh-chezmoi) - Adds completions and aliases for [chezmoi](https://www.chezmoi.io/). Detects if you have `git` aliases and generates `chezmoi` aliases for them.

### Themes / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [netmask (⭐0)](https://github.com/swomf/netmask-zsh-theme) - Termux-first theme. Includes decorators for ip address, full path to current directory, `git` status and python virtual environment.

---

- Next: [Aug 12 - Aug 18, 2024](/content/2024/33/README.md)