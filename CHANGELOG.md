# Changelog

## [0.4.0](https://github.com/najmialazhar/gradsun/compare/gradsun-v0.3.0...gradsun-v0.4.0) (2026-11-21)


### Features

* **database:** configure supabase pooled/direct urls and baseline schema ([#4](https://github.com/najmialazhar/gradsun/issues/4)) ([74a843f](https://github.com/najmialazhar/gradsun/commit/74a843fce22874e8f1b5ceeb0ba32702416b4f1d)), closes [#3](https://github.com/najmialazhar/gradsun/issues/3)
* **database:** define master data domain models and relations ([#21](https://github.com/najmialazhar/gradsun/issues/21)) ([f43975b](https://github.com/najmialazhar/gradsun/commit/f43975b797447445a302ba1a3261eaded4e84d6b)), closes [#12](https://github.com/najmialazhar/gradsun/issues/12)
* **governance:** implement ast guardrails and agents mandate ([#6](https://github.com/najmialazhar/gradsun/issues/6)) ([b81dcd3](https://github.com/najmialazhar/gradsun/commit/b81dcd38aff0037085febd72018452f1a4dd19f2)), closes [#5](https://github.com/najmialazhar/gradsun/issues/5)
* initial project setup ([efe61be](https://github.com/najmialazhar/gradsun/commit/efe61beda397ca0b72245541d9b925360e1e94ab))
* **packages:** implement packages domain slice with repository, use-cases, and safe actions ([#42](https://github.com/najmialazhar/gradsun/issues/42)) ([95ecfb1](https://github.com/najmialazhar/gradsun/commit/95ecfb1348b15df2cfa76e4e3da3a16ccce44401))
* **presentation:** add root layout, page, i18n dictionaries, and module structure ([#10](https://github.com/najmialazhar/gradsun/issues/10)) ([2523ff7](https://github.com/najmialazhar/gradsun/commit/2523ff7ba039b04404b766e84a5c68f38762677d)), closes [#9](https://github.com/najmialazhar/gradsun/issues/9)
* **reservations:** implement slot-calculator and pricing-calculator domain services ([#13](https://github.com/najmialazhar/gradsun/issues/13)) ([#25](https://github.com/najmialazhar/gradsun/issues/25)) ([bbb193b](https://github.com/najmialazhar/gradsun/commit/bbb193b7f747b20f270ea3f8b319a387717bba65))
* **storage:** setup supabase s3 client and sharp webp watermarking pipeline ([#14](https://github.com/najmialazhar/gradsun/issues/14)) ([#26](https://github.com/najmialazhar/gradsun/issues/26)) ([e3a7d2f](https://github.com/najmialazhar/gradsun/commit/e3a7d2f46ef827c5ffdbac5394f71f196ff48df2))
* **studios:** implement studio rooms and blackout dates domain slice with repository and actions ([#46](https://github.com/najmialazhar/gradsun/issues/46)) ([f0ba7da](https://github.com/najmialazhar/gradsun/commit/f0ba7daf07a8bd7d629439223a315b909db1809b))
* **ui:** implement complete public and admin ui framework for [#23](https://github.com/najmialazhar/gradsun/issues/23) ([#24](https://github.com/najmialazhar/gradsun/issues/24)) ([1ec032d](https://github.com/najmialazhar/gradsun/commit/1ec032d34fe4b6bf52e4ec1ab6c1ace83fc192a3))
* **ui:** install core shadcn/ui radix-nova primitives in common components ([79c121b](https://github.com/najmialazhar/gradsun/commit/79c121b3ca0938b2429f079414555cc45a7a8427))


### Bug Fixes

* **ci:** lock swc helpers, add prisma generation, and configure ci env validation ([90ca122](https://github.com/najmialazhar/gradsun/commit/90ca122a1f2213310b29f737cfa2fd3c1b2b36e8))


### Documentation

* **architecture:** add diataxis suite, adrs, ci workflow, and agent skills ([#8](https://github.com/najmialazhar/gradsun/issues/8)) ([bd70a61](https://github.com/najmialazhar/gradsun/commit/bd70a61af5dde7aaa2924da3d125017b4b909be0)), closes [#7](https://github.com/najmialazhar/gradsun/issues/7)
* modernize root readme with architecture overview, tech stack, and quality gates ([d96faab](https://github.com/najmialazhar/gradsun/commit/d96faab2f1cb7c069b40c032cc5d374e74ff597e))


### Miscellaneous Chores

* **docs:** prune obsolete scaffolding blueprints and legacy audit notes ([a08e5ba](https://github.com/najmialazhar/gradsun/commit/a08e5bada2aa4aa30cabb9ea2280ceb19e8ec79c))
* **git:** refine gitignore with enterprise os, editor, and log exclusions ([f560597](https://github.com/najmialazhar/gradsun/commit/f5605979fa67f3adce232da1d3889a562c31e1c2))
* **governance:** enforce agent issue-first workflow, semver release advisory, and package rename to gradsun ([#44](https://github.com/najmialazhar/gradsun/issues/44)) ([7c784b7](https://github.com/najmialazhar/gradsun/commit/7c784b701333096650288fa01769cc6b113dd7b2))
* **governance:** setup semantic pr validation and release-please automation ([1424ef5](https://github.com/najmialazhar/gradsun/commit/1424ef52708ed064170de0e544a4b13f58b6b08c))
* **main:** release photo-reserve 0.2.0 ([#19](https://github.com/najmialazhar/gradsun/issues/19)) ([7a40441](https://github.com/najmialazhar/gradsun/commit/7a404413d0863dbf94349f3a01ab164dbb9f5f9b))
* **main:** release photo-reserve 0.3.0 ([#22](https://github.com/najmialazhar/gradsun/issues/22)) ([ec77194](https://github.com/najmialazhar/gradsun/commit/ec77194b5164c8db65a706c4ace9d60875253b9c))
* **toolchain:** bootstrap next.js 15 toolchain, env validation, and styling ([#2](https://github.com/najmialazhar/gradsun/issues/2)) ([ebfac41](https://github.com/najmialazhar/gradsun/commit/ebfac41002d250337eb8f8282fde371956df1fe9)), closes [#1](https://github.com/najmialazhar/gradsun/issues/1)
* **toolchain:** ignore legacy audit notes in biome linter ([c264297](https://github.com/najmialazhar/gradsun/commit/c264297bb8d60281049303125d5600eb0ff252c0))
* **toolchain:** prune default create-next-app boilerplate assets and unused svgs ([#41](https://github.com/najmialazhar/gradsun/issues/41)) ([81e3dd9](https://github.com/najmialazhar/gradsun/commit/81e3dd9012b9cafcf0fe2d16816d0c57cd8ca7ad))

## [0.3.0](https://github.com/najmialazhar/gradsun/compare/photo-reserve-v0.2.0...photo-reserve-v0.3.0) (2026-11-21)


### Features

* **database:** define master data domain models and relations ([#21](https://github.com/najmialazhar/gradsun/issues/21)) ([f43975b](https://github.com/najmialazhar/gradsun/commit/f43975b797447445a302ba1a3261eaded4e84d6b)), closes [#12](https://github.com/najmialazhar/gradsun/issues/12)
* **packages:** implement packages domain slice with repository, use-cases, and safe actions ([#42](https://github.com/najmialazhar/gradsun/issues/42)) ([95ecfb1](https://github.com/najmialazhar/gradsun/commit/95ecfb1348b15df2cfa76e4e3da3a16ccce44401))
* **reservations:** implement slot-calculator and pricing-calculator domain services ([#13](https://github.com/najmialazhar/gradsun/issues/13)) ([#25](https://github.com/najmialazhar/gradsun/issues/25)) ([bbb193b](https://github.com/najmialazhar/gradsun/commit/bbb193b7f747b20f270ea3f8b319a387717bba65))
* **storage:** setup supabase s3 client and sharp webp watermarking pipeline ([#14](https://github.com/najmialazhar/gradsun/issues/14)) ([#26](https://github.com/najmialazhar/gradsun/issues/26)) ([e3a7d2f](https://github.com/najmialazhar/gradsun/commit/e3a7d2f46ef827c5ffdbac5394f71f196ff48df2))
* **ui:** implement complete public and admin ui framework for [#23](https://github.com/najmialazhar/gradsun/issues/23) ([#24](https://github.com/najmialazhar/gradsun/issues/24)) ([1ec032d](https://github.com/najmialazhar/gradsun/commit/1ec032d34fe4b6bf52e4ec1ab6c1ace83fc192a3))


### Miscellaneous Chores

* **toolchain:** prune default create-next-app boilerplate assets and unused svgs ([#41](https://github.com/najmialazhar/gradsun/issues/41)) ([81e3dd9](https://github.com/najmialazhar/gradsun/commit/81e3dd9012b9cafcf0fe2d16816d0c57cd8ca7ad))

## [0.2.0](https://github.com/najmialazhar/gradsun/compare/photo-reserve-v0.1.0...photo-reserve-v0.2.0) (2026-11-18)


### Features

* **database:** configure supabase pooled/direct urls and baseline schema ([#4](https://github.com/najmialazhar/gradsun/issues/4)) ([74a843f](https://github.com/najmialazhar/gradsun/commit/74a843fce22874e8f1b5ceeb0ba32702416b4f1d)), closes [#3](https://github.com/najmialazhar/gradsun/issues/3)
* **governance:** implement ast guardrails and agents mandate ([#6](https://github.com/najmialazhar/gradsun/issues/6)) ([b81dcd3](https://github.com/najmialazhar/gradsun/commit/b81dcd38aff0037085febd72018452f1a4dd19f2)), closes [#5](https://github.com/najmialazhar/gradsun/issues/5)
* initial project setup ([efe61be](https://github.com/najmialazhar/gradsun/commit/efe61beda397ca0b72245541d9b925360e1e94ab))
* **presentation:** add root layout, page, i18n dictionaries, and module structure ([#10](https://github.com/najmialazhar/gradsun/issues/10)) ([2523ff7](https://github.com/najmialazhar/gradsun/commit/2523ff7ba039b04404b766e84a5c68f38762677d)), closes [#9](https://github.com/najmialazhar/gradsun/issues/9)
* **ui:** install core shadcn/ui radix-nova primitives in common components ([79c121b](https://github.com/najmialazhar/gradsun/commit/79c121b3ca0938b2429f079414555cc45a7a8427))


### Bug Fixes

* **ci:** lock swc helpers, add prisma generation, and configure ci env validation ([90ca122](https://github.com/najmialazhar/gradsun/commit/90ca122a1f2213310b29f737cfa2fd3c1b2b36e8))


### Documentation

* **architecture:** add diataxis suite, adrs, ci workflow, and agent skills ([#8](https://github.com/najmialazhar/gradsun/issues/8)) ([bd70a61](https://github.com/najmialazhar/gradsun/commit/bd70a61af5dde7aaa2924da3d125017b4b909be0)), closes [#7](https://github.com/najmialazhar/gradsun/issues/7)
* modernize root readme with architecture overview, tech stack, and quality gates ([d96faab](https://github.com/najmialazhar/gradsun/commit/d96faab2f1cb7c069b40c032cc5d374e74ff597e))


### Miscellaneous Chores

* **docs:** prune obsolete scaffolding blueprints and legacy audit notes ([a08e5ba](https://github.com/najmialazhar/gradsun/commit/a08e5bada2aa4aa30cabb9ea2280ceb19e8ec79c))
* **git:** refine gitignore with enterprise os, editor, and log exclusions ([f560597](https://github.com/najmialazhar/gradsun/commit/f5605979fa67f3adce232da1d3889a562c31e1c2))
* **governance:** setup semantic pr validation and release-please automation ([1424ef5](https://github.com/najmialazhar/gradsun/commit/1424ef52708ed064170de0e544a4b13f58b6b08c))
* **toolchain:** bootstrap next.js 15 toolchain, env validation, and styling ([#2](https://github.com/najmialazhar/gradsun/issues/2)) ([ebfac41](https://github.com/najmialazhar/gradsun/commit/ebfac41002d250337eb8f8282fde371956df1fe9)), closes [#1](https://github.com/najmialazhar/gradsun/issues/1)
* **toolchain:** ignore legacy audit notes in biome linter ([c264297](https://github.com/najmialazhar/gradsun/commit/c264297bb8d60281049303125d5600eb0ff252c0))
