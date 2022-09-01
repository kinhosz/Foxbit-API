# Changelog

<!--next-version-placeholder-->

## v0.3.2 (2022-09-01)
### Fix
* Remove print ([`d394d84`](https://github.com/kinhosz/Saturn/commit/d394d84c5927bfeeda3424f02821b3373c8ad281))

## v0.3.1 (2022-09-01)
### Performance
* Improve ping and log messages ([`ceac5db`](https://github.com/kinhosz/Saturn/commit/ceac5dbc2e6564c6792e4d7444e6d3b3b0e40d2f))

## v0.3.0 (2022-09-01)
### Feature
* Add search21 model for a project ([`2331e8c`](https://github.com/kinhosz/Saturn/commit/2331e8cb5f8a50a648249ea3fe96a208c2d6908d))

## v0.2.0 (2022-04-11)
### Feature
* **session/buy:** Add a buy service ([`b59cbfa`](https://github.com/kinhosz/Saturn/commit/b59cbfa732cb4bbd634e27576852e332ac9a904a))
* **db/update:** Create update queries to database ([`cb6950c`](https://github.com/kinhosz/Saturn/commit/cb6950ca87b48f9c1808f1d23890d14e399f7c90))
* **fserver.sellTrade:** Sell order and close trade ([`4d65b4e`](https://github.com/kinhosz/Saturn/commit/4d65b4ef2f0237198775abe146e5a02ddae37590))
* **fserver:** Add insert database interface ([`2f622e8`](https://github.com/kinhosz/Saturn/commit/2f622e817275e0ab45adc3841218fadbc33fa2d8))
* **fserver:** Adding a listenner for foxbit currency values ([`0ab86d7`](https://github.com/kinhosz/Saturn/commit/0ab86d76577981baf24f55e59f3b53cc5430d7a7))
* **db:** Sql queries ([`5b4ac56`](https://github.com/kinhosz/Saturn/commit/5b4ac56373d902b675f3515bc45aaafbf4166781))
* **database:** Adding mult trades for a single account ([`ccdaa4a`](https://github.com/kinhosz/Saturn/commit/ccdaa4ada7dffd6cb03d46aa8f20e86be0f077fa))

### Fix
* **fserver:** Change the default profit value ([`8435944`](https://github.com/kinhosz/Saturn/commit/843594461b0cde7ca5647fcbb6d8e607e3cb0276))
* **workflow:** Fix name and test release ([`f7f6e22`](https://github.com/kinhosz/Saturn/commit/f7f6e22c474eaa6eeed88771996cbe480baf6d48))
* **user_session:** Fix start_trade ([`8b3dfb1`](https://github.com/kinhosz/Saturn/commit/8b3dfb1384df57847bd3cde10483475fd2185695))
* **handshake:** Database_url regex ([`269602c`](https://github.com/kinhosz/Saturn/commit/269602c866d338378958df05359afa67a17f50da))
* **sell_trade:** Selling trades ([`76d0ae7`](https://github.com/kinhosz/Saturn/commit/76d0ae7350337d2d9e592f88c09d92a4ca07985c))
* **db:** Add autocommit command ([`cee8ac7`](https://github.com/kinhosz/Saturn/commit/cee8ac7a299470ef3ff6b820aceb60226e438468))
* **db/create_table:** Replace serial to int ([`f8e2b8d`](https://github.com/kinhosz/Saturn/commit/f8e2b8d4f24fd29e80b740a1c7d6dde8b13e67e6))

## v0.1.9 (2022-01-28)
### Fix
* **foxbit:** Set ping_interval=None ([`fdb9843`](https://github.com/kinhosz/Saturn/commit/fdb98437cf3ad946a4fd676c0e7804baa7dcc368))

## v0.1.8 (2022-01-24)
### Fix
* **receive:** Remove unless connectionClosed ([`7fed6b8`](https://github.com/kinhosz/Saturn/commit/7fed6b8a7de6cb161f415b53ae032d099a3cc4db))

## v0.1.7 (2022-01-24)
### Fix
* **recv, deletePassword:** Fix the json format ([`71fbc8e`](https://github.com/kinhosz/Saturn/commit/71fbc8e4acf8d302d36f2d44bff0644b1e74e21b))

## v0.1.6 (2022-01-21)
### Fix
* **user_session, foxbit:** Fix a connectionClosedError during websocket.send ([`95b109e`](https://github.com/kinhosz/Saturn/commit/95b109e5b27aced8c8398ec9787643abf89b2c28))

## v0.1.5 (2022-01-20)
### Performance
* **websocket.send:** Improve exceptions ([`7762ed8`](https://github.com/kinhosz/Saturn/commit/7762ed8d6ed7cbdf754a158c05fcff50e9fe8466))

## v0.1.3 (2022-01-18)
### Fix
* Version ([`a6edd34`](https://github.com/kinhosz/Saturn/commit/a6edd34d241e0e228af2e054a6813f012645ef33))
* Py version ([`a74733b`](https://github.com/kinhosz/Saturn/commit/a74733b92e963a078d9dd3505b2f57f844b3ec4d))
* Workflow ([`b1b739a`](https://github.com/kinhosz/Saturn/commit/b1b739aa8cd71ddd2e93173c565e6e2324eaa13e))
* Github token ([`44b92f5`](https://github.com/kinhosz/Saturn/commit/44b92f5dae64b6490faa1a3ea9f210e85a2bb477))
* Yaml ([`b3bb541`](https://github.com/kinhosz/Saturn/commit/b3bb54156d4988257b2975c214e644e81d3d94b6))
* Ci.yml ([`c2c69bb`](https://github.com/kinhosz/Saturn/commit/c2c69bb5b434341e30b169013fd3e3edd3623ee1))
* Semantic-release ([`f40c9d6`](https://github.com/kinhosz/Saturn/commit/f40c9d64b1c9747db0fae9f0aa604edc29b43b4f))
* Ci.yml ([`5741537`](https://github.com/kinhosz/Saturn/commit/5741537d019466739043174d45137d5b12c9366f))
* Zzz ([`0de95ae`](https://github.com/kinhosz/Saturn/commit/0de95ae1e439545081a6fac41e1895c92d0a5196))
* Z ([`549b26a`](https://github.com/kinhosz/Saturn/commit/549b26a1d2106534222b8dc5add112f3efc3b668))
* ... ([`908223c`](https://github.com/kinhosz/Saturn/commit/908223c47643c6f68e1b526295d5868cf9ea8a00))
* Remove pypy token ([`d17e039`](https://github.com/kinhosz/Saturn/commit/d17e039f8715d4d72ca71cb99dea36e032b12ee5))
* Add branch main ([`80c7fa1`](https://github.com/kinhosz/Saturn/commit/80c7fa1ceeb632dcc7914e7b7f1767fd315cd539))
* Add username ([`62cf7c4`](https://github.com/kinhosz/Saturn/commit/62cf7c4d42d126daced769a26f31128e4bcd7446))
* Add branch main ([`43502f5`](https://github.com/kinhosz/Saturn/commit/43502f593d7d1b30d99a796b435b7b4b95ccbf32))
* Add username ([`5acbaef`](https://github.com/kinhosz/Saturn/commit/5acbaef2a384b3f38baf03608bde8688f586f27c))
* Remove pypy token ([`026e3b8`](https://github.com/kinhosz/Saturn/commit/026e3b8f3bc4a5af10b0bf4a254b3621d467ddee))
* **ci.yml:** Add a new workflow ([`ebd699b`](https://github.com/kinhosz/Saturn/commit/ebd699b85702d2e63909d290fd8b961604434880))
* D ([`642c0a9`](https://github.com/kinhosz/Saturn/commit/642c0a93a42305457bee7d6d956956395b1995f2))
* G ([`4c1593d`](https://github.com/kinhosz/Saturn/commit/4c1593d256ce6b2bbe83a4bdaa90ee55b6cab13f))
* Im crying.... ([`61d1d26`](https://github.com/kinhosz/Saturn/commit/61d1d265e6f28da0e4d7cb7c0510b2ecf599b52d))
* G ([`21a2a1d`](https://github.com/kinhosz/Saturn/commit/21a2a1d37c66a97a76a33fb78e632b230e89bd69))
* E ([`9573db2`](https://github.com/kinhosz/Saturn/commit/9573db2de4748ff73eb630cc392f89306ef26251))
* D ([`44cec86`](https://github.com/kinhosz/Saturn/commit/44cec860e163e3e7b4a8d547ac87c86f673f4357))
* D ([`dabbaec`](https://github.com/kinhosz/Saturn/commit/dabbaece43a9eedae3b808d6991b3831bc0d0383))
* C ([`813b3fd`](https://github.com/kinhosz/Saturn/commit/813b3fd860785b99f02823014e14ed7f234525c1))
* B ([`434d06c`](https://github.com/kinhosz/Saturn/commit/434d06ca69a36823bceb0748cfb276f1c0a2cbfd))
* A ([`281e072`](https://github.com/kinhosz/Saturn/commit/281e072cea835a00fd83f5711acad616ce68ed64))
* Semantic release ([`e1872c7`](https://github.com/kinhosz/Saturn/commit/e1872c7501c30400d93be73fb91c13996359d18a))
