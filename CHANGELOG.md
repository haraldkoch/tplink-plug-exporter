# Changelog

## [0.7.1](https://github.com/haraldkoch/tplink-plug-exporter/compare/0.7.0...0.7.1) (2026-08-20)


### Miscellaneous Chores

* **mise:** update tool go (1.26.7 ➔ 1.27.0) ([#88](https://github.com/haraldkoch/tplink-plug-exporter/issues/88)) ([1c6a7fe](https://github.com/haraldkoch/tplink-plug-exporter/commit/1c6a7feb64e785aaeaf910831c8fba0dd380b39e))
* **mise:** update tool golangci-lint (2.12.2 ➔ 2.13.0) ([#89](https://github.com/haraldkoch/tplink-plug-exporter/issues/89)) ([18012ed](https://github.com/haraldkoch/tplink-plug-exporter/commit/18012edfd72661022089116c8ec82b9824a3c548))
* **mise:** update tool yq (4.53.4 ➔ 4.53.6) ([#90](https://github.com/haraldkoch/tplink-plug-exporter/issues/90)) ([eeb0669](https://github.com/haraldkoch/tplink-plug-exporter/commit/eeb06697f067499a8559bb8c99722dfcaf81070c))

## [0.7.0](https://github.com/haraldkoch/tplink-plug-exporter/compare/0.6.1...0.7.0) (2026-08-19)


### ⚠ BREAKING CHANGES

* **mise:** Update tool oxfmt (0.63.0 ➔ 0.64.0) ([#83](https://github.com/haraldkoch/tplink-plug-exporter/issues/83))

### Features

* **mise:** Update tool oxfmt (0.63.0 ➔ 0.64.0) ([#83](https://github.com/haraldkoch/tplink-plug-exporter/issues/83)) ([411f24c](https://github.com/haraldkoch/tplink-plug-exporter/commit/411f24c2987e4d888e70c91ace36cb962b148c2c))


### Bug Fixes

* **deps:** update module github.com/sirupsen/logrus (v1.10.0 ➔ v1.10.1) ([#85](https://github.com/haraldkoch/tplink-plug-exporter/issues/85)) ([b1a3e49](https://github.com/haraldkoch/tplink-plug-exporter/commit/b1a3e493f74a170f0db8bff5f8fd4996d2d7bb83))


### Miscellaneous Chores

* **mise:** update tool go (1.26.6 ➔ 1.26.7) ([#86](https://github.com/haraldkoch/tplink-plug-exporter/issues/86)) ([c04e4d7](https://github.com/haraldkoch/tplink-plug-exporter/commit/c04e4d738c5574d39173d9420ac6afe63e3c22a7))
* **mise:** update tool yq (4.53.3 ➔ 4.53.4) ([#84](https://github.com/haraldkoch/tplink-plug-exporter/issues/84)) ([7112b56](https://github.com/haraldkoch/tplink-plug-exporter/commit/7112b5697ce0a8b6dc9e5bc0977093bf7de349d1))

## [0.6.1](https://github.com/haraldkoch/tplink-plug-exporter/compare/0.6.0...0.6.1) (2026-08-16)


### Continuous Integration

* **github-action:** update action jdx/mise-action (v4.2.4 ➔ v4.2.5) ([#81](https://github.com/haraldkoch/tplink-plug-exporter/issues/81)) ([aec8dcd](https://github.com/haraldkoch/tplink-plug-exporter/commit/aec8dcd37f8dc1a137a359021877234c909be2b7))

## [0.6.0](https://github.com/haraldkoch/tplink-plug-exporter/compare/0.5.2...0.6.0) (2026-08-14)


### ⚠ BREAKING CHANGES

* **github-action:** Update action actions/setup-go (v6.5.0 ➔ v7.0.0) ([#63](https://github.com/haraldkoch/tplink-plug-exporter/issues/63))
* **github-action:** Update action actions/checkout (v6.0.3 ➔ v7.0.0) ([#56](https://github.com/haraldkoch/tplink-plug-exporter/issues/56))
* **github-action:** Update actions/create-github-app-token ( v2.2.2 → v3.0.0 ) ([#29](https://github.com/haraldkoch/tplink-plug-exporter/issues/29))
* **github-action:** Update actions/upload-artifact ( v6.0.0 → v7.0.0 ) ([#25](https://github.com/haraldkoch/tplink-plug-exporter/issues/25))
* **github-action:** Update goreleaser/goreleaser-action ( v6 → v7 ) ([#22](https://github.com/haraldkoch/tplink-plug-exporter/issues/22))
* **github-action:** Update renovatebot/github-action ( v44.2.6 → v46.0.0 ) ([#13](https://github.com/haraldkoch/tplink-plug-exporter/issues/13))

### Features

* add deviceId to all metrics, add kasa_metadata ([2437246](https://github.com/haraldkoch/tplink-plug-exporter/commit/24372466450de07cd66c4c0bd79a723627bd9a86))
* allows to bind on localhost or specific IP address ([#11](https://github.com/haraldkoch/tplink-plug-exporter/issues/11)) ([7a47935](https://github.com/haraldkoch/tplink-plug-exporter/commit/7a47935d6931a02b60380d519eddc734759217e1))
* **container:** update alpine ( 3.12.1 → 3.23.3 ) ([#3](https://github.com/haraldkoch/tplink-plug-exporter/issues/3)) ([d09ceb3](https://github.com/haraldkoch/tplink-plug-exporter/commit/d09ceb3c8b3c0d9a1a7f816b9b6c0d503ed67291))
* **container:** update golang ( 1.18 → 1.25 ) ([#4](https://github.com/haraldkoch/tplink-plug-exporter/issues/4)) ([3eb11da](https://github.com/haraldkoch/tplink-plug-exporter/commit/3eb11dad706a164eefa7dfb162bfb8c4b5cabc11))
* **container:** update golang ( 1.25 → 1.26 ) ([#18](https://github.com/haraldkoch/tplink-plug-exporter/issues/18)) ([58dfa83](https://github.com/haraldkoch/tplink-plug-exporter/commit/58dfa838512bb6830080e7515b3e00e7b9f17a35))
* **container:** update image alpine (3.23.4 ➔ 3.24.0) ([#54](https://github.com/haraldkoch/tplink-plug-exporter/issues/54)) ([02590bf](https://github.com/haraldkoch/tplink-plug-exporter/commit/02590bfeda55a34b1f616c9c85fd623290bb1630))
* **deps:** update module github.com/prometheus/client_golang (v1.23.2 ➔ v1.24.0) ([#66](https://github.com/haraldkoch/tplink-plug-exporter/issues/66)) ([ea2a777](https://github.com/haraldkoch/tplink-plug-exporter/commit/ea2a777d853d8086b6041d6dde01d5109ce95adb))
* **deps:** update module github.com/sirupsen/logrus (v1.9.4 ➔ v1.10.0) ([#73](https://github.com/haraldkoch/tplink-plug-exporter/issues/73)) ([36b7d02](https://github.com/haraldkoch/tplink-plug-exporter/commit/36b7d0244bdc90de7661886dd673c17edc28adf6))
* **github-action:** Update actions/create-github-app-token ( v2.2.2 → v3.0.0 ) ([#29](https://github.com/haraldkoch/tplink-plug-exporter/issues/29)) ([4fac20c](https://github.com/haraldkoch/tplink-plug-exporter/commit/4fac20cbd2022bbf2825efef78bbb2138e4c4f44))
* **github-action:** update actions/create-github-app-token ( v3.0.0 → v3.1.0 ) ([#36](https://github.com/haraldkoch/tplink-plug-exporter/issues/36)) ([dbe685f](https://github.com/haraldkoch/tplink-plug-exporter/commit/dbe685fdc806bb25ddd7396595b906aa2b7c0275))
* **github-action:** update actions/create-github-app-token ( v3.1.1 → v3.2.0 ) ([#47](https://github.com/haraldkoch/tplink-plug-exporter/issues/47)) ([74bbad3](https://github.com/haraldkoch/tplink-plug-exporter/commit/74bbad3a0a44263467c298e8a91f949db2654b3e))
* **github-action:** update actions/setup-go ( v6.0.0 → v6.4.0 ) ([#49](https://github.com/haraldkoch/tplink-plug-exporter/issues/49)) ([b63d2b6](https://github.com/haraldkoch/tplink-plug-exporter/commit/b63d2b6e2193fecd6c3289a8999d87fca5b4c8b3))
* **github-action:** Update actions/upload-artifact ( v6.0.0 → v7.0.0 ) ([#25](https://github.com/haraldkoch/tplink-plug-exporter/issues/25)) ([a1d5c03](https://github.com/haraldkoch/tplink-plug-exporter/commit/a1d5c033e46823d117cd95d2537c5c6b9b279bdf))
* **github-action:** update go ( 1.18.10 → 1.25.5 ) ([d6f3d67](https://github.com/haraldkoch/tplink-plug-exporter/commit/d6f3d6758d2dee5d18cbda91b66ab355977f09ac))
* **github-action:** update go ( 1.25.7 → 1.26.0 ) ([#19](https://github.com/haraldkoch/tplink-plug-exporter/issues/19)) ([2783782](https://github.com/haraldkoch/tplink-plug-exporter/commit/2783782d8243b0983fa63cdf75fb699f78e35700))
* **github-action:** Update goreleaser/goreleaser-action ( v6 → v7 ) ([#22](https://github.com/haraldkoch/tplink-plug-exporter/issues/22)) ([d7dd956](https://github.com/haraldkoch/tplink-plug-exporter/commit/d7dd9560d1ee88feead23108d9f483f59b831613))
* **github-action:** update goreleaser/goreleaser-action ( v7.0.0 → v7.2.1 ) ([#50](https://github.com/haraldkoch/tplink-plug-exporter/issues/50)) ([a34c7cc](https://github.com/haraldkoch/tplink-plug-exporter/commit/a34c7ccf7c3eb20537923aee7fa752cc30b0c533))
* **github-action:** Update renovatebot/github-action ( v44.2.6 → v46.0.0 ) ([#13](https://github.com/haraldkoch/tplink-plug-exporter/issues/13)) ([989205c](https://github.com/haraldkoch/tplink-plug-exporter/commit/989205cb16361a3b1a4d155a9896a94bb6f2461f))
* **github-action:** update renovatebot/github-action ( v46.0.2 → v46.1.0 ) ([#20](https://github.com/haraldkoch/tplink-plug-exporter/issues/20)) ([2e71e18](https://github.com/haraldkoch/tplink-plug-exporter/commit/2e71e18ee476c3b64451e0f08f9e08e485b60a28))
* restructure repository with modern layout and workflows ([#75](https://github.com/haraldkoch/tplink-plug-exporter/issues/75)) ([5071b11](https://github.com/haraldkoch/tplink-plug-exporter/commit/5071b1127885c9ed55276c6b0b2ed2f91e94b4b1))
* support powerstrips like HS300 ([dd56d46](https://github.com/haraldkoch/tplink-plug-exporter/commit/dd56d46d8e302eb0145086dbd110b0febaa41286)), closes [#8](https://github.com/haraldkoch/tplink-plug-exporter/issues/8)


### Bug Fixes

* **container:** update alpine ( 3.23.3 → 3.23.4 ) ([#39](https://github.com/haraldkoch/tplink-plug-exporter/issues/39)) ([959f279](https://github.com/haraldkoch/tplink-plug-exporter/commit/959f27977ce9263a9590eec1892ab0fb98d2c865))
* **container:** update image alpine (3.24.0 ➔ 3.24.1) ([#55](https://github.com/haraldkoch/tplink-plug-exporter/issues/55)) ([32f3383](https://github.com/haraldkoch/tplink-plug-exporter/commit/32f33830bb86aefd8d4084b046250ce397861089))
* correctly serving default /metrics path ([79817d0](https://github.com/haraldkoch/tplink-plug-exporter/commit/79817d03e122540f994fafbc190489149ac228b4))
* **deps:** update module github.com/mitchellh/mapstructure to v1.5.0 ([#5](https://github.com/haraldkoch/tplink-plug-exporter/issues/5)) ([ef2cc35](https://github.com/haraldkoch/tplink-plug-exporter/commit/ef2cc350c838ca5a8f20bbfbfe3f70c6650a9d91))
* **deps:** update module github.com/prometheus/client_golang (v1.24.0 ➔ v1.24.1) ([#67](https://github.com/haraldkoch/tplink-plug-exporter/issues/67)) ([5f663d8](https://github.com/haraldkoch/tplink-plug-exporter/commit/5f663d8257b0afdc1575d858bd6bb11e9a97faf1))
* **deps:** update module github.com/prometheus/client_golang to v1.23.2 ([#6](https://github.com/haraldkoch/tplink-plug-exporter/issues/6)) ([3976874](https://github.com/haraldkoch/tplink-plug-exporter/commit/3976874d7bbb5ef3913d355ede8cdfa2e535c829))
* **deps:** update module github.com/sirupsen/logrus to v1.9.4 ([#7](https://github.com/haraldkoch/tplink-plug-exporter/issues/7)) ([1e87064](https://github.com/haraldkoch/tplink-plug-exporter/commit/1e87064666e592fe38bcdd435e98718d30e6bad9))
* **github-action:** update actions/create-github-app-token ( v2.2.1 → v2.2.2 ) ([#28](https://github.com/haraldkoch/tplink-plug-exporter/issues/28)) ([1cf1414](https://github.com/haraldkoch/tplink-plug-exporter/commit/1cf1414a7d6f7bce8bad3c76c1b39590e5cef68b))
* **github-action:** update actions/create-github-app-token ( v3.1.0 → v3.1.1 ) ([#37](https://github.com/haraldkoch/tplink-plug-exporter/issues/37)) ([4d983dd](https://github.com/haraldkoch/tplink-plug-exporter/commit/4d983dd7329439636ce07f1029e9a4a243e0e915))
* **github-action:** update actions/upload-artifact ( v7.0.0 → v7.0.1 ) ([#35](https://github.com/haraldkoch/tplink-plug-exporter/issues/35)) ([ed2c201](https://github.com/haraldkoch/tplink-plug-exporter/commit/ed2c20151bbcf51226600d106a7b91f9d616f85d))
* **github-action:** update renovatebot/github-action ( v44.2.5 → v44.2.6 ) ([#12](https://github.com/haraldkoch/tplink-plug-exporter/issues/12)) ([9221004](https://github.com/haraldkoch/tplink-plug-exporter/commit/922100443af742d3d0f1cf69ad4cc39a6a3ca422))
* **github-action:** update renovatebot/github-action ( v46.0.0 → v46.0.1 ) ([#16](https://github.com/haraldkoch/tplink-plug-exporter/issues/16)) ([f227e7b](https://github.com/haraldkoch/tplink-plug-exporter/commit/f227e7b210579eb5a3be5e912c0580c2e7cc064d))
* **github-action:** update renovatebot/github-action ( v46.0.1 → v46.0.2 ) ([#17](https://github.com/haraldkoch/tplink-plug-exporter/issues/17)) ([a5d83ce](https://github.com/haraldkoch/tplink-plug-exporter/commit/a5d83ce21cbec0912983f7fb7dc1d970d3bd3a31))
* **github-action:** update renovatebot/github-action ( v46.1.0 → v46.1.1 ) ([#21](https://github.com/haraldkoch/tplink-plug-exporter/issues/21)) ([e9304e9](https://github.com/haraldkoch/tplink-plug-exporter/commit/e9304e9564bcdccb664f4afbbceca61aca89bde7))
* **github-action:** update renovatebot/github-action ( v46.1.1 → v46.1.2 ) ([#23](https://github.com/haraldkoch/tplink-plug-exporter/issues/23)) ([f3ea20b](https://github.com/haraldkoch/tplink-plug-exporter/commit/f3ea20beaef49b79d9cfe8481919edca4dc00463))
* **github-action:** update renovatebot/github-action ( v46.1.10 → v46.1.11 ) ([#43](https://github.com/haraldkoch/tplink-plug-exporter/issues/43)) ([690995e](https://github.com/haraldkoch/tplink-plug-exporter/commit/690995e4c57cee7b63995cf9190e8efbab5bc346))
* **github-action:** update renovatebot/github-action ( v46.1.11 → v46.1.12 ) ([#44](https://github.com/haraldkoch/tplink-plug-exporter/issues/44)) ([50eadb9](https://github.com/haraldkoch/tplink-plug-exporter/commit/50eadb930ffedfc25ba9570c97a940414ca25c18))
* **github-action:** update renovatebot/github-action ( v46.1.12 → v46.1.13 ) ([#45](https://github.com/haraldkoch/tplink-plug-exporter/issues/45)) ([4628b14](https://github.com/haraldkoch/tplink-plug-exporter/commit/4628b1485391c4e45b18d01f7690571f0394aa30))
* **github-action:** update renovatebot/github-action ( v46.1.13 → v46.1.14 ) ([#46](https://github.com/haraldkoch/tplink-plug-exporter/issues/46)) ([8370d59](https://github.com/haraldkoch/tplink-plug-exporter/commit/8370d5920d82f432ecdc43585032769617a898d6))
* **github-action:** update renovatebot/github-action ( v46.1.2 → v46.1.3 ) ([#26](https://github.com/haraldkoch/tplink-plug-exporter/issues/26)) ([89bf23c](https://github.com/haraldkoch/tplink-plug-exporter/commit/89bf23c5274c38abc6b4bbb4b8050bb21ee1aeca))
* **github-action:** update renovatebot/github-action ( v46.1.3 → v46.1.4 ) ([#27](https://github.com/haraldkoch/tplink-plug-exporter/issues/27)) ([4711ed5](https://github.com/haraldkoch/tplink-plug-exporter/commit/4711ed546b9423514affad5518da2a99a4d01eb5))
* **github-action:** update renovatebot/github-action ( v46.1.4 → v46.1.5 ) ([#30](https://github.com/haraldkoch/tplink-plug-exporter/issues/30)) ([6dccbec](https://github.com/haraldkoch/tplink-plug-exporter/commit/6dccbec01e9a25cef1d6de0e6a9f55fdcd6df8ec))
* **github-action:** update renovatebot/github-action ( v46.1.5 → v46.1.6 ) ([#31](https://github.com/haraldkoch/tplink-plug-exporter/issues/31)) ([6432e23](https://github.com/haraldkoch/tplink-plug-exporter/commit/6432e236b4693c8ce041beebd3d7701990392c29))
* **github-action:** update renovatebot/github-action ( v46.1.6 → v46.1.7 ) ([#33](https://github.com/haraldkoch/tplink-plug-exporter/issues/33)) ([6dd9dc3](https://github.com/haraldkoch/tplink-plug-exporter/commit/6dd9dc3ddb78f4505e86cc4f441fd6c6087256ee))
* **github-action:** update renovatebot/github-action ( v46.1.7 → v46.1.8 ) ([#34](https://github.com/haraldkoch/tplink-plug-exporter/issues/34)) ([0b06200](https://github.com/haraldkoch/tplink-plug-exporter/commit/0b06200522d718f89d79b4dcf03f36de08eb0faa))
* **github-action:** update renovatebot/github-action ( v46.1.8 → v46.1.9 ) ([#38](https://github.com/haraldkoch/tplink-plug-exporter/issues/38)) ([5685efa](https://github.com/haraldkoch/tplink-plug-exporter/commit/5685efa40d850b11ce49beb2da1daf13b9f47b24))
* **github-action:** update renovatebot/github-action ( v46.1.9 → v46.1.10 ) ([#41](https://github.com/haraldkoch/tplink-plug-exporter/issues/41)) ([eae4c9b](https://github.com/haraldkoch/tplink-plug-exporter/commit/eae4c9b3c950feb1ac1d0ce4546b3b6df512cf30))
* make goreleaser and PR workflows work correctly ([#77](https://github.com/haraldkoch/tplink-plug-exporter/issues/77)) ([007e0f2](https://github.com/haraldkoch/tplink-plug-exporter/commit/007e0f214d8dfa314df382c1478fe3e0225fa286))
* support emeter key with units ([0a31bfc](https://github.com/haraldkoch/tplink-plug-exporter/commit/0a31bfc49a30f5bb4e3d3e5a82b8b4f4744c07f8)), closes [#1](https://github.com/haraldkoch/tplink-plug-exporter/issues/1)


### Continuous Integration

* **github-action:** update action actions/checkout (v6.0.2 ➔ v6.0.3) ([#52](https://github.com/haraldkoch/tplink-plug-exporter/issues/52)) ([e8ac647](https://github.com/haraldkoch/tplink-plug-exporter/commit/e8ac647fa90fcc60cfd85cfc7577d7bdb1a55437))
* **github-action:** Update action actions/checkout (v6.0.3 ➔ v7.0.0) ([#56](https://github.com/haraldkoch/tplink-plug-exporter/issues/56)) ([28bbcca](https://github.com/haraldkoch/tplink-plug-exporter/commit/28bbccaee74b7114ad331a3792508dab91e70c5c))
* **github-action:** update action actions/checkout (v7.0.0 ➔ v7.0.1) ([#65](https://github.com/haraldkoch/tplink-plug-exporter/issues/65)) ([36bf6ad](https://github.com/haraldkoch/tplink-plug-exporter/commit/36bf6ad8dbfcbfb760cb68bb1eac192a634e185b))
* **github-action:** update action actions/setup-go (v6.4.0 ➔ v6.5.0) ([#58](https://github.com/haraldkoch/tplink-plug-exporter/issues/58)) ([5116190](https://github.com/haraldkoch/tplink-plug-exporter/commit/51161904edcf4adaf5ee38369408cef78b5a74c2))
* **github-action:** Update action actions/setup-go (v6.5.0 ➔ v7.0.0) ([#63](https://github.com/haraldkoch/tplink-plug-exporter/issues/63)) ([7ed6094](https://github.com/haraldkoch/tplink-plug-exporter/commit/7ed6094b504f9daceb9b63f6264f2638d05178bd))
* **github-action:** update action goreleaser/goreleaser-action (v7.2.1 ➔ v7.2.2) ([#51](https://github.com/haraldkoch/tplink-plug-exporter/issues/51)) ([11be28c](https://github.com/haraldkoch/tplink-plug-exporter/commit/11be28cfb5747f1bd794a43d8028a0b089aeb5bf))
* **github-action:** update action goreleaser/goreleaser-action (v7.2.2 ➔ v7.2.3) ([#60](https://github.com/haraldkoch/tplink-plug-exporter/issues/60)) ([8c16f78](https://github.com/haraldkoch/tplink-plug-exporter/commit/8c16f78dd65e50fb7b145e4802057d8e022a57a6))
* **github-action:** update action renovatebot/github-action (v46.1.14 ➔ v46.1.15) ([#53](https://github.com/haraldkoch/tplink-plug-exporter/issues/53)) ([c4c62e9](https://github.com/haraldkoch/tplink-plug-exporter/commit/c4c62e99bad8a6d2c3537c11954772a2cb0fee80))
* **github-action:** update action renovatebot/github-action (v46.1.15 ➔ v46.1.16) ([#57](https://github.com/haraldkoch/tplink-plug-exporter/issues/57)) ([da61ec9](https://github.com/haraldkoch/tplink-plug-exporter/commit/da61ec9b198cb84fbed50d756a912f1dc5138222))
* **github-action:** update action renovatebot/github-action (v46.1.16 ➔ v46.1.17) ([#59](https://github.com/haraldkoch/tplink-plug-exporter/issues/59)) ([611e32b](https://github.com/haraldkoch/tplink-plug-exporter/commit/611e32b5b7c9b5644355ff61a66f87f14d408c09))
* **github-action:** update action renovatebot/github-action (v46.1.17 ➔ v46.1.18) ([#61](https://github.com/haraldkoch/tplink-plug-exporter/issues/61)) ([645d3c6](https://github.com/haraldkoch/tplink-plug-exporter/commit/645d3c6c1d2b6b2e23f3de6b4b6c6355ae77c0ec))
* **github-action:** update action renovatebot/github-action (v46.1.18 ➔ v46.1.19) ([#62](https://github.com/haraldkoch/tplink-plug-exporter/issues/62)) ([6e2d355](https://github.com/haraldkoch/tplink-plug-exporter/commit/6e2d35598b58919e0f59077cd493c76ed1cdbf16))
* **github-action:** update action renovatebot/github-action (v46.1.19 ➔ v46.1.20) ([#64](https://github.com/haraldkoch/tplink-plug-exporter/issues/64)) ([58bc5e1](https://github.com/haraldkoch/tplink-plug-exporter/commit/58bc5e1d6cf942d2cb89915997ce9a25a07b5bc1))
* **github-action:** update action renovatebot/github-action (v46.1.20 ➔ v46.1.21) ([#68](https://github.com/haraldkoch/tplink-plug-exporter/issues/68)) ([b799121](https://github.com/haraldkoch/tplink-plug-exporter/commit/b7991218a1ad10abe20005540a6bb5d8cd1b19eb))
* **github-action:** update action renovatebot/github-action (v46.1.21 ➔ v46.2.0) ([#69](https://github.com/haraldkoch/tplink-plug-exporter/issues/69)) ([89e30cc](https://github.com/haraldkoch/tplink-plug-exporter/commit/89e30cc3ae8895f87d88a64cc6ed7b91f8c0b841))
* **github-action:** update action renovatebot/github-action (v46.2.0 ➔ v46.2.1) ([#70](https://github.com/haraldkoch/tplink-plug-exporter/issues/70)) ([6336f8c](https://github.com/haraldkoch/tplink-plug-exporter/commit/6336f8c113edd0fff2a133ca822d021842d4869a))
* **github-action:** update action renovatebot/github-action (v46.2.1 ➔ v46.2.2) ([#72](https://github.com/haraldkoch/tplink-plug-exporter/issues/72)) ([c00ed07](https://github.com/haraldkoch/tplink-plug-exporter/commit/c00ed07904d658995777275c45c09e8b444480ee))


### Miscellaneous Chores

* add Dockerfile ([#4](https://github.com/haraldkoch/tplink-plug-exporter/issues/4)) ([66bf73f](https://github.com/haraldkoch/tplink-plug-exporter/commit/66bf73f89719bba085008ccddeaa0447eba34d8e))
* add github actions to build go binary ([ce1825d](https://github.com/haraldkoch/tplink-plug-exporter/commit/ce1825d66e110db8a343d9832b1ad2abaf50c98b))
* add license ([#7](https://github.com/haraldkoch/tplink-plug-exporter/issues/7)) ([cc4a731](https://github.com/haraldkoch/tplink-plug-exporter/commit/cc4a731ac8cd148f6fea4fec5f5844d032814cf5)), closes [#6](https://github.com/haraldkoch/tplink-plug-exporter/issues/6)
* add local renovate action ([cba15bb](https://github.com/haraldkoch/tplink-plug-exporter/commit/cba15bb9c41c136d178c1643c1f0b72afaefd400))
* add success ([334b6fe](https://github.com/haraldkoch/tplink-plug-exporter/commit/334b6fe6825eccb3b7c870cebfab73c669c9c6fe))
* **deps:** add renovate.json ([#1](https://github.com/haraldkoch/tplink-plug-exporter/issues/1)) ([293fa71](https://github.com/haraldkoch/tplink-plug-exporter/commit/293fa7182bd4595b327e3eacf34b38b16273000d))
* **deps:** pin goreleaser/goreleaser-action action to e435ccd ([#14](https://github.com/haraldkoch/tplink-plug-exporter/issues/14)) ([468cd23](https://github.com/haraldkoch/tplink-plug-exporter/commit/468cd2335d8341927b32054712724d972c5f7825))
* **deps:** pin goreleaser/goreleaser-action action to e435ccd ([#2](https://github.com/haraldkoch/tplink-plug-exporter/issues/2)) ([80c0bfd](https://github.com/haraldkoch/tplink-plug-exporter/commit/80c0bfd93ee724b86db08cfe3b064e5a103be18d))
* **deps:** update actions/setup-go digest to 4a36011 ([#32](https://github.com/haraldkoch/tplink-plug-exporter/issues/32)) ([450b19d](https://github.com/haraldkoch/tplink-plug-exporter/commit/450b19dffec62a2332eccd8d717ec88eca92e4b4))
* **deps:** update actions/setup-go digest to 4b73464 ([#24](https://github.com/haraldkoch/tplink-plug-exporter/issues/24)) ([009a022](https://github.com/haraldkoch/tplink-plug-exporter/commit/009a0225e48e39a250660e735e3648846d225f54))
* **deps:** update goreleaser/goreleaser-action digest to 1a80836 ([#42](https://github.com/haraldkoch/tplink-plug-exporter/issues/42)) ([35118b1](https://github.com/haraldkoch/tplink-plug-exporter/commit/35118b1a6dc59451b8629f3198cc94bc01633cdd))
* **deps:** update goreleaser/goreleaser-action digest to 5daf1e9 ([#48](https://github.com/haraldkoch/tplink-plug-exporter/issues/48)) ([f271db8](https://github.com/haraldkoch/tplink-plug-exporter/commit/f271db8c25ae8c078df813f605692eab0c8d55d7))
* **deps:** update goreleaser/goreleaser-action digest to e24998b ([#40](https://github.com/haraldkoch/tplink-plug-exporter/issues/40)) ([a22c8d2](https://github.com/haraldkoch/tplink-plug-exporter/commit/a22c8d28c512faa94b365cdbd319a529abb657ce))
* enable dockerfile to produce arm64 image ([#10](https://github.com/haraldkoch/tplink-plug-exporter/issues/10)) ([9199b34](https://github.com/haraldkoch/tplink-plug-exporter/commit/9199b34f2475c10a6638d014c34e02a7178c8e1f))
* go v1.26.6 ([#78](https://github.com/haraldkoch/tplink-plug-exporter/issues/78)) ([1e42e50](https://github.com/haraldkoch/tplink-plug-exporter/commit/1e42e50a7f997de0609096350e0e455081c8c1e1))
* **mise:** update tool go:golang.org/x/vuln/cmd/govulncheck (1.6.0 ➔ v1.7.0) ([#79](https://github.com/haraldkoch/tplink-plug-exporter/issues/79)) ([5278081](https://github.com/haraldkoch/tplink-plug-exporter/commit/52780815be38afcd0bcea4a856cc2ed47c9561b4))
* **mise:** update tool syft (1.50.0 ➔ 1.51.0) ([#80](https://github.com/haraldkoch/tplink-plug-exporter/issues/80)) ([3a14251](https://github.com/haraldkoch/tplink-plug-exporter/commit/3a142513fb82af38962da92061921a768a0185f4))
* rename ([2a022fb](https://github.com/haraldkoch/tplink-plug-exporter/commit/2a022fb1fc9636c21228259fb0e41def0c0b4889))
* rename renovate file again ([86d7dcb](https://github.com/haraldkoch/tplink-plug-exporter/commit/86d7dcb333cda7d7b7227740540b7a6dbd241962))
* rename workflows ([b8fdf7e](https://github.com/haraldkoch/tplink-plug-exporter/commit/b8fdf7e5ba07c389dedfb01990047ccdf096f729))
* replace goreleaser config ([91ee734](https://github.com/haraldkoch/tplink-plug-exporter/commit/91ee73497ff93daf135a5204bdd9312b5ec7549a))
* run goreleaser as bot ([aded79a](https://github.com/haraldkoch/tplink-plug-exporter/commit/aded79aedc2382490d048610296d64ff42d04459))
* separate pull/release workflows ([ee2eee1](https://github.com/haraldkoch/tplink-plug-exporter/commit/ee2eee18da5eef6722fd3c01b67c49938a4fd145))
* try renovate.json ([39eaf5f](https://github.com/haraldkoch/tplink-plug-exporter/commit/39eaf5fa162ea3a0421431fa1c445ce9f17e554d))
* update goreleaser workflow ([88821b4](https://github.com/haraldkoch/tplink-plug-exporter/commit/88821b4e5e4180faa5d4831ec4d02001ac60ddeb))
* update prometheus dependencies, import logrus directly ([#14](https://github.com/haraldkoch/tplink-plug-exporter/issues/14)) ([eb68b73](https://github.com/haraldkoch/tplink-plug-exporter/commit/eb68b731781ed3e0d17f93ab634f6a284136d3cc))
* update reonvate config; add go postUpdateOptions ([#74](https://github.com/haraldkoch/tplink-plug-exporter/issues/74)) ([ebd5292](https://github.com/haraldkoch/tplink-plug-exporter/commit/ebd5292782599b6bdb0da96b3e52ee148dca8e0c))
