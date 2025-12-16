# [4.1.0](https://github.com/5e-bits/5e-database/compare/v4.0.0...v4.1.0) (2025-09-15)


### Features

* **2024:** Adding equipment and equipment categories ([#860](https://github.com/5e-bits/5e-database/issues/860)) ([15fb5eb](https://github.com/5e-bits/5e-database/commit/15fb5ebeb2eed406bd97e8ea566a67a59793b340))

# [4.0.0](https://github.com/5e-bits/5e-database/compare/v3.26.1...v4.0.0) (2025-09-04)


* refactor(race/subrace)!: remove redundant data ([#875](https://github.com/5e-bits/5e-database/issues/875)) ([67261fb](https://github.com/5e-bits/5e-database/commit/67261fbf4b1c5c785aeab47fbd4356c328b0593c)), closes [#874](https://github.com/5e-bits/5e-database/issues/874)


### BREAKING CHANGES

* dropped the `race.starting_proficiencies`,
`race.starting_proficiency_options`, `subrace.starting_proficiencies`,
`subrace.language_options`, and `subrace.languages` properties of all
races and subraces in the database. Clients can instead find this data
on the corresponding traits linked to each race or subrace.

## How was it tested?

I ran the database + API project locally with Docker and called the
endpoints of the various classes and subclasses. I also ran the unit and
integration tests in the API project.

## Is there a Github issue this is resolving?

## [5.0.0](https://github.com/jereimers/5e-database/compare/v4.2.1...v5.0.0) (2025-12-16)


### ⚠ BREAKING CHANGES

* **race/subrace:** dropped the `race.starting_proficiencies`, `race.starting_proficiency_options`, `subrace.starting_proficiencies`, `subrace.language_options`, and `subrace.languages` properties of all races and subraces in the database. Clients can instead find this data on the corresponding traits linked to each race or subrace.
* Add Monster Armor Types
* **choice structure:** Choice structure reform

### Features

* :sparkles: add monster proficiency_bonus field ([#551](https://github.com/jereimers/5e-database/issues/551)) ([eb90424](https://github.com/jereimers/5e-database/commit/eb90424e10559c36b8898d0b5afbb63bade58343)), closes [#550](https://github.com/jereimers/5e-database/issues/550)
* (src/5e-SRD-Monsters.json): added modifiers to hit dice ([#500](https://github.com/jereimers/5e-database/issues/500)) ([11cedaa](https://github.com/jereimers/5e-database/commit/11cedaad2cff0a58de2c3aa8869626c6e285a4be))
* **2014:** Start versioning ([#762](https://github.com/jereimers/5e-database/issues/762)) ([63c7069](https://github.com/jereimers/5e-database/commit/63c7069e5d2c932a6b1853e83e743acbb4e19f17))
* **2024:** Add 2024 ability scores and skills tables ([#815](https://github.com/jereimers/5e-database/issues/815)) ([d7dcadc](https://github.com/jereimers/5e-database/commit/d7dcadca05f3ea7cc0e23b5a9cebbb72bf41834e))
* **2024:** Add a bunch of easy tables to 2024 ([#856](https://github.com/jereimers/5e-database/issues/856)) ([40ec703](https://github.com/jereimers/5e-database/commit/40ec703049aadb25607e44843c9afcafd5ce1b86))
* **2024:** Adding equipment and equipment categories ([#860](https://github.com/jereimers/5e-database/issues/860)) ([15fb5eb](https://github.com/jereimers/5e-database/commit/15fb5ebeb2eed406bd97e8ea566a67a59793b340))
* add enemy type options to Favored Enemy features ([#795](https://github.com/jereimers/5e-database/issues/795)) ([76aa1ed](https://github.com/jereimers/5e-database/commit/76aa1edb597868057985fed5d3a91d374620c8f0))
* Add magic item attunement, wielding, and activation rules ([#527](https://github.com/jereimers/5e-database/issues/527)) ([ca88bd6](https://github.com/jereimers/5e-database/commit/ca88bd65506171ee6b00f88be7479e5222064beb))
* Add magic item attunment, wielding, and activation rules ([ca88bd6](https://github.com/jereimers/5e-database/commit/ca88bd65506171ee6b00f88be7479e5222064beb))
* Add Monster Armor Types ([#518](https://github.com/jereimers/5e-database/issues/518)) ([b7bf853](https://github.com/jereimers/5e-database/commit/b7bf85367b033bc45e3c80adfcd6fb327995e4e2))
* Add size and shape to dragonborn's breath weapon ([#495](https://github.com/jereimers/5e-database/issues/495)) ([94799a6](https://github.com/jereimers/5e-database/commit/94799a6084a400218785c06852fc56afc4b095b3))
* add terrain type options to Natural Explorer features ([#794](https://github.com/jereimers/5e-database/issues/794)) ([d2620b8](https://github.com/jereimers/5e-database/commit/d2620b8c1989dc7e55e62915025648d4ccd7fb99))
* Add the first image ([#506](https://github.com/jereimers/5e-database/issues/506)) ([c653e3a](https://github.com/jereimers/5e-database/commit/c653e3a368a605fdd9f84fbbc9ec2f89b6669e05))
* **all:** Add `updated_at` to all entities ([#763](https://github.com/jereimers/5e-database/issues/763)) ([e99ed09](https://github.com/jereimers/5e-database/commit/e99ed09d4c8eb4c85af0f18aa380f7d9fa04501c))
* **db:** Refactor dbRefresh and add dbUpdate ([#810](https://github.com/jereimers/5e-database/issues/810)) ([7c1ad44](https://github.com/jereimers/5e-database/commit/7c1ad44ba8efca57dcd40c5cb26523cb045c923c))
* **deployment:** Add Semantic Release for auto-release ([#456](https://github.com/jereimers/5e-database/issues/456)) ([7e4ed56](https://github.com/jereimers/5e-database/commit/7e4ed56e0175e7a1085609449c646486ac5e6899))
* **images:** Add a few more magic item images ([cb0d4cc](https://github.com/jereimers/5e-database/commit/cb0d4cc79472f1295c03f91e031121f71251b94e))
* **images:** All remaining monster images ([4805d07](https://github.com/jereimers/5e-database/commit/4805d07e433cd2fa4be82990bfe434ef40843086))
* **images:** Cultist to Druid ([92d2db9](https://github.com/jereimers/5e-database/commit/92d2db94de4a4fae89a8aa99804759c0487bcd54))
* **images:** Duergar to Ghost ([2460333](https://github.com/jereimers/5e-database/commit/24603330712099ea478a61c9924a262d43a06fb2))
* **images:** Ghoul to Hell Hound ([7061e7f](https://github.com/jereimers/5e-database/commit/7061e7f0237527de06c46426ab965595faa75fdf))
* **images:** Hezrou to Manticore, Warhorse Skeleton, and Werebear to White Dragon Wyrmling ([3f54cae](https://github.com/jereimers/5e-database/commit/3f54caeacceeb38b351424cbc7f6653b926c6ae4))
* **images:** Moar images for equipment, magic items, and monsters ([#817](https://github.com/jereimers/5e-database/issues/817)) ([6b69426](https://github.com/jereimers/5e-database/commit/6b69426052b7015db2dca276e987dadae0443b20))
* **images:** Redirect image urls to new image urls ([#826](https://github.com/jereimers/5e-database/issues/826)) ([be7e6aa](https://github.com/jereimers/5e-database/commit/be7e6aad5c66e588af81730ead77480b0925720b))
* **language:** Add language options to extra language feat ([#494](https://github.com/jereimers/5e-database/issues/494)) ([6268398](https://github.com/jereimers/5e-database/commit/626839812c0beb7a5c2eaa0bea1f1c2e34eeb9c6))
* **magic-items:** Add first magic item image ([#636](https://github.com/jereimers/5e-database/issues/636)) ([0d62f81](https://github.com/jereimers/5e-database/commit/0d62f819163622919b81bfea96ae9f835916e9bd))
* **magic-items:** add rarity to magic items ([#455](https://github.com/jereimers/5e-database/issues/455)) ([db36b74](https://github.com/jereimers/5e-database/commit/db36b74e525e818c444ab6584f78198f230149e0))
* **magic-items:** Add some images for A-Bead ([c057995](https://github.com/jereimers/5e-database/commit/c05799569a2268d9baf4f7d300e03965037b6d1e))
* **magic-items:** Images for Boots of striding and sprinting to Deck of Illusions ([46155eb](https://github.com/jereimers/5e-database/commit/46155ebea6594ef9864dfd329bb45b63668b4c8e))
* **magic-items:** Images for Deck of Many Things to Elemental Gems ([1936368](https://github.com/jereimers/5e-database/commit/19363688c37cff32175f8784a54bbcf3182924ed))
* **monster:** add flavor text where available ([#488](https://github.com/jereimers/5e-database/issues/488)) ([2015ebd](https://github.com/jereimers/5e-database/commit/2015ebd3158626a2265e19fdf3a0d37f8bd4914a))
* **monsters:** Add images for ancient, adult, and young dragons ([#635](https://github.com/jereimers/5e-database/issues/635)) ([28b92cf](https://github.com/jereimers/5e-database/commit/28b92cfb37a3cd33a6c44ba9dd77caf66ad1c2de))
* **monsters:** Add more images ([02ce19a](https://github.com/jereimers/5e-database/commit/02ce19a2e05b5176d3e25c4f09569f9f31c49c36))
* **monsters:** Add more monster images ([#715](https://github.com/jereimers/5e-database/issues/715)) ([9410977](https://github.com/jereimers/5e-database/commit/9410977d8b5710d8cec9daa47e4b399689acb432))
* **node:** Upgrade to Node 20 ([#581](https://github.com/jereimers/5e-database/issues/581)) ([c3407cd](https://github.com/jereimers/5e-database/commit/c3407cd45973acba9ca04855a51ab4e354a1567a))
* Redo Warlock Eldritch Invocations ([#498](https://github.com/jereimers/5e-database/issues/498)) ([34de23b](https://github.com/jereimers/5e-database/commit/34de23b53a3f508440ef26e9e47158d163402fa9))
* release docker image to github container registry ([#451](https://github.com/jereimers/5e-database/issues/451)) ([dcc8bd6](https://github.com/jereimers/5e-database/commit/dcc8bd6ead9771b9cb5302c9f40094efd39634a7))
* **release:** Now create CHANGELOG.md and npm version bump with semantic release ([935a3c6](https://github.com/jereimers/5e-database/commit/935a3c6dce3b7197b563b8f0be279670ba0f4076))
* **release:** Remove PAT dependency ([#818](https://github.com/jereimers/5e-database/issues/818)) ([aefc47e](https://github.com/jereimers/5e-database/commit/aefc47eb420b58a3b746d68148a5ce93073cf627))
* **release:** Swap to release-please ([#934](https://github.com/jereimers/5e-database/issues/934)) ([bf73da0](https://github.com/jereimers/5e-database/commit/bf73da05f0a5044ca43db789d0871f351fde6ddd))
* Removing a wrong space. ([#756](https://github.com/jereimers/5e-database/issues/756)) ([abacd5a](https://github.com/jereimers/5e-database/commit/abacd5ae46b36073897d97121afac087c6948422))
* upgrade eslint to v9.15 ([#753](https://github.com/jereimers/5e-database/issues/753)) ([7169b60](https://github.com/jereimers/5e-database/commit/7169b601017f21e6b170d526e4c746ae259cb4d6))


### Bug Fixes

* :bug: cleric spell list includes Animal Friendship ([#555](https://github.com/jereimers/5e-database/issues/555)) ([8c55edc](https://github.com/jereimers/5e-database/commit/8c55edcd6b3944c12d5dc226c9ef64487e1266ee))
* :bug: duplicate "blinded" condition in Black Pudding immunities ([#549](https://github.com/jereimers/5e-database/issues/549)) ([4857e65](https://github.com/jereimers/5e-database/commit/4857e6543bd5d950b6b64d1222f367dd6d5b8edd))
* :bug: make urls in 2014 data to point to `/api/2014` endpoint ([#784](https://github.com/jereimers/5e-database/issues/784)) ([0cf4a6c](https://github.com/jereimers/5e-database/commit/0cf4a6cda9936f76b78fc1497ec980468fe9ff1b))
* :bug: make urls in 2014 data to point to the new `/api/2014` endpoint ([0cf4a6c](https://github.com/jereimers/5e-database/commit/0cf4a6cda9936f76b78fc1497ec980468fe9ff1b))
* **5e-SRD-Monsters.json:** small inconsistencies ([#598](https://github.com/jereimers/5e-database/issues/598)) ([3e6ce8e](https://github.com/jereimers/5e-database/commit/3e6ce8e820882dd187d6d7e393d34533c863f1e9))
* Add axe beak image ([f4104e9](https://github.com/jereimers/5e-database/commit/f4104e9bf706213173c0aca26a9668e8eeb9ada6))
* Add black dragon images for [@fergcb](https://github.com/fergcb) ([5bc92f1](https://github.com/jereimers/5e-database/commit/5bc92f186cabcc113247bf73958755646665e963))
* Add dc to ray of enfeeblement ([#516](https://github.com/jereimers/5e-database/issues/516)) ([0580dc0](https://github.com/jereimers/5e-database/commit/0580dc076f802f0dcf422fef4f9c5cce8c579b53))
* Add druid class to poison spray class list ([#554](https://github.com/jereimers/5e-database/issues/554)) ([26086c7](https://github.com/jereimers/5e-database/commit/26086c7ec4610a34f30a0d8d5fda1cfd90449dc1))
* Add earth elemental image ([99eb491](https://github.com/jereimers/5e-database/commit/99eb491acbd96ae4c25d8da9a360e0d2d45ee241))
* Add higher slot level damage to Hellish Rebuke ([#540](https://github.com/jereimers/5e-database/issues/540)) ([59690fd](https://github.com/jereimers/5e-database/commit/59690fd66ad75ad048c470eecd4e7405dfabda37))
* Add image for Air Elemental ([13d4416](https://github.com/jereimers/5e-database/commit/13d44163088089e61164610d1e019de051875ab2))
* Add image of crocodile ([da2d83a](https://github.com/jereimers/5e-database/commit/da2d83a5e5d02ea1662a67ee28539e677a03195a))
* Add images for assassin, awakend shrub, and awakened tree ([e1cdb53](https://github.com/jereimers/5e-database/commit/e1cdb53f13a45a645b87fcf48f828fdfd14cd726))
* Add in images for water elemental, warhorse, and weasel ([28deb9a](https://github.com/jereimers/5e-database/commit/28deb9a5702c3b2dad255be47dcf48311e22498b))
* Add mimic image ([86fc079](https://github.com/jereimers/5e-database/commit/86fc079f90fd8b3a887beda9b7513d7bcddbf9e2))
* Add some images for monsters ([#507](https://github.com/jereimers/5e-database/issues/507)) ([c520a1c](https://github.com/jereimers/5e-database/commit/c520a1ce1e01fcdeb8f218aac9a75ac052b30b77))
* Add subclass improvements to level features ([#836](https://github.com/jereimers/5e-database/issues/836)) ([0907a8a](https://github.com/jereimers/5e-database/commit/0907a8a18d7d92b8ba91d23e0c076d0598caebc8))
* Add usage dict to recharge 6 actions ([#526](https://github.com/jereimers/5e-database/issues/526)) ([cf829b5](https://github.com/jereimers/5e-database/commit/cf829b5f4b3017d532fb36910f71cbbc59a12bb2))
* Blowgun damage (1d1 -&gt; 1) ([#522](https://github.com/jereimers/5e-database/issues/522)) ([ff2b34b](https://github.com/jereimers/5e-database/commit/ff2b34b331769ff4f18afb8ad46d255c5d86de60))
* Bone Devil CR, XP, passive perception ([#531](https://github.com/jereimers/5e-database/issues/531)) ([dab45db](https://github.com/jereimers/5e-database/commit/dab45db3bf4bedef60f6386d6a3ce2b559f42b90))
* Change Eldritch Blast damage to match Magic Missile ([#539](https://github.com/jereimers/5e-database/issues/539)) ([9171b22](https://github.com/jereimers/5e-database/commit/9171b2268c0f780c4ab7d58f447482e3f00e567b))
* Changed instances of Weapon Attack to Melee Weapon Attack ([#523](https://github.com/jereimers/5e-database/issues/523)) ([7884c29](https://github.com/jereimers/5e-database/commit/7884c2902013667a42e7ca7dc6e3b79c506faf64))
* **ci:** Bump ci node versions as well ([#583](https://github.com/jereimers/5e-database/issues/583)) ([3eb6886](https://github.com/jereimers/5e-database/commit/3eb6886479a56220a6e294890ffe82c8c131284c))
* **ci:** Revert "fix(ci): Upgrade to v4 correctly for Semantic Release action ([#585](https://github.com/jereimers/5e-database/issues/585))" ([602ce9f](https://github.com/jereimers/5e-database/commit/602ce9f71e6f072c9611fa709ae0f6efa0d2da8f))
* **ci:** revert action version ([#584](https://github.com/jereimers/5e-database/issues/584)) ([edb44a9](https://github.com/jereimers/5e-database/commit/edb44a9770d6992a1f440ed05d7d65b2af4603b3))
* **ci:** Set correct repo url ([13b7175](https://github.com/jereimers/5e-database/commit/13b7175a00414837ccc6ce60885f564a75befcf3))
* **ci:** Upgrade to v4 correctly for Semantic Release action ([#585](https://github.com/jereimers/5e-database/issues/585)) ([1339490](https://github.com/jereimers/5e-database/commit/1339490e5d5bf7ad8bace5a75f758a158e2bcc32))
* Damage issue raised in Discord ([#505](https://github.com/jereimers/5e-database/issues/505)) ([4a532ba](https://github.com/jereimers/5e-database/commit/4a532ba125bd9b84025ed9282f1fbe6569d72995))
* **dependabot:** use build instead of deps ([#941](https://github.com/jereimers/5e-database/issues/941)) ([782da71](https://github.com/jereimers/5e-database/commit/782da71224510f0118de187c7f7431bf2780f616))
* **deploy:** Fix Semantic release deployment ([#582](https://github.com/jereimers/5e-database/issues/582)) ([922f87d](https://github.com/jereimers/5e-database/commit/922f87d543736aa02a059cc3ae4fb00fd07a8a05))
* **docker:** also copy package-lock.json before install ([#461](https://github.com/jereimers/5e-database/issues/461)) ([20fd832](https://github.com/jereimers/5e-database/commit/20fd832216bf3be86053ff9dc9076e86f66b164c))
* Edit content with rule changes and typographical fixes from SRD 5.1  ([#529](https://github.com/jereimers/5e-database/issues/529)) ([4908e91](https://github.com/jereimers/5e-database/commit/4908e91ed1a07277b8502aa08788f335b457fe68))
* **ghost horrifying visage:** times years, not plus ([#472](https://github.com/jereimers/5e-database/issues/472)) ([906e6c2](https://github.com/jereimers/5e-database/commit/906e6c25573c05043161f2bed56f072d90903cc5))
* Giant Centipede xp ([#520](https://github.com/jereimers/5e-database/issues/520)) ([e39d874](https://github.com/jereimers/5e-database/commit/e39d8740084e611b8777db136dc56886623024f2))
* **git:** Empty commit to remake version 3.3.1 ([e9f769d](https://github.com/jereimers/5e-database/commit/e9f769d605e2f6ee4434e8263c37eb954b504337))
* Give oath of devotion correct channel divinity ([#499](https://github.com/jereimers/5e-database/issues/499)) ([cc30498](https://github.com/jereimers/5e-database/commit/cc30498d2b183a1fd435c461a8e0087dc1aae465))
* Image for animated armor ([e6c4237](https://github.com/jereimers/5e-database/commit/e6c42370d6c0dd0f38b1764325ba7b1ffee98971))
* **image:** Fix image key for black dragon wyrmling thanks to @DMcCallion ([#547](https://github.com/jereimers/5e-database/issues/547)) ([cff5a1b](https://github.com/jereimers/5e-database/commit/cff5a1b1ecd78145e64c6873f4e3b9e491da63d9))
* Images for aboleth, acolyte, ankheg, ape, and archmage ([c50486e](https://github.com/jereimers/5e-database/commit/c50486ef2df779c6e7f7a70ec0ac9c0d164e26f8))
* **images:** Add image for Grick ([cf5105d](https://github.com/jereimers/5e-database/commit/cf5105d99637a0e89480b7bca8a6d08e934bd2bf))
* Lock MongoDB Docker version ([#504](https://github.com/jereimers/5e-database/issues/504)) ([774a8ae](https://github.com/jereimers/5e-database/commit/774a8aeb352de87e38e0b2b36f7ca737970989c0))
* **magic-item:** Add image to the correct magic item ([#714](https://github.com/jereimers/5e-database/issues/714)) ([c6a742f](https://github.com/jereimers/5e-database/commit/c6a742f5300012146b54f086fe1a5ab25d85d0de))
* **monster actions:** Remove whitespace in action description text co… ([#560](https://github.com/jereimers/5e-database/issues/560)) ([033d589](https://github.com/jereimers/5e-database/commit/033d5892f01075200d4df58af2b4235dade89cf9))
* **monster actions:** Remove whitespace in action description text concerning ranges ([033d589](https://github.com/jereimers/5e-database/commit/033d5892f01075200d4df58af2b4235dade89cf9))
* Monster indentation should use spaces and not tabs ([24f2411](https://github.com/jereimers/5e-database/commit/24f24117e1f67fd1ef3588449f69cf5d7400c6e4))
* **monster:** add missing legendary resistance ([#482](https://github.com/jereimers/5e-database/issues/482)) ([04e2362](https://github.com/jereimers/5e-database/commit/04e2362a3feefca2e4abbe011a12847a65152b1f))
* **monster:** fix condition_immunities for Gelatinous Cube ([#464](https://github.com/jereimers/5e-database/issues/464)) ([256a727](https://github.com/jereimers/5e-database/commit/256a72718fd6a72c224b23ee8d5b098120c4d0d3))
* **monster:** Fixed prerequisite to reference correct spell ([#474](https://github.com/jereimers/5e-database/issues/474)) ([e1edacd](https://github.com/jereimers/5e-database/commit/e1edacdf81fa298ddc7115280186e152f8f05da4))
* **monster:** giant disesased rat special abilities ([#483](https://github.com/jereimers/5e-database/issues/483)) ([961f7e2](https://github.com/jereimers/5e-database/commit/961f7e28778ae7299f999766452c3aa16b97d12c))
* **monster:** innate spellcasting required components ([#479](https://github.com/jereimers/5e-database/issues/479)) ([63f17fa](https://github.com/jereimers/5e-database/commit/63f17faef7b07f73c0e8c967636885531258bbaf))
* **monster:** Lamia spells ([#477](https://github.com/jereimers/5e-database/issues/477)) ([f160c8a](https://github.com/jereimers/5e-database/commit/f160c8a06895c3d2fcb524cf1fabb9168ff0aecc))
* **monster:** Make vampire consistent with other shapechangers ([#473](https://github.com/jereimers/5e-database/issues/473)) ([4fd4bc0](https://github.com/jereimers/5e-database/commit/4fd4bc0e63a4e5a5bb5d99a2aad1b5c16260d4fc))
* **monster:** remove non-srd lair actions ([#481](https://github.com/jereimers/5e-database/issues/481)) ([8093f6e](https://github.com/jereimers/5e-database/commit/8093f6ef4e2b92600ee61899119a6e474d6598e5))
* **monster:** remove non-srd variants ([#480](https://github.com/jereimers/5e-database/issues/480)) ([7cd5575](https://github.com/jereimers/5e-database/commit/7cd55759775e070b45e4495228efb00a4314df3e))
* Monsters indent by 2 not 4 ([#514](https://github.com/jereimers/5e-database/issues/514)) ([7227b05](https://github.com/jereimers/5e-database/commit/7227b059e09a2e4e46158244c9143ab6e1400466))
* **monsters:** Change burrow speed for young-blue-dragon to 20 ft. (from 40 ft.) ([#632](https://github.com/jereimers/5e-database/issues/632)) ([2ca6e3c](https://github.com/jereimers/5e-database/commit/2ca6e3c3d9da39d00249644fb47c528453e933f5))
* **monsters:** Fix Badger damage type ([#562](https://github.com/jereimers/5e-database/issues/562)) ([d48372d](https://github.com/jereimers/5e-database/commit/d48372d430b58f6bf205334689864a654c509566))
* **monsters:** unnecessary attack bonus and OCR-related problem ([#811](https://github.com/jereimers/5e-database/issues/811)) ([1401043](https://github.com/jereimers/5e-database/commit/1401043eee8af76c6e19c771530c6d8565d1fa53))
* **monsters:** white spaces, OCR, etc. ([#816](https://github.com/jereimers/5e-database/issues/816)) ([30913dd](https://github.com/jereimers/5e-database/commit/30913dd4d4295f3017a148d3f9c3cb6ae2b49a9b))
* Move Traps, Diseases, Madness from Appendices to Adventuring ([#528](https://github.com/jereimers/5e-database/issues/528)) ([2abe3fb](https://github.com/jereimers/5e-database/commit/2abe3fbd41db23912edcd4d49621af6818996468))
* Normalize resistance/immunity/vulnerability strings ([#561](https://github.com/jereimers/5e-database/issues/561)) ([1e7fa28](https://github.com/jereimers/5e-database/commit/1e7fa28106f06a8932b6e1a0d2e2d430bb1aea1a))
* **npm:** Set to private so we don't publish to npm ([08e582a](https://github.com/jereimers/5e-database/commit/08e582a848e89c7cd79bd1373332d427c4413663))
* **npm:** Update npm lockfile ([9fdcf7d](https://github.com/jereimers/5e-database/commit/9fdcf7dd941856bfe042972598317573e7a8bcb9))
* Prereq type to be lower case ([7f64f39](https://github.com/jereimers/5e-database/commit/7f64f39d5c957987b60872ecce0554259bd61dc7))
* **release-please:** Include all commit types in changelog config ([c16433d](https://github.com/jereimers/5e-database/commit/c16433dbd7b1bdd500733da5e1efe8f6de9c27fc))
* **release:** Add release to .releaserc.json ([#458](https://github.com/jereimers/5e-database/issues/458)) ([e36f3ac](https://github.com/jereimers/5e-database/commit/e36f3ac663e395fb7f4e489bfc9de26d10a08c2d))
* **release:** fix .releaserc.json ([#459](https://github.com/jereimers/5e-database/issues/459)) ([fb89f40](https://github.com/jereimers/5e-database/commit/fb89f40708499cb27c4923ade3b1dacc823d5642))
* **release:** fix Dockerfile ([#460](https://github.com/jereimers/5e-database/issues/460)) ([f79bf4b](https://github.com/jereimers/5e-database/commit/f79bf4b17f25fdc1636d84769dbeaaa918a81bcf))
* **release:** Mirror changes from 5e-srd-api ([#462](https://github.com/jereimers/5e-database/issues/462)) ([d56743f](https://github.com/jereimers/5e-database/commit/d56743f7583f01611eb9c9584df73cb45086b590))
* Remove "s" from Sorcerous Origin subclass flavor ([#497](https://github.com/jereimers/5e-database/issues/497)) ([88329d8](https://github.com/jereimers/5e-database/commit/88329d8ca3132475d6231a4d1149ad8972931e11))
* Remove attack type from spells do not have one ([#512](https://github.com/jereimers/5e-database/issues/512)) ([ad98ce5](https://github.com/jereimers/5e-database/commit/ad98ce52bfed01b280fa5d6dfb49d67d9a06b80b))
* **rules:** travel pace table ([#492](https://github.com/jereimers/5e-database/issues/492)) ([52c62e4](https://github.com/jereimers/5e-database/commit/52c62e4162fc916421e5c17a2c2e651539a1e6e1))
* **saving throw:** Add saving throw proficiencies to class proficiencies ([#491](https://github.com/jereimers/5e-database/issues/491)) ([f9246fb](https://github.com/jereimers/5e-database/commit/f9246fbe5b6acc799d3b1bdb58eb4f46ceff7cca))
* Small spelling errors ([#525](https://github.com/jereimers/5e-database/issues/525)) ([5f61fed](https://github.com/jereimers/5e-database/commit/5f61fed0dbab17a3d8de4f70c843ca1b243651e2))
* Small spelling errors. ([5f61fed](https://github.com/jereimers/5e-database/commit/5f61fed0dbab17a3d8de4f70c843ca1b243651e2))
* **spells:** Fix spell classes ([#557](https://github.com/jereimers/5e-database/issues/557)) ([5554517](https://github.com/jereimers/5e-database/commit/5554517de2aa00f77a9e5037693394fcef384523))
* **spells:** fixed the shatter spell's description ([#502](https://github.com/jereimers/5e-database/issues/502)) ([16dd4b5](https://github.com/jereimers/5e-database/commit/16dd4b5d0592b52287f7c01b84f27b4594a901f6))
* **spell:** Spelling Error on Magic Circle ([#553](https://github.com/jereimers/5e-database/issues/553)) ([4be71ba](https://github.com/jereimers/5e-database/commit/4be71ba4917b3d0a8a5883419b9d6ac0196b0379))
* **trident:** change damage type to piercing ([#865](https://github.com/jereimers/5e-database/issues/865)) ([84c2fe6](https://github.com/jereimers/5e-database/commit/84c2fe653ecbfd9e51fb2755b922d17ce412889c))
* Update npm packages ([#471](https://github.com/jereimers/5e-database/issues/471)) ([9303387](https://github.com/jereimers/5e-database/commit/930338756c1f95368902661adafbcf7cfa565c34))
* **wand-of-wonder:** Fixed wand of wonder description table. ([#501](https://github.com/jereimers/5e-database/issues/501)) ([cbf6c70](https://github.com/jereimers/5e-database/commit/cbf6c70033a3a2cbebd657a03f0ea0ebdceef445))
* Workflow isn't releasing containers ([#493](https://github.com/jereimers/5e-database/issues/493)) ([ca8f539](https://github.com/jereimers/5e-database/commit/ca8f539be1fcc178a08cd788120b44bd93069fb4))


### Code Refactoring

* **choice structure:** Choice structure reform ([#465](https://github.com/jereimers/5e-database/issues/465)) ([19eb096](https://github.com/jereimers/5e-database/commit/19eb0962855808f42800df7cd7f416dc304d11f8))
* **race/subrace:** remove redundant data ([#875](https://github.com/jereimers/5e-database/issues/875)) ([67261fb](https://github.com/jereimers/5e-database/commit/67261fbf4b1c5c785aeab47fbd4356c328b0593c))

## [4.2.1](https://github.com/5e-bits/5e-database/compare/v4.2.0...v4.2.1) (2025-10-24)


### Bug Fixes

* **dependabot:** use build instead of deps ([#941](https://github.com/5e-bits/5e-database/issues/941)) ([782da71](https://github.com/5e-bits/5e-database/commit/782da71224510f0118de187c7f7431bf2780f616))

## [4.2.0](https://github.com/5e-bits/5e-database/compare/v4.1.0...v4.2.0) (2025-10-24)


### Features

* **release:** Swap to release-please ([#934](https://github.com/5e-bits/5e-database/issues/934)) ([bf73da0](https://github.com/5e-bits/5e-database/commit/bf73da05f0a5044ca43db789d0871f351fde6ddd))

## [3.26.1](https://github.com/5e-bits/5e-database/compare/v3.26.0...v3.26.1) (2025-06-30)


### Bug Fixes

* **trident:** change damage type to piercing ([#865](https://github.com/5e-bits/5e-database/issues/865)) ([84c2fe6](https://github.com/5e-bits/5e-database/commit/84c2fe653ecbfd9e51fb2755b922d17ce412889c))

# [3.26.0](https://github.com/5e-bits/5e-database/compare/v3.25.1...v3.26.0) (2025-06-13)


### Features

* **2024:** Add a bunch of easy tables to 2024 ([#856](https://github.com/5e-bits/5e-database/issues/856)) ([40ec703](https://github.com/5e-bits/5e-database/commit/40ec703049aadb25607e44843c9afcafd5ce1b86))

## [3.25.1](https://github.com/5e-bits/5e-database/compare/v3.25.0...v3.25.1) (2025-05-16)


### Bug Fixes

* Add subclass improvements to level features ([#836](https://github.com/5e-bits/5e-database/issues/836)) ([0907a8a](https://github.com/5e-bits/5e-database/commit/0907a8a18d7d92b8ba91d23e0c076d0598caebc8))

# [3.25.0](https://github.com/5e-bits/5e-database/compare/v3.24.0...v3.25.0) (2025-05-04)


### Features

* **images:** Redirect image urls to new image urls ([#826](https://github.com/5e-bits/5e-database/issues/826)) ([be7e6aa](https://github.com/5e-bits/5e-database/commit/be7e6aad5c66e588af81730ead77480b0925720b))

# [3.24.0](https://github.com/5e-bits/5e-database/compare/v3.23.0...v3.24.0) (2025-04-28)


### Features

* **magic-items:** Images for Deck of Many Things to Elemental Gems ([1936368](https://github.com/5e-bits/5e-database/commit/19363688c37cff32175f8784a54bbcf3182924ed))

# [3.23.0](https://github.com/5e-bits/5e-database/compare/v3.22.0...v3.23.0) (2025-04-28)


### Features

* **magic-items:** Images for Boots of striding and sprinting to Deck of Illusions ([46155eb](https://github.com/5e-bits/5e-database/commit/46155ebea6594ef9864dfd329bb45b63668b4c8e))

# [3.22.0](https://github.com/5e-bits/5e-database/compare/v3.21.0...v3.22.0) (2025-04-27)


### Features

* **images:** All remaining monster images ([4805d07](https://github.com/5e-bits/5e-database/commit/4805d07e433cd2fa4be82990bfe434ef40843086))

# [3.21.0](https://github.com/5e-bits/5e-database/compare/v3.20.0...v3.21.0) (2025-04-27)


### Features

* **images:** Hezrou to Manticore, Warhorse Skeleton, and Werebear to White Dragon Wyrmling ([3f54cae](https://github.com/5e-bits/5e-database/commit/3f54caeacceeb38b351424cbc7f6653b926c6ae4))

# [3.20.0](https://github.com/5e-bits/5e-database/compare/v3.19.2...v3.20.0) (2025-04-27)


### Features

* **release:** Remove PAT dependency ([#818](https://github.com/5e-bits/5e-database/issues/818)) ([aefc47e](https://github.com/5e-bits/5e-database/commit/aefc47eb420b58a3b746d68148a5ce93073cf627))

## [3.19.2](https://github.com/5e-bits/5e-database/compare/v3.19.1...v3.19.2) (2025-04-27)


### Bug Fixes

* **monsters:** white spaces, OCR, etc. ([#816](https://github.com/5e-bits/5e-database/issues/816)) ([30913dd](https://github.com/5e-bits/5e-database/commit/30913dd4d4295f3017a148d3f9c3cb6ae2b49a9b))

## [3.19.1](https://github.com/5e-bits/5e-database/compare/v3.19.0...v3.19.1) (2025-04-27)


### Bug Fixes

* **images:** Add image for Grick ([cf5105d](https://github.com/5e-bits/5e-database/commit/cf5105d99637a0e89480b7bca8a6d08e934bd2bf))

# [3.19.0](https://github.com/5e-bits/5e-database/compare/v3.18.0...v3.19.0) (2025-04-27)


### Features

* **images:** Duergar to Ghost ([2460333](https://github.com/5e-bits/5e-database/commit/24603330712099ea478a61c9924a262d43a06fb2))
* **images:** Ghoul to Hell Hound ([7061e7f](https://github.com/5e-bits/5e-database/commit/7061e7f0237527de06c46426ab965595faa75fdf))

# [3.18.0](https://github.com/5e-bits/5e-database/compare/v3.17.0...v3.18.0) (2025-04-26)


### Features

* **images:** Cultist to Druid ([92d2db9](https://github.com/5e-bits/5e-database/commit/92d2db94de4a4fae89a8aa99804759c0487bcd54))

# [3.17.0](https://github.com/5e-bits/5e-database/compare/v3.16.0...v3.17.0) (2025-04-25)


### Bug Fixes

* **npm:** Set to private so we don't publish to npm ([08e582a](https://github.com/5e-bits/5e-database/commit/08e582a848e89c7cd79bd1373332d427c4413663))
* **npm:** Update npm lockfile ([9fdcf7d](https://github.com/5e-bits/5e-database/commit/9fdcf7dd941856bfe042972598317573e7a8bcb9))


### Features

* **release:** Now create CHANGELOG.md and npm version bump with semantic release ([935a3c6](https://github.com/5e-bits/5e-database/commit/935a3c6dce3b7197b563b8f0be279670ba0f4076))
