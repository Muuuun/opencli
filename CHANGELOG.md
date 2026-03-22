# Changelog

## [1.2.0](https://github.com/jackwener/opencli/compare/v1.1.1...v1.2.0) (2026-03-22)


### Features

* add douban, sinablog, substack adapters; upgrade medium to TS ([#185](https://github.com/jackwener/opencli/issues/185)) ([bdf5967](https://github.com/jackwener/opencli/commit/bdf5967abd4f1955c63dcbc48718ad719a30365a))
* add Lobste.rs, Instagram, and Facebook adapters ([#199](https://github.com/jackwener/opencli/issues/199)) ([ce484c2](https://github.com/jackwener/opencli/commit/ce484c2a632b19fe4990e8f5a01f4b44ad499d87))
* **browser:** advanced DOM snapshot engine with 13-layer pruning pipeline ([#210](https://github.com/jackwener/opencli/issues/210)) ([d831b04](https://github.com/jackwener/opencli/commit/d831b04d481ea9a8f65116e4333d129ebe269ab7))
* **devto:** add devto adapter ([#234](https://github.com/jackwener/opencli/issues/234)) ([ea113a6](https://github.com/jackwener/opencli/commit/ea113a6471c5db56b27d5200ba519f437eb61aac))
* **google:** add search, suggest, news, and trends adapters ([#184](https://github.com/jackwener/opencli/issues/184)) ([4e32599](https://github.com/jackwener/opencli/commit/4e3259976b2a52d9013c3d562a4f134d8d8e489f))
* **grok:** add opt-in --web flow for grok ask ([#193](https://github.com/jackwener/opencli/issues/193)) ([fcff2e4](https://github.com/jackwener/opencli/commit/fcff2e40be3d88feed47b159b443de694e33cfb0))
* **instagram,facebook:** add write actions and extended commands ([#201](https://github.com/jackwener/opencli/issues/201)) ([eb0ccaf](https://github.com/jackwener/opencli/commit/eb0ccaf549ab0b0feba21dea5d890a3a6f3d7c6e))
* make primary args positional across all CLIs ([#242](https://github.com/jackwener/opencli/issues/242)) ([9696db9](https://github.com/jackwener/opencli/commit/9696db9ed43eab7287f8c3bd725b5cdbd1f9f232))
* **medium:** add medium adapter ([#190](https://github.com/jackwener/opencli/issues/190)) ([06c902a](https://github.com/jackwener/opencli/commit/06c902aeed6facde9316f86bb46fa4f598bf95eb))
* plugin system (Stage 0-2) ([1d39295](https://github.com/jackwener/opencli/commit/1d39295f4b9ee89f0fa606775974f3942a34c015))
* **tiktok:** add TikTok adapter with 15 commands ([#202](https://github.com/jackwener/opencli/issues/202)) ([4391ccf](https://github.com/jackwener/opencli/commit/4391ccfcb8cda572895562ea7b0a4640213f1832))
* **twitter:** add --type flag to timeline command ([#83](https://github.com/jackwener/opencli/issues/83)) ([#232](https://github.com/jackwener/opencli/issues/232)) ([e98cf75](https://github.com/jackwener/opencli/commit/e98cf756e99aefb85e9348f365c8b070fafda971))
* **xueqiu:** add earnings-date command ([#211](https://github.com/jackwener/opencli/issues/211)) ([fae1dce](https://github.com/jackwener/opencli/commit/fae1dce027a016ef151dfe1d3e0b17744b21e5ea))
* **xueqiu:** make primary args positional ([#213](https://github.com/jackwener/opencli/issues/213)) ([fb2a145](https://github.com/jackwener/opencli/commit/fb2a145e361fd1797cc5b32f5e12f1071033a2a0))


### Bug Fixes

* align positional primary args and docs ([#220](https://github.com/jackwener/opencli/issues/220)) ([4c8a447](https://github.com/jackwener/opencli/commit/4c8a447eadb44f611e92498eaf9a0fd404e78c0b))
* correct SKILL.md github reference and add missing adapter docs ([#230](https://github.com/jackwener/opencli/issues/230)) ([1ecac25](https://github.com/jackwener/opencli/commit/1ecac25df5bef3d99deebcf198654d6066eba2bf))
* **docs:** remove dead link to deleted github adapter ([#194](https://github.com/jackwener/opencli/issues/194)) ([50ec7c6](https://github.com/jackwener/opencli/commit/50ec7c6868eb83b04ac105133c36cc76adac78f8))
* **extension:** skip chrome-extension:// tabs in resolveTabId fallback ([#198](https://github.com/jackwener/opencli/issues/198)) ([fbf051d](https://github.com/jackwener/opencli/commit/fbf051d53905d066519f70a9ef85387d40eb94fa))
* fix social adapter bugs, sync docs, refactor boss common utils ([#204](https://github.com/jackwener/opencli/issues/204)) ([3669a89](https://github.com/jackwener/opencli/commit/3669a893237aa1c87904dd4333cf0e97f7d12b77))
* harden twitter timeline review findings ([#236](https://github.com/jackwener/opencli/issues/236)) ([4cd0409](https://github.com/jackwener/opencli/commit/4cd0409ded8ca739dd8cb2482b597dd973778f61))
* resolve inconsistent doctor --live report (fix [#121](https://github.com/jackwener/opencli/issues/121)) ([#224](https://github.com/jackwener/opencli/issues/224)) ([387aa0d](https://github.com/jackwener/opencli/commit/387aa0d6e5eeaa1dc4148cc87c3633995b36de4a))
* **wikipedia:** fix search arg name + add random and trending commands ([#231](https://github.com/jackwener/opencli/issues/231)) ([1d56dd7](https://github.com/jackwener/opencli/commit/1d56dd77a88250e24b30cc79254c893f8efcded1))

## [1.1.0](https://github.com/jackwener/opencli/compare/v1.0.6...v1.1.0) (2026-03-20)


### Features

* add antigravity serve command — Anthropic API proxy ([35a0fed](https://github.com/jackwener/opencli/commit/35a0fed8a0c1cb714298f672c19f017bbc9a9630))
* add arxiv and wikipedia adapters ([#132](https://github.com/jackwener/opencli/issues/132)) ([3cda14a](https://github.com/jackwener/opencli/commit/3cda14a2ab502e3bebfba6cdd9842c35b2b66b41))
* add external CLI hub for discovery, auto-installation, and execution of external tools. ([b3e32d8](https://github.com/jackwener/opencli/commit/b3e32d8a05744c9bcdfef96f5ff3085ac72bd353))
* add sinafinance 7x24 news adapter ([#131](https://github.com/jackwener/opencli/issues/131)) ([02793e9](https://github.com/jackwener/opencli/commit/02793e990ef4bdfdde9d7a748960b8a9ed6ea988))
* **boss:** add 8 new recruitment management commands ([#133](https://github.com/jackwener/opencli/issues/133)) ([7e973ca](https://github.com/jackwener/opencli/commit/7e973ca59270029f33021a483ca4974dc3975d36))
* **serve:** implement auto new conv, model mapping, and precise completion detection ([0e8c96b](https://github.com/jackwener/opencli/commit/0e8c96b6d9baebad5deb90b9e0620af5570b259d))
* **serve:** use CDP mouse click + Input.insertText for reliable message injection ([c63af6d](https://github.com/jackwener/opencli/commit/c63af6d41808dddf6f0f76789aa6c042f391f0b0))
* xiaohongshu creator flows migration ([#124](https://github.com/jackwener/opencli/issues/124)) ([8f17259](https://github.com/jackwener/opencli/commit/8f1725982ec06d121d7c15b5cf3cda2f5941c32a))


### Bug Fixes

* **docs:** use base '/' for custom domain and add CNAME file ([#129](https://github.com/jackwener/opencli/issues/129)) ([2876750](https://github.com/jackwener/opencli/commit/2876750891bc8a66be577b06ead4db61852c8e81))
* **serve:** update model mappings to match actual Antigravity UI ([36bc57a](https://github.com/jackwener/opencli/commit/36bc57a9624cdfaa50ffb2c1ad7f9c518c5e6c55))
* type safety for wikiFetch and arxiv abstract truncation ([4600b9d](https://github.com/jackwener/opencli/commit/4600b9d46dc7b56ff564c5f100c3a94c6a792c06))
* use UTC+8 for XHS timestamp formatting (CI timezone fix) ([03f067d](https://github.com/jackwener/opencli/commit/03f067d90764487f0439705df36e1a5c969a7f98))
* **xiaohongshu:** use fixed UTC+8 offset in trend timestamp formatting (CI timezone fix) ([593436e](https://github.com/jackwener/opencli/commit/593436e4cb5852f396fbaaa9f87ef1a0b518e76d))

## [1.0.6](https://github.com/jackwener/opencli/compare/v1.0.5...v1.0.6) (2026-03-20)


### Bug Fixes

* use %20 instead of + for spaces in Bilibili WBI signed requests ([#126](https://github.com/jackwener/opencli/issues/126)) ([4cabca1](https://github.com/jackwener/opencli/commit/4cabca12dfa6ca027b938b80ee6b940b5e89ea5c)), closes [#125](https://github.com/jackwener/opencli/issues/125)
