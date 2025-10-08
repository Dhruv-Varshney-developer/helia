:robot: I have created a release *beep* *boop*
---


<details><summary>bitswap: 3.0.0</summary>

## [3.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/bitswap-v2.2.0...bitswap-v3.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x

### Features

* add @helia/bitswap with sessions ([#409](https://github.com/Dhruv-Varshney-developer/helia/issues/409)) ([e582c63](https://github.com/Dhruv-Varshney-developer/helia/commit/e582c63ca296c789312f5fcf5e3e18f267f74c03))
* add block received event ([#837](https://github.com/Dhruv-Varshney-developer/helia/issues/837)) ([7d471a0](https://github.com/Dhruv-Varshney-developer/helia/commit/7d471a027606254f4fb4e1b73d62b8646426237d))
* add metrics property to helia interface ([#512](https://github.com/Dhruv-Varshney-developer/helia/issues/512)) ([f7f71bb](https://github.com/Dhruv-Varshney-developer/helia/commit/f7f71bb20ab0b4efbe802be5af1189e76153b826))
* pass initial providers to session ([#777](https://github.com/Dhruv-Varshney-developer/helia/issues/777)) ([3d77369](https://github.com/Dhruv-Varshney-developer/helia/commit/3d773698389deb70e1a0181eb81fb8b5992857b8))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* define max bitswap message sizes ([#510](https://github.com/Dhruv-Varshney-developer/helia/issues/510)) ([58d7ddf](https://github.com/Dhruv-Varshney-developer/helia/commit/58d7ddf19cd965a8a5cc1d8148fa073a6b44d8ae))
* improve bitswap message merging ([#522](https://github.com/Dhruv-Varshney-developer/helia/issues/522)) ([7419dfc](https://github.com/Dhruv-Varshney-developer/helia/commit/7419dfc2fe273d3f816d27b62062636be0964d7a))
* improve sessions implementation ([#495](https://github.com/Dhruv-Varshney-developer/helia/issues/495)) ([9ea934e](https://github.com/Dhruv-Varshney-developer/helia/commit/9ea934ed7208e87c28bc65e9090bdedf66ceeffd))
* increase default listers on abort signals ([#484](https://github.com/Dhruv-Varshney-developer/helia/issues/484)) ([7cd012a](https://github.com/Dhruv-Varshney-developer/helia/commit/7cd012aa2ba568845d49d63a71806d20f6ac678f))
* remove @libp2p/interfaces dep ([#591](https://github.com/Dhruv-Varshney-developer/helia/issues/591)) ([e567717](https://github.com/Dhruv-Varshney-developer/helia/commit/e567717102464a925f87cb10fc05808a50be960e))
* remove wants from wantlist when multiple block retrievers are used ([#491](https://github.com/Dhruv-Varshney-developer/helia/issues/491)) ([b1c761d](https://github.com/Dhruv-Varshney-developer/helia/commit/b1c761db6db7a7aca3044263fdd5e8967204deeb))
* split bitswap messages ([#507](https://github.com/Dhruv-Varshney-developer/helia/issues/507)) ([59de059](https://github.com/Dhruv-Varshney-developer/helia/commit/59de0599367c828998069ac37dc93e10ddb565a1))
* update deps and fix types ([#572](https://github.com/Dhruv-Varshney-developer/helia/issues/572)) ([f16c9ea](https://github.com/Dhruv-Varshney-developer/helia/commit/f16c9eac32677333313c433eb918b705439c0819))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))


### Dependencies

* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump it-length-prefixed from 9.1.1 to 10.0.1 ([#740](https://github.com/Dhruv-Varshney-developer/helia/issues/740)) ([ac7185a](https://github.com/Dhruv-Varshney-developer/helia/commit/ac7185af8f0da0782f6273fba76ccfe9427d2fa4))
* **dev:** bump sinon from 17.0.2 to 18.0.0 ([#536](https://github.com/Dhruv-Varshney-developer/helia/issues/536)) ([62f77df](https://github.com/Dhruv-Varshney-developer/helia/commit/62f77dfbff94a64e9c248f5be54055c18a6427f7))
* **dev:** bump sinon from 18.0.1 to 19.0.2 ([#634](https://github.com/Dhruv-Varshney-developer/helia/issues/634)) ([23e62e1](https://github.com/Dhruv-Varshney-developer/helia/commit/23e62e16b8962bfe982a1bbb157a144382ca7099))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
    * @helia/utils bumped from ^1.4.0 to ^2.0.0
</details>

<details><summary>block-brokers: 5.0.0</summary>

## [5.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/block-brokers-v4.2.4...block-brokers-v5.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* the `.dagWalkers` property has been removed
* helia now uses libp2p@2.x.x
* the gateways init option has been removed from trustless gateway block brokers
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module

### Features

* add @helia/bitswap with sessions ([#409](https://github.com/Dhruv-Varshney-developer/helia/issues/409)) ([e582c63](https://github.com/Dhruv-Varshney-developer/helia/commit/e582c63ca296c789312f5fcf5e3e18f267f74c03))
* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add block session support to @helia/interface ([#398](https://github.com/Dhruv-Varshney-developer/helia/issues/398)) ([5cf216b](https://github.com/Dhruv-Varshney-developer/helia/commit/5cf216baa6806cd82f8fcddd1f024ef6a506f667))
* add sessions to trustless gateways ([#459](https://github.com/Dhruv-Varshney-developer/helia/issues/459)) ([6ddefb0](https://github.com/Dhruv-Varshney-developer/helia/commit/6ddefb01154b970f5ab7ec7cb7445d9eedbc5474))
* allow modifying trustless-gateway fetch ([#751](https://github.com/Dhruv-Varshney-developer/helia/issues/751)) ([15de32f](https://github.com/Dhruv-Varshney-developer/helia/commit/15de32fe0e2c6293d166d6ab95fa373fc9630a88))
* expose configured dag walkers and hashers on helia interface ([#381](https://github.com/Dhruv-Varshney-developer/helia/issues/381)) ([843fba4](https://github.com/Dhruv-Varshney-developer/helia/commit/843fba467ebb032907c888da499147a5349ec10e)), closes [#375](https://github.com/Dhruv-Varshney-developer/helia/issues/375)
* pass initial providers to session ([#777](https://github.com/Dhruv-Varshney-developer/helia/issues/777)) ([3d77369](https://github.com/Dhruv-Varshney-developer/helia/commit/3d773698389deb70e1a0181eb81fb8b5992857b8))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* @helia/block-brokers gateways uses path gateways ([#374](https://github.com/Dhruv-Varshney-developer/helia/issues/374)) ([94b0cd1](https://github.com/Dhruv-Varshney-developer/helia/commit/94b0cd162ce864d44726a1d486389b0a1fdd3efc))
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* Adjust filtering logic for secure contexts; improve tests ([#579](https://github.com/Dhruv-Varshney-developer/helia/issues/579)) ([ac4bdb8](https://github.com/Dhruv-Varshney-developer/helia/commit/ac4bdb8a73cab23500221340830969552a1d8db6))
* create @helia/block-brokers package ([#341](https://github.com/Dhruv-Varshney-developer/helia/issues/341)) ([#342](https://github.com/Dhruv-Varshney-developer/helia/issues/342)) ([2979147](https://github.com/Dhruv-Varshney-developer/helia/commit/297914756fa06dc0c28890a2654d1159d16689c2))
* http blockbroker loads gateways from routing ([#519](https://github.com/Dhruv-Varshney-developer/helia/issues/519)) ([6a62d1c](https://github.com/Dhruv-Varshney-developer/helia/commit/6a62d1c8dcfadead0498d0bb59958837dc204c91))
* improve sessions implementation ([#495](https://github.com/Dhruv-Varshney-developer/helia/issues/495)) ([9ea934e](https://github.com/Dhruv-Varshney-developer/helia/commit/9ea934ed7208e87c28bc65e9090bdedf66ceeffd))
* prevent duplicate trustless-gateway reqs ([#503](https://github.com/Dhruv-Varshney-developer/helia/issues/503)) ([338885f](https://github.com/Dhruv-Varshney-developer/helia/commit/338885f20277a25277ba9192d8e15cca95e640e4))
* reject blockstore session get promise when signal fires  ([#776](https://github.com/Dhruv-Varshney-developer/helia/issues/776)) ([d883eaf](https://github.com/Dhruv-Varshney-developer/helia/commit/d883eafbdcd981a0cc7c78cf361bb72324a8cbdc))
* remove  example from readme.md ([55c64b4](https://github.com/Dhruv-Varshney-developer/helia/commit/55c64b4c9b6becbbe66165d3d952e130b828e095))
* remove w3s.link default block-broker ([#371](https://github.com/Dhruv-Varshney-developer/helia/issues/371)) ([5c4fd54](https://github.com/Dhruv-Varshney-developer/helia/commit/5c4fd54207384165c4e6309ec7663e996d7d66d4))
* replace dag walkers with generic CID extraction from blocks ([#447](https://github.com/Dhruv-Varshney-developer/helia/issues/447)) ([5ff6998](https://github.com/Dhruv-Varshney-developer/helia/commit/5ff6998e6bc8b04e3407bc98c1924c55f632d9b7))
* respect trustless gateway options for sessions ([#566](https://github.com/Dhruv-Varshney-developer/helia/issues/566)) ([5643b1d](https://github.com/Dhruv-Varshney-developer/helia/commit/5643b1d31a821a31d61f5a37256465895260f117))
* trustless gateway brokers no longer take a gateways arg ([#530](https://github.com/Dhruv-Varshney-developer/helia/issues/530)) ([a8fdfc2](https://github.com/Dhruv-Varshney-developer/helia/commit/a8fdfc27e3c2c75d75cc14dafe971796d70d8411))
* trustless gateway returned blocks can be limited ([#791](https://github.com/Dhruv-Varshney-developer/helia/issues/791)) ([7a52e95](https://github.com/Dhruv-Varshney-developer/helia/commit/7a52e95165f4a16a1fb2f62cfc6e936cb6f78b69))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use a short-lived AbortSignal for fetch operations ([#511](https://github.com/Dhruv-Varshney-developer/helia/issues/511)) ([5e98950](https://github.com/Dhruv-Varshney-developer/helia/commit/5e989501203c48661416aff090c135268b5c8445))


### Documentation

* add example for customizing fetch requests to trustless gateways. ([3d34808](https://github.com/Dhruv-Varshney-developer/helia/commit/3d3480861af9e07867988daf37cd6ecc481a9fff))
* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* Example for customizing fetch requests to trustless gateways ([7d96cfe](https://github.com/Dhruv-Varshney-developer/helia/commit/7d96cfef2c41bd29bae3a164e2be3873a297c161))
* Example for customizing fetch requests to trustless gateways ([1d58068](https://github.com/Dhruv-Varshney-developer/helia/commit/1d58068936adc81ff0ed99b40e34ac7baaf99c71))
* Example for customizing fetch requests to trustless gateways ([340085f](https://github.com/Dhruv-Varshney-developer/helia/commit/340085f9edcd73d9d1d6e9cbae019fdb7f5c6bcc))
* fix API docs link ([#809](https://github.com/Dhruv-Varshney-developer/helia/issues/809)) ([41bcc88](https://github.com/Dhruv-Varshney-developer/helia/commit/41bcc88dbc6f516c4ad4ca3740b83eafdcd5e1c9))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))


### Dependencies

* bump @multiformats/multiaddr-to-uri from 10.1.2 to 11.0.0 ([#676](https://github.com/Dhruv-Varshney-developer/helia/issues/676)) ([74f392c](https://github.com/Dhruv-Varshney-developer/helia/commit/74f392c207db3536c597d2fa59ad86a647672ec9))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* **dev:** bump sinon from 17.0.2 to 18.0.0 ([#536](https://github.com/Dhruv-Varshney-developer/helia/issues/536)) ([62f77df](https://github.com/Dhruv-Varshney-developer/helia/commit/62f77dfbff94a64e9c248f5be54055c18a6427f7))
* **dev:** bump sinon from 18.0.1 to 19.0.2 ([#634](https://github.com/Dhruv-Varshney-developer/helia/issues/634)) ([23e62e1](https://github.com/Dhruv-Varshney-developer/helia/commit/23e62e16b8962bfe982a1bbb157a144382ca7099))
* update @multiformats/multiaddr matcher ([#827](https://github.com/Dhruv-Varshney-developer/helia/issues/827)) ([a026690](https://github.com/Dhruv-Varshney-developer/helia/commit/a0266903e981c5e6e2771e7d0d4b60fc659e0eef))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* The following workspace dependencies were updated
  * dependencies
    * @helia/bitswap bumped from ^2.2.0 to ^3.0.0
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
    * @helia/utils bumped from ^1.4.0 to ^2.0.0
</details>

<details><summary>car: 5.0.0</summary>

## [5.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/car-v4.2.0...car-v5.0.0) (2025-10-08)


###   BREAKING CHANGES

* car.stream has been renamed car.export
* uses libp2p v3 and updated block/data stores
* the `.dagWalkers` property has been removed
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add `filter` option to de-duplicate blocks in car files ([461d219](https://github.com/Dhruv-Varshney-developer/helia/commit/461d219927a6725508014392340820d01a76a64f))
* car export supports custom dag traversal and export ([#767](https://github.com/Dhruv-Varshney-developer/helia/issues/767)) ([313e2c1](https://github.com/Dhruv-Varshney-developer/helia/commit/313e2c10a71c4f42533c3f077c6720563dd09ce5))
* expose configured dag walkers and hashers on helia interface ([#381](https://github.com/Dhruv-Varshney-developer/helia/issues/381)) ([843fba4](https://github.com/Dhruv-Varshney-developer/helia/commit/843fba467ebb032907c888da499147a5349ec10e)), closes [#375](https://github.com/Dhruv-Varshney-developer/helia/issues/375)
* expose providers option ([#834](https://github.com/Dhruv-Varshney-developer/helia/issues/834)) ([5a911c6](https://github.com/Dhruv-Varshney-developer/helia/commit/5a911c6977ec47d1906ccc69b5f57667f22d9ccf))
* rename car stream to export ([#859](https://github.com/Dhruv-Varshney-developer/helia/issues/859)) ([63338b9](https://github.com/Dhruv-Varshney-developer/helia/commit/63338b9c261a1120592e5afb256dfa8c8feed16b))
* stream car file bytes from @helia/car ([#444](https://github.com/Dhruv-Varshney-developer/helia/issues/444)) ([7c07e11](https://github.com/Dhruv-Varshney-developer/helia/commit/7c07e113d644a1efc32b7fd0c268f5f892256ce9))
* update helia to v3 and multiformats to v13 ([#52](https://github.com/Dhruv-Varshney-developer/helia/issues/52)) ([6405c34](https://github.com/Dhruv-Varshney-developer/helia/commit/6405c3487879614dc4dd7308b15c946d644e0488))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* remove @libp2p/interfaces dep ([#591](https://github.com/Dhruv-Varshney-developer/helia/issues/591)) ([e567717](https://github.com/Dhruv-Varshney-developer/helia/commit/e567717102464a925f87cb10fc05808a50be960e))
* replace dag walkers with generic CID extraction from blocks ([#447](https://github.com/Dhruv-Varshney-developer/helia/issues/447)) ([5ff6998](https://github.com/Dhruv-Varshney-developer/helia/commit/5ff6998e6bc8b04e3407bc98c1924c55f632d9b7))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use blockstore interface where possible ([#417](https://github.com/Dhruv-Varshney-developer/helia/issues/417)) ([30c8981](https://github.com/Dhruv-Varshney-developer/helia/commit/30c8981934ffba72d572a7b8b2712ec93b7f4d31))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* update @helia/car export method example ([#761](https://github.com/Dhruv-Varshney-developer/helia/issues/761)) ([73cb631](https://github.com/Dhruv-Varshney-developer/helia/commit/73cb631e7347688012f429cd69b1046db249e694))


### Dependencies

* bump @helia/interface from 1.2.2 to 2.0.0 ([#32](https://github.com/Dhruv-Varshney-developer/helia/issues/32)) ([68656a8](https://github.com/Dhruv-Varshney-developer/helia/commit/68656a81b7cd1238641a41573915635905e4a6ed))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump cborg from 1.10.2 to 2.0.5 ([#35](https://github.com/Dhruv-Varshney-developer/helia/issues/35)) ([10994ea](https://github.com/Dhruv-Varshney-developer/helia/commit/10994ea9abdff8906ae8c3f7d0ff5f50b50d9e60))
* bump multiformats from 11.0.2 to 12.0.1 ([#4](https://github.com/Dhruv-Varshney-developer/helia/issues/4)) ([50bed0f](https://github.com/Dhruv-Varshney-developer/helia/commit/50bed0f32b3c07111de804b0e6471e36d8e66626))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#30](https://github.com/Dhruv-Varshney-developer/helia/issues/30)) ([ea26a0b](https://github.com/Dhruv-Varshney-developer/helia/commit/ea26a0bd14137eb1de6ab282cdcecd55578064ab))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#41](https://github.com/Dhruv-Varshney-developer/helia/issues/41)) ([e8fc99f](https://github.com/Dhruv-Varshney-developer/helia/commit/e8fc99f4e372eaf72c2598f5a7a9942143c6d788))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
  * devDependencies
    * @helia/mfs bumped from ^5.1.0 to ^6.0.0
    * @helia/unixfs bumped from ^5.1.0 to ^6.0.0
</details>

<details><summary>dag-cbor: 5.0.0</summary>

## [5.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/dag-cbor-v4.1.0...dag-cbor-v5.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* expose providers option ([#834](https://github.com/Dhruv-Varshney-developer/helia/issues/834)) ([5a911c6](https://github.com/Dhruv-Varshney-developer/helia/commit/5a911c6977ec47d1906ccc69b5f57667f22d9ccf))
* update helia to v3 and multiformats to v13 ([#45](https://github.com/Dhruv-Varshney-developer/helia/issues/45)) ([f078447](https://github.com/Dhruv-Varshney-developer/helia/commit/f078447b6eba4c3d404d62bb930757aa1c0efe74))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* @helia/* modules validate CID codec ([#643](https://github.com/Dhruv-Varshney-developer/helia/issues/643)) ([93aa464](https://github.com/Dhruv-Varshney-developer/helia/commit/93aa46459dcff81f0e5eef479f76e39ef5f03736))
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* remove @libp2p/interfaces dep ([#591](https://github.com/Dhruv-Varshney-developer/helia/issues/591)) ([e567717](https://github.com/Dhruv-Varshney-developer/helia/commit/e567717102464a925f87cb10fc05808a50be960e))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use blockstore interface where possible ([#417](https://github.com/Dhruv-Varshney-developer/helia/issues/417)) ([30c8981](https://github.com/Dhruv-Varshney-developer/helia/commit/30c8981934ffba72d572a7b8b2712ec93b7f4d31))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix API docs link ([#809](https://github.com/Dhruv-Varshney-developer/helia/issues/809)) ([41bcc88](https://github.com/Dhruv-Varshney-developer/helia/commit/41bcc88dbc6f516c4ad4ca3740b83eafdcd5e1c9))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* fix module name typo in readme ([#829](https://github.com/Dhruv-Varshney-developer/helia/issues/829)) ([8df30db](https://github.com/Dhruv-Varshney-developer/helia/commit/8df30dbe6fda3e5e6ebb4928a118ae3464d8c4e8))


### Dependencies

* bump @helia/interface from 1.2.2 to 2.0.0 ([#30](https://github.com/Dhruv-Varshney-developer/helia/issues/30)) ([aa6ebcf](https://github.com/Dhruv-Varshney-developer/helia/commit/aa6ebcf9f58eebf842113985adee4710b009562d))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump multiformats from 11.0.2 to 12.0.1 ([#8](https://github.com/Dhruv-Varshney-developer/helia/issues/8)) ([7a842d3](https://github.com/Dhruv-Varshney-developer/helia/commit/7a842d3cc4cd97e02e5a196aa512cfe36be4c388))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#29](https://github.com/Dhruv-Varshney-developer/helia/issues/29)) ([973bb5b](https://github.com/Dhruv-Varshney-developer/helia/commit/973bb5b6c8db0fedd70e4058f97bc339018a8193))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([77e29bc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e29bcdda33387b8bf15124bc316ef03b434433))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
</details>

<details><summary>dag-json: 5.0.0</summary>

## [5.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/dag-json-v4.1.0...dag-json-v5.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* expose providers option ([#834](https://github.com/Dhruv-Varshney-developer/helia/issues/834)) ([5a911c6](https://github.com/Dhruv-Varshney-developer/helia/commit/5a911c6977ec47d1906ccc69b5f57667f22d9ccf))
* update helia to v3 and multiformats to v13 ([#45](https://github.com/Dhruv-Varshney-developer/helia/issues/45)) ([3c7d9d4](https://github.com/Dhruv-Varshney-developer/helia/commit/3c7d9d4a8e74e1a808c265fbc6ecbdc24f0f3da9))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* @helia/* modules validate CID codec ([#643](https://github.com/Dhruv-Varshney-developer/helia/issues/643)) ([93aa464](https://github.com/Dhruv-Varshney-developer/helia/commit/93aa46459dcff81f0e5eef479f76e39ef5f03736))
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* remove @libp2p/interfaces dep ([#591](https://github.com/Dhruv-Varshney-developer/helia/issues/591)) ([e567717](https://github.com/Dhruv-Varshney-developer/helia/commit/e567717102464a925f87cb10fc05808a50be960e))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use blockstore interface where possible ([#417](https://github.com/Dhruv-Varshney-developer/helia/issues/417)) ([30c8981](https://github.com/Dhruv-Varshney-developer/helia/commit/30c8981934ffba72d572a7b8b2712ec93b7f4d31))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix API docs link ([#809](https://github.com/Dhruv-Varshney-developer/helia/issues/809)) ([41bcc88](https://github.com/Dhruv-Varshney-developer/helia/commit/41bcc88dbc6f516c4ad4ca3740b83eafdcd5e1c9))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))


### Dependencies

* bump @helia/interface from 1.2.2 to 2.0.0 ([#32](https://github.com/Dhruv-Varshney-developer/helia/issues/32)) ([eb836ef](https://github.com/Dhruv-Varshney-developer/helia/commit/eb836ef15f6bc754fbab4fdbe47c76f5492a56d9))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump multiformats from 11.0.2 to 12.0.1 ([#8](https://github.com/Dhruv-Varshney-developer/helia/issues/8)) ([c89b8f1](https://github.com/Dhruv-Varshney-developer/helia/commit/c89b8f12d700f0e23dc574cc32f7726d9c9558de))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#28](https://github.com/Dhruv-Varshney-developer/helia/issues/28)) ([d126e6a](https://github.com/Dhruv-Varshney-developer/helia/commit/d126e6a3c845f25a4910c18fa476304d8534be91))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([9f57d11](https://github.com/Dhruv-Varshney-developer/helia/commit/9f57d11e461a3b1fddbc2a92e225d31eee56613c))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
</details>

<details><summary>dnslink: 1.0.0</summary>

## 1.0.0 (2025-10-08)


###   BREAKING CHANGES

* `ipns.publish` now accepts key name strings rather than private keys Names previously publishing using an user controlled private key, will need to be explicitly published again by first importing the key into the keychain (`await libp2p.keychain.importKey('my-key', key)` and then published with `ipns.publish('my-key', ...)`.

### Features

* add ipns reproviding/republishing ([#764](https://github.com/Dhruv-Varshney-developer/helia/issues/764)) ([008747b](https://github.com/Dhruv-Varshney-developer/helia/commit/008747b59a03682e1b6f648a39635e1b1971e481))
</details>

<details><summary>http: 3.0.0</summary>

## [3.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/http-v2.2.1...http-v3.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add libp2p to @helia/http ([#826](https://github.com/Dhruv-Varshney-developer/helia/issues/826)) ([235e5c4](https://github.com/Dhruv-Varshney-developer/helia/commit/235e5c4093a51bda1e0331f9dd26754f601b582c))
* export default helia config ([#783](https://github.com/Dhruv-Varshney-developer/helia/issues/783)) ([ae67092](https://github.com/Dhruv-Varshney-developer/helia/commit/ae670928a7aeb023d7f3d6aa41bcf9f23a413cdf))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* http blockbroker loads gateways from routing ([#519](https://github.com/Dhruv-Varshney-developer/helia/issues/519)) ([6a62d1c](https://github.com/Dhruv-Varshney-developer/helia/commit/6a62d1c8dcfadead0498d0bb59958837dc204c91))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))


### Dependencies

* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* **dev:** bump sinon from 17.0.2 to 18.0.0 ([#536](https://github.com/Dhruv-Varshney-developer/helia/issues/536)) ([62f77df](https://github.com/Dhruv-Varshney-developer/helia/commit/62f77dfbff94a64e9c248f5be54055c18a6427f7))
* **dev:** bump sinon from 18.0.1 to 19.0.2 ([#634](https://github.com/Dhruv-Varshney-developer/helia/issues/634)) ([23e62e1](https://github.com/Dhruv-Varshney-developer/helia/commit/23e62e16b8962bfe982a1bbb157a144382ca7099))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* The following workspace dependencies were updated
  * dependencies
    * @helia/block-brokers bumped from ^4.2.4 to ^5.0.0
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
    * @helia/routers bumped from ^3.1.3 to ^4.0.0
    * @helia/utils bumped from ^1.4.0 to ^2.0.0
</details>

<details><summary>interface: 6.0.0</summary>

## [6.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/interface-v5.4.0...interface-v6.0.0) (2025-10-08)


###   BREAKING CHANGES

* `ipns.publish` now accepts key name strings rather than private keys Names previously publishing using an user controlled private key, will need to be explicitly published again by first importing the key into the keychain (`await libp2p.keychain.importKey('my-key', key)` and then published with `ipns.publish('my-key', ...)`.
* uses libp2p v3 and updated block/data stores
* the metadata record value field has changed from `any` to `string | number | boolean`
* the `.dagWalkers` property has been removed
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* `helia.pin.add` and `helia.pin.rm` now return `AsyncGenerator<CID>`
* The libp2p API has changed in a couple of places - please see the [upgrade guide](https://github.com/libp2p/js-libp2p/blob/main/doc/migrations/v0.46-v1.0.0.md)
* libp2p has been updated to 0.46.x

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add block session support to @helia/interface ([#398](https://github.com/Dhruv-Varshney-developer/helia/issues/398)) ([5cf216b](https://github.com/Dhruv-Varshney-developer/helia/commit/5cf216baa6806cd82f8fcddd1f024ef6a506f667))
* add cancelReprovide function to routing ([#672](https://github.com/Dhruv-Varshney-developer/helia/issues/672)) ([dc13525](https://github.com/Dhruv-Varshney-developer/helia/commit/dc1352563ab5ed7b204ae702c1e48035d196a470))
* add ipns reproviding/republishing ([#764](https://github.com/Dhruv-Varshney-developer/helia/issues/764)) ([008747b](https://github.com/Dhruv-Varshney-developer/helia/commit/008747b59a03682e1b6f648a39635e1b1971e481))
* add libp2p to @helia/http ([#826](https://github.com/Dhruv-Varshney-developer/helia/issues/826)) ([235e5c4](https://github.com/Dhruv-Varshney-developer/helia/commit/235e5c4093a51bda1e0331f9dd26754f601b582c))
* add method tracing to routing ([#715](https://github.com/Dhruv-Varshney-developer/helia/issues/715)) ([5784ceb](https://github.com/Dhruv-Varshney-developer/helia/commit/5784cebb3225157d6220668d4f58481f046debf2))
* add metrics property to helia interface ([#512](https://github.com/Dhruv-Varshney-developer/helia/issues/512)) ([f7f71bb](https://github.com/Dhruv-Varshney-developer/helia/commit/f7f71bb20ab0b4efbe802be5af1189e76153b826))
* allow updating pin metadata ([#647](https://github.com/Dhruv-Varshney-developer/helia/issues/647)) ([bc64f47](https://github.com/Dhruv-Varshney-developer/helia/commit/bc64f47897691295435568beee61383116b0032b))
* configurable block brokers ([#280](https://github.com/Dhruv-Varshney-developer/helia/issues/280)) ([0749cbf](https://github.com/Dhruv-Varshney-developer/helia/commit/0749cbf99745ea6ab4363f1b5d635634ca0ddcfa))
* expose .dns property on @helia/interface ([#465](https://github.com/Dhruv-Varshney-developer/helia/issues/465)) ([8c9bb7d](https://github.com/Dhruv-Varshney-developer/helia/commit/8c9bb7d224a1b786cba1fba18bffe07001a3b95d))
* expose configured dag walkers and hashers on helia interface ([#381](https://github.com/Dhruv-Varshney-developer/helia/issues/381)) ([843fba4](https://github.com/Dhruv-Varshney-developer/helia/commit/843fba467ebb032907c888da499147a5349ec10e)), closes [#375](https://github.com/Dhruv-Varshney-developer/helia/issues/375)
* GatewayBlockBroker prioritizes & tries all gateways ([#281](https://github.com/Dhruv-Varshney-developer/helia/issues/281)) ([9bad21b](https://github.com/Dhruv-Varshney-developer/helia/commit/9bad21bd59fe6d1ba4a137db5a46bd2ead5238c3))
* iterable pinning ([#231](https://github.com/Dhruv-Varshney-developer/helia/issues/231)) ([c15c774](https://github.com/Dhruv-Varshney-developer/helia/commit/c15c7749294d3d4aea5aef70544d088250336798))
* pass initial providers to session ([#777](https://github.com/Dhruv-Varshney-developer/helia/issues/777)) ([3d77369](https://github.com/Dhruv-Varshney-developer/helia/commit/3d773698389deb70e1a0181eb81fb8b5992857b8))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* @helia/* modules validate CID codec ([#643](https://github.com/Dhruv-Varshney-developer/helia/issues/643)) ([93aa464](https://github.com/Dhruv-Varshney-developer/helia/commit/93aa46459dcff81f0e5eef479f76e39ef5f03736))
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* create @helia/block-brokers package ([#341](https://github.com/Dhruv-Varshney-developer/helia/issues/341)) ([#342](https://github.com/Dhruv-Varshney-developer/helia/issues/342)) ([2979147](https://github.com/Dhruv-Varshney-developer/helia/commit/297914756fa06dc0c28890a2654d1159d16689c2))
* define string metadata type ([#641](https://github.com/Dhruv-Varshney-developer/helia/issues/641)) ([c04dbf5](https://github.com/Dhruv-Varshney-developer/helia/commit/c04dbf5f6bf5ef37ba9fc854c0c3080f37d5c7c3))
* improve sessions implementation ([#495](https://github.com/Dhruv-Varshney-developer/helia/issues/495)) ([9ea934e](https://github.com/Dhruv-Varshney-developer/helia/commit/9ea934ed7208e87c28bc65e9090bdedf66ceeffd))
* replace dag walkers with generic CID extraction from blocks ([#447](https://github.com/Dhruv-Varshney-developer/helia/issues/447)) ([5ff6998](https://github.com/Dhruv-Varshney-developer/helia/commit/5ff6998e6bc8b04e3407bc98c1924c55f632d9b7))
* trustless gateway returned blocks can be limited ([#791](https://github.com/Dhruv-Varshney-developer/helia/issues/791)) ([7a52e95](https://github.com/Dhruv-Varshney-developer/helia/commit/7a52e95165f4a16a1fb2f62cfc6e936cb6f78b69))
* update ipns module to v9 and fix double verification of records ([#396](https://github.com/Dhruv-Varshney-developer/helia/issues/396)) ([f2853f8](https://github.com/Dhruv-Varshney-developer/helia/commit/f2853f8bd5bdcee8ab7a685355b0be47f29620e0))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* update generated docs to include version in module names ([#296](https://github.com/Dhruv-Varshney-developer/helia/issues/296)) ([0776106](https://github.com/Dhruv-Varshney-developer/helia/commit/0776106710d6641ac82b446f7fde6c40d788a0b4))


### Dependencies

* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump multiformats from 12.1.3 to 13.0.0 ([#354](https://github.com/Dhruv-Varshney-developer/helia/issues/354)) ([1d16bf8](https://github.com/Dhruv-Varshney-developer/helia/commit/1d16bf89acd10ac79baf53f0cbc5f92d0e9d8301))
* **dev:** bump aegir from 39.0.13 to 40.0.8 ([#198](https://github.com/Dhruv-Varshney-developer/helia/issues/198)) ([4d75ecf](https://github.com/Dhruv-Varshney-developer/helia/commit/4d75ecffb79e5177da35d3106e42dac7bc63153a))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#273](https://github.com/Dhruv-Varshney-developer/helia/issues/273)) ([9a9f637](https://github.com/Dhruv-Varshney-developer/helia/commit/9a9f63787223eff7eae3b72e59b79b11baa621ea))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* update libp2p to 0.46.x ([#215](https://github.com/Dhruv-Varshney-developer/helia/issues/215)) ([65b68f0](https://github.com/Dhruv-Varshney-developer/helia/commit/65b68f071d04d2f6f0fcf35938b146706b1a3cd0))
* updates to libp2p v1 ([#320](https://github.com/Dhruv-Varshney-developer/helia/issues/320)) ([635d7a2](https://github.com/Dhruv-Varshney-developer/helia/commit/635d7a2938111ccc53f8defbd9b8f8f8ea3e8e6a))


### Refactors

* use functions for block broker creation ([#286](https://github.com/Dhruv-Varshney-developer/helia/issues/286)) ([43932a5](https://github.com/Dhruv-Varshney-developer/helia/commit/43932a54036dafdf1265b034b30b12784fd22d82))
</details>

<details><summary>interop: 9.0.0</summary>

## [9.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/interop-v8.3.0...interop-v9.0.0) (2025-10-08)


###   BREAKING CHANGES

* `ipns.publish` now accepts key name strings rather than private keys Names previously publishing using an user controlled private key, will need to be explicitly published again by first importing the key into the keychain (`await libp2p.keychain.importKey('my-key', key)` and then published with `ipns.publish('my-key', ...)`.
* car.stream has been renamed car.export
* uses libp2p v3 and updated block/data stores
* Fields that would involve DAG traversal have been removed from the output of `fs.stat` - pass the `extended` option to have them returned
* helia now uses libp2p@2.x.x
* requires @helia/interface@4.1.x or later, `resolveDns` has been renamed `resolveDNSLink`
* to support paths in `@helia/ipns`, the return type of `ipns.resolve` is now `{ path: string, cid: CID }` instead of just `CID`
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401))
* `helia.routing` is the default routing used, the `libp2p` routing has been removed as it is redundant
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3, renames `dht` routing to `libp2p`
* uses multiformats v13
* uses multiformats v13 and helia v3
* `helia.pin.add` and `helia.pin.rm` now return `AsyncGenerator<CID>`
* alters the options object passed to the `ipns` factory function
* The libp2p API has changed in a couple of places - please see the [upgrade guide](https://github.com/libp2p/js-libp2p/blob/main/doc/migrations/v0.46-v1.0.0.md)
* the `IPNSRecord` type returned from the `publish` method has changed
* libp2p has been updated to 0.46.x

### Features

* add @helia/bitswap with sessions ([#409](https://github.com/Dhruv-Varshney-developer/helia/issues/409)) ([e582c63](https://github.com/Dhruv-Varshney-developer/helia/commit/e582c63ca296c789312f5fcf5e3e18f267f74c03))
* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add auto-tls support ([#716](https://github.com/Dhruv-Varshney-developer/helia/issues/716)) ([e45e1de](https://github.com/Dhruv-Varshney-developer/helia/commit/e45e1dea40120b993f009f8fbb81a9737742196c))
* add ipns reproviding/republishing ([#764](https://github.com/Dhruv-Varshney-developer/helia/issues/764)) ([008747b](https://github.com/Dhruv-Varshney-developer/helia/commit/008747b59a03682e1b6f648a39635e1b1971e481))
* add libp2p to @helia/http ([#826](https://github.com/Dhruv-Varshney-developer/helia/issues/826)) ([235e5c4](https://github.com/Dhruv-Varshney-developer/helia/commit/235e5c4093a51bda1e0331f9dd26754f601b582c))
* create @helia/verified-fetch ([#392](https://github.com/Dhruv-Varshney-developer/helia/issues/392)) ([f243de2](https://github.com/Dhruv-Varshney-developer/helia/commit/f243de26eda64951c2909121730b6a1b8a689bf6))
* export binary from @helia/interop ([#384](https://github.com/Dhruv-Varshney-developer/helia/issues/384)) ([3477b27](https://github.com/Dhruv-Varshney-developer/helia/commit/3477b2748d44a862e8afeae1a7a2668cdd8a7100))
* expose providers option ([#834](https://github.com/Dhruv-Varshney-developer/helia/issues/834)) ([5a911c6](https://github.com/Dhruv-Varshney-developer/helia/commit/5a911c6977ec47d1906ccc69b5f57667f22d9ccf))
* GatewayBlockBroker prioritizes & tries all gateways ([#281](https://github.com/Dhruv-Varshney-developer/helia/issues/281)) ([9bad21b](https://github.com/Dhruv-Varshney-developer/helia/commit/9bad21bd59fe6d1ba4a137db5a46bd2ead5238c3))
* initial import ([a70f4eb](https://github.com/Dhruv-Varshney-developer/helia/commit/a70f4eb982e377eeeeb6fd4a53f7baf40c09641b))
* iterable pinning ([#231](https://github.com/Dhruv-Varshney-developer/helia/issues/231)) ([c15c774](https://github.com/Dhruv-Varshney-developer/helia/commit/c15c7749294d3d4aea5aef70544d088250336798))
* pass initial providers to session ([#777](https://github.com/Dhruv-Varshney-developer/helia/issues/777)) ([3d77369](https://github.com/Dhruv-Varshney-developer/helia/commit/3d773698389deb70e1a0181eb81fb8b5992857b8))
* rename car stream to export ([#859](https://github.com/Dhruv-Varshney-developer/helia/issues/859)) ([63338b9](https://github.com/Dhruv-Varshney-developer/helia/commit/63338b9c261a1120592e5afb256dfa8c8feed16b))
* require content-type parser to set content-type ([#423](https://github.com/Dhruv-Varshney-developer/helia/issues/423)) ([f58d467](https://github.com/Dhruv-Varshney-developer/helia/commit/f58d467108e0b99d1e15b18a899ef81082ad59a7))
* support DNS over HTTPS and DNS-JSON over HTTPS ([#55](https://github.com/Dhruv-Varshney-developer/helia/issues/55)) ([2ac0e8b](https://github.com/Dhruv-Varshney-developer/helia/commit/2ac0e8b26556b73961e67191c564ac2b18d32b31))
* support paths in @helia/ipns ([#410](https://github.com/Dhruv-Varshney-developer/helia/issues/410)) ([ca8d5eb](https://github.com/Dhruv-Varshney-developer/helia/commit/ca8d5ebdf587574c7fb84517b558226c3479caa9))
* update helia to v3 and multiformats to v13 ([9f7dc0a](https://github.com/Dhruv-Varshney-developer/helia/commit/9f7dc0a0581524531501fc062fefb6ba26d99c02))
* update helia to v3 and multiformats to v13 ([#147](https://github.com/Dhruv-Varshney-developer/helia/issues/147)) ([001247c](https://github.com/Dhruv-Varshney-developer/helia/commit/001247c6fc38ff3d810736371de901e5e1099f26))
* update helia to v3 and multiformats to v13 ([#167](https://github.com/Dhruv-Varshney-developer/helia/issues/167)) ([a0381b9](https://github.com/Dhruv-Varshney-developer/helia/commit/a0381b95051bbf3edfa4f53e0ae2d5f43c1e4382))
* update helia to v3 and multiformats to v13 ([#45](https://github.com/Dhruv-Varshney-developer/helia/issues/45)) ([f078447](https://github.com/Dhruv-Varshney-developer/helia/commit/f078447b6eba4c3d404d62bb930757aa1c0efe74))
* update helia to v3 and multiformats to v13 ([#45](https://github.com/Dhruv-Varshney-developer/helia/issues/45)) ([3c7d9d4](https://github.com/Dhruv-Varshney-developer/helia/commit/3c7d9d4a8e74e1a808c265fbc6ecbdc24f0f3da9))
* update helia to v3 and multiformats to v13 ([#46](https://github.com/Dhruv-Varshney-developer/helia/issues/46)) ([e3dc586](https://github.com/Dhruv-Varshney-developer/helia/commit/e3dc5867ffc4de0dd3b05b56eb1b0ce98d50dcb1))
* update helia to v3 and multiformats to v13 ([#52](https://github.com/Dhruv-Varshney-developer/helia/issues/52)) ([6405c34](https://github.com/Dhruv-Varshney-developer/helia/commit/6405c3487879614dc4dd7308b15c946d644e0488))
* update helia to v3 and multiformats to v13 ([#87](https://github.com/Dhruv-Varshney-developer/helia/issues/87)) ([ae7cbc9](https://github.com/Dhruv-Varshney-developer/helia/commit/ae7cbc9a16a267cb0f6d7cecd381f919430afaea))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))
* use custom DNS resolver in @helia/ipns for DNSLink ([#466](https://github.com/Dhruv-Varshney-developer/helia/issues/466)) ([2c71b6e](https://github.com/Dhruv-Varshney-developer/helia/commit/2c71b6ec8d34dcc722a3914702f67603492c335f)), closes [#369](https://github.com/Dhruv-Varshney-developer/helia/issues/369)
* use helia router for IPNS put/get ([#387](https://github.com/Dhruv-Varshney-developer/helia/issues/387)) ([ce74026](https://github.com/Dhruv-Varshney-developer/helia/commit/ce740268e83f50e6f144b74969a98d54005cd852))


### Bug Fixes

* @helia/* modules validate CID codec ([#643](https://github.com/Dhruv-Varshney-developer/helia/issues/643)) ([93aa464](https://github.com/Dhruv-Varshney-developer/helia/commit/93aa46459dcff81f0e5eef479f76e39ef5f03736))
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* allow contentTypeParser with Helia instance ([#427](https://github.com/Dhruv-Varshney-developer/helia/issues/427)) ([3283a5c](https://github.com/Dhruv-Varshney-developer/helia/commit/3283a5c91ce87894f2b9d7c93126fc74647ba17d))
* convert date to mtime in glob source ([#106](https://github.com/Dhruv-Varshney-developer/helia/issues/106)) ([cd9e903](https://github.com/Dhruv-Varshney-developer/helia/commit/cd9e903c2ccac61372eaa64a61b4a8f3d79f9d4a))
* create @helia/block-brokers package ([#341](https://github.com/Dhruv-Varshney-developer/helia/issues/341)) ([#342](https://github.com/Dhruv-Varshney-developer/helia/issues/342)) ([2979147](https://github.com/Dhruv-Varshney-developer/helia/commit/297914756fa06dc0c28890a2654d1159d16689c2))
* do not depend on external domains in dnslink tests ([#547](https://github.com/Dhruv-Varshney-developer/helia/issues/547)) ([21ef20c](https://github.com/Dhruv-Varshney-developer/helia/commit/21ef20cd05e4d0231d0e3d7d2cfbd21fb75b78a2))
* enable dcutr by default ([#239](https://github.com/Dhruv-Varshney-developer/helia/issues/239)) ([7431f09](https://github.com/Dhruv-Varshney-developer/helia/commit/7431f09aef332dc142a5f7c2c59c9410e4529a92))
* include aegir config in interop and run from install dir ([#389](https://github.com/Dhruv-Varshney-developer/helia/issues/389)) ([a2229bd](https://github.com/Dhruv-Varshney-developer/helia/commit/a2229bd79d5c8b805604bb24bad222462a9ed8cc))
* **kubo:**  Upgrading go-ipfs to kubo ([#251](https://github.com/Dhruv-Varshney-developer/helia/issues/251)) ([963a7a2](https://github.com/Dhruv-Varshney-developer/helia/commit/963a7a21774703a105c865a5b6db670f278eec73))
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401)) ([99c94f4](https://github.com/Dhruv-Varshney-developer/helia/commit/99c94f4b85c4ed826a6195207e3545cbbc87a6d1))
* return simple stats or extended stats ([#760](https://github.com/Dhruv-Varshney-developer/helia/issues/760)) ([325b36f](https://github.com/Dhruv-Varshney-developer/helia/commit/325b36f70624d3dcc25b2723f9e3e2d26e1e5199))
* test for subscribers to ipns pubsub topic ([#584](https://github.com/Dhruv-Varshney-developer/helia/issues/584)) ([c9c644c](https://github.com/Dhruv-Varshney-developer/helia/commit/c9c644c11657ec1411b3f04933fa62501151f732))
* update ipns module to v9 and fix double verification of records ([#396](https://github.com/Dhruv-Varshney-developer/helia/issues/396)) ([f2853f8](https://github.com/Dhruv-Varshney-developer/helia/commit/f2853f8bd5bdcee8ab7a685355b0be47f29620e0))
* update js-libp2p types ([#570](https://github.com/Dhruv-Varshney-developer/helia/issues/570)) ([b4877b5](https://github.com/Dhruv-Varshney-developer/helia/commit/b4877b5b768895684be90a26f4303ae65fc209e7))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* update type import path ([#379](https://github.com/Dhruv-Varshney-developer/helia/issues/379)) ([ece384a](https://github.com/Dhruv-Varshney-developer/helia/commit/ece384aab5e1c95857aa4aa07b86656710d8ca35))
* use bytestream methods to add byte streams ([#758](https://github.com/Dhruv-Varshney-developer/helia/issues/758)) ([70b8fa9](https://github.com/Dhruv-Varshney-developer/helia/commit/70b8fa96cb5fe0fddbb0e1528e6685778af90aa8))
* use hasCode from multiformats ([#635](https://github.com/Dhruv-Varshney-developer/helia/issues/635)) ([f5a03fc](https://github.com/Dhruv-Varshney-developer/helia/commit/f5a03fc28d0cd59841b842306f912c092aeabd5f))
* use unixfs exporter to traverse DAGs ([#455](https://github.com/Dhruv-Varshney-developer/helia/issues/455)) ([6f8c15b](https://github.com/Dhruv-Varshney-developer/helia/commit/6f8c15b769c08bf73e7c62dab79909b5ecfc3c93))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* update generated docs to include version in module names ([#296](https://github.com/Dhruv-Varshney-developer/helia/issues/296)) ([0776106](https://github.com/Dhruv-Varshney-developer/helia/commit/0776106710d6641ac82b446f7fde6c40d788a0b4))


### Dependencies

* bump @chainsafe/libp2p-gossipsub from 11.2.1 to 12.0.0 ([#430](https://github.com/Dhruv-Varshney-developer/helia/issues/430)) ([9b1ddf8](https://github.com/Dhruv-Varshney-developer/helia/commit/9b1ddf85e503ecf5c3ddaa04826bef2f75454b44))
* bump @chainsafe/libp2p-gossipsub from 12.0.0 to 13.0.0 ([#457](https://github.com/Dhruv-Varshney-developer/helia/issues/457)) ([cb35a1b](https://github.com/Dhruv-Varshney-developer/helia/commit/cb35a1ba149628181b3bb48e14d927d2ebc9c23b))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#2](https://github.com/Dhruv-Varshney-developer/helia/issues/2)) ([351fae7](https://github.com/Dhruv-Varshney-developer/helia/commit/351fae7a129e642a6f312c9a61609273dec190bf))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#30](https://github.com/Dhruv-Varshney-developer/helia/issues/30)) ([aa6ebcf](https://github.com/Dhruv-Varshney-developer/helia/commit/aa6ebcf9f58eebf842113985adee4710b009562d))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#32](https://github.com/Dhruv-Varshney-developer/helia/issues/32)) ([68656a8](https://github.com/Dhruv-Varshney-developer/helia/commit/68656a81b7cd1238641a41573915635905e4a6ed))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#32](https://github.com/Dhruv-Varshney-developer/helia/issues/32)) ([eb836ef](https://github.com/Dhruv-Varshney-developer/helia/commit/eb836ef15f6bc754fbab4fdbe47c76f5492a56d9))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#34](https://github.com/Dhruv-Varshney-developer/helia/issues/34)) ([d48f2c5](https://github.com/Dhruv-Varshney-developer/helia/commit/d48f2c58338af0d096a1f855ab85a621fce1cc01))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#39](https://github.com/Dhruv-Varshney-developer/helia/issues/39)) ([7c9bc2e](https://github.com/Dhruv-Varshney-developer/helia/commit/7c9bc2e9f99ccbaec1d8c25c900585deb5f6a327))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#87](https://github.com/Dhruv-Varshney-developer/helia/issues/87)) ([098a305](https://github.com/Dhruv-Varshney-developer/helia/commit/098a305241024ed3903b686892ded8abfca55f5f))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump ipfsd-ctl from 13.0.0 to 14.0.0 ([#505](https://github.com/Dhruv-Varshney-developer/helia/issues/505)) ([97fb1a7](https://github.com/Dhruv-Varshney-developer/helia/commit/97fb1a78a2e585a66861a2d0fdc4eabf8b28bd04))
* bump kubo from 0.25.0 to 0.26.0 ([#400](https://github.com/Dhruv-Varshney-developer/helia/issues/400)) ([a9c55f0](https://github.com/Dhruv-Varshney-developer/helia/commit/a9c55f0e672e439cbcc6b938963ab150997c6e45))
* bump kubo from 0.26.0 to 0.27.0 ([#461](https://github.com/Dhruv-Varshney-developer/helia/issues/461)) ([c69913c](https://github.com/Dhruv-Varshney-developer/helia/commit/c69913c546f2bb74344f804f25a93f23adeb9b49))
* bump kubo from 0.28.0 to 0.29.0 ([#555](https://github.com/Dhruv-Varshney-developer/helia/issues/555)) ([117198f](https://github.com/Dhruv-Varshney-developer/helia/commit/117198f85511bfe339b96b588cd62015ed6e69a4))
* bump kubo from 0.30.0 to 0.31.0 ([#656](https://github.com/Dhruv-Varshney-developer/helia/issues/656)) ([8364296](https://github.com/Dhruv-Varshney-developer/helia/commit/83642961c7c6417e58229226048d69a642edcfff))
* bump kubo from 0.31.0 to 0.32.0 ([#679](https://github.com/Dhruv-Varshney-developer/helia/issues/679)) ([c09fef2](https://github.com/Dhruv-Varshney-developer/helia/commit/c09fef29b749eecf969f9812dea7ab49477582f7))
* bump kubo from 0.34.1 to 0.35.0 in the kubo-deps group ([#806](https://github.com/Dhruv-Varshney-developer/helia/issues/806)) ([50a9766](https://github.com/Dhruv-Varshney-developer/helia/commit/50a9766297d9a55678c4ab785960b9fa9768715b))
* bump multiformats from 11.0.2 to 12.0.1 ([#4](https://github.com/Dhruv-Varshney-developer/helia/issues/4)) ([50bed0f](https://github.com/Dhruv-Varshney-developer/helia/commit/50bed0f32b3c07111de804b0e6471e36d8e66626))
* bump multiformats from 11.0.2 to 12.0.1 ([#57](https://github.com/Dhruv-Varshney-developer/helia/issues/57)) ([6f93e51](https://github.com/Dhruv-Varshney-developer/helia/commit/6f93e51e9b6f603f7c1d396705dc5b190108fe79))
* bump multiformats from 11.0.2 to 12.0.1 ([#8](https://github.com/Dhruv-Varshney-developer/helia/issues/8)) ([c2a2ee3](https://github.com/Dhruv-Varshney-developer/helia/commit/c2a2ee38cc8fa76c8a6d0c92c44023c148148a7e))
* bump multiformats from 11.0.2 to 12.0.1 ([#8](https://github.com/Dhruv-Varshney-developer/helia/issues/8)) ([c89b8f1](https://github.com/Dhruv-Varshney-developer/helia/commit/c89b8f12d700f0e23dc574cc32f7726d9c9558de))
* bump multiformats from 12.1.3 to 13.0.0 ([#354](https://github.com/Dhruv-Varshney-developer/helia/issues/354)) ([1d16bf8](https://github.com/Dhruv-Varshney-developer/helia/commit/1d16bf89acd10ac79baf53f0cbc5f92d0e9d8301))
* bump the kubo-deps group across 7 directories with 1 update ([#734](https://github.com/Dhruv-Varshney-developer/helia/issues/734)) ([f7155d8](https://github.com/Dhruv-Varshney-developer/helia/commit/f7155d8bece43dd91d19060881294f61df9d222c))
* **dev:** bump @libp2p/websockets from 6.0.3 to 7.0.5 ([#35](https://github.com/Dhruv-Varshney-developer/helia/issues/35)) ([de04834](https://github.com/Dhruv-Varshney-developer/helia/commit/de048348666a7961cda517ce26f8aedfa987a3bc))
* **dev:** bump @libp2p/websockets from 6.0.3 to 7.0.5 ([#35](https://github.com/Dhruv-Varshney-developer/helia/issues/35)) ([2836bb8](https://github.com/Dhruv-Varshney-developer/helia/commit/2836bb85b75d32cbe4b0dc7bd3ef85912a26396d))
* **dev:** bump @libp2p/websockets from 6.0.3 to 7.0.5 ([#35](https://github.com/Dhruv-Varshney-developer/helia/issues/35)) ([4354316](https://github.com/Dhruv-Varshney-developer/helia/commit/4354316e6870440bf04ecb14bf323649b4582c05))
* **dev:** bump @libp2p/websockets from 6.0.3 to 7.0.5 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([5f4169e](https://github.com/Dhruv-Varshney-developer/helia/commit/5f4169e9ddb16a7d026db395ad3e9c1a2f764bb7))
* **dev:** bump @multiformats/sha3 from 2.0.17 to 3.0.0 ([#249](https://github.com/Dhruv-Varshney-developer/helia/issues/249)) ([7f2dcf8](https://github.com/Dhruv-Varshney-developer/helia/commit/7f2dcf8b878f80e75b3d0dc5a3c49caeb0430785))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#26](https://github.com/Dhruv-Varshney-developer/helia/issues/26)) ([37b6ba1](https://github.com/Dhruv-Varshney-developer/helia/commit/37b6ba14e085073b966fced3c3777519601d0a81))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#28](https://github.com/Dhruv-Varshney-developer/helia/issues/28)) ([d126e6a](https://github.com/Dhruv-Varshney-developer/helia/commit/d126e6a3c845f25a4910c18fa476304d8534be91))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#29](https://github.com/Dhruv-Varshney-developer/helia/issues/29)) ([973bb5b](https://github.com/Dhruv-Varshney-developer/helia/commit/973bb5b6c8db0fedd70e4058f97bc339018a8193))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#30](https://github.com/Dhruv-Varshney-developer/helia/issues/30)) ([ea26a0b](https://github.com/Dhruv-Varshney-developer/helia/commit/ea26a0bd14137eb1de6ab282cdcecd55578064ab))
* **dev:** bump aegir from 39.0.13 to 40.0.8 ([#198](https://github.com/Dhruv-Varshney-developer/helia/issues/198)) ([4d75ecf](https://github.com/Dhruv-Varshney-developer/helia/commit/4d75ecffb79e5177da35d3106e42dac7bc63153a))
* **dev:** bump aegir from 39.0.13 to 40.0.8 ([#65](https://github.com/Dhruv-Varshney-developer/helia/issues/65)) ([174987b](https://github.com/Dhruv-Varshney-developer/helia/commit/174987b2817cfe99cbabb9835dd6a2d99c1c35a9))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#105](https://github.com/Dhruv-Varshney-developer/helia/issues/105)) ([2421ee2](https://github.com/Dhruv-Varshney-developer/helia/commit/2421ee2b4440446160e1a665bc5ecfc92d2b64de))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#107](https://github.com/Dhruv-Varshney-developer/helia/issues/107)) ([5402d30](https://github.com/Dhruv-Varshney-developer/helia/commit/5402d30de1437052e9e9b955d9be3c2898515447))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#273](https://github.com/Dhruv-Varshney-developer/helia/issues/273)) ([9a9f637](https://github.com/Dhruv-Varshney-developer/helia/commit/9a9f63787223eff7eae3b72e59b79b11baa621ea))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([ca3f05a](https://github.com/Dhruv-Varshney-developer/helia/commit/ca3f05a74316f53b0e44f5edd6e303b6e8463bf2))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([9f57d11](https://github.com/Dhruv-Varshney-developer/helia/commit/9f57d11e461a3b1fddbc2a92e225d31eee56613c))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([77e29bc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e29bcdda33387b8bf15124bc316ef03b434433))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#41](https://github.com/Dhruv-Varshney-developer/helia/issues/41)) ([e8fc99f](https://github.com/Dhruv-Varshney-developer/helia/commit/e8fc99f4e372eaf72c2598f5a7a9942143c6d788))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#22](https://github.com/Dhruv-Varshney-developer/helia/issues/22)) ([c8a2e7f](https://github.com/Dhruv-Varshney-developer/helia/commit/c8a2e7ff11df35b6c7e4e3d336890e5d9f5f51fb))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#24](https://github.com/Dhruv-Varshney-developer/helia/issues/24)) ([cff694f](https://github.com/Dhruv-Varshney-developer/helia/commit/cff694f6bc88b25e71d3243b045c65932bfa9874))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#24](https://github.com/Dhruv-Varshney-developer/helia/issues/24)) ([104a1dd](https://github.com/Dhruv-Varshney-developer/helia/commit/104a1dd17e4e4e01a0b48de06cceceb40ff0025c))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#24](https://github.com/Dhruv-Varshney-developer/helia/issues/24)) ([2c89d9f](https://github.com/Dhruv-Varshney-developer/helia/commit/2c89d9f3b61e9975e98f58535bc708bf4fc3927f))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#81](https://github.com/Dhruv-Varshney-developer/helia/issues/81)) ([15fb863](https://github.com/Dhruv-Varshney-developer/helia/commit/15fb86380bff97b54120009fb20a0dc5bfa4cc92))
* **dev:** bump go-ipfs from 0.21.0 to 0.22.0 ([#228](https://github.com/Dhruv-Varshney-developer/helia/issues/228)) ([2e8e447](https://github.com/Dhruv-Varshney-developer/helia/commit/2e8e447f782745e517e935cd1bb3312db6384a5b))
* **dev:** bump helia from 2.0.1 to 2.0.3 ([#10](https://github.com/Dhruv-Varshney-developer/helia/issues/10)) ([6911470](https://github.com/Dhruv-Varshney-developer/helia/commit/6911470cb43720798fca571669a166eb3689dad2))
* **dev:** bump kubo from 0.22.0 to 0.23.0 ([#278](https://github.com/Dhruv-Varshney-developer/helia/issues/278)) ([51316ba](https://github.com/Dhruv-Varshney-developer/helia/commit/51316baa71ec22b91013a7f98b46f5ad420b984a))
* **dev:** bump kubo from 0.24.0 to 0.25.0 ([#351](https://github.com/Dhruv-Varshney-developer/helia/issues/351)) ([9efe50d](https://github.com/Dhruv-Varshney-developer/helia/commit/9efe50df7f130c062f42b0a391bdb1f1e7e50af8))
* **dev:** bump libp2p from 0.45.9 to 0.46.6 ([#92](https://github.com/Dhruv-Varshney-developer/helia/issues/92)) ([efe02e5](https://github.com/Dhruv-Varshney-developer/helia/commit/efe02e5b38992189edb40cd34d79e76dca4c34a3))
* go-ipfs -&gt; kubo ([#53](https://github.com/Dhruv-Varshney-developer/helia/issues/53)) ([f13daae](https://github.com/Dhruv-Varshney-developer/helia/commit/f13daae3d62579b0b181bc5387c5d7b8e10029a5))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update ipns to v7.x.x ([#106](https://github.com/Dhruv-Varshney-developer/helia/issues/106)) ([83a1d14](https://github.com/Dhruv-Varshney-developer/helia/commit/83a1d147e8ba758efd7d2574ea486218bd1f3df2))
* update kad-dht to 14.0.0 ([#648](https://github.com/Dhruv-Varshney-developer/helia/issues/648)) ([60d8c8a](https://github.com/Dhruv-Varshney-developer/helia/commit/60d8c8a9ff2104302d1c87bcf39258f1da33cd45))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* update libp2p to 0.46.x ([#215](https://github.com/Dhruv-Varshney-developer/helia/issues/215)) ([65b68f0](https://github.com/Dhruv-Varshney-developer/helia/commit/65b68f071d04d2f6f0fcf35938b146706b1a3cd0))
* updates to libp2p v1 ([#320](https://github.com/Dhruv-Varshney-developer/helia/issues/320)) ([635d7a2](https://github.com/Dhruv-Varshney-developer/helia/commit/635d7a2938111ccc53f8defbd9b8f8f8ea3e8e6a))
## [9.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/interop-v8.3.0...interop-v9.0.0) (2025-10-08)


###   BREAKING CHANGES

* `ipns.publish` now accepts key name strings rather than private keys Names previously publishing using an user controlled private key, will need to be explicitly published again by first importing the key into the keychain (`await libp2p.keychain.importKey('my-key', key)` and then published with `ipns.publish('my-key', ...)`.
* car.stream has been renamed car.export
* uses libp2p v3 and updated block/data stores
* Fields that would involve DAG traversal have been removed from the output of `fs.stat` - pass the `extended` option to have them returned
* helia now uses libp2p@2.x.x
* requires @helia/interface@4.1.x or later, `resolveDns` has been renamed `resolveDNSLink`
* to support paths in `@helia/ipns`, the return type of `ipns.resolve` is now `{ path: string, cid: CID }` instead of just `CID`
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401))
* `helia.routing` is the default routing used, the `libp2p` routing has been removed as it is redundant
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3
* uses multiformats v13 and helia v3, renames `dht` routing to `libp2p`
* uses multiformats v13
* uses multiformats v13 and helia v3
* `helia.pin.add` and `helia.pin.rm` now return `AsyncGenerator<CID>`
* alters the options object passed to the `ipns` factory function
* The libp2p API has changed in a couple of places - please see the [upgrade guide](https://github.com/libp2p/js-libp2p/blob/main/doc/migrations/v0.46-v1.0.0.md)
* the `IPNSRecord` type returned from the `publish` method has changed
* libp2p has been updated to 0.46.x

### Features

* add @helia/bitswap with sessions ([#409](https://github.com/Dhruv-Varshney-developer/helia/issues/409)) ([e582c63](https://github.com/Dhruv-Varshney-developer/helia/commit/e582c63ca296c789312f5fcf5e3e18f267f74c03))
* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add auto-tls support ([#716](https://github.com/Dhruv-Varshney-developer/helia/issues/716)) ([e45e1de](https://github.com/Dhruv-Varshney-developer/helia/commit/e45e1dea40120b993f009f8fbb81a9737742196c))
* add ipns reproviding/republishing ([#764](https://github.com/Dhruv-Varshney-developer/helia/issues/764)) ([008747b](https://github.com/Dhruv-Varshney-developer/helia/commit/008747b59a03682e1b6f648a39635e1b1971e481))
* add libp2p to @helia/http ([#826](https://github.com/Dhruv-Varshney-developer/helia/issues/826)) ([235e5c4](https://github.com/Dhruv-Varshney-developer/helia/commit/235e5c4093a51bda1e0331f9dd26754f601b582c))
* create @helia/verified-fetch ([#392](https://github.com/Dhruv-Varshney-developer/helia/issues/392)) ([f243de2](https://github.com/Dhruv-Varshney-developer/helia/commit/f243de26eda64951c2909121730b6a1b8a689bf6))
* export binary from @helia/interop ([#384](https://github.com/Dhruv-Varshney-developer/helia/issues/384)) ([3477b27](https://github.com/Dhruv-Varshney-developer/helia/commit/3477b2748d44a862e8afeae1a7a2668cdd8a7100))
* expose providers option ([#834](https://github.com/Dhruv-Varshney-developer/helia/issues/834)) ([5a911c6](https://github.com/Dhruv-Varshney-developer/helia/commit/5a911c6977ec47d1906ccc69b5f57667f22d9ccf))
* GatewayBlockBroker prioritizes & tries all gateways ([#281](https://github.com/Dhruv-Varshney-developer/helia/issues/281)) ([9bad21b](https://github.com/Dhruv-Varshney-developer/helia/commit/9bad21bd59fe6d1ba4a137db5a46bd2ead5238c3))
* initial import ([a70f4eb](https://github.com/Dhruv-Varshney-developer/helia/commit/a70f4eb982e377eeeeb6fd4a53f7baf40c09641b))
* iterable pinning ([#231](https://github.com/Dhruv-Varshney-developer/helia/issues/231)) ([c15c774](https://github.com/Dhruv-Varshney-developer/helia/commit/c15c7749294d3d4aea5aef70544d088250336798))
* pass initial providers to session ([#777](https://github.com/Dhruv-Varshney-developer/helia/issues/777)) ([3d77369](https://github.com/Dhruv-Varshney-developer/helia/commit/3d773698389deb70e1a0181eb81fb8b5992857b8))
* rename car stream to export ([#859](https://github.com/Dhruv-Varshney-developer/helia/issues/859)) ([63338b9](https://github.com/Dhruv-Varshney-developer/helia/commit/63338b9c261a1120592e5afb256dfa8c8feed16b))
* require content-type parser to set content-type ([#423](https://github.com/Dhruv-Varshney-developer/helia/issues/423)) ([f58d467](https://github.com/Dhruv-Varshney-developer/helia/commit/f58d467108e0b99d1e15b18a899ef81082ad59a7))
* support DNS over HTTPS and DNS-JSON over HTTPS ([#55](https://github.com/Dhruv-Varshney-developer/helia/issues/55)) ([2ac0e8b](https://github.com/Dhruv-Varshney-developer/helia/commit/2ac0e8b26556b73961e67191c564ac2b18d32b31))
* support paths in @helia/ipns ([#410](https://github.com/Dhruv-Varshney-developer/helia/issues/410)) ([ca8d5eb](https://github.com/Dhruv-Varshney-developer/helia/commit/ca8d5ebdf587574c7fb84517b558226c3479caa9))
* update helia to v3 and multiformats to v13 ([9f7dc0a](https://github.com/Dhruv-Varshney-developer/helia/commit/9f7dc0a0581524531501fc062fefb6ba26d99c02))
* update helia to v3 and multiformats to v13 ([#147](https://github.com/Dhruv-Varshney-developer/helia/issues/147)) ([001247c](https://github.com/Dhruv-Varshney-developer/helia/commit/001247c6fc38ff3d810736371de901e5e1099f26))
* update helia to v3 and multiformats to v13 ([#167](https://github.com/Dhruv-Varshney-developer/helia/issues/167)) ([a0381b9](https://github.com/Dhruv-Varshney-developer/helia/commit/a0381b95051bbf3edfa4f53e0ae2d5f43c1e4382))
* update helia to v3 and multiformats to v13 ([#45](https://github.com/Dhruv-Varshney-developer/helia/issues/45)) ([f078447](https://github.com/Dhruv-Varshney-developer/helia/commit/f078447b6eba4c3d404d62bb930757aa1c0efe74))
* update helia to v3 and multiformats to v13 ([#45](https://github.com/Dhruv-Varshney-developer/helia/issues/45)) ([3c7d9d4](https://github.com/Dhruv-Varshney-developer/helia/commit/3c7d9d4a8e74e1a808c265fbc6ecbdc24f0f3da9))
* update helia to v3 and multiformats to v13 ([#46](https://github.com/Dhruv-Varshney-developer/helia/issues/46)) ([e3dc586](https://github.com/Dhruv-Varshney-developer/helia/commit/e3dc5867ffc4de0dd3b05b56eb1b0ce98d50dcb1))
* update helia to v3 and multiformats to v13 ([#52](https://github.com/Dhruv-Varshney-developer/helia/issues/52)) ([6405c34](https://github.com/Dhruv-Varshney-developer/helia/commit/6405c3487879614dc4dd7308b15c946d644e0488))
* update helia to v3 and multiformats to v13 ([#87](https://github.com/Dhruv-Varshney-developer/helia/issues/87)) ([ae7cbc9](https://github.com/Dhruv-Varshney-developer/helia/commit/ae7cbc9a16a267cb0f6d7cecd381f919430afaea))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))
* use custom DNS resolver in @helia/ipns for DNSLink ([#466](https://github.com/Dhruv-Varshney-developer/helia/issues/466)) ([2c71b6e](https://github.com/Dhruv-Varshney-developer/helia/commit/2c71b6ec8d34dcc722a3914702f67603492c335f)), closes [#369](https://github.com/Dhruv-Varshney-developer/helia/issues/369)
* use helia router for IPNS put/get ([#387](https://github.com/Dhruv-Varshney-developer/helia/issues/387)) ([ce74026](https://github.com/Dhruv-Varshney-developer/helia/commit/ce740268e83f50e6f144b74969a98d54005cd852))


### Bug Fixes

* @helia/* modules validate CID codec ([#643](https://github.com/Dhruv-Varshney-developer/helia/issues/643)) ([93aa464](https://github.com/Dhruv-Varshney-developer/helia/commit/93aa46459dcff81f0e5eef479f76e39ef5f03736))
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* allow contentTypeParser with Helia instance ([#427](https://github.com/Dhruv-Varshney-developer/helia/issues/427)) ([3283a5c](https://github.com/Dhruv-Varshney-developer/helia/commit/3283a5c91ce87894f2b9d7c93126fc74647ba17d))
* convert date to mtime in glob source ([#106](https://github.com/Dhruv-Varshney-developer/helia/issues/106)) ([cd9e903](https://github.com/Dhruv-Varshney-developer/helia/commit/cd9e903c2ccac61372eaa64a61b4a8f3d79f9d4a))
* create @helia/block-brokers package ([#341](https://github.com/Dhruv-Varshney-developer/helia/issues/341)) ([#342](https://github.com/Dhruv-Varshney-developer/helia/issues/342)) ([2979147](https://github.com/Dhruv-Varshney-developer/helia/commit/297914756fa06dc0c28890a2654d1159d16689c2))
* do not depend on external domains in dnslink tests ([#547](https://github.com/Dhruv-Varshney-developer/helia/issues/547)) ([21ef20c](https://github.com/Dhruv-Varshney-developer/helia/commit/21ef20cd05e4d0231d0e3d7d2cfbd21fb75b78a2))
* enable dcutr by default ([#239](https://github.com/Dhruv-Varshney-developer/helia/issues/239)) ([7431f09](https://github.com/Dhruv-Varshney-developer/helia/commit/7431f09aef332dc142a5f7c2c59c9410e4529a92))
* include aegir config in interop and run from install dir ([#389](https://github.com/Dhruv-Varshney-developer/helia/issues/389)) ([a2229bd](https://github.com/Dhruv-Varshney-developer/helia/commit/a2229bd79d5c8b805604bb24bad222462a9ed8cc))
* **kubo:**  Upgrading go-ipfs to kubo ([#251](https://github.com/Dhruv-Varshney-developer/helia/issues/251)) ([963a7a2](https://github.com/Dhruv-Varshney-developer/helia/commit/963a7a21774703a105c865a5b6db670f278eec73))
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401)) ([99c94f4](https://github.com/Dhruv-Varshney-developer/helia/commit/99c94f4b85c4ed826a6195207e3545cbbc87a6d1))
* return simple stats or extended stats ([#760](https://github.com/Dhruv-Varshney-developer/helia/issues/760)) ([325b36f](https://github.com/Dhruv-Varshney-developer/helia/commit/325b36f70624d3dcc25b2723f9e3e2d26e1e5199))
* test for subscribers to ipns pubsub topic ([#584](https://github.com/Dhruv-Varshney-developer/helia/issues/584)) ([c9c644c](https://github.com/Dhruv-Varshney-developer/helia/commit/c9c644c11657ec1411b3f04933fa62501151f732))
* update ipns module to v9 and fix double verification of records ([#396](https://github.com/Dhruv-Varshney-developer/helia/issues/396)) ([f2853f8](https://github.com/Dhruv-Varshney-developer/helia/commit/f2853f8bd5bdcee8ab7a685355b0be47f29620e0))
* update js-libp2p types ([#570](https://github.com/Dhruv-Varshney-developer/helia/issues/570)) ([b4877b5](https://github.com/Dhruv-Varshney-developer/helia/commit/b4877b5b768895684be90a26f4303ae65fc209e7))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* update type import path ([#379](https://github.com/Dhruv-Varshney-developer/helia/issues/379)) ([ece384a](https://github.com/Dhruv-Varshney-developer/helia/commit/ece384aab5e1c95857aa4aa07b86656710d8ca35))
* use bytestream methods to add byte streams ([#758](https://github.com/Dhruv-Varshney-developer/helia/issues/758)) ([70b8fa9](https://github.com/Dhruv-Varshney-developer/helia/commit/70b8fa96cb5fe0fddbb0e1528e6685778af90aa8))
* use hasCode from multiformats ([#635](https://github.com/Dhruv-Varshney-developer/helia/issues/635)) ([f5a03fc](https://github.com/Dhruv-Varshney-developer/helia/commit/f5a03fc28d0cd59841b842306f912c092aeabd5f))
* use unixfs exporter to traverse DAGs ([#455](https://github.com/Dhruv-Varshney-developer/helia/issues/455)) ([6f8c15b](https://github.com/Dhruv-Varshney-developer/helia/commit/6f8c15b769c08bf73e7c62dab79909b5ecfc3c93))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* update generated docs to include version in module names ([#296](https://github.com/Dhruv-Varshney-developer/helia/issues/296)) ([0776106](https://github.com/Dhruv-Varshney-developer/helia/commit/0776106710d6641ac82b446f7fde6c40d788a0b4))


### Dependencies

* bump @chainsafe/libp2p-gossipsub from 11.2.1 to 12.0.0 ([#430](https://github.com/Dhruv-Varshney-developer/helia/issues/430)) ([9b1ddf8](https://github.com/Dhruv-Varshney-developer/helia/commit/9b1ddf85e503ecf5c3ddaa04826bef2f75454b44))
* bump @chainsafe/libp2p-gossipsub from 12.0.0 to 13.0.0 ([#457](https://github.com/Dhruv-Varshney-developer/helia/issues/457)) ([cb35a1b](https://github.com/Dhruv-Varshney-developer/helia/commit/cb35a1ba149628181b3bb48e14d927d2ebc9c23b))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#2](https://github.com/Dhruv-Varshney-developer/helia/issues/2)) ([351fae7](https://github.com/Dhruv-Varshney-developer/helia/commit/351fae7a129e642a6f312c9a61609273dec190bf))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#30](https://github.com/Dhruv-Varshney-developer/helia/issues/30)) ([aa6ebcf](https://github.com/Dhruv-Varshney-developer/helia/commit/aa6ebcf9f58eebf842113985adee4710b009562d))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#32](https://github.com/Dhruv-Varshney-developer/helia/issues/32)) ([68656a8](https://github.com/Dhruv-Varshney-developer/helia/commit/68656a81b7cd1238641a41573915635905e4a6ed))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#32](https://github.com/Dhruv-Varshney-developer/helia/issues/32)) ([eb836ef](https://github.com/Dhruv-Varshney-developer/helia/commit/eb836ef15f6bc754fbab4fdbe47c76f5492a56d9))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#34](https://github.com/Dhruv-Varshney-developer/helia/issues/34)) ([d48f2c5](https://github.com/Dhruv-Varshney-developer/helia/commit/d48f2c58338af0d096a1f855ab85a621fce1cc01))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#39](https://github.com/Dhruv-Varshney-developer/helia/issues/39)) ([7c9bc2e](https://github.com/Dhruv-Varshney-developer/helia/commit/7c9bc2e9f99ccbaec1d8c25c900585deb5f6a327))
* bump @helia/interface from 1.2.2 to 2.0.0 ([#87](https://github.com/Dhruv-Varshney-developer/helia/issues/87)) ([098a305](https://github.com/Dhruv-Varshney-developer/helia/commit/098a305241024ed3903b686892ded8abfca55f5f))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump ipfsd-ctl from 13.0.0 to 14.0.0 ([#505](https://github.com/Dhruv-Varshney-developer/helia/issues/505)) ([97fb1a7](https://github.com/Dhruv-Varshney-developer/helia/commit/97fb1a78a2e585a66861a2d0fdc4eabf8b28bd04))
* bump kubo from 0.25.0 to 0.26.0 ([#400](https://github.com/Dhruv-Varshney-developer/helia/issues/400)) ([a9c55f0](https://github.com/Dhruv-Varshney-developer/helia/commit/a9c55f0e672e439cbcc6b938963ab150997c6e45))
* bump kubo from 0.26.0 to 0.27.0 ([#461](https://github.com/Dhruv-Varshney-developer/helia/issues/461)) ([c69913c](https://github.com/Dhruv-Varshney-developer/helia/commit/c69913c546f2bb74344f804f25a93f23adeb9b49))
* bump kubo from 0.28.0 to 0.29.0 ([#555](https://github.com/Dhruv-Varshney-developer/helia/issues/555)) ([117198f](https://github.com/Dhruv-Varshney-developer/helia/commit/117198f85511bfe339b96b588cd62015ed6e69a4))
* bump kubo from 0.30.0 to 0.31.0 ([#656](https://github.com/Dhruv-Varshney-developer/helia/issues/656)) ([8364296](https://github.com/Dhruv-Varshney-developer/helia/commit/83642961c7c6417e58229226048d69a642edcfff))
* bump kubo from 0.31.0 to 0.32.0 ([#679](https://github.com/Dhruv-Varshney-developer/helia/issues/679)) ([c09fef2](https://github.com/Dhruv-Varshney-developer/helia/commit/c09fef29b749eecf969f9812dea7ab49477582f7))
* bump kubo from 0.34.1 to 0.35.0 in the kubo-deps group ([#806](https://github.com/Dhruv-Varshney-developer/helia/issues/806)) ([50a9766](https://github.com/Dhruv-Varshney-developer/helia/commit/50a9766297d9a55678c4ab785960b9fa9768715b))
* bump multiformats from 11.0.2 to 12.0.1 ([#4](https://github.com/Dhruv-Varshney-developer/helia/issues/4)) ([50bed0f](https://github.com/Dhruv-Varshney-developer/helia/commit/50bed0f32b3c07111de804b0e6471e36d8e66626))
* bump multiformats from 11.0.2 to 12.0.1 ([#57](https://github.com/Dhruv-Varshney-developer/helia/issues/57)) ([6f93e51](https://github.com/Dhruv-Varshney-developer/helia/commit/6f93e51e9b6f603f7c1d396705dc5b190108fe79))
* bump multiformats from 11.0.2 to 12.0.1 ([#8](https://github.com/Dhruv-Varshney-developer/helia/issues/8)) ([c2a2ee3](https://github.com/Dhruv-Varshney-developer/helia/commit/c2a2ee38cc8fa76c8a6d0c92c44023c148148a7e))
* bump multiformats from 11.0.2 to 12.0.1 ([#8](https://github.com/Dhruv-Varshney-developer/helia/issues/8)) ([c89b8f1](https://github.com/Dhruv-Varshney-developer/helia/commit/c89b8f12d700f0e23dc574cc32f7726d9c9558de))
* bump multiformats from 12.1.3 to 13.0.0 ([#354](https://github.com/Dhruv-Varshney-developer/helia/issues/354)) ([1d16bf8](https://github.com/Dhruv-Varshney-developer/helia/commit/1d16bf89acd10ac79baf53f0cbc5f92d0e9d8301))
* bump the kubo-deps group across 7 directories with 1 update ([#734](https://github.com/Dhruv-Varshney-developer/helia/issues/734)) ([f7155d8](https://github.com/Dhruv-Varshney-developer/helia/commit/f7155d8bece43dd91d19060881294f61df9d222c))
* **dev:** bump @libp2p/websockets from 6.0.3 to 7.0.5 ([#35](https://github.com/Dhruv-Varshney-developer/helia/issues/35)) ([de04834](https://github.com/Dhruv-Varshney-developer/helia/commit/de048348666a7961cda517ce26f8aedfa987a3bc))
* **dev:** bump @libp2p/websockets from 6.0.3 to 7.0.5 ([#35](https://github.com/Dhruv-Varshney-developer/helia/issues/35)) ([2836bb8](https://github.com/Dhruv-Varshney-developer/helia/commit/2836bb85b75d32cbe4b0dc7bd3ef85912a26396d))
* **dev:** bump @libp2p/websockets from 6.0.3 to 7.0.5 ([#35](https://github.com/Dhruv-Varshney-developer/helia/issues/35)) ([4354316](https://github.com/Dhruv-Varshney-developer/helia/commit/4354316e6870440bf04ecb14bf323649b4582c05))
* **dev:** bump @libp2p/websockets from 6.0.3 to 7.0.5 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([5f4169e](https://github.com/Dhruv-Varshney-developer/helia/commit/5f4169e9ddb16a7d026db395ad3e9c1a2f764bb7))
* **dev:** bump @multiformats/sha3 from 2.0.17 to 3.0.0 ([#249](https://github.com/Dhruv-Varshney-developer/helia/issues/249)) ([7f2dcf8](https://github.com/Dhruv-Varshney-developer/helia/commit/7f2dcf8b878f80e75b3d0dc5a3c49caeb0430785))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#26](https://github.com/Dhruv-Varshney-developer/helia/issues/26)) ([37b6ba1](https://github.com/Dhruv-Varshney-developer/helia/commit/37b6ba14e085073b966fced3c3777519601d0a81))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#28](https://github.com/Dhruv-Varshney-developer/helia/issues/28)) ([d126e6a](https://github.com/Dhruv-Varshney-developer/helia/commit/d126e6a3c845f25a4910c18fa476304d8534be91))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#29](https://github.com/Dhruv-Varshney-developer/helia/issues/29)) ([973bb5b](https://github.com/Dhruv-Varshney-developer/helia/commit/973bb5b6c8db0fedd70e4058f97bc339018a8193))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#30](https://github.com/Dhruv-Varshney-developer/helia/issues/30)) ([ea26a0b](https://github.com/Dhruv-Varshney-developer/helia/commit/ea26a0bd14137eb1de6ab282cdcecd55578064ab))
* **dev:** bump aegir from 39.0.13 to 40.0.8 ([#198](https://github.com/Dhruv-Varshney-developer/helia/issues/198)) ([4d75ecf](https://github.com/Dhruv-Varshney-developer/helia/commit/4d75ecffb79e5177da35d3106e42dac7bc63153a))
* **dev:** bump aegir from 39.0.13 to 40.0.8 ([#65](https://github.com/Dhruv-Varshney-developer/helia/issues/65)) ([174987b](https://github.com/Dhruv-Varshney-developer/helia/commit/174987b2817cfe99cbabb9835dd6a2d99c1c35a9))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#105](https://github.com/Dhruv-Varshney-developer/helia/issues/105)) ([2421ee2](https://github.com/Dhruv-Varshney-developer/helia/commit/2421ee2b4440446160e1a665bc5ecfc92d2b64de))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#107](https://github.com/Dhruv-Varshney-developer/helia/issues/107)) ([5402d30](https://github.com/Dhruv-Varshney-developer/helia/commit/5402d30de1437052e9e9b955d9be3c2898515447))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#273](https://github.com/Dhruv-Varshney-developer/helia/issues/273)) ([9a9f637](https://github.com/Dhruv-Varshney-developer/helia/commit/9a9f63787223eff7eae3b72e59b79b11baa621ea))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([ca3f05a](https://github.com/Dhruv-Varshney-developer/helia/commit/ca3f05a74316f53b0e44f5edd6e303b6e8463bf2))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([9f57d11](https://github.com/Dhruv-Varshney-developer/helia/commit/9f57d11e461a3b1fddbc2a92e225d31eee56613c))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([77e29bc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e29bcdda33387b8bf15124bc316ef03b434433))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#41](https://github.com/Dhruv-Varshney-developer/helia/issues/41)) ([e8fc99f](https://github.com/Dhruv-Varshney-developer/helia/commit/e8fc99f4e372eaf72c2598f5a7a9942143c6d788))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#22](https://github.com/Dhruv-Varshney-developer/helia/issues/22)) ([c8a2e7f](https://github.com/Dhruv-Varshney-developer/helia/commit/c8a2e7ff11df35b6c7e4e3d336890e5d9f5f51fb))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#24](https://github.com/Dhruv-Varshney-developer/helia/issues/24)) ([cff694f](https://github.com/Dhruv-Varshney-developer/helia/commit/cff694f6bc88b25e71d3243b045c65932bfa9874))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#24](https://github.com/Dhruv-Varshney-developer/helia/issues/24)) ([104a1dd](https://github.com/Dhruv-Varshney-developer/helia/commit/104a1dd17e4e4e01a0b48de06cceceb40ff0025c))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#24](https://github.com/Dhruv-Varshney-developer/helia/issues/24)) ([2c89d9f](https://github.com/Dhruv-Varshney-developer/helia/commit/2c89d9f3b61e9975e98f58535bc708bf4fc3927f))
* **dev:** bump go-ipfs from 0.20.0 to 0.22.0 ([#81](https://github.com/Dhruv-Varshney-developer/helia/issues/81)) ([15fb863](https://github.com/Dhruv-Varshney-developer/helia/commit/15fb86380bff97b54120009fb20a0dc5bfa4cc92))
* **dev:** bump go-ipfs from 0.21.0 to 0.22.0 ([#228](https://github.com/Dhruv-Varshney-developer/helia/issues/228)) ([2e8e447](https://github.com/Dhruv-Varshney-developer/helia/commit/2e8e447f782745e517e935cd1bb3312db6384a5b))
* **dev:** bump helia from 2.0.1 to 2.0.3 ([#10](https://github.com/Dhruv-Varshney-developer/helia/issues/10)) ([6911470](https://github.com/Dhruv-Varshney-developer/helia/commit/6911470cb43720798fca571669a166eb3689dad2))
* **dev:** bump kubo from 0.22.0 to 0.23.0 ([#278](https://github.com/Dhruv-Varshney-developer/helia/issues/278)) ([51316ba](https://github.com/Dhruv-Varshney-developer/helia/commit/51316baa71ec22b91013a7f98b46f5ad420b984a))
* **dev:** bump kubo from 0.24.0 to 0.25.0 ([#351](https://github.com/Dhruv-Varshney-developer/helia/issues/351)) ([9efe50d](https://github.com/Dhruv-Varshney-developer/helia/commit/9efe50df7f130c062f42b0a391bdb1f1e7e50af8))
* **dev:** bump libp2p from 0.45.9 to 0.46.6 ([#92](https://github.com/Dhruv-Varshney-developer/helia/issues/92)) ([efe02e5](https://github.com/Dhruv-Varshney-developer/helia/commit/efe02e5b38992189edb40cd34d79e76dca4c34a3))
* go-ipfs -&gt; kubo ([#53](https://github.com/Dhruv-Varshney-developer/helia/issues/53)) ([f13daae](https://github.com/Dhruv-Varshney-developer/helia/commit/f13daae3d62579b0b181bc5387c5d7b8e10029a5))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update ipns to v7.x.x ([#106](https://github.com/Dhruv-Varshney-developer/helia/issues/106)) ([83a1d14](https://github.com/Dhruv-Varshney-developer/helia/commit/83a1d147e8ba758efd7d2574ea486218bd1f3df2))
* update kad-dht to 14.0.0 ([#648](https://github.com/Dhruv-Varshney-developer/helia/issues/648)) ([60d8c8a](https://github.com/Dhruv-Varshney-developer/helia/commit/60d8c8a9ff2104302d1c87bcf39258f1da33cd45))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* update libp2p to 0.46.x ([#215](https://github.com/Dhruv-Varshney-developer/helia/issues/215)) ([65b68f0](https://github.com/Dhruv-Varshney-developer/helia/commit/65b68f071d04d2f6f0fcf35938b146706b1a3cd0))
* updates to libp2p v1 ([#320](https://github.com/Dhruv-Varshney-developer/helia/issues/320)) ([635d7a2](https://github.com/Dhruv-Varshney-developer/helia/commit/635d7a2938111ccc53f8defbd9b8f8f8ea3e8e6a))


### Refactors

* use functions for block broker creation ([#286](https://github.com/Dhruv-Varshney-developer/helia/issues/286)) ([43932a5](https://github.com/Dhruv-Varshney-developer/helia/commit/43932a54036dafdf1265b034b30b12784fd22d82))


### Refactors

* use functions for block broker creation ([#286](https://github.com/Dhruv-Varshney-developer/helia/issues/286)) ([43932a5](https://github.com/Dhruv-Varshney-developer/helia/commit/43932a54036dafdf1265b034b30b12784fd22d82))
</details>

<details><summary>ipns: 9.0.0</summary>

## [9.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/ipns-v8.2.4...ipns-v9.0.0) (2025-10-08)


###   BREAKING CHANGES

* `ipns.publish` now accepts key name strings rather than private keys Names previously publishing using an user controlled private key, will need to be explicitly published again by first importing the key into the keychain (`await libp2p.keychain.importKey('my-key', key)` and then published with `ipns.publish('my-key', ...)`.
* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x
* requires @helia/interface@4.1.x or later, `resolveDns` has been renamed `resolveDNSLink`
* to support paths in `@helia/ipns`, the return type of `ipns.resolve` is now `{ path: string, cid: CID }` instead of just `CID`
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401))
* `helia.routing` is the default routing used, the `libp2p` routing has been removed as it is redundant
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3, renames `dht` routing to `libp2p`
* alters the options object passed to the `ipns` factory function
* the `IPNSRecord` type returned from the `publish` method has changed

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add `record`/`answer` fields to IPNS results ([#471](https://github.com/Dhruv-Varshney-developer/helia/issues/471)) ([b6765fe](https://github.com/Dhruv-Varshney-developer/helia/commit/b6765fe7632231407c4a8506015ac07e30152190))
* add cache control to IPNS ([#473](https://github.com/Dhruv-Varshney-developer/helia/issues/473)) ([b00f682](https://github.com/Dhruv-Varshney-developer/helia/commit/b00f682647d3687e54bd48f8f68ab79d1e4e96cc))
* add ipns reproviding/republishing ([#764](https://github.com/Dhruv-Varshney-developer/helia/issues/764)) ([008747b](https://github.com/Dhruv-Varshney-developer/helia/commit/008747b59a03682e1b6f648a39635e1b1971e481))
* add republish signed ipns records ([#745](https://github.com/Dhruv-Varshney-developer/helia/issues/745)) ([91880b0](https://github.com/Dhruv-Varshney-developer/helia/commit/91880b076fbfa24e5354fb6cda8a556a807f17cc))
* allow passing custom ttl when publishing ipns ([#723](https://github.com/Dhruv-Varshney-developer/helia/issues/723)) ([12df657](https://github.com/Dhruv-Varshney-developer/helia/commit/12df657aa421c86df53bc54becf1d505b1c145ce))
* resolve IPNS records with PeerId and CID keys ([#861](https://github.com/Dhruv-Varshney-developer/helia/issues/861)) ([b81ec52](https://github.com/Dhruv-Varshney-developer/helia/commit/b81ec52026bee611f859c896da7d4234bac486a2)), closes [#801](https://github.com/Dhruv-Varshney-developer/helia/issues/801)
* support DNS over HTTPS and DNS-JSON over HTTPS ([#55](https://github.com/Dhruv-Varshney-developer/helia/issues/55)) ([2ac0e8b](https://github.com/Dhruv-Varshney-developer/helia/commit/2ac0e8b26556b73961e67191c564ac2b18d32b31))
* support paths in @helia/ipns ([#410](https://github.com/Dhruv-Varshney-developer/helia/issues/410)) ([ca8d5eb](https://github.com/Dhruv-Varshney-developer/helia/commit/ca8d5ebdf587574c7fb84517b558226c3479caa9))
* update helia to v3 and multiformats to v13 ([#167](https://github.com/Dhruv-Varshney-developer/helia/issues/167)) ([a0381b9](https://github.com/Dhruv-Varshney-developer/helia/commit/a0381b95051bbf3edfa4f53e0ae2d5f43c1e4382))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))
* use custom DNS resolver in @helia/ipns for DNSLink ([#466](https://github.com/Dhruv-Varshney-developer/helia/issues/466)) ([2c71b6e](https://github.com/Dhruv-Varshney-developer/helia/commit/2c71b6ec8d34dcc722a3914702f67603492c335f)), closes [#369](https://github.com/Dhruv-Varshney-developer/helia/issues/369)
* use helia router for IPNS put/get ([#387](https://github.com/Dhruv-Varshney-developer/helia/issues/387)) ([ce74026](https://github.com/Dhruv-Varshney-developer/helia/commit/ce740268e83f50e6f144b74969a98d54005cd852))


### Bug Fixes

* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* align implicit default ttl with specs ([#749](https://github.com/Dhruv-Varshney-developer/helia/issues/749)) ([375796a](https://github.com/Dhruv-Varshney-developer/helia/commit/375796aaead36111c4d663b061bf0edfe01c62ca))
* export IPNSRoutingEvents ([#407](https://github.com/Dhruv-Varshney-developer/helia/issues/407)) ([44f4e88](https://github.com/Dhruv-Varshney-developer/helia/commit/44f4e88030a21d86b2a8473d3d00efb624cfce8f))
* flaky test to publish an IPNS record  ([#810](https://github.com/Dhruv-Varshney-developer/helia/issues/810)) ([28a7091](https://github.com/Dhruv-Varshney-developer/helia/commit/28a7091260fda1f711b93318084a65ff3d2f3f8a))
* handle /ipns/ prefixed keys in republishRecord ([#763](https://github.com/Dhruv-Varshney-developer/helia/issues/763)) ([e6339ed](https://github.com/Dhruv-Varshney-developer/helia/commit/e6339ed3cf86f7d56d1aa098de5e091b322e654e))
* handle dnslink pointing to CID with peer id (ipns name) ([#722](https://github.com/Dhruv-Varshney-developer/helia/issues/722)) ([2666d64](https://github.com/Dhruv-Varshney-developer/helia/commit/2666d643d8bd90db077095f20edb1924c8594185))
* make @libp2p/interface a dependency ([#159](https://github.com/Dhruv-Varshney-developer/helia/issues/159)) ([546ecf0](https://github.com/Dhruv-Varshney-developer/helia/commit/546ecf023bd619d32e187fa6a55d39fcf12e4bbe)), closes [#158](https://github.com/Dhruv-Varshney-developer/helia/issues/158)
* propagate ipns failures ([#789](https://github.com/Dhruv-Varshney-developer/helia/issues/789)) ([cd1eb58](https://github.com/Dhruv-Varshney-developer/helia/commit/cd1eb588998ddb1eb17894230cde4a68f9455398))
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401)) ([99c94f4](https://github.com/Dhruv-Varshney-developer/helia/commit/99c94f4b85c4ed826a6195207e3545cbbc87a6d1))
* remove is-ipfs from @helia/ipns dependencies ([#421](https://github.com/Dhruv-Varshney-developer/helia/issues/421)) ([3851fe2](https://github.com/Dhruv-Varshney-developer/helia/commit/3851fe2df6af337b7e2cabe694bd3dba17748fce))
* respect the IPNS TTL field ([#482](https://github.com/Dhruv-Varshney-developer/helia/issues/482)) ([1561e4a](https://github.com/Dhruv-Varshney-developer/helia/commit/1561e4a106074b94e421a77b0b8776b065e48bc5))
* update ipns module to v9 and fix double verification of records ([#396](https://github.com/Dhruv-Varshney-developer/helia/issues/396)) ([f2853f8](https://github.com/Dhruv-Varshney-developer/helia/commit/f2853f8bd5bdcee8ab7a685355b0be47f29620e0))
* update libp2p interfaces ([#109](https://github.com/Dhruv-Varshney-developer/helia/issues/109)) ([514b6e1](https://github.com/Dhruv-Varshney-developer/helia/commit/514b6e1e4192f700a6f0e769d52a4ec5dfe757ec))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* fix typo ([#113](https://github.com/Dhruv-Varshney-developer/helia/issues/113)) ([d732db9](https://github.com/Dhruv-Varshney-developer/helia/commit/d732db9f4fea23aa11456d451f02d4f143846ba3))


### Dependencies

* bump @libp2p/logger from 2.1.1 to 3.0.2 ([#87](https://github.com/Dhruv-Varshney-developer/helia/issues/87)) ([b2886b9](https://github.com/Dhruv-Varshney-developer/helia/commit/b2886b9598a66a31c69ee0c3c7e13748614be37e))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump multiformats from 11.0.2 to 12.0.1 ([#57](https://github.com/Dhruv-Varshney-developer/helia/issues/57)) ([6f93e51](https://github.com/Dhruv-Varshney-developer/helia/commit/6f93e51e9b6f603f7c1d396705dc5b190108fe79))
* **dev:** bump aegir from 39.0.13 to 40.0.8 ([#65](https://github.com/Dhruv-Varshney-developer/helia/issues/65)) ([174987b](https://github.com/Dhruv-Varshney-developer/helia/commit/174987b2817cfe99cbabb9835dd6a2d99c1c35a9))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#107](https://github.com/Dhruv-Varshney-developer/helia/issues/107)) ([5402d30](https://github.com/Dhruv-Varshney-developer/helia/commit/5402d30de1437052e9e9b955d9be3c2898515447))
* **dev:** bump libp2p from 0.45.9 to 0.46.6 ([#92](https://github.com/Dhruv-Varshney-developer/helia/issues/92)) ([efe02e5](https://github.com/Dhruv-Varshney-developer/helia/commit/efe02e5b38992189edb40cd34d79e76dca4c34a3))
* **dev:** bump sinon from 15.2.0 to 16.0.0 ([#105](https://github.com/Dhruv-Varshney-developer/helia/issues/105)) ([231ebbd](https://github.com/Dhruv-Varshney-developer/helia/commit/231ebbd4cda2196d7914a81aa1b0d79473c3a325))
* **dev:** bump sinon from 16.1.3 to 17.0.0 ([#108](https://github.com/Dhruv-Varshney-developer/helia/issues/108)) ([530aeff](https://github.com/Dhruv-Varshney-developer/helia/commit/530aeff8af103c9126411cc1b035ee106f113f1f))
* **dev:** bump sinon from 17.0.2 to 18.0.0 ([#536](https://github.com/Dhruv-Varshney-developer/helia/issues/536)) ([62f77df](https://github.com/Dhruv-Varshney-developer/helia/commit/62f77dfbff94a64e9c248f5be54055c18a6427f7))
* **dev:** bump sinon from 18.0.1 to 19.0.2 ([#634](https://github.com/Dhruv-Varshney-developer/helia/issues/634)) ([23e62e1](https://github.com/Dhruv-Varshney-developer/helia/commit/23e62e16b8962bfe982a1bbb157a144382ca7099))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update ipns to v7.x.x ([#106](https://github.com/Dhruv-Varshney-developer/helia/issues/106)) ([83a1d14](https://github.com/Dhruv-Varshney-developer/helia/commit/83a1d147e8ba758efd7d2574ea486218bd1f3df2))
* update kad-dht to 14.0.0 ([#648](https://github.com/Dhruv-Varshney-developer/helia/issues/648)) ([60d8c8a](https://github.com/Dhruv-Varshney-developer/helia/commit/60d8c8a9ff2104302d1c87bcf39258f1da33cd45))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
</details>

<details><summary>json: 5.0.0</summary>

## [5.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/json-v4.0.7...json-v5.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* update helia to v3 and multiformats to v13 ([#46](https://github.com/Dhruv-Varshney-developer/helia/issues/46)) ([e3dc586](https://github.com/Dhruv-Varshney-developer/helia/commit/e3dc5867ffc4de0dd3b05b56eb1b0ce98d50dcb1))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* @helia/* modules validate CID codec ([#643](https://github.com/Dhruv-Varshney-developer/helia/issues/643)) ([93aa464](https://github.com/Dhruv-Varshney-developer/helia/commit/93aa46459dcff81f0e5eef479f76e39ef5f03736))
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* remove @libp2p/interfaces dep ([#591](https://github.com/Dhruv-Varshney-developer/helia/issues/591)) ([e567717](https://github.com/Dhruv-Varshney-developer/helia/commit/e567717102464a925f87cb10fc05808a50be960e))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use blockstore interface where possible ([#417](https://github.com/Dhruv-Varshney-developer/helia/issues/417)) ([30c8981](https://github.com/Dhruv-Varshney-developer/helia/commit/30c8981934ffba72d572a7b8b2712ec93b7f4d31))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))


### Dependencies

* bump @helia/interface from 1.2.2 to 2.0.0 ([#34](https://github.com/Dhruv-Varshney-developer/helia/issues/34)) ([d48f2c5](https://github.com/Dhruv-Varshney-developer/helia/commit/d48f2c58338af0d096a1f855ab85a621fce1cc01))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump multiformats from 11.0.2 to 12.0.1 ([#8](https://github.com/Dhruv-Varshney-developer/helia/issues/8)) ([c2a2ee3](https://github.com/Dhruv-Varshney-developer/helia/commit/c2a2ee38cc8fa76c8a6d0c92c44023c148148a7e))
* **dev:** bump aegir from 39.0.13 to 40.0.11 ([#26](https://github.com/Dhruv-Varshney-developer/helia/issues/26)) ([37b6ba1](https://github.com/Dhruv-Varshney-developer/helia/commit/37b6ba14e085073b966fced3c3777519601d0a81))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#36](https://github.com/Dhruv-Varshney-developer/helia/issues/36)) ([ca3f05a](https://github.com/Dhruv-Varshney-developer/helia/commit/ca3f05a74316f53b0e44f5edd6e303b6e8463bf2))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
</details>

<details><summary>mfs: 6.0.0</summary>

## [6.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/mfs-v5.1.0...mfs-v6.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* Fields that would involve DAG traversal have been removed from the output of `fs.stat` - pass the `extended` option to have them returned
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* expose extended option for ls in mfs and unixfs ([#836](https://github.com/Dhruv-Varshney-developer/helia/issues/836)) ([9f51b17](https://github.com/Dhruv-Varshney-developer/helia/commit/9f51b175c003a8e052231f4b85c1119165b590c6))
* initial import ([a70f4eb](https://github.com/Dhruv-Varshney-developer/helia/commit/a70f4eb982e377eeeeb6fd4a53f7baf40c09641b))
* update helia to v3 and multiformats to v13 ([9f7dc0a](https://github.com/Dhruv-Varshney-developer/helia/commit/9f7dc0a0581524531501fc062fefb6ba26d99c02))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* remove @libp2p/interfaces dep ([#591](https://github.com/Dhruv-Varshney-developer/helia/issues/591)) ([e567717](https://github.com/Dhruv-Varshney-developer/helia/commit/e567717102464a925f87cb10fc05808a50be960e))
* return simple stats or extended stats ([#760](https://github.com/Dhruv-Varshney-developer/helia/issues/760)) ([325b36f](https://github.com/Dhruv-Varshney-developer/helia/commit/325b36f70624d3dcc25b2723f9e3e2d26e1e5199))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use blockstore interface where possible ([#417](https://github.com/Dhruv-Varshney-developer/helia/issues/417)) ([30c8981](https://github.com/Dhruv-Varshney-developer/helia/commit/30c8981934ffba72d572a7b8b2712ec93b7f4d31))
* use bytestream methods to add byte streams ([#758](https://github.com/Dhruv-Varshney-developer/helia/issues/758)) ([70b8fa9](https://github.com/Dhruv-Varshney-developer/helia/commit/70b8fa96cb5fe0fddbb0e1528e6685778af90aa8))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* update docs to use MFS style API ([#4](https://github.com/Dhruv-Varshney-developer/helia/issues/4)) ([88b23b0](https://github.com/Dhruv-Varshney-developer/helia/commit/88b23b0db4ac9da2a9e94291f2db7b10f436ce00))


### Dependencies

* bump @helia/interface from 1.2.2 to 2.0.0 ([#2](https://github.com/Dhruv-Varshney-developer/helia/issues/2)) ([351fae7](https://github.com/Dhruv-Varshney-developer/helia/commit/351fae7a129e642a6f312c9a61609273dec190bf))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* **dev:** bump helia from 2.0.1 to 2.0.3 ([#10](https://github.com/Dhruv-Varshney-developer/helia/issues/10)) ([6911470](https://github.com/Dhruv-Varshney-developer/helia/commit/6911470cb43720798fca571669a166eb3689dad2))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* The following workspace dependencies were updated
  * dependencies
    * @helia/unixfs bumped from ^5.1.0 to ^6.0.0
</details>

<details><summary>routers: 4.0.0</summary>

## [4.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/routers-v3.1.3...routers-v4.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* fix typo in HTTPGatewayRouter class/interface name ([#664](https://github.com/Dhruv-Varshney-developer/helia/issues/664))
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add cancelReprovide function to routing ([#672](https://github.com/Dhruv-Varshney-developer/helia/issues/672)) ([dc13525](https://github.com/Dhruv-Varshney-developer/helia/commit/dc1352563ab5ed7b204ae702c1e48035d196a470))
* add provider shuffle option to HTTPGatewayRouter ([#772](https://github.com/Dhruv-Varshney-developer/helia/issues/772)) ([daaa511](https://github.com/Dhruv-Varshney-developer/helia/commit/daaa511a74583844244e6f51d55a8bc25a9f5f02))
* add static http gateway routing ([#515](https://github.com/Dhruv-Varshney-developer/helia/issues/515)) ([2d070b9](https://github.com/Dhruv-Varshney-developer/helia/commit/2d070b9cfe0e225e4a66be85cceac900516a8a1f))
* enable customising delegated http router ([#654](https://github.com/Dhruv-Varshney-developer/helia/issues/654)) ([693c82d](https://github.com/Dhruv-Varshney-developer/helia/commit/693c82d2117536d89b2e82d9c482ad807af2e1be))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add tls to default delegated routing filters ([#670](https://github.com/Dhruv-Varshney-developer/helia/issues/670)) ([aecac3d](https://github.com/Dhruv-Varshney-developer/helia/commit/aecac3d92cbd22a7331afee8e6f87ef31a9f7d95))
* fix typo in HTTPGatewayRouter class/interface name ([#664](https://github.com/Dhruv-Varshney-developer/helia/issues/664)) ([87aa9b4](https://github.com/Dhruv-Varshney-developer/helia/commit/87aa9b4b21593870296c9a1c8b11c9123bbc5da1))
* http blockbroker loads gateways from routing ([#519](https://github.com/Dhruv-Varshney-developer/helia/issues/519)) ([6a62d1c](https://github.com/Dhruv-Varshney-developer/helia/commit/6a62d1c8dcfadead0498d0bb59958837dc204c91))
* remove delegated routing api client patch ([#632](https://github.com/Dhruv-Varshney-developer/helia/issues/632)) ([9de08ef](https://github.com/Dhruv-Varshney-developer/helia/commit/9de08ef9c1cbdb723f524672f67574bf1dbed937))
* update ipns module to v9 and fix double verification of records ([#396](https://github.com/Dhruv-Varshney-developer/helia/issues/396)) ([f2853f8](https://github.com/Dhruv-Varshney-developer/helia/commit/f2853f8bd5bdcee8ab7a685355b0be47f29620e0))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))


### Dependencies

* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
</details>

<details><summary>strings: 5.0.0</summary>

## [5.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/strings-v4.1.0...strings-v5.0.0) (2025-10-08)


###   BREAKING CHANGES

* CIDs returned from `@helia/strings` will always use the raw codec
* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* expose providers option ([#834](https://github.com/Dhruv-Varshney-developer/helia/issues/834)) ([5a911c6](https://github.com/Dhruv-Varshney-developer/helia/commit/5a911c6977ec47d1906ccc69b5f57667f22d9ccf))
* update helia to v3 and multiformats to v13 ([#87](https://github.com/Dhruv-Varshney-developer/helia/issues/87)) ([ae7cbc9](https://github.com/Dhruv-Varshney-developer/helia/commit/ae7cbc9a16a267cb0f6d7cecd381f919430afaea))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* @helia/* modules validate CID codec ([#643](https://github.com/Dhruv-Varshney-developer/helia/issues/643)) ([93aa464](https://github.com/Dhruv-Varshney-developer/helia/commit/93aa46459dcff81f0e5eef479f76e39ef5f03736))
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* remove @libp2p/interfaces dep ([#591](https://github.com/Dhruv-Varshney-developer/helia/issues/591)) ([e567717](https://github.com/Dhruv-Varshney-developer/helia/commit/e567717102464a925f87cb10fc05808a50be960e))
* remove codec from AddOptions ([#668](https://github.com/Dhruv-Varshney-developer/helia/issues/668)) ([b1261c6](https://github.com/Dhruv-Varshney-developer/helia/commit/b1261c6e2d5961d72558264374ab0aeed37ce304))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use blockstore interface where possible ([#417](https://github.com/Dhruv-Varshney-developer/helia/issues/417)) ([30c8981](https://github.com/Dhruv-Varshney-developer/helia/commit/30c8981934ffba72d572a7b8b2712ec93b7f4d31))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))


### Dependencies

* bump @helia/interface from 1.2.2 to 2.0.0 ([#39](https://github.com/Dhruv-Varshney-developer/helia/issues/39)) ([7c9bc2e](https://github.com/Dhruv-Varshney-developer/helia/commit/7c9bc2e9f99ccbaec1d8c25c900585deb5f6a327))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
</details>

<details><summary>unixfs: 6.0.0</summary>

## [6.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/unixfs-v5.1.0...unixfs-v6.0.0) (2025-10-08)


###   BREAKING CHANGES

* uses libp2p v3 and updated block/data stores
* Fields that would involve DAG traversal have been removed from the output of `fs.stat` - pass the `extended` option to have them returned
* addFile requires the import candidate to have `path` and `content` properties and the returned CID will always resolve to a directory
* helia now uses libp2p@2.x.x
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* uses multiformats v13 and helia v3

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* expose extended option for ls in mfs and unixfs ([#836](https://github.com/Dhruv-Varshney-developer/helia/issues/836)) ([9f51b17](https://github.com/Dhruv-Varshney-developer/helia/commit/9f51b175c003a8e052231f4b85c1119165b590c6))
* expose providers option ([#834](https://github.com/Dhruv-Varshney-developer/helia/issues/834)) ([5a911c6](https://github.com/Dhruv-Varshney-developer/helia/commit/5a911c6977ec47d1906ccc69b5f57667f22d9ccf))
* update helia to v3 and multiformats to v13 ([#147](https://github.com/Dhruv-Varshney-developer/helia/issues/147)) ([001247c](https://github.com/Dhruv-Varshney-developer/helia/commit/001247c6fc38ff3d810736371de901e5e1099f26))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* Add GlobSourceResult to globSource return type in unixfs. ([#475](https://github.com/Dhruv-Varshney-developer/helia/issues/475)) ([9ac5909](https://github.com/Dhruv-Varshney-developer/helia/commit/9ac59098d3e4c8644756a83b185308d7d91626c1))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* convert date to mtime in glob source ([#106](https://github.com/Dhruv-Varshney-developer/helia/issues/106)) ([cd9e903](https://github.com/Dhruv-Varshney-developer/helia/commit/cd9e903c2ccac61372eaa64a61b4a8f3d79f9d4a))
* correct browser override path for glob-source ([#60](https://github.com/Dhruv-Varshney-developer/helia/issues/60)) ([fd0f33b](https://github.com/Dhruv-Varshney-developer/helia/commit/fd0f33b2a66e2840b5a03f27a48240b3c5d2b67e))
* relax unixfs blockstore input type ([#509](https://github.com/Dhruv-Varshney-developer/helia/issues/509)) ([5d62dfb](https://github.com/Dhruv-Varshney-developer/helia/commit/5d62dfb3dd520e6d557b273e446e63b76f57144e))
* require path in addFile call ([#754](https://github.com/Dhruv-Varshney-developer/helia/issues/754)) ([c0bf36e](https://github.com/Dhruv-Varshney-developer/helia/commit/c0bf36eb45ae0551a1c406e5b806d01425abb1f9))
* return simple stats or extended stats ([#760](https://github.com/Dhruv-Varshney-developer/helia/issues/760)) ([325b36f](https://github.com/Dhruv-Varshney-developer/helia/commit/325b36f70624d3dcc25b2723f9e3e2d26e1e5199))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use blockstore interface where possible ([#417](https://github.com/Dhruv-Varshney-developer/helia/issues/417)) ([30c8981](https://github.com/Dhruv-Varshney-developer/helia/commit/30c8981934ffba72d572a7b8b2712ec93b7f4d31))
* use unixfs exporter to traverse DAGs ([#455](https://github.com/Dhruv-Varshney-developer/helia/issues/455)) ([6f8c15b](https://github.com/Dhruv-Varshney-developer/helia/commit/6f8c15b769c08bf73e7c62dab79909b5ecfc3c93))


### Documentation

* add example of adding browser file/dir to unixfs ([#817](https://github.com/Dhruv-Varshney-developer/helia/issues/817)) ([1e9745c](https://github.com/Dhruv-Varshney-developer/helia/commit/1e9745c0671ced6a1f9142555e5074cbd47d88b3))
* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix API docs link ([#809](https://github.com/Dhruv-Varshney-developer/helia/issues/809)) ([41bcc88](https://github.com/Dhruv-Varshney-developer/helia/commit/41bcc88dbc6f516c4ad4ca3740b83eafdcd5e1c9))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* fix typos in example code ([#57](https://github.com/Dhruv-Varshney-developer/helia/issues/57)) ([b7625c3](https://github.com/Dhruv-Varshney-developer/helia/commit/b7625c3426380e63052968b1476e2d689c9213de))


### Dependencies

* bump @helia/interface from 1.2.2 to 2.0.0 ([#87](https://github.com/Dhruv-Varshney-developer/helia/issues/87)) ([098a305](https://github.com/Dhruv-Varshney-developer/helia/commit/098a305241024ed3903b686892ded8abfca55f5f))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#105](https://github.com/Dhruv-Varshney-developer/helia/issues/105)) ([2421ee2](https://github.com/Dhruv-Varshney-developer/helia/commit/2421ee2b4440446160e1a665bc5ecfc92d2b64de))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update it-glob ([#520](https://github.com/Dhruv-Varshney-developer/helia/issues/520)) ([36081e0](https://github.com/Dhruv-Varshney-developer/helia/commit/36081e063972e89c0c7b258aeb220e60bf024249))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
</details>

<details><summary>utils: 2.0.0</summary>

## [2.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/utils-v1.4.0...utils-v2.0.0) (2025-10-08)


###   BREAKING CHANGES

* `ipns.publish` now accepts key name strings rather than private keys Names previously publishing using an user controlled private key, will need to be explicitly published again by first importing the key into the keychain (`await libp2p.keychain.importKey('my-key', key)` and then published with `ipns.publish('my-key', ...)`.
* uses libp2p v3 and updated block/data stores
* the `.dagWalkers` property has been removed
* helia now uses libp2p@2.x.x

### Features

* add block session support to @helia/interface ([#398](https://github.com/Dhruv-Varshney-developer/helia/issues/398)) ([5cf216b](https://github.com/Dhruv-Varshney-developer/helia/commit/5cf216baa6806cd82f8fcddd1f024ef6a506f667))
* add cancelReprovide function to routing ([#672](https://github.com/Dhruv-Varshney-developer/helia/issues/672)) ([dc13525](https://github.com/Dhruv-Varshney-developer/helia/commit/dc1352563ab5ed7b204ae702c1e48035d196a470))
* add ipns reproviding/republishing ([#764](https://github.com/Dhruv-Varshney-developer/helia/issues/764)) ([008747b](https://github.com/Dhruv-Varshney-developer/helia/commit/008747b59a03682e1b6f648a39635e1b1971e481))
* add libp2p to @helia/http ([#826](https://github.com/Dhruv-Varshney-developer/helia/issues/826)) ([235e5c4](https://github.com/Dhruv-Varshney-developer/helia/commit/235e5c4093a51bda1e0331f9dd26754f601b582c))
* add method tracing to routing ([#715](https://github.com/Dhruv-Varshney-developer/helia/issues/715)) ([5784ceb](https://github.com/Dhruv-Varshney-developer/helia/commit/5784cebb3225157d6220668d4f58481f046debf2))
* add metrics property to helia interface ([#512](https://github.com/Dhruv-Varshney-developer/helia/issues/512)) ([f7f71bb](https://github.com/Dhruv-Varshney-developer/helia/commit/f7f71bb20ab0b4efbe802be5af1189e76153b826))
* allow updating pin metadata ([#647](https://github.com/Dhruv-Varshney-developer/helia/issues/647)) ([bc64f47](https://github.com/Dhruv-Varshney-developer/helia/commit/bc64f47897691295435568beee61383116b0032b))
* expose .dns property on @helia/interface ([#465](https://github.com/Dhruv-Varshney-developer/helia/issues/465)) ([8c9bb7d](https://github.com/Dhruv-Varshney-developer/helia/commit/8c9bb7d224a1b786cba1fba18bffe07001a3b95d))
* pass initial providers to session ([#777](https://github.com/Dhruv-Varshney-developer/helia/issues/777)) ([3d77369](https://github.com/Dhruv-Varshney-developer/helia/commit/3d773698389deb70e1a0181eb81fb8b5992857b8))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))


### Bug Fixes

* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add missing log prefix colon for helia:session-storage ([#544](https://github.com/Dhruv-Varshney-developer/helia/issues/544)) ([011fa92](https://github.com/Dhruv-Varshney-developer/helia/commit/011fa92c05bf42fb20666b1df4c86fb47889a07e))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* blockstore operations should throw when passed an aborted signal ([#497](https://github.com/Dhruv-Varshney-developer/helia/issues/497)) ([9a10498](https://github.com/Dhruv-Varshney-developer/helia/commit/9a10498e55b4380191135535f7f607082e9c00c6))
* cancel in-flight block requests when racing brokers ([#490](https://github.com/Dhruv-Varshney-developer/helia/issues/490)) ([395cd9e](https://github.com/Dhruv-Varshney-developer/helia/commit/395cd9e6ac2f829ef47b503cc7a6c77922f484cf))
* check eviction filter for new providers ([#542](https://github.com/Dhruv-Varshney-developer/helia/issues/542)) ([f46700f](https://github.com/Dhruv-Varshney-developer/helia/commit/f46700fd871d5419e75ecfb0b00fb01aedbe84c7)), closes [#501](https://github.com/Dhruv-Varshney-developer/helia/issues/501)
* do not append peer ids to provider multiaddrs ([#516](https://github.com/Dhruv-Varshney-developer/helia/issues/516)) ([e4e67d0](https://github.com/Dhruv-Varshney-developer/helia/commit/e4e67d0cc64593eca8c3eaa67a4e27544a1692ee))
* improve sessions implementation ([#495](https://github.com/Dhruv-Varshney-developer/helia/issues/495)) ([9ea934e](https://github.com/Dhruv-Varshney-developer/helia/commit/9ea934ed7208e87c28bc65e9090bdedf66ceeffd))
* increase default listers on abort signals ([#484](https://github.com/Dhruv-Varshney-developer/helia/issues/484)) ([7cd012a](https://github.com/Dhruv-Varshney-developer/helia/commit/7cd012aa2ba568845d49d63a71806d20f6ac678f))
* log peer id as string not object ([#514](https://github.com/Dhruv-Varshney-developer/helia/issues/514)) ([f6bcbd4](https://github.com/Dhruv-Varshney-developer/helia/commit/f6bcbd4e784a0c7a230f8c5ccb7889850d692af4))
* reject blockstore session get promise when signal fires  ([#776](https://github.com/Dhruv-Varshney-developer/helia/issues/776)) ([d883eaf](https://github.com/Dhruv-Varshney-developer/helia/commit/d883eafbdcd981a0cc7c78cf361bb72324a8cbdc))
* remove redundant filter ([#663](https://github.com/Dhruv-Varshney-developer/helia/issues/663)) ([efc47fa](https://github.com/Dhruv-Varshney-developer/helia/commit/efc47fa081107d31a8985ed72b36a244385b55ca))
* replace dag walkers with generic CID extraction from blocks ([#447](https://github.com/Dhruv-Varshney-developer/helia/issues/447)) ([5ff6998](https://github.com/Dhruv-Varshney-developer/helia/commit/5ff6998e6bc8b04e3407bc98c1924c55f632d9b7))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* type error ([#537](https://github.com/Dhruv-Varshney-developer/helia/issues/537)) ([e6b976a](https://github.com/Dhruv-Varshney-developer/helia/commit/e6b976a4df96b27bf3aa239356d2e991801da28c))
* update deps and fix types ([#572](https://github.com/Dhruv-Varshney-developer/helia/issues/572)) ([f16c9ea](https://github.com/Dhruv-Varshney-developer/helia/commit/f16c9eac32677333313c433eb918b705439c0819))
* update libp2p deps, send user agent with auto-tls ([#736](https://github.com/Dhruv-Varshney-developer/helia/issues/736)) ([c015793](https://github.com/Dhruv-Varshney-developer/helia/commit/c01579393ddd622352d0d0179c67adaf5ccc4c8f))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use hasCode from multiformats ([#635](https://github.com/Dhruv-Varshney-developer/helia/issues/635)) ([f5a03fc](https://github.com/Dhruv-Varshney-developer/helia/commit/f5a03fc28d0cd59841b842306f912c092aeabd5f))
* wrap blockstore in identity blockstore ([#493](https://github.com/Dhruv-Varshney-developer/helia/issues/493)) ([b67ac5f](https://github.com/Dhruv-Varshney-developer/helia/commit/b67ac5f16eca1df5534c985045250bdb334a85cf))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))


### Dependencies

* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* **dev:** bump sinon from 17.0.2 to 18.0.0 ([#536](https://github.com/Dhruv-Varshney-developer/helia/issues/536)) ([62f77df](https://github.com/Dhruv-Varshney-developer/helia/commit/62f77dfbff94a64e9c248f5be54055c18a6427f7))
* **dev:** bump sinon from 18.0.1 to 19.0.2 ([#634](https://github.com/Dhruv-Varshney-developer/helia/issues/634)) ([23e62e1](https://github.com/Dhruv-Varshney-developer/helia/commit/23e62e16b8962bfe982a1bbb157a144382ca7099))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* The following workspace dependencies were updated
  * dependencies
    * @helia/interface bumped from ^5.4.0 to ^6.0.0
</details>

<details><summary>helia: 6.0.0</summary>

## [6.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/helia-v5.5.1...helia-v6.0.0) (2025-10-08)


###   BREAKING CHANGES

* use `Helia` interface instead of `HeliaLibp2p`
* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401))
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* `helia.pin.add` and `helia.pin.rm` now return `AsyncGenerator<CID>`
* The libp2p API has changed in a couple of places - please see the [upgrade guide](https://github.com/libp2p/js-libp2p/blob/main/doc/migrations/v0.46-v1.0.0.md)
* libp2p has been updated to 0.46.x

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add auto-tls support ([#716](https://github.com/Dhruv-Varshney-developer/helia/issues/716)) ([e45e1de](https://github.com/Dhruv-Varshney-developer/helia/commit/e45e1dea40120b993f009f8fbb81a9737742196c))
* add libp2p to @helia/http ([#826](https://github.com/Dhruv-Varshney-developer/helia/issues/826)) ([235e5c4](https://github.com/Dhruv-Varshney-developer/helia/commit/235e5c4093a51bda1e0331f9dd26754f601b582c))
* add metrics property to helia interface ([#512](https://github.com/Dhruv-Varshney-developer/helia/issues/512)) ([f7f71bb](https://github.com/Dhruv-Varshney-developer/helia/commit/f7f71bb20ab0b4efbe802be5af1189e76153b826))
* add WebRTC-Direct listener ([#741](https://github.com/Dhruv-Varshney-developer/helia/issues/741)) ([deb9165](https://github.com/Dhruv-Varshney-developer/helia/commit/deb9165efe92ce9590c400955c073625eb358bb6))
* configurable block brokers ([#280](https://github.com/Dhruv-Varshney-developer/helia/issues/280)) ([0749cbf](https://github.com/Dhruv-Varshney-developer/helia/commit/0749cbf99745ea6ab4363f1b5d635634ca0ddcfa))
* enable filtering in delegated routing client ([#651](https://github.com/Dhruv-Varshney-developer/helia/issues/651)) ([23ebae1](https://github.com/Dhruv-Varshney-developer/helia/commit/23ebae1072fbbda371ee1d68efb5ecd25d6e339e))
* export default helia config ([#783](https://github.com/Dhruv-Varshney-developer/helia/issues/783)) ([ae67092](https://github.com/Dhruv-Varshney-developer/helia/commit/ae670928a7aeb023d7f3d6aa41bcf9f23a413cdf))
* expose .dns property on @helia/interface ([#465](https://github.com/Dhruv-Varshney-developer/helia/issues/465)) ([8c9bb7d](https://github.com/Dhruv-Varshney-developer/helia/commit/8c9bb7d224a1b786cba1fba18bffe07001a3b95d))
* GatewayBlockBroker prioritizes & tries all gateways ([#281](https://github.com/Dhruv-Varshney-developer/helia/issues/281)) ([9bad21b](https://github.com/Dhruv-Varshney-developer/helia/commit/9bad21bd59fe6d1ba4a137db5a46bd2ead5238c3))
* iterable pinning ([#231](https://github.com/Dhruv-Varshney-developer/helia/issues/231)) ([c15c774](https://github.com/Dhruv-Varshney-developer/helia/commit/c15c7749294d3d4aea5aef70544d088250336798))
* re-export types from @helia/interface ([#232](https://github.com/Dhruv-Varshney-developer/helia/issues/232)) ([09c1e47](https://github.com/Dhruv-Varshney-developer/helia/commit/09c1e4787a506d34a00d9ce7852d73471d47db1b))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))
* use trustless-gateway.link by default ([#299](https://github.com/Dhruv-Varshney-developer/helia/issues/299)) ([bf11efa](https://github.com/Dhruv-Varshney-developer/helia/commit/bf11efa4875f3b8f844511d70122983fc46b4f88))


### Bug Fixes

* add a test for reading the peer id from the datastore ([#397](https://github.com/Dhruv-Varshney-developer/helia/issues/397)) ([4836d52](https://github.com/Dhruv-Varshney-developer/helia/commit/4836d52bf721bc0c3e5920ebd0a05186fb19c6c6))
* add dag walker for json codec ([#247](https://github.com/Dhruv-Varshney-developer/helia/issues/247)) ([5c4b570](https://github.com/Dhruv-Varshney-developer/helia/commit/5c4b5709e6b98de5efc9bed388942e367f5874e7)), closes [#246](https://github.com/Dhruv-Varshney-developer/helia/issues/246)
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* add tls to default delegated routing filters ([#670](https://github.com/Dhruv-Varshney-developer/helia/issues/670)) ([aecac3d](https://github.com/Dhruv-Varshney-developer/helia/commit/aecac3d92cbd22a7331afee8e6f87ef31a9f7d95))
* add va1 bootstrapper ([#649](https://github.com/Dhruv-Varshney-developer/helia/issues/649)) ([460853f](https://github.com/Dhruv-Varshney-developer/helia/commit/460853f915661c794e52299529bda41a893f7b5b))
* create @helia/block-brokers package ([#341](https://github.com/Dhruv-Varshney-developer/helia/issues/341)) ([#342](https://github.com/Dhruv-Varshney-developer/helia/issues/342)) ([2979147](https://github.com/Dhruv-Varshney-developer/helia/commit/297914756fa06dc0c28890a2654d1159d16689c2))
* enable dcutr by default ([#239](https://github.com/Dhruv-Varshney-developer/helia/issues/239)) ([7431f09](https://github.com/Dhruv-Varshney-developer/helia/commit/7431f09aef332dc142a5f7c2c59c9410e4529a92))
* export libp2p service return type ([#263](https://github.com/Dhruv-Varshney-developer/helia/issues/263)) ([76769cf](https://github.com/Dhruv-Varshney-developer/helia/commit/76769cf33e06746f998b4f16b52d3e2a6a7a20a8))
* helia init should extend base helia init ([#464](https://github.com/Dhruv-Varshney-developer/helia/issues/464)) ([a64e5de](https://github.com/Dhruv-Varshney-developer/helia/commit/a64e5de937fbbade035657a18e07bcad4de0a53f))
* http blockbroker loads gateways from routing ([#519](https://github.com/Dhruv-Varshney-developer/helia/issues/519)) ([6a62d1c](https://github.com/Dhruv-Varshney-developer/helia/commit/6a62d1c8dcfadead0498d0bb59958837dc204c91))
* ignore libp2p start param in helia factory ([#382](https://github.com/Dhruv-Varshney-developer/helia/issues/382)) ([c8d2fac](https://github.com/Dhruv-Varshney-developer/helia/commit/c8d2fac002ef73fc3eba83914de12d2e73074c64)), closes [#344](https://github.com/Dhruv-Varshney-developer/helia/issues/344)
* listen on ip6 addresses ([#271](https://github.com/Dhruv-Varshney-developer/helia/issues/271)) ([7ef5e79](https://github.com/Dhruv-Varshney-developer/helia/commit/7ef5e79620f043522ff0dacc260af1fe83e5d77e))
* remove delegated routing api client patch ([#632](https://github.com/Dhruv-Varshney-developer/helia/issues/632)) ([9de08ef](https://github.com/Dhruv-Varshney-developer/helia/commit/9de08ef9c1cbdb723f524672f67574bf1dbed937))
* remove deprecated HeliaLibp2p interace ([#862](https://github.com/Dhruv-Varshney-developer/helia/issues/862)) ([061f3cd](https://github.com/Dhruv-Varshney-developer/helia/commit/061f3cdb6d47b2962617da2a3f83857000c58f80))
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401)) ([99c94f4](https://github.com/Dhruv-Varshney-developer/helia/commit/99c94f4b85c4ed826a6195207e3545cbbc87a6d1))
* remove rust bootstrapper ([#523](https://github.com/Dhruv-Varshney-developer/helia/issues/523)) ([fa9bd4b](https://github.com/Dhruv-Varshney-developer/helia/commit/fa9bd4b53702f3ae71b76a46549535b63629d820))
* remove trustless-gateway.link ([#301](https://github.com/Dhruv-Varshney-developer/helia/issues/301)) ([0343725](https://github.com/Dhruv-Varshney-developer/helia/commit/03437255213b14f5931aed91e8555d7fb7f92926))
* remove webtransport from default transports ([#674](https://github.com/Dhruv-Varshney-developer/helia/issues/674)) ([1aa6c8d](https://github.com/Dhruv-Varshney-developer/helia/commit/1aa6c8d93edb779d2e5668081fb847314b2e2c79))
* replace IPNI gateway with delegated routing client ([#297](https://github.com/Dhruv-Varshney-developer/helia/issues/297)) ([57d580d](https://github.com/Dhruv-Varshney-developer/helia/commit/57d580da26c5e28852cc9fe4d0d80adb36699ece))
* respect routers config in helia constructor ([#652](https://github.com/Dhruv-Varshney-developer/helia/issues/652)) ([1b2934b](https://github.com/Dhruv-Varshney-developer/helia/commit/1b2934b313800fdb0c9684fe203f44471769eb17))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* try circuit relay transport first ([#267](https://github.com/Dhruv-Varshney-developer/helia/issues/267)) ([d5e9c3c](https://github.com/Dhruv-Varshney-developer/helia/commit/d5e9c3c45c8dc3e63969105b785f6a836820a1f8))
* update attempt to add helia to identify agent version ([#268](https://github.com/Dhruv-Varshney-developer/helia/issues/268)) ([6dc7d55](https://github.com/Dhruv-Varshney-developer/helia/commit/6dc7d55cd3099785417a7a2c99db755e856bd59a))
* update circuit relay server args ([#561](https://github.com/Dhruv-Varshney-developer/helia/issues/561)) ([3577d3d](https://github.com/Dhruv-Varshney-developer/helia/commit/3577d3d106e255ff0d2a1d47a197f04632b903ec))
* update ipns module to v9 and fix double verification of records ([#396](https://github.com/Dhruv-Varshney-developer/helia/issues/396)) ([f2853f8](https://github.com/Dhruv-Varshney-developer/helia/commit/f2853f8bd5bdcee8ab7a685355b0be47f29620e0))
* update js-libp2p types ([#570](https://github.com/Dhruv-Varshney-developer/helia/issues/570)) ([b4877b5](https://github.com/Dhruv-Varshney-developer/helia/commit/b4877b5b768895684be90a26f4303ae65fc209e7))
* update libp2p deps, send user agent with auto-tls ([#736](https://github.com/Dhruv-Varshney-developer/helia/issues/736)) ([c015793](https://github.com/Dhruv-Varshney-developer/helia/commit/c01579393ddd622352d0d0179c67adaf5ccc4c8f))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use @libp2p/config to load private key from keystore ([#714](https://github.com/Dhruv-Varshney-developer/helia/issues/714)) ([b4f9d4f](https://github.com/Dhruv-Varshney-developer/helia/commit/b4f9d4fc234cc66e9cdf444900e365b1c63b9920))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* update generated docs to include version in module names ([#296](https://github.com/Dhruv-Varshney-developer/helia/issues/296)) ([0776106](https://github.com/Dhruv-Varshney-developer/helia/commit/0776106710d6641ac82b446f7fde6c40d788a0b4))


### Dependencies

* bump @chainsafe/libp2p-noise from 14.1.0 to 15.0.0 ([#393](https://github.com/Dhruv-Varshney-developer/helia/issues/393)) ([4943c5b](https://github.com/Dhruv-Varshney-developer/helia/commit/4943c5b7e8779bc326ee156b1d80152225189343))
* bump @libp2p/identify from 1.0.21 to 2.0.0 ([#528](https://github.com/Dhruv-Varshney-developer/helia/issues/528)) ([9fa2427](https://github.com/Dhruv-Varshney-developer/helia/commit/9fa2427fece28a4b4dc0980ae65480ff002a2bc6))
* bump @libp2p/ipni-content-routing from 1.0.2 to 2.0.0 ([#227](https://github.com/Dhruv-Varshney-developer/helia/issues/227)) ([a33cb3e](https://github.com/Dhruv-Varshney-developer/helia/commit/a33cb3ef2dd21a55b598f206e8d4295935ea2bcc))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump cborg from 2.0.5 to 4.0.1 ([#260](https://github.com/Dhruv-Varshney-developer/helia/issues/260)) ([230b15b](https://github.com/Dhruv-Varshney-developer/helia/commit/230b15b7aa1c5403abdeed81710c7d6d0862f041))
* bump ipns from 6.0.7 to 7.0.1 ([#266](https://github.com/Dhruv-Varshney-developer/helia/issues/266)) ([373a22c](https://github.com/Dhruv-Varshney-developer/helia/commit/373a22c342401f7ad8b85d5f082d66934eddaa70))
* bump multiformats from 12.1.3 to 13.0.0 ([#354](https://github.com/Dhruv-Varshney-developer/helia/issues/354)) ([1d16bf8](https://github.com/Dhruv-Varshney-developer/helia/commit/1d16bf89acd10ac79baf53f0cbc5f92d0e9d8301))
* bump the helia-deps group across 2 directories with 1 update ([#717](https://github.com/Dhruv-Varshney-developer/helia/issues/717)) ([1c8583c](https://github.com/Dhruv-Varshney-developer/helia/commit/1c8583c89bbf47bfbe10636a9e226aabb61e20da))
* bump uint8arrays from 4.0.10 to 5.0.0 ([#339](https://github.com/Dhruv-Varshney-developer/helia/issues/339)) ([299bb09](https://github.com/Dhruv-Varshney-developer/helia/commit/299bb0942bbfae492db938c4ccad4e835bab2dbd))
* **dev:** bump aegir from 39.0.13 to 40.0.8 ([#198](https://github.com/Dhruv-Varshney-developer/helia/issues/198)) ([4d75ecf](https://github.com/Dhruv-Varshney-developer/helia/commit/4d75ecffb79e5177da35d3106e42dac7bc63153a))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#273](https://github.com/Dhruv-Varshney-developer/helia/issues/273)) ([9a9f637](https://github.com/Dhruv-Varshney-developer/helia/commit/9a9f63787223eff7eae3b72e59b79b11baa621ea))
* **dev:** bump sinon from 15.2.0 to 16.0.0 ([#262](https://github.com/Dhruv-Varshney-developer/helia/issues/262)) ([fb3081a](https://github.com/Dhruv-Varshney-developer/helia/commit/fb3081adc3e6cfcb16ff0b11f340848b7568863b))
* **dev:** bump sinon from 16.1.3 to 17.0.0 ([#288](https://github.com/Dhruv-Varshney-developer/helia/issues/288)) ([ecdb46e](https://github.com/Dhruv-Varshney-developer/helia/commit/ecdb46e0d40df86a59e58fcdfb701db6e36d36e6))
* **dev:** bump sinon-ts from 1.0.2 to 2.0.0 ([#298](https://github.com/Dhruv-Varshney-developer/helia/issues/298)) ([dbbee17](https://github.com/Dhruv-Varshney-developer/helia/commit/dbbee17959c0a737f196c468eb06cc055bbc9711))
* update @libp2p/circuit-relay-v2 to 3.x.x ([#661](https://github.com/Dhruv-Varshney-developer/helia/issues/661)) ([0238ed4](https://github.com/Dhruv-Varshney-developer/helia/commit/0238ed47a63a4f51f66010c50659e6f892b212b5))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update kad-dht to 14.0.0 ([#648](https://github.com/Dhruv-Varshney-developer/helia/issues/648)) ([60d8c8a](https://github.com/Dhruv-Varshney-developer/helia/commit/60d8c8a9ff2104302d1c87bcf39258f1da33cd45))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* update libp2p to 0.46.x ([#215](https://github.com/Dhruv-Varshney-developer/helia/issues/215)) ([65b68f0](https://github.com/Dhruv-Varshney-developer/helia/commit/65b68f071d04d2f6f0fcf35938b146706b1a3cd0))
* update sibling dependencies ([07847bb](https://github.com/Dhruv-Varshney-developer/helia/commit/07847bb60b9ebd26497080373e45871abb4b82dd))
* update sibling dependencies ([beb10b5](https://github.com/Dhruv-Varshney-developer/helia/commit/beb10b5590d66d1d5bef9b5e890b888263df2c92))
* update sibling dependencies ([aa249bc](https://github.com/Dhruv-Varshney-developer/helia/commit/aa249bca021ca513c7847331970219e4a36dee97))
* update sibling dependencies ([89df3fe](https://github.com/Dhruv-Varshney-developer/helia/commit/89df3fe803daa3228290bef105ce5d0b769dc3a0))
* update sibling dependencies ([0970da7](https://github.com/Dhruv-Varshney-developer/helia/commit/0970da79e974a4c172e8fdfb7c207d5ba8152a83))
* update sibling dependencies ([5850e51](https://github.com/Dhruv-Varshney-developer/helia/commit/5850e513c486f6d20e23c04936bbf843653cb5e4))
* update sibling dependencies ([2c52da3](https://github.com/Dhruv-Varshney-developer/helia/commit/2c52da3957d56fe4e3ff6f161f9bec814abd5d8c))
* updates to libp2p v1 ([#320](https://github.com/Dhruv-Varshney-developer/helia/issues/320)) ([635d7a2](https://github.com/Dhruv-Varshney-developer/helia/commit/635d7a2938111ccc53f8defbd9b8f8f8ea3e8e6a))
## [6.0.0](https://github.com/Dhruv-Varshney-developer/helia/compare/helia-v5.5.1...helia-v6.0.0) (2025-10-08)


###   BREAKING CHANGES

* use `Helia` interface instead of `HeliaLibp2p`
* uses libp2p v3 and updated block/data stores
* helia now uses libp2p@2.x.x
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401))
* the `libp2p` property has been removed from the `Helia` interface in `@helia/interface` - it is still present on the return type of `createHelia` from the `helia` module
* `helia.pin.add` and `helia.pin.rm` now return `AsyncGenerator<CID>`
* The libp2p API has changed in a couple of places - please see the [upgrade guide](https://github.com/libp2p/js-libp2p/blob/main/doc/migrations/v0.46-v1.0.0.md)
* libp2p has been updated to 0.46.x

### Features

* add @helia/http to monorepo ([#372](https://github.com/Dhruv-Varshney-developer/helia/issues/372)) ([76220cd](https://github.com/Dhruv-Varshney-developer/helia/commit/76220cd5adf45af7fa61fd0a1321de4722b744d6))
* add auto-tls support ([#716](https://github.com/Dhruv-Varshney-developer/helia/issues/716)) ([e45e1de](https://github.com/Dhruv-Varshney-developer/helia/commit/e45e1dea40120b993f009f8fbb81a9737742196c))
* add libp2p to @helia/http ([#826](https://github.com/Dhruv-Varshney-developer/helia/issues/826)) ([235e5c4](https://github.com/Dhruv-Varshney-developer/helia/commit/235e5c4093a51bda1e0331f9dd26754f601b582c))
* add metrics property to helia interface ([#512](https://github.com/Dhruv-Varshney-developer/helia/issues/512)) ([f7f71bb](https://github.com/Dhruv-Varshney-developer/helia/commit/f7f71bb20ab0b4efbe802be5af1189e76153b826))
* add WebRTC-Direct listener ([#741](https://github.com/Dhruv-Varshney-developer/helia/issues/741)) ([deb9165](https://github.com/Dhruv-Varshney-developer/helia/commit/deb9165efe92ce9590c400955c073625eb358bb6))
* configurable block brokers ([#280](https://github.com/Dhruv-Varshney-developer/helia/issues/280)) ([0749cbf](https://github.com/Dhruv-Varshney-developer/helia/commit/0749cbf99745ea6ab4363f1b5d635634ca0ddcfa))
* enable filtering in delegated routing client ([#651](https://github.com/Dhruv-Varshney-developer/helia/issues/651)) ([23ebae1](https://github.com/Dhruv-Varshney-developer/helia/commit/23ebae1072fbbda371ee1d68efb5ecd25d6e339e))
* export default helia config ([#783](https://github.com/Dhruv-Varshney-developer/helia/issues/783)) ([ae67092](https://github.com/Dhruv-Varshney-developer/helia/commit/ae670928a7aeb023d7f3d6aa41bcf9f23a413cdf))
* expose .dns property on @helia/interface ([#465](https://github.com/Dhruv-Varshney-developer/helia/issues/465)) ([8c9bb7d](https://github.com/Dhruv-Varshney-developer/helia/commit/8c9bb7d224a1b786cba1fba18bffe07001a3b95d))
* GatewayBlockBroker prioritizes & tries all gateways ([#281](https://github.com/Dhruv-Varshney-developer/helia/issues/281)) ([9bad21b](https://github.com/Dhruv-Varshney-developer/helia/commit/9bad21bd59fe6d1ba4a137db5a46bd2ead5238c3))
* iterable pinning ([#231](https://github.com/Dhruv-Varshney-developer/helia/issues/231)) ([c15c774](https://github.com/Dhruv-Varshney-developer/helia/commit/c15c7749294d3d4aea5aef70544d088250336798))
* re-export types from @helia/interface ([#232](https://github.com/Dhruv-Varshney-developer/helia/issues/232)) ([09c1e47](https://github.com/Dhruv-Varshney-developer/helia/commit/09c1e4787a506d34a00d9ce7852d73471d47db1b))
* update to libp2p@v3 and latest data/block stores ([#856](https://github.com/Dhruv-Varshney-developer/helia/issues/856)) ([34d3ecd](https://github.com/Dhruv-Varshney-developer/helia/commit/34d3ecd76c8424387c57221000e226f08ccd1d1e))
* use trustless-gateway.link by default ([#299](https://github.com/Dhruv-Varshney-developer/helia/issues/299)) ([bf11efa](https://github.com/Dhruv-Varshney-developer/helia/commit/bf11efa4875f3b8f844511d70122983fc46b4f88))


### Bug Fixes

* add a test for reading the peer id from the datastore ([#397](https://github.com/Dhruv-Varshney-developer/helia/issues/397)) ([4836d52](https://github.com/Dhruv-Varshney-developer/helia/commit/4836d52bf721bc0c3e5920ebd0a05186fb19c6c6))
* add dag walker for json codec ([#247](https://github.com/Dhruv-Varshney-developer/helia/issues/247)) ([5c4b570](https://github.com/Dhruv-Varshney-developer/helia/commit/5c4b5709e6b98de5efc9bed388942e367f5874e7)), closes [#246](https://github.com/Dhruv-Varshney-developer/helia/issues/246)
* add doc-check script and export types used by functions ([#637](https://github.com/Dhruv-Varshney-developer/helia/issues/637)) ([4f14996](https://github.com/Dhruv-Varshney-developer/helia/commit/4f14996a9b976f2b60f4c8fe52a4fd1632420749))
* add sideEffects: false to package.json ([#485](https://github.com/Dhruv-Varshney-developer/helia/issues/485)) ([8c45267](https://github.com/Dhruv-Varshney-developer/helia/commit/8c45267a474ab10b2faadfebdab33cfe446e8c03))
* add tls to default delegated routing filters ([#670](https://github.com/Dhruv-Varshney-developer/helia/issues/670)) ([aecac3d](https://github.com/Dhruv-Varshney-developer/helia/commit/aecac3d92cbd22a7331afee8e6f87ef31a9f7d95))
* add va1 bootstrapper ([#649](https://github.com/Dhruv-Varshney-developer/helia/issues/649)) ([460853f](https://github.com/Dhruv-Varshney-developer/helia/commit/460853f915661c794e52299529bda41a893f7b5b))
* create @helia/block-brokers package ([#341](https://github.com/Dhruv-Varshney-developer/helia/issues/341)) ([#342](https://github.com/Dhruv-Varshney-developer/helia/issues/342)) ([2979147](https://github.com/Dhruv-Varshney-developer/helia/commit/297914756fa06dc0c28890a2654d1159d16689c2))
* enable dcutr by default ([#239](https://github.com/Dhruv-Varshney-developer/helia/issues/239)) ([7431f09](https://github.com/Dhruv-Varshney-developer/helia/commit/7431f09aef332dc142a5f7c2c59c9410e4529a92))
* export libp2p service return type ([#263](https://github.com/Dhruv-Varshney-developer/helia/issues/263)) ([76769cf](https://github.com/Dhruv-Varshney-developer/helia/commit/76769cf33e06746f998b4f16b52d3e2a6a7a20a8))
* helia init should extend base helia init ([#464](https://github.com/Dhruv-Varshney-developer/helia/issues/464)) ([a64e5de](https://github.com/Dhruv-Varshney-developer/helia/commit/a64e5de937fbbade035657a18e07bcad4de0a53f))
* http blockbroker loads gateways from routing ([#519](https://github.com/Dhruv-Varshney-developer/helia/issues/519)) ([6a62d1c](https://github.com/Dhruv-Varshney-developer/helia/commit/6a62d1c8dcfadead0498d0bb59958837dc204c91))
* ignore libp2p start param in helia factory ([#382](https://github.com/Dhruv-Varshney-developer/helia/issues/382)) ([c8d2fac](https://github.com/Dhruv-Varshney-developer/helia/commit/c8d2fac002ef73fc3eba83914de12d2e73074c64)), closes [#344](https://github.com/Dhruv-Varshney-developer/helia/issues/344)
* listen on ip6 addresses ([#271](https://github.com/Dhruv-Varshney-developer/helia/issues/271)) ([7ef5e79](https://github.com/Dhruv-Varshney-developer/helia/commit/7ef5e79620f043522ff0dacc260af1fe83e5d77e))
* remove delegated routing api client patch ([#632](https://github.com/Dhruv-Varshney-developer/helia/issues/632)) ([9de08ef](https://github.com/Dhruv-Varshney-developer/helia/commit/9de08ef9c1cbdb723f524672f67574bf1dbed937))
* remove deprecated HeliaLibp2p interace ([#862](https://github.com/Dhruv-Varshney-developer/helia/issues/862)) ([061f3cd](https://github.com/Dhruv-Varshney-developer/helia/commit/061f3cdb6d47b2962617da2a3f83857000c58f80))
* remove gossipsub from default libp2p services ([#401](https://github.com/Dhruv-Varshney-developer/helia/issues/401)) ([99c94f4](https://github.com/Dhruv-Varshney-developer/helia/commit/99c94f4b85c4ed826a6195207e3545cbbc87a6d1))
* remove rust bootstrapper ([#523](https://github.com/Dhruv-Varshney-developer/helia/issues/523)) ([fa9bd4b](https://github.com/Dhruv-Varshney-developer/helia/commit/fa9bd4b53702f3ae71b76a46549535b63629d820))
* remove trustless-gateway.link ([#301](https://github.com/Dhruv-Varshney-developer/helia/issues/301)) ([0343725](https://github.com/Dhruv-Varshney-developer/helia/commit/03437255213b14f5931aed91e8555d7fb7f92926))
* remove webtransport from default transports ([#674](https://github.com/Dhruv-Varshney-developer/helia/issues/674)) ([1aa6c8d](https://github.com/Dhruv-Varshney-developer/helia/commit/1aa6c8d93edb779d2e5668081fb847314b2e2c79))
* replace IPNI gateway with delegated routing client ([#297](https://github.com/Dhruv-Varshney-developer/helia/issues/297)) ([57d580d](https://github.com/Dhruv-Varshney-developer/helia/commit/57d580da26c5e28852cc9fe4d0d80adb36699ece))
* respect routers config in helia constructor ([#652](https://github.com/Dhruv-Varshney-developer/helia/issues/652)) ([1b2934b](https://github.com/Dhruv-Varshney-developer/helia/commit/1b2934b313800fdb0c9684fe203f44471769eb17))
* support reading identity cids ([#429](https://github.com/Dhruv-Varshney-developer/helia/issues/429)) ([98308f7](https://github.com/Dhruv-Varshney-developer/helia/commit/98308f77488b8196b2d18f78f05ecd2d37456834))
* try circuit relay transport first ([#267](https://github.com/Dhruv-Varshney-developer/helia/issues/267)) ([d5e9c3c](https://github.com/Dhruv-Varshney-developer/helia/commit/d5e9c3c45c8dc3e63969105b785f6a836820a1f8))
* update attempt to add helia to identify agent version ([#268](https://github.com/Dhruv-Varshney-developer/helia/issues/268)) ([6dc7d55](https://github.com/Dhruv-Varshney-developer/helia/commit/6dc7d55cd3099785417a7a2c99db755e856bd59a))
* update circuit relay server args ([#561](https://github.com/Dhruv-Varshney-developer/helia/issues/561)) ([3577d3d](https://github.com/Dhruv-Varshney-developer/helia/commit/3577d3d106e255ff0d2a1d47a197f04632b903ec))
* update ipns module to v9 and fix double verification of records ([#396](https://github.com/Dhruv-Varshney-developer/helia/issues/396)) ([f2853f8](https://github.com/Dhruv-Varshney-developer/helia/commit/f2853f8bd5bdcee8ab7a685355b0be47f29620e0))
* update js-libp2p types ([#570](https://github.com/Dhruv-Varshney-developer/helia/issues/570)) ([b4877b5](https://github.com/Dhruv-Varshney-developer/helia/commit/b4877b5b768895684be90a26f4303ae65fc209e7))
* update libp2p deps, send user agent with auto-tls ([#736](https://github.com/Dhruv-Varshney-developer/helia/issues/736)) ([c015793](https://github.com/Dhruv-Varshney-developer/helia/commit/c01579393ddd622352d0d0179c67adaf5ccc4c8f))
* update project deps and docs ([77e34fc](https://github.com/Dhruv-Varshney-developer/helia/commit/77e34fc115cbfb82585fd954bcf389ecebf655bc))
* update to libp2p@2.x.x ([#630](https://github.com/Dhruv-Varshney-developer/helia/issues/630)) ([ec8bf66](https://github.com/Dhruv-Varshney-developer/helia/commit/ec8bf66dd870b42d6e5ef2b41706102397e0d39a))
* use @libp2p/config to load private key from keystore ([#714](https://github.com/Dhruv-Varshney-developer/helia/issues/714)) ([b4f9d4f](https://github.com/Dhruv-Varshney-developer/helia/commit/b4f9d4fc234cc66e9cdf444900e365b1c63b9920))


### Documentation

* add spell checker to ci ([#743](https://github.com/Dhruv-Varshney-developer/helia/issues/743)) ([45ca6bc](https://github.com/Dhruv-Varshney-developer/helia/commit/45ca6bc70b1644028500101044595fa0e2199b07))
* fix grammar - it's -&gt; its ([#565](https://github.com/Dhruv-Varshney-developer/helia/issues/565)) ([155e24d](https://github.com/Dhruv-Varshney-developer/helia/commit/155e24db8c06c33972895d702a656e0c2996f3d9))
* update generated docs to include version in module names ([#296](https://github.com/Dhruv-Varshney-developer/helia/issues/296)) ([0776106](https://github.com/Dhruv-Varshney-developer/helia/commit/0776106710d6641ac82b446f7fde6c40d788a0b4))


### Dependencies

* bump @chainsafe/libp2p-noise from 14.1.0 to 15.0.0 ([#393](https://github.com/Dhruv-Varshney-developer/helia/issues/393)) ([4943c5b](https://github.com/Dhruv-Varshney-developer/helia/commit/4943c5b7e8779bc326ee156b1d80152225189343))
* bump @libp2p/identify from 1.0.21 to 2.0.0 ([#528](https://github.com/Dhruv-Varshney-developer/helia/issues/528)) ([9fa2427](https://github.com/Dhruv-Varshney-developer/helia/commit/9fa2427fece28a4b4dc0980ae65480ff002a2bc6))
* bump @libp2p/ipni-content-routing from 1.0.2 to 2.0.0 ([#227](https://github.com/Dhruv-Varshney-developer/helia/issues/227)) ([a33cb3e](https://github.com/Dhruv-Varshney-developer/helia/commit/a33cb3ef2dd21a55b598f206e8d4295935ea2bcc))
* bump aegir from 42.2.11 to 43.0.1 ([#552](https://github.com/Dhruv-Varshney-developer/helia/issues/552)) ([74ccc92](https://github.com/Dhruv-Varshney-developer/helia/commit/74ccc92793a6d0bb4bee714d9fe4fa4183aa4ee8))
* bump aegir from 43.0.3 to 44.0.1 ([#569](https://github.com/Dhruv-Varshney-developer/helia/issues/569)) ([6952f05](https://github.com/Dhruv-Varshney-developer/helia/commit/6952f05357844e5aa3dffb2afaf261df06b9b7c1))
* bump aegir from 44.1.4 to 45.0.1 ([#669](https://github.com/Dhruv-Varshney-developer/helia/issues/669)) ([e58e49c](https://github.com/Dhruv-Varshney-developer/helia/commit/e58e49c6aed8ea9d1e9851435a25e33fdbee3781))
* bump cborg from 2.0.5 to 4.0.1 ([#260](https://github.com/Dhruv-Varshney-developer/helia/issues/260)) ([230b15b](https://github.com/Dhruv-Varshney-developer/helia/commit/230b15b7aa1c5403abdeed81710c7d6d0862f041))
* bump ipns from 6.0.7 to 7.0.1 ([#266](https://github.com/Dhruv-Varshney-developer/helia/issues/266)) ([373a22c](https://github.com/Dhruv-Varshney-developer/helia/commit/373a22c342401f7ad8b85d5f082d66934eddaa70))
* bump multiformats from 12.1.3 to 13.0.0 ([#354](https://github.com/Dhruv-Varshney-developer/helia/issues/354)) ([1d16bf8](https://github.com/Dhruv-Varshney-developer/helia/commit/1d16bf89acd10ac79baf53f0cbc5f92d0e9d8301))
* bump the helia-deps group across 2 directories with 1 update ([#717](https://github.com/Dhruv-Varshney-developer/helia/issues/717)) ([1c8583c](https://github.com/Dhruv-Varshney-developer/helia/commit/1c8583c89bbf47bfbe10636a9e226aabb61e20da))
* bump uint8arrays from 4.0.10 to 5.0.0 ([#339](https://github.com/Dhruv-Varshney-developer/helia/issues/339)) ([299bb09](https://github.com/Dhruv-Varshney-developer/helia/commit/299bb0942bbfae492db938c4ccad4e835bab2dbd))
* **dev:** bump aegir from 39.0.13 to 40.0.8 ([#198](https://github.com/Dhruv-Varshney-developer/helia/issues/198)) ([4d75ecf](https://github.com/Dhruv-Varshney-developer/helia/commit/4d75ecffb79e5177da35d3106e42dac7bc63153a))
* **dev:** bump aegir from 40.0.13 to 41.0.0 ([#273](https://github.com/Dhruv-Varshney-developer/helia/issues/273)) ([9a9f637](https://github.com/Dhruv-Varshney-developer/helia/commit/9a9f63787223eff7eae3b72e59b79b11baa621ea))
* **dev:** bump sinon from 15.2.0 to 16.0.0 ([#262](https://github.com/Dhruv-Varshney-developer/helia/issues/262)) ([fb3081a](https://github.com/Dhruv-Varshney-developer/helia/commit/fb3081adc3e6cfcb16ff0b11f340848b7568863b))
* **dev:** bump sinon from 16.1.3 to 17.0.0 ([#288](https://github.com/Dhruv-Varshney-developer/helia/issues/288)) ([ecdb46e](https://github.com/Dhruv-Varshney-developer/helia/commit/ecdb46e0d40df86a59e58fcdfb701db6e36d36e6))
* **dev:** bump sinon-ts from 1.0.2 to 2.0.0 ([#298](https://github.com/Dhruv-Varshney-developer/helia/issues/298)) ([dbbee17](https://github.com/Dhruv-Varshney-developer/helia/commit/dbbee17959c0a737f196c468eb06cc055bbc9711))
* update @libp2p/circuit-relay-v2 to 3.x.x ([#661](https://github.com/Dhruv-Varshney-developer/helia/issues/661)) ([0238ed4](https://github.com/Dhruv-Varshney-developer/helia/commit/0238ed47a63a4f51f66010c50659e6f892b212b5))
* update aegir to 47.x.x ([#804](https://github.com/Dhruv-Varshney-developer/helia/issues/804)) ([60fbbc2](https://github.com/Dhruv-Varshney-developer/helia/commit/60fbbc2eb08e023e2eac02ae0e89ed143d715084))
* update all deps ([#792](https://github.com/Dhruv-Varshney-developer/helia/issues/792)) ([d43efc7](https://github.com/Dhruv-Varshney-developer/helia/commit/d43efc7bdfff34071a8e4e22e01f659fbac0b78e))
* update kad-dht to 14.0.0 ([#648](https://github.com/Dhruv-Varshney-developer/helia/issues/648)) ([60d8c8a](https://github.com/Dhruv-Varshney-developer/helia/commit/60d8c8a9ff2104302d1c87bcf39258f1da33cd45))
* update libp2p patch versions ([917a1bc](https://github.com/Dhruv-Varshney-developer/helia/commit/917a1bceb9e9b56428a15dc3377a963f06affd12))
* update libp2p to 0.46.x ([#215](https://github.com/Dhruv-Varshney-developer/helia/issues/215)) ([65b68f0](https://github.com/Dhruv-Varshney-developer/helia/commit/65b68f071d04d2f6f0fcf35938b146706b1a3cd0))
* update sibling dependencies ([07847bb](https://github.com/Dhruv-Varshney-developer/helia/commit/07847bb60b9ebd26497080373e45871abb4b82dd))
* update sibling dependencies ([beb10b5](https://github.com/Dhruv-Varshney-developer/helia/commit/beb10b5590d66d1d5bef9b5e890b888263df2c92))
* update sibling dependencies ([aa249bc](https://github.com/Dhruv-Varshney-developer/helia/commit/aa249bca021ca513c7847331970219e4a36dee97))
* update sibling dependencies ([89df3fe](https://github.com/Dhruv-Varshney-developer/helia/commit/89df3fe803daa3228290bef105ce5d0b769dc3a0))
* update sibling dependencies ([0970da7](https://github.com/Dhruv-Varshney-developer/helia/commit/0970da79e974a4c172e8fdfb7c207d5ba8152a83))
* update sibling dependencies ([5850e51](https://github.com/Dhruv-Varshney-developer/helia/commit/5850e513c486f6d20e23c04936bbf843653cb5e4))
* update sibling dependencies ([2c52da3](https://github.com/Dhruv-Varshney-developer/helia/commit/2c52da3957d56fe4e3ff6f161f9bec814abd5d8c))
* updates to libp2p v1 ([#320](https://github.com/Dhruv-Varshney-developer/helia/issues/320)) ([635d7a2](https://github.com/Dhruv-Varshney-developer/helia/commit/635d7a2938111ccc53f8defbd9b8f8f8ea3e8e6a))


### Refactors

* use functions for block broker creation ([#286](https://github.com/Dhruv-Varshney-developer/helia/issues/286)) ([43932a5](https://github.com/Dhruv-Varshney-developer/helia/commit/43932a54036dafdf1265b034b30b12784fd22d82))


### Refactors

* use functions for block broker creation ([#286](https://github.com/Dhruv-Varshney-developer/helia/issues/286)) ([43932a5](https://github.com/Dhruv-Varshney-developer/helia/commit/43932a54036dafdf1265b034b30b12784fd22d82))
</details>

---
This PR was generated with [Release Please](https://github.com/googleapis/release-please). See [documentation](https://github.com/googleapis/release-please#release-please).