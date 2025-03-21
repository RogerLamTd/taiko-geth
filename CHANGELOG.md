# Changelog

## [1.14.0](https://github.com/RogerLamTd/taiko-geth/compare/v1.13.0...v1.14.0) (2025-03-21)


### Features

* **all:** changes based on Taiko protocol ([7e1b8b6](https://github.com/RogerLamTd/taiko-geth/commit/7e1b8b65a3f8b931a5f141281c6ff82ad17028d0))
* **beacon:** introduce soft blocks ([#342](https://github.com/RogerLamTd/taiko-geth/issues/342)) ([a2cbf90](https://github.com/RogerLamTd/taiko-geth/commit/a2cbf904eaaed308bea29ab67ab9059bde013634))
* **beacon:** remove soft blocks implementation ([#366](https://github.com/RogerLamTd/taiko-geth/issues/366)) ([3b30523](https://github.com/RogerLamTd/taiko-geth/commit/3b305232a53a8fe85ca49d93fe80b289cf3ba8cf))
* **consensus:** improve `VerifyHeaders` for `taiko` consensus ([#238](https://github.com/RogerLamTd/taiko-geth/issues/238)) ([4f36879](https://github.com/RogerLamTd/taiko-geth/commit/4f368792dc27d1e5c5d92f44b2d4b0a3f2986e02))
* **consensus:** introduce `AnchorV3GasLimit` ([#378](https://github.com/RogerLamTd/taiko-geth/issues/378)) ([a0b97be](https://github.com/RogerLamTd/taiko-geth/commit/a0b97be30cc01a93cebbd2d7188d28b0dcc5989a))
* **consensus:** introduce cache for the payloads ([#380](https://github.com/RogerLamTd/taiko-geth/issues/380)) ([36430eb](https://github.com/RogerLamTd/taiko-geth/commit/36430eb4f53a1455eb331f58c3ad2e88d8f40ecf))
* **consensus:** update `TaikoAnchor.anchorV3` selector ([#379](https://github.com/RogerLamTd/taiko-geth/issues/379)) ([1e948cf](https://github.com/RogerLamTd/taiko-geth/commit/1e948cff4c83e7a5cb0d8a4db27cbe59ce2a8884))
* **consensus:** update `ValidateAnchorTx` ([#289](https://github.com/RogerLamTd/taiko-geth/issues/289)) ([8ff161f](https://github.com/RogerLamTd/taiko-geth/commit/8ff161fb39b76ef15585d26033131433c4530a3e))
* **core:** align the upstream `types.Header` ([#393](https://github.com/RogerLamTd/taiko-geth/issues/393)) ([573f8fc](https://github.com/RogerLamTd/taiko-geth/commit/573f8fc144670d7221b387661f1f18dcd0935fe1))
* **core:** changes based on the latest `block.extradata` format ([#295](https://github.com/RogerLamTd/taiko-geth/issues/295)) ([a875cc8](https://github.com/RogerLamTd/taiko-geth/commit/a875cc83b907b026b88da887ce0a0d46c91d6980))
* **core:** decode basefee params from `block.extraData` ([#290](https://github.com/RogerLamTd/taiko-geth/issues/290)) ([83564ba](https://github.com/RogerLamTd/taiko-geth/commit/83564ba6fc9c20b1fa28ff94d65d5e19211a1aa2))
* **core:** introduce `BasefeeSharingPctg` in `BlockMetadata` ([#287](https://github.com/RogerLamTd/taiko-geth/issues/287)) ([e6487f0](https://github.com/RogerLamTd/taiko-geth/commit/e6487f00ed74139fb4169cf4ccd70488d933a01a))
* **core:** update `MainnetOntakeBlock` ([#330](https://github.com/RogerLamTd/taiko-geth/issues/330)) ([cd72c5b](https://github.com/RogerLamTd/taiko-geth/commit/cd72c5bf056cce5870b685226ae70e0d2620dc5e))
* **core:** update `ontakeForkHeight` to Sep 24, 2024 ([#309](https://github.com/RogerLamTd/taiko-geth/issues/309)) ([4e05e58](https://github.com/RogerLamTd/taiko-geth/commit/4e05e5893b18482a90b1560019f93e90745cc0e0))
* **core:** update devnet ontake fork height ([#345](https://github.com/RogerLamTd/taiko-geth/issues/345)) ([4578ce1](https://github.com/RogerLamTd/taiko-geth/commit/4578ce1ffeed8065d70fb2bc39bff20a9df50f56))
* **eip1559:** remove `CalcBaseFeeOntake()` method ([#293](https://github.com/RogerLamTd/taiko-geth/issues/293)) ([124fde7](https://github.com/RogerLamTd/taiko-geth/commit/124fde7e025d6ba88c5cf796d6a0a5fd19c21a19))
* **eth:** add default gpo price flag ([#258](https://github.com/RogerLamTd/taiko-geth/issues/258)) ([0fb7ce1](https://github.com/RogerLamTd/taiko-geth/commit/0fb7ce1999e6b8f4d39e78787525e236e007948f))
* **eth:** changes based on protocol `Pacaya` fork ([#367](https://github.com/RogerLamTd/taiko-geth/issues/367)) ([7bf5c0d](https://github.com/RogerLamTd/taiko-geth/commit/7bf5c0d259f60f9d62d481c873053548c87b6fb5))
* **miner:** change invalid transaction log level to `DEBUG` ([#224](https://github.com/RogerLamTd/taiko-geth/issues/224)) ([286ffe2](https://github.com/RogerLamTd/taiko-geth/commit/286ffe2cbfd6e1b234c9ab3976b4daa60c8a24ce))
* **miner:** compress the txlist bytes after checking the transaction is executable ([#269](https://github.com/RogerLamTd/taiko-geth/issues/269)) ([aa70708](https://github.com/RogerLamTd/taiko-geth/commit/aa70708a69d9612bf2dffd218db7e703de1654c1))
* **miner:** count last oversized transaction ([#273](https://github.com/RogerLamTd/taiko-geth/issues/273)) ([451a668](https://github.com/RogerLamTd/taiko-geth/commit/451a668d79bb9e41bb34dfb5fdbd1e0301977a9b))
* **miner:** improve `prepareWork()` ([#292](https://github.com/RogerLamTd/taiko-geth/issues/292)) ([06b2903](https://github.com/RogerLamTd/taiko-geth/commit/06b29039cbf1f72d6163c0c4f658053acfcc5c47))
* **miner:** move `TAIKO_MIN_TIP` check to `commitL2Transactions` ([#272](https://github.com/RogerLamTd/taiko-geth/issues/272)) ([f3a7fb6](https://github.com/RogerLamTd/taiko-geth/commit/f3a7fb6311e9d59ba2fb55799b9eab614d488095))
* **miner:** use `[]*ethapi.RPCTransaction` in RPC response body ([#391](https://github.com/RogerLamTd/taiko-geth/issues/391)) ([afd09af](https://github.com/RogerLamTd/taiko-geth/commit/afd09afd03871f9c66231a92bba706f4c491b877))
* **repo:** `geth/v1.14.11` upstream merge ([#313](https://github.com/RogerLamTd/taiko-geth/issues/313)) ([5c84a20](https://github.com/RogerLamTd/taiko-geth/commit/5c84a20827473cbe60ed16827df21b4ad395c9c2))
* **repo:** `go-ethereum` v1.15.5 upstream merge  ([#395](https://github.com/RogerLamTd/taiko-geth/issues/395)) ([364acd0](https://github.com/RogerLamTd/taiko-geth/commit/364acd00d1f2b45a07b7b1d20ec9b0f77be50b91))
* **repo:** add do-not-merge and rename files ([#390](https://github.com/RogerLamTd/taiko-geth/issues/390)) ([3792f93](https://github.com/RogerLamTd/taiko-geth/commit/3792f9356bfdc391fc8e112fccc7bf31d9edbb63))
* **taiko_api:** reduce the frequency of `zlib` compression when fetching txpool content ([#323](https://github.com/RogerLamTd/taiko-geth/issues/323)) ([27b4d6e](https://github.com/RogerLamTd/taiko-geth/commit/27b4d6ebf9959b096fb6c6ed7f5910fa93a59df3))
* **taiko_genesis:** update `TaikoGenesisBlock` configs ([#400](https://github.com/RogerLamTd/taiko-geth/issues/400)) ([139e562](https://github.com/RogerLamTd/taiko-geth/commit/139e56205075ba5897c2a4ca707a52b096a3f200))
* **taiko_genesis:** update devnet genesis JSONs for new `AnchorV3` method ([#382](https://github.com/RogerLamTd/taiko-geth/issues/382)) ([2448fb9](https://github.com/RogerLamTd/taiko-geth/commit/2448fb97a8b873c7bd7c0051cd83aaea339050e0))
* **taiko_genesis:** update genesis JSONs ([#305](https://github.com/RogerLamTd/taiko-geth/issues/305)) ([73df1f1](https://github.com/RogerLamTd/taiko-geth/commit/73df1f1a116bdb530c5a8bd7fc20b64b491f2f3c))
* **taiko_genesis:** update genesis JSONs ([#315](https://github.com/RogerLamTd/taiko-geth/issues/315)) ([ae8a194](https://github.com/RogerLamTd/taiko-geth/commit/ae8a194c517e39fda7a4c330cd6e5a49a8df3621))
* **taiko_genesis:** update interanl devnet genesis JSON for ontake hardfork ([#288](https://github.com/RogerLamTd/taiko-geth/issues/288)) ([a748b91](https://github.com/RogerLamTd/taiko-geth/commit/a748b914abb1b5bc2a25fe40de6e38bb70e4235a))
* **taiko_genesis:** update interanl devnet genesis JSON for ontake hardfork ([#291](https://github.com/RogerLamTd/taiko-geth/issues/291)) ([217c9ec](https://github.com/RogerLamTd/taiko-geth/commit/217c9ec0f42f4785b44b8d2dbc4c046eb43e1d02))
* **taiko_genesis:** update internal devnet genesis JSON ([#285](https://github.com/RogerLamTd/taiko-geth/issues/285)) ([b137b2a](https://github.com/RogerLamTd/taiko-geth/commit/b137b2ac113dfe899bc538220cbdadf45b24f133))
* **taiko_genesis:** update internal devnet genesis JSON ([#296](https://github.com/RogerLamTd/taiko-geth/issues/296)) ([882a6cd](https://github.com/RogerLamTd/taiko-geth/commit/882a6cd3294cd1c74eac37fbc37c54e64f0dc363))
* **taiko_miner:** add `BuildTransactionsListsWithMinTip` method ([#283](https://github.com/RogerLamTd/taiko-geth/issues/283)) ([c777d24](https://github.com/RogerLamTd/taiko-geth/commit/c777d24af16915030536564b8cb44346866ab0b1))
* **taiko_miner:** remove an unnecessary check ([#239](https://github.com/RogerLamTd/taiko-geth/issues/239)) ([974b338](https://github.com/RogerLamTd/taiko-geth/commit/974b338e20c3a2ff48ecfd0174c595d6cb02e935))
* **taiko_worker:** skip blob transactions ([#280](https://github.com/RogerLamTd/taiko-geth/issues/280)) ([30a615b](https://github.com/RogerLamTd/taiko-geth/commit/30a615b4c3aafd0d395309035d58b86ff53c8eb0))
* **txpool:** introduce `TAIKO_MIN_TIP` env ([#264](https://github.com/RogerLamTd/taiko-geth/issues/264)) ([a29520e](https://github.com/RogerLamTd/taiko-geth/commit/a29520e066809dda21af463272b6ec1ef1cdfcae))
* **txpool:** update `ValidateTransaction` ([#237](https://github.com/RogerLamTd/taiko-geth/issues/237)) ([6cc43e1](https://github.com/RogerLamTd/taiko-geth/commit/6cc43e1d9c1ef34cba5fff2db3735ced3ad0a3a0))
* **txpool:** update `ValidateTransaction` ([#255](https://github.com/RogerLamTd/taiko-geth/issues/255)) ([87f4206](https://github.com/RogerLamTd/taiko-geth/commit/87f42062d9d02fd99be1f8c318baf573ef08135f))
* **txpool:** update max fee check in `ValidateTransaction()` ([#259](https://github.com/RogerLamTd/taiko-geth/issues/259)) ([ef40d46](https://github.com/RogerLamTd/taiko-geth/commit/ef40d46c0efbda50f0a2b84987291a4b8f9f2a2d))
* **worker:** add `chainId` check in `worker` ([#228](https://github.com/RogerLamTd/taiko-geth/issues/228)) ([4ebcf66](https://github.com/RogerLamTd/taiko-geth/commit/4ebcf6656c507c3164722148c16e76f7766fe52e))


### Bug Fixes

* broken url link ([#28342](https://github.com/RogerLamTd/taiko-geth/issues/28342)) ([a5544d3](https://github.com/RogerLamTd/taiko-geth/commit/a5544d35f6746c93d01e9c54c5bc5ef6567463b3))
* **core/txpool:** fix typos ([a081130](https://github.com/RogerLamTd/taiko-geth/commit/a0811300815f1d4e79881113a102e91fdfeecdb8))
* **core:** fix a transaction `Message` assembling issue ([#308](https://github.com/RogerLamTd/taiko-geth/issues/308)) ([04d76e8](https://github.com/RogerLamTd/taiko-geth/commit/04d76e8f012e8a3d89d04f38dabac08e758f5a00))
* **eth:** mark anchor transaction in `traceBlockParallel` ([#243](https://github.com/RogerLamTd/taiko-geth/issues/243)) ([8622b2c](https://github.com/RogerLamTd/taiko-geth/commit/8622b2cce09330fc4957e22be5bd4685675411d9))
* **eth:** write `L1Origin` even if the payload is already in the cache ([#396](https://github.com/RogerLamTd/taiko-geth/issues/396)) ([43a60b3](https://github.com/RogerLamTd/taiko-geth/commit/43a60b36ea53a416ba01f271749d20f1251ce607))
* fix some (ST1005)go-staticcheck ([2814ee0](https://github.com/RogerLamTd/taiko-geth/commit/2814ee0547cb49dddf182bad802f19100608d5f8))
* management api links ([4c15d58](https://github.com/RogerLamTd/taiko-geth/commit/4c15d58007422069794cada5e38ec8b90940a969))
* **taiko_api:** fix an `EstimatedGasUsed` calculation issue ([#322](https://github.com/RogerLamTd/taiko-geth/issues/322)) ([96296fb](https://github.com/RogerLamTd/taiko-geth/commit/96296fb42e08da4f0db1c836efb9c427740c92e4))
* **taiko_genesis:** update devnet Ontake fork hight ([#302](https://github.com/RogerLamTd/taiko-geth/issues/302)) ([d065dd2](https://github.com/RogerLamTd/taiko-geth/commit/d065dd2c3d005fb01590ecc82cda9c91678dfd13))
* **taiko_miner:** fix a typo ([#299](https://github.com/RogerLamTd/taiko-geth/issues/299)) ([5faa71b](https://github.com/RogerLamTd/taiko-geth/commit/5faa71b531cc889fb66868380d9063e8c78c7646))
* **taiko_worker:** fix a `maxBytesPerTxList` check issue ([#282](https://github.com/RogerLamTd/taiko-geth/issues/282)) ([f930382](https://github.com/RogerLamTd/taiko-geth/commit/f930382f4bf789bdc6c6fae5a410758a9f9bed7c))
* **taiko_worker:** fix a size limit check in `commitL2Transactions` ([#245](https://github.com/RogerLamTd/taiko-geth/issues/245)) ([7a75d5e](https://github.com/RogerLamTd/taiko-geth/commit/7a75d5e6b42ee57fed4df8713049c71e9b08657a))
* **taiko-geth:** fix a mempool fetch issue ([#333](https://github.com/RogerLamTd/taiko-geth/issues/333)) ([1340ded](https://github.com/RogerLamTd/taiko-geth/commit/1340ded3811193b46d18241e5810c5b47083821f))
* **taiko-geth:** revert a `tx.Shift()` change ([#335](https://github.com/RogerLamTd/taiko-geth/issues/335)) ([46576d2](https://github.com/RogerLamTd/taiko-geth/commit/46576d27209194db9e02ba38b9ab6b919679fcbd))
* **taiko-geth:** stop using `RevertToSnapshot` when fetching mempool ([#336](https://github.com/RogerLamTd/taiko-geth/issues/336)) ([1216d8d](https://github.com/RogerLamTd/taiko-geth/commit/1216d8d6051ba6f73ee42b395e973dccf1d90cf9))
* **taiko:** decode basefeeSharingPctg from extradata for ontake blocks ([#370](https://github.com/RogerLamTd/taiko-geth/issues/370)) ([cdca791](https://github.com/RogerLamTd/taiko-geth/commit/cdca79128bc606f89c12e08474f228ad5d0d89c3))
* **txpool:** basefee requires mintip to not be nil. ([#297](https://github.com/RogerLamTd/taiko-geth/issues/297)) ([6315fd4](https://github.com/RogerLamTd/taiko-geth/commit/6315fd49697701beb1f18b8c8c0a6bdf97e862d5))
* **txpool:** fix the unit in a log ([#266](https://github.com/RogerLamTd/taiko-geth/issues/266)) ([9594e0a](https://github.com/RogerLamTd/taiko-geth/commit/9594e0a6a87d14bdaa594b3a31eec116ce24c948))
* update link to trezor ([1a79089](https://github.com/RogerLamTd/taiko-geth/commit/1a79089193f2046c0cab60954bc05be2f52a2a90))
* update outdated link to trezor docs ([#28966](https://github.com/RogerLamTd/taiko-geth/issues/28966)) ([1a79089](https://github.com/RogerLamTd/taiko-geth/commit/1a79089193f2046c0cab60954bc05be2f52a2a90))
* **wokrer:** fix an issue in `sealBlockWith` ([#240](https://github.com/RogerLamTd/taiko-geth/issues/240)) ([02c6ee9](https://github.com/RogerLamTd/taiko-geth/commit/02c6ee9672c1b47ac534ec7224f45d9ab0652cdf))


### Chores

* **ci:** add docker multi arch image build ([#339](https://github.com/RogerLamTd/taiko-geth/issues/339)) ([eeab36d](https://github.com/RogerLamTd/taiko-geth/commit/eeab36de475a23b8d6f37d4845f1517c8464dd9e))
* **ci:** add go cache dependency in action ([#235](https://github.com/RogerLamTd/taiko-geth/issues/235)) ([a998c80](https://github.com/RogerLamTd/taiko-geth/commit/a998c80533832202c576120974c8049f2d03e623))
* **ci:** fix an issue in docker build cache ([#262](https://github.com/RogerLamTd/taiko-geth/issues/262)) ([037640e](https://github.com/RogerLamTd/taiko-geth/commit/037640eccdd161454fb144fd57909b47a84c259a))
* **ci:** introduce docker build cache ([#234](https://github.com/RogerLamTd/taiko-geth/issues/234)) ([fdb980a](https://github.com/RogerLamTd/taiko-geth/commit/fdb980ab0600d1f7b143a7b6c53648fa1934a646))
* **ci:** use `arc-runner-set` ([#340](https://github.com/RogerLamTd/taiko-geth/issues/340)) ([fe966d4](https://github.com/RogerLamTd/taiko-geth/commit/fe966d48ab1f1b16f34a4357fbdc93f766dad194))
* **cmd:** add `--taiko` flag ([#365](https://github.com/RogerLamTd/taiko-geth/issues/365)) ([ca784a2](https://github.com/RogerLamTd/taiko-geth/commit/ca784a23df4a62529a79e779e3c3083f41c00129))
* **cmd:** remove `--taiko.preconfirmationForwardingUrl` flag ([#362](https://github.com/RogerLamTd/taiko-geth/issues/362)) ([283fedd](https://github.com/RogerLamTd/taiko-geth/commit/283fedd05b57bbedc8142601ac86e9992b3c12cd))
* **consensus:** change `SetHeadL1Origin` && `UpdateL1Origin` to `taikoauth_` namespace ([#386](https://github.com/RogerLamTd/taiko-geth/issues/386)) ([838f653](https://github.com/RogerLamTd/taiko-geth/commit/838f65315354488ada3c18e8a9924b69cb61b002))
* **consensus:** update `maxTrackedPayloads` to `maxBlocksPerBatch` ([#389](https://github.com/RogerLamTd/taiko-geth/issues/389)) ([516eff7](https://github.com/RogerLamTd/taiko-geth/commit/516eff7ae9a9504d7d3cc42db7ce83c2242d870c))
* **core,eth:** fix a couple of typos ([edc864f](https://github.com/RogerLamTd/taiko-geth/commit/edc864f9ba186fd307d9c98c42136db6c9411cf9))
* **core:** revert `[]*ethapi.RPCTransaction` changes in miner ([#394](https://github.com/RogerLamTd/taiko-geth/issues/394)) ([03f614f](https://github.com/RogerLamTd/taiko-geth/commit/03f614fb278a7da17fcd6231d9de1ff1086d704f))
* **core:** update Hekla Pacaya fork height ([#397](https://github.com/RogerLamTd/taiko-geth/issues/397)) ([3aefd22](https://github.com/RogerLamTd/taiko-geth/commit/3aefd22fccd97eec2c3dec9508b51eda179988c1))
* **ethclient:** remove some unused APIs ([#387](https://github.com/RogerLamTd/taiko-geth/issues/387)) ([437b5c6](https://github.com/RogerLamTd/taiko-geth/commit/437b5c6114e34fd7b34d8d04fba1ee3e1eab5d45))
* **repo:** add changelog sections ([#398](https://github.com/RogerLamTd/taiko-geth/issues/398)) ([772a559](https://github.com/RogerLamTd/taiko-geth/commit/772a55954cb5e94b08b89b3d61a639919362cb59))
* **taiko_genesis:** update `TaikoGenesisBlock` configs ([#399](https://github.com/RogerLamTd/taiko-geth/issues/399)) ([3da62a2](https://github.com/RogerLamTd/taiko-geth/commit/3da62a24383c27c7bdda8ae9e68586e22a97ee87))
* **taiko_genesis:** update devnet genesis JSON ([#341](https://github.com/RogerLamTd/taiko-geth/issues/341)) ([50f97ba](https://github.com/RogerLamTd/taiko-geth/commit/50f97ba6835058036536a0ba669c232186cf5b7b))
* **taiko_genesis:** update devnet genesis JSONs ([#383](https://github.com/RogerLamTd/taiko-geth/issues/383)) ([a3e2b34](https://github.com/RogerLamTd/taiko-geth/commit/a3e2b34b4857d4b37c54ecd1f6bbac2ce8f6836a))
* **taiko_genesis:** update genesis block configs ([#304](https://github.com/RogerLamTd/taiko-geth/issues/304)) ([062d4b7](https://github.com/RogerLamTd/taiko-geth/commit/062d4b71f94ebf663a1f3045b432847199be6e82))
* **taiko_genesis:** update genesis JSON ([#344](https://github.com/RogerLamTd/taiko-geth/issues/344)) ([699e2d9](https://github.com/RogerLamTd/taiko-geth/commit/699e2d938c9092f3625ad5db10bae61cd8849e47))
* **taiko_genesis:** update genesis JSONs ([#233](https://github.com/RogerLamTd/taiko-geth/issues/233)) ([68308e3](https://github.com/RogerLamTd/taiko-geth/commit/68308e37810e3a16e443ffa84e5f1c33327b580e))
* **taiko_genesis:** update genesis JSONs ([#236](https://github.com/RogerLamTd/taiko-geth/issues/236)) ([471db71](https://github.com/RogerLamTd/taiko-geth/commit/471db7166393f7413fbe21b1df0971bf45ca774a))
* **taiko_genesis:** update genesis JSONs ([#246](https://github.com/RogerLamTd/taiko-geth/issues/246)) ([dcb6c4e](https://github.com/RogerLamTd/taiko-geth/commit/dcb6c4e978ad96cbad52148993a5b392d36214c4))
* **taiko_genesis:** update genesis JSONs ([#247](https://github.com/RogerLamTd/taiko-geth/issues/247)) ([9efa13f](https://github.com/RogerLamTd/taiko-geth/commit/9efa13f84a2cceaf21ef7add73f950ebc2b70316))
* **taiko_genesis:** update genesis JSONs ([#248](https://github.com/RogerLamTd/taiko-geth/issues/248)) ([ac9ccc8](https://github.com/RogerLamTd/taiko-geth/commit/ac9ccc8caffd5d38a37c0446d29fabd201ec8297))
* **taiko_genesis:** update genesis JSONs ([#253](https://github.com/RogerLamTd/taiko-geth/issues/253)) ([91be6dd](https://github.com/RogerLamTd/taiko-geth/commit/91be6dd14ac84ebebfcaf4efcecc3ae261e3de4d))
* **taiko_genesis:** update genesis JSONs ([#254](https://github.com/RogerLamTd/taiko-geth/issues/254)) ([7874437](https://github.com/RogerLamTd/taiko-geth/commit/78744374c1c009c5fde6382d6a8fd571f541eb61))
* **taiko_genesis:** update genesis JSONs ([#298](https://github.com/RogerLamTd/taiko-geth/issues/298)) ([2134337](https://github.com/RogerLamTd/taiko-geth/commit/21343370352005e02db1c7d7eeeb51bb0d9f3bce))
* **taiko_genesis:** update genesis JSONs ([#301](https://github.com/RogerLamTd/taiko-geth/issues/301)) ([c65e9b9](https://github.com/RogerLamTd/taiko-geth/commit/c65e9b9a95c4a315a186c2d77a96ffc9778f3e9a))
* **taiko_genesis:** update genesis JSONs ([#307](https://github.com/RogerLamTd/taiko-geth/issues/307)) ([b5ac526](https://github.com/RogerLamTd/taiko-geth/commit/b5ac526d9a0707e5dfcf0b8e5941d4f0bb770d26))
* **taiko_genesis:** update genesis JSONs ([#347](https://github.com/RogerLamTd/taiko-geth/issues/347)) ([fdd905a](https://github.com/RogerLamTd/taiko-geth/commit/fdd905ad9d7eb0bf2aa1c0235cc36f5bf1ad412d))
* **taiko_genesis:** update genesis JSONs ([#359](https://github.com/RogerLamTd/taiko-geth/issues/359)) ([594cdab](https://github.com/RogerLamTd/taiko-geth/commit/594cdabbdb5bd53aade9cb447ad6b171b180671e))
* **taiko_genesis:** update genesis JSONs ([#360](https://github.com/RogerLamTd/taiko-geth/issues/360)) ([5ef7421](https://github.com/RogerLamTd/taiko-geth/commit/5ef74219ab7df769e01d5521f34b5934444e5444))
* **taiko:** release 1.0.0 ([#251](https://github.com/RogerLamTd/taiko-geth/issues/251)) ([f2d2957](https://github.com/RogerLamTd/taiko-geth/commit/f2d2957421cdedfa956b65939847a4151b8dd8b5))
* **taiko:** release 1.1.0 ([#260](https://github.com/RogerLamTd/taiko-geth/issues/260)) ([67b74ce](https://github.com/RogerLamTd/taiko-geth/commit/67b74ce05576ad34f48dbd49b481238a7e54e149))
* **taiko:** release 1.10.0 ([#319](https://github.com/RogerLamTd/taiko-geth/issues/319)) ([92f5d06](https://github.com/RogerLamTd/taiko-geth/commit/92f5d06dc2f5e44038b49b3fff40427c03a3e293))
* **taiko:** release 1.11.0 ([#331](https://github.com/RogerLamTd/taiko-geth/issues/331)) ([3229807](https://github.com/RogerLamTd/taiko-geth/commit/3229807585f16e6858f08e415a0a874881843f02))
* **taiko:** release 1.11.1 ([#334](https://github.com/RogerLamTd/taiko-geth/issues/334)) ([467c93e](https://github.com/RogerLamTd/taiko-geth/commit/467c93e79802e61e6489b7080f76f21ccb5b19f1))
* **taiko:** release 1.12.0 ([#346](https://github.com/RogerLamTd/taiko-geth/issues/346)) ([02597d7](https://github.com/RogerLamTd/taiko-geth/commit/02597d73f9c012caea5d55c69e09c530be499091))
* **taiko:** release 1.13.0 ([#376](https://github.com/RogerLamTd/taiko-geth/issues/376)) ([55a75b6](https://github.com/RogerLamTd/taiko-geth/commit/55a75b6d207cdc6393aa79c4557702fe7427f774))
* **taiko:** release 1.14.0 ([#401](https://github.com/RogerLamTd/taiko-geth/issues/401)) ([53531d9](https://github.com/RogerLamTd/taiko-geth/commit/53531d9614cab58bbc6cbcb02cd9b970374895a0))
* **taiko:** release 1.2.0 ([#265](https://github.com/RogerLamTd/taiko-geth/issues/265)) ([8bd80e4](https://github.com/RogerLamTd/taiko-geth/commit/8bd80e422f02bdef240768331ef173df47aa2088))
* **taiko:** release 1.3.0 ([#271](https://github.com/RogerLamTd/taiko-geth/issues/271)) ([b93ef66](https://github.com/RogerLamTd/taiko-geth/commit/b93ef66540676dd6ad6e69ff4b2cc39a7dc9cef1))
* **taiko:** release 1.4.0 ([#275](https://github.com/RogerLamTd/taiko-geth/issues/275)) ([47893ae](https://github.com/RogerLamTd/taiko-geth/commit/47893aead41c29d1cd14eec3df30f5e44cc5f55e))
* **taiko:** release 1.5.0 ([#284](https://github.com/RogerLamTd/taiko-geth/issues/284)) ([4954004](https://github.com/RogerLamTd/taiko-geth/commit/4954004f4e2964d46f89d36b04af721168ca40c1))
* **taiko:** release 1.6.0 ([#286](https://github.com/RogerLamTd/taiko-geth/issues/286)) ([80e3cb4](https://github.com/RogerLamTd/taiko-geth/commit/80e3cb427a03823c6e153bb72a077619b3700ca2))
* **taiko:** release 1.6.1 ([#303](https://github.com/RogerLamTd/taiko-geth/issues/303)) ([5b4a961](https://github.com/RogerLamTd/taiko-geth/commit/5b4a9619f95a40395d23f25274450949a363dd32))
* **taiko:** release 1.7.0 ([#306](https://github.com/RogerLamTd/taiko-geth/issues/306)) ([50da615](https://github.com/RogerLamTd/taiko-geth/commit/50da61542536b03e76ea6e88d2c8548092c53681))
* **taiko:** release 1.8.0 ([#310](https://github.com/RogerLamTd/taiko-geth/issues/310)) ([c29e304](https://github.com/RogerLamTd/taiko-geth/commit/c29e3043e451e28ce10942f4f371942d30bc1fd3))
* **taiko:** release 1.9.0 ([#317](https://github.com/RogerLamTd/taiko-geth/issues/317)) ([89b85fb](https://github.com/RogerLamTd/taiko-geth/commit/89b85fb4b27ebca3d4811f1ec8dd3cce458ec4c1))


### Documentation

* fix badge in README ([#28796](https://github.com/RogerLamTd/taiko-geth/issues/28796)) ([5c2de7f](https://github.com/RogerLamTd/taiko-geth/commit/5c2de7fcbebe3aa7ea3a00414038a604067a4ef4))
* remove reference to being official ([#28858](https://github.com/RogerLamTd/taiko-geth/issues/28858)) ([6a724b9](https://github.com/RogerLamTd/taiko-geth/commit/6a724b94db95a58fae772c389e379bb38ed5b93c))


### Code Refactoring

* **accounts/abi:** use embed pkg to split default template to file ([5c84a20](https://github.com/RogerLamTd/taiko-geth/commit/5c84a20827473cbe60ed16827df21b4ad395c9c2))
* improve readability of NewMethod print ([db7895d](https://github.com/RogerLamTd/taiko-geth/commit/db7895d3b6e449cd4be6b5dbbd921979612f0d5f))


### Workflow

* add release please and remove old workflow ([#250](https://github.com/RogerLamTd/taiko-geth/issues/250)) ([d5f5f19](https://github.com/RogerLamTd/taiko-geth/commit/d5f5f191b689570672435aadb152d65b1ce5412a))
* add taiko-kitty bot ([#256](https://github.com/RogerLamTd/taiko-geth/issues/256)) ([8152c90](https://github.com/RogerLamTd/taiko-geth/commit/8152c90c4fb9487d331376a66b9724a8029abd04))
* disable lint on travis ([#28706](https://github.com/RogerLamTd/taiko-geth/issues/28706)) ([435bed5](https://github.com/RogerLamTd/taiko-geth/commit/435bed5da04a386198ca25c5e1264330c7a0da5b))


### Build

* add support for ubuntu 23.10 (mantic minotaur) ([#28728](https://github.com/RogerLamTd/taiko-geth/issues/28728)) ([76a5474](https://github.com/RogerLamTd/taiko-geth/commit/76a5474b3245ef07cdeaaaeed298b0101bea246b))
* **deps:** bump golang.org/x/crypto from 0.15.0 to 0.17.0 ([#28702](https://github.com/RogerLamTd/taiko-geth/issues/28702)) ([0cc192b](https://github.com/RogerLamTd/taiko-geth/commit/0cc192bd3a89cae6d3c2a787b9265dda631d6529))
* fix hash for go1.23.0.linux-riscv64.tar.gz ([5c84a20](https://github.com/RogerLamTd/taiko-geth/commit/5c84a20827473cbe60ed16827df21b4ad395c9c2))
* fix problem with windows line-endings in CI download ([#28900](https://github.com/RogerLamTd/taiko-geth/issues/28900)) ([3adf1ce](https://github.com/RogerLamTd/taiko-geth/commit/3adf1cecf203e9506d6ef87147693de4087e7d97)), closes [#28890](https://github.com/RogerLamTd/taiko-geth/issues/28890)
* fix typo in comment ([#28800](https://github.com/RogerLamTd/taiko-geth/issues/28800)) ([7280a5b](https://github.com/RogerLamTd/taiko-geth/commit/7280a5b31a6e385b54e006ee476b76bfdbbde744))
* make linter emit output ([#28704](https://github.com/RogerLamTd/taiko-geth/issues/28704)) ([952b343](https://github.com/RogerLamTd/taiko-geth/commit/952b343cb3d319b77076ef3acb60e29e04cd51fd))
* move version-info into checksum file ([#28324](https://github.com/RogerLamTd/taiko-geth/issues/28324)) ([ed5da55](https://github.com/RogerLamTd/taiko-geth/commit/ed5da55149c8df2420a262ec20cbc2edd3004aea))
* remove ubuntu 'lunar' build ([#28962](https://github.com/RogerLamTd/taiko-geth/issues/28962)) ([f0c5b67](https://github.com/RogerLamTd/taiko-geth/commit/f0c5b6765d1815a3c6a0cd1b2740607a8b5bb1f8))
* upgrade -dlgo version to Go 1.21.4 ([#28505](https://github.com/RogerLamTd/taiko-geth/issues/28505)) ([49b2c5f](https://github.com/RogerLamTd/taiko-geth/commit/49b2c5f43c00b12f345182096f12b25f6599786a))
* upgrade -dlgo version to Go 1.21.5 ([#28648](https://github.com/RogerLamTd/taiko-geth/issues/28648)) ([77c4bbc](https://github.com/RogerLamTd/taiko-geth/commit/77c4bbcaa5f554f4cd73bdb7033d17b1fec493e9))
* upgrade -dlgo version to Go 1.21.6 ([#28836](https://github.com/RogerLamTd/taiko-geth/issues/28836)) ([4c8d92d](https://github.com/RogerLamTd/taiko-geth/commit/4c8d92d30342ccaa839ca590bafd5bfe5ca8c130))
* upgrade to golangci-lint v1.55.2 ([#28712](https://github.com/RogerLamTd/taiko-geth/issues/28712)) ([8c2d455](https://github.com/RogerLamTd/taiko-geth/commit/8c2d455ccd216fb8589c15339392ce9640d8090d))

## [1.13.0](https://github.com/taikoxyz/taiko-geth/compare/v1.12.0...v1.13.0) (2025-03-15)


### Features

* **consensus:** introduce `AnchorV3GasLimit` ([#378](https://github.com/taikoxyz/taiko-geth/issues/378)) ([a0b97be](https://github.com/taikoxyz/taiko-geth/commit/a0b97be30cc01a93cebbd2d7188d28b0dcc5989a))
* **consensus:** introduce cache for the payloads ([#380](https://github.com/taikoxyz/taiko-geth/issues/380)) ([36430eb](https://github.com/taikoxyz/taiko-geth/commit/36430eb4f53a1455eb331f58c3ad2e88d8f40ecf))
* **consensus:** update `TaikoAnchor.anchorV3` selector ([#379](https://github.com/taikoxyz/taiko-geth/issues/379)) ([1e948cf](https://github.com/taikoxyz/taiko-geth/commit/1e948cff4c83e7a5cb0d8a4db27cbe59ce2a8884))
* **core:** align the upstream `types.Header` ([#393](https://github.com/taikoxyz/taiko-geth/issues/393)) ([573f8fc](https://github.com/taikoxyz/taiko-geth/commit/573f8fc144670d7221b387661f1f18dcd0935fe1))
* **eth:** changes based on protocol `Pacaya` fork ([#367](https://github.com/taikoxyz/taiko-geth/issues/367)) ([7bf5c0d](https://github.com/taikoxyz/taiko-geth/commit/7bf5c0d259f60f9d62d481c873053548c87b6fb5))
* **miner:** use `[]*ethapi.RPCTransaction` in RPC response body ([#391](https://github.com/taikoxyz/taiko-geth/issues/391)) ([afd09af](https://github.com/taikoxyz/taiko-geth/commit/afd09afd03871f9c66231a92bba706f4c491b877))
* **repo:** `go-ethereum` v1.15.5 upstream merge  ([#395](https://github.com/taikoxyz/taiko-geth/issues/395)) ([364acd0](https://github.com/taikoxyz/taiko-geth/commit/364acd00d1f2b45a07b7b1d20ec9b0f77be50b91))
* **repo:** add do-not-merge and rename files ([#390](https://github.com/taikoxyz/taiko-geth/issues/390)) ([3792f93](https://github.com/taikoxyz/taiko-geth/commit/3792f9356bfdc391fc8e112fccc7bf31d9edbb63))
* **taiko_genesis:** update devnet genesis JSONs for new `AnchorV3` method ([#382](https://github.com/taikoxyz/taiko-geth/issues/382)) ([2448fb9](https://github.com/taikoxyz/taiko-geth/commit/2448fb97a8b873c7bd7c0051cd83aaea339050e0))


### Bug Fixes

* **eth:** write `L1Origin` even if the payload is already in the cache ([#396](https://github.com/taikoxyz/taiko-geth/issues/396)) ([43a60b3](https://github.com/taikoxyz/taiko-geth/commit/43a60b36ea53a416ba01f271749d20f1251ce607))
