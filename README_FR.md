# Encyclopédie des clients Discord

<p align="center">
  <a href="https://discord.gg/qQQAnahBxZ">
    <img alt="Discord" src="https://img.shields.io/discord/1044501553731600414?color=%7767d2&label=Serveur%20d%27assistance&logo=discord&logoColor=%cd67d2&style=for-the-badge">
  </a>
</p>
<p align="center">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Discord-Client-Encyclopedia-Management/Discord3rdparties?color=ec9c36&logo=github&style=for-the-badge">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/Discord-Client-Encyclopedia-Management/Discord3rdparties?color=ec365a&logo=github&style=for-the-badge">
  <a href="https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/Discord-Client-Encyclopedia-Management/Discord3rdparties?style=for-the-badge">
  </a>
</p>

Une collection non exhaustive de clients et mods tiers pour Discord.

Version française du README. Les liens, noms et projets restent identiques à la version originale ; seule la documentation introduit une traduction en français pour faciliter la lecture.

## Table des matières

- [Encyclopédie des clients Discord](#encyclopédie-des-clients-discord)
  - [Table des matières](#table-des-matières)
  - [Mobile](#mobile)
    - [Clients et mods Android](#clients-et-mods-android)
    - [Clients et mods iOS](#clients-et-mods-ios)
  - [Ordinateur](#ordinateur)
    - [Clients officiels](#clients-officiels)
    - [Mods](#mods)
      - [Bundlers de plugins](#bundlers-de-plugins)
      - [Enveloppes/adaptateurs/lanceurs pour les clients officiels](#enveloppesadaptateurslanceurs-pour-les-clients-officiels)
      - [Réimplémentations tierces](#réimplémentations-tierces)
  - [Clients pour consoles de jeu](#clients-pour-consoles-de-jeu)
  - [Autres clients](#autres-clients)
  - [Implémentations de serveurs tiers](#implémentations-de-serveurs-tiers)
  - [Contribuer](#contribuer)
  - [Commentaires complémentaires](#commentaires-complémentaires)
  - [Avertissement](#avertissement)

## Mobile

### Clients et mods Android

| Nom | Fonctionnalités | Langage(s) | Statut de développement |
| :---: | :---: | :---: | :---: |
| [Discord Android](https://play.google.com/store/apps/details?id=com.discord&fingerprint=1129189278619021403._iqMp85lJ8wwcey3i6XvuHeKLYA&attemptId=a267ef68-ca9f-435f-99a6-f6a11875cf6c) | Client officiel Android | [Closed source] | 🟢 Actif |
| [Microcord](https://github.com/microcord/microcord) | Un client Discord natif pour Android recréé en Kotlin avec Android Views et XML, avec beaucoup de rétroportages et de fonctionnalités issues des nouvelles versions de Discord. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🟢 Actif |
| [VendroidEnhanced](https://git.nin0.dev/nin0/VendroidEnhanced) | Un fork de [Vencord/Vendroid](https://github.com/Vencord/Android) qui améliore le projet original. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🟢 Actif |
| [Vendroid](https://github.com/Vencord/Vendroid) | [Vencord](https://github.com/Vendicated/Vencord) pour Android ! Un WebView embarquant le site Discord, chargant [Vencord](https://github.com/Vendicated/Vencord). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Kettu](https://github.com/C0C0B01/Kettu) | Un client modifié pour l'application mobile Discord, poursuivant la mission de [Bunny](https://github.com/pyoncord/Bunny). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Voxi](https://github.com/ApexTeamPL/voxi-bundle) | Un client mobile Discord, fork de [Revenge Classic](https://github.com/revenge-mod/revenge-bundle) avec des fonctionnalités supplémentaires. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Revenge](https://github.com/revenge-mod/Revenge) | Un fork de [Bunny](https://github.com/pyoncord/Bunny). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Valenced](https://github.com/Valenced/valenced) | Boostez votre expérience Discord. Valenced est une modification client pour Discord mobile. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [ShiggyCord](https://github.com/kmmiio99o/ShiggyCord) | Shiggy votre Discord ! Fork de [Kettu](https://codeberg.org/cocobo1/Kettu). Plus rapide, rafraîchi, avec des fonctionnalités supplémentaires. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Aliucord](https://github.com/Aliucord/Aliucord) | Un mod pour l'application Discord Android. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] [![Java][Java-Badge]][Java-Url] | 🔵 Actif *(Ancienne app[^1])* |
| [Reseam](https://reseam.app/) | Une application Android native patchée avec des patches pour le client Discord React Native officiel. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [Lampcord](https://github.com/l6t9/Lampcord) | Un client Discord multiplateforme Kotlin avec Material 3. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🔵🧻 Actif *(en bêta)* |
| [Rain](https://codeberg.org/raincord/rain) | Un mod Discord mobile écrit de zéro par les créateurs de [Kettu](https://github.com/C0C0B01/Kettu). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Unbound](https://www.unbound.rip/) | Client modifié multiplateforme pour Discord mobile. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(toujours en développement)* |
| [Linecord](https://github.com/rniii/linecord) | Client Discord RN modifié en cours de travail. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(toujours en développement)* |
| [Revenge Next](https://github.com/revenge-mod/revenge-bundle-next) | Un mod Discord pour Android. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Rebaptisé en Valenced |
| [ReCord](https://github.com/record-mod/record-bundle) | Un mod Discord en cours de développement, inspiré par des mods tels que Bunny et Revenge, avec un objectif de légèreté et de simplicité d'utilisation. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟡 En développement |
| [Wintry](https://github.com/amsyarasyiq/wintry) | Rendre Discord plus cool, littéralement. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Cassé |
| [Lumi](https://github.com/C0C0B01/Lumi) | Un fork de [Wintry](https://github.com/amsyarasyiq/wintry) visant à donner une expérience proche de [Vencord](https://github.com/Vendicated/Vencord) sur Android. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟡 En développement |
| [Bunny](https://github.com/pyoncord/Bunny) | Un mod pour les applications mobile de Discord, fork de [Vendetta](https://github.com/vendetta-mod/Vendetta). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Vendetta](https://github.com/vendetta-mod/Vendetta) | Un mod Discord compatible avec Android et iOS. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [CutTheCord](https://gitdab.com/distok/cutthecord) | Mod client modulaire pour l'application Android de Discord. | [![Python][Python-Badge]][Python-Url] [![Java][Java-Badge]][Java-Url] | 🔴 Abandonné |
| [OpenCord](https://github.com/X1nto/OpenCord) | Une implémentation open-source de l'application Android de Discord. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🔴 Abandonné |
| [Treecord](https://github.com/Treecord/Treecord) | Un client Discord modifié pour Android. | [![Shell Script][Shell Script-Badge]][Shell Script-Url] | 🔴 Abandonné |
| Bluecord | Client modifié pour Android | [Code fermé] | ⛔ Malware (arnaques et espionnage)[^8] |

### Clients et mods iOS

| Nom | Fonctionnalités | Langage(s) | Statut de développement |
| :---: | :---: | :---: | :---: |
| [Discord iOS](https://apps.apple.com/us/app/discord-chat-talk-hangout/id985746746) | Client officiel iOS | [Code fermé] | 🟢 Actif |
| [Kettu](https://github.com/C0C0B01/Kettu) | Un client modifié pour les applications mobile Discord, poursuivant la mission de [Bunny](https://github.com/pyoncord/Bunny). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Rain](https://codeberg.org/raincord/rain) | Un mod Discord mobile écrit de zéro par les créateurs de [Kettu](https://github.com/C0C0B01/Kettu). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Lampcord](https://github.com/l6t9/Lampcord) | Un client Discord multiplateforme Kotlin avec Material 3. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🔵🧻 Actif *(en bêta)* |
| [Stossycord](https://github.com/Stossycord/Stossycord) | Stossycord est un client Discord natif pour iOS. Fabriqué entièrement en Swift et SwiftUI pour la confidentialité, la réactivité et la sécurité. | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Actif |
| [Paicord](https://github.com/llsc12/Paicord) | Un client Discord natif pour iOS et macOS écrit en Swift avec SwiftUI, visant la parité fonctionnelle avec personnalisation et améliorations qualité de vie. | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Actif |
| [Unbound](https://www.unbound.rip/) | Client modifié multiplateforme pour Discord mobile. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(toujours en développement)* |
| [Valenced](https://github.com/Valenced/valenced) | Boostez votre expérience Discord. Valenced est une modification client pour Discord mobile. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Linecord](https://github.com/rniii/linecord) | Client Discord RN modifié en cours de travail. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 *(toujours en développement)* |
| [BTLoader](https://github.com/CloudySn0w/BTLoader) | Fournit des builds de [Kettu](https://github.com/C0C0B01/Kettu) pour iOS, mais utilisera [Rain](https://codeberg.org/raincord/rain) à l'avenir. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Revenge](https://github.com/revenge-mod/Revenge) | Revenge est un fork de [Bunny](https://github.com/pyoncord/Bunny). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Bunny](https://github.com/pyoncord/Bunny) | Un mod pour les applications mobile Discord, fork de [Vendetta](https://github.com/vendetta-mod/Vendetta). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Vendetta](https://github.com/vendetta-mod/Vendetta) | Un mod Discord compatible avec Android et iOS. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Enmity](https://enmity.unbound.rip/) | Le pouvoir des addons, dans votre main. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Discord Classic](https://github.com/cellomonster/iOS-Discord-Classic) | Un client Discord minimaliste pour iOS 5 et 6. | [![Objective-C][Objective-C-Badge]][Objective-C-Url] | 🔴 Abandonné |
| [Discord Classic (continuation)](https://github.com/ToruTheRedFox/iOS-Discord-Classic) | Client Discord pour iOS historique avec interface améliorée et fonctionnalités supplémentaires. Basé sur le client original Discord... | [![Objective-C][Objective-C-Badge]][Objective-C-Url] | 🟢 Actif |

## Ordinateur

### Clients officiels

| Nom | Lien | Infos |
| :---: | :---: | :---: |
| [Discord](https://discord.com) | [Web](https://discord.com/app), [Windows x64](https://discord.com/api/downloads/distributions/app/installers/latest?channel=stable&platform=win&arch=x64), [Windows arm64](https://discord.com/api/downloads/distributions/app/installers/latest?channel=stable&platform=win&arch=arm64), [macOS](https://discord.com/api/downloads/distributions/app/installers/latest?channel=stable&platform=osx), [Linux](https://discord.com/api/downloads/distributions/app/installers/latest?channel=stable&platform=linux) | Client officiel |
| [Discord PTB](https://ptb.discord.com) | [Web](https://ptb.discord.com/app), [Windows x64](https://discord.com/api/downloads/distributions/app/installers/latest?channel=ptb&platform=win&arch=x64), [Windows arm64](https://discord.com/api/downloads/distributions/app/installers/latest?channel=ptb&platform=win&arch=arm64), [macOS](https://discord.com/api/downloads/distributions/app/installers/latest?channel=ptb&platform=osx), [Linux](https://discord.com/api/downloads/distributions/app/installers/latest?channel=ptb&platform=linux) | Client officiel |
| [Discord Canary](https://canary.discord.com) | [Web](https://canary.discord.com/app), [Windows x64](https://discord.com/api/downloads/distributions/app/installers/latest?channel=canary&platform=win&arch=x64), [Windows arm64](https://discord.com/api/downloads/distributions/app/installers/latest?channel=canary&platform=win&arch=arm64), [macOS](https://discord.com/api/downloads/distributions/app/installers/latest?channel=canary&platform=osx), [Linux](https://discord.com/api/downloads/distributions/app/installers/latest?channel=canary&platform=linux) | Client officiel |
| Discord Development | [Windows x64](https://discord.com/api/downloads/distributions/app/installers/latest?channel=development&platform=win&arch=x64), [Windows arm64](https://discord.com/api/downloads/distributions/app/installers/latest?channel=development&platform=win&arch=arm64), [macOS](https://discord.com/api/downloads/distributions/app/installers/latest?channel=development&platform=osx), [Linux](https://discord.com/api/downloads/distributions/app/installers/latest?channel=development&platform=linux) | Client officiel |
| Discord Phoenix | Windows x64, Windows arm64 | C'est un client Rust, il est encore en version interne. Nous avons très peu d'informations sur ce client. |

### Mods

| Nom | Fonctionnalités | Langage(s) | Statut de développement |
| :---: | :---: | :---: | :---: |
| [BeautifulDiscord](https://github.com/leovoel/BeautifulDiscord) | Script Python simple ajoutant le rechargement CSS hot-reload à Discord. | [![Python][Python-Badge]][Python-Url] | 🟢 Actif |
| [BetterDiscord](https://betterdiscord.app/) | BetterDiscord étend les fonctionnalités de DiscordApp en ajoutant de nouvelles fonctionnalités. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [DiscoCSS](https://github.com/mlvzk/discocss) | Un petit injecteur CSS pour Discord sur Linux et macOS. | [![Shell Script][Shell Script-Badge]][Shell Script-Url] | 🟢 Actif |
| [Evi](https://evi.rest/) | Un mod client pour l'application Discord sur Windows, macOS et Linux. Plugins, thèmes et fonds d'écran depuis une boutique intégrée, installés en un clic, avec corrections livrées automatiquement. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Kernel](https://github.com/kernel-mod) | Un petit mod client Electron très rapide avec le maximum de possibilités. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Moonlight](https://moonlight-mod.github.io/) | Un autre mod client Discord, centré sur une bonne expérience utilisateur et développeur. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [OpenAsar](https://openasar.dev/) | Alternative `app.asar` pour Discord. Rend votre client plus rapide. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![Nim][Nim-Badge]][Nim-Url] | 🟢 Actif |
| [reUpdater](https://github.com/cordpackers/reUpdater) | Alternative open-source à `updater.node` de Discord, avec téléchargements multithread et patchs de client desktop personnalisés. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [Replugged](https://replugged.dev) | Un mod client Discord léger axé sur la simplicité et la performance. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [shelter](https://github.com/uwu/shelter) | shelter est une nouvelle génération de mod client construit pour être presque infaillible (par ex. Discord bascule vers SWC). | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Equicord](https://github.com/Equicord/Equicord) | Fork de Vencord avec des plugins et fonctionnalités supplémentaires. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Vencord](https://github.com/Vendicated/Vencord) | Isolation de contexte correcte, correctifs inline, CSS personnalisé, plugins utiles. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Paicord](https://github.com/llsc12/Paicord) | Un client Discord natif pour iOS et macOS écrit en Swift avec SwiftUI, visant la parité fonctionnelle avec personnalisé et qualité de vie. | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Actif |
| [VX](https://github.com/doggybootsy/vx) | Une modification légère du client Discord compatible avec les applications desktop et navigateur. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Voxa](https://github.com/plyght/voxa) | Voxa est un client Discord macOS élégant, léger et natif, construit avec SwiftUI. | [![Swift][Swift-Badge]][Swift-Url] | 🟠 En pause depuis juillet 2026 |
| [Crycord](https://crycord.geopjr.dev/) | Une modification Discord avec plugins. Utilise l'injecteur CSS de BeautifulDiscord. Il est aussi écrit en Crystal. | [![Crystal][Crystal-Badge]][Crystal-Url] | 🟢 Actif |
| [Aero](https://github.com/aero-mod/aero) | Un mod Discord de nouvelle génération donnant du pouvoir aux utilisateurs et développeurs. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Cumcord](https://web.archive.org/web/20250101015227/https://github.com/Cumcord/Cumcord) | Cumcord est un mod client Discord qui vise à rendre le développement de plugins plus simple. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟡 Ancien |
| [DrDiscord](https://github.com/Dr-Discord/DrDiscord) | Un simple mod client (compatible avec d'autres mods comme BD). | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [Demoncord](https://web.archive.org/web/20240224170707/https://git.ruthenic.com/Demon/demoncord-rewrite) | Un mod client Discord créé par des satanistes, pour des satanistes. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [Suncord](https://github.com/verticalsync/Suncord) | Un fork de Vencord. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Vizality](https://vizality.com/) | Une modification du client app Discord, permettant une expérience vraiment personnalisable par l'utilisation de plugins, thèmes et réglages intégrés. Fonctionne aussi dans les navigateurs web. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Hykord](https://github.com/xHyroM/hykord) | La modification du client @discord de xHyroM. Prend en charge les thèmes BD et travaille sur le support des plugins BD et PC/RP. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [EndPwn](https://github.com/EndPwnArchive) | Un modif client basé sur ASAR pour Discord. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [Yelm](https://github.com/adryd325/yelm) | Un mod Discord privé et utilitaire de datamining utilisé et développé vers 2017. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [EnhancedDiscord](https://github.com/joe27g/EnhancedDiscord) | Un mod léger pour Discord. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| Acord Premium | Un client que vous devez payer pour et qui a volé son code. | [Code fermé] | ⛔ comportement suspect (code volé) |
| hh3 | Un mod client privé. | [Code fermé] | ⛔ *(statut[^4])* |
| [GooseMod](https://goosemod.com/) | GooseMod est un nouveau mod Discord orienté boutique. *Fonctionne aussi dans les navigateurs web* | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [HolyMod](https://github.com/HolyMod/HolyMod) | Un mod client léger centré sur la simplicité et la performance. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| Lightcord | Lightcord est un client simple et personnalisable pour Discord. | [Code fermé] | ⛔ comportement suspect (GitHub et autres éléments manquants) |
| [Powercord](https://github.com/powercord-org/powercord) | Un mod client Discord léger centré sur la simplicité et la performance. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Topaz](https://web.archive.org/web/20230920032845/https://topaz.goosemod.com/) | Topaz est un mod à venir visant à être « next-gen » en utilisant des technologies avancées pour ajouter des fonctionnalités inédites. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [Velocity](https://github.com/Velocity-Discord/Velocity) | Velocity est une modification du client Discord qui permet d'étendre les fonctionnalités et capacités de Discord. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟡 En développement |
| [DiscordInjections](https://github.com/Snazzah/DiscordInjections) | Était un mod client affirmant « reprendre où BeautifulDiscord s'arrête » en proposant du JavaScript personnalisé ainsi que du CSS personnalisé. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [Pyoncord ou POC](https://github.com/pyoncord/poc) | Une preuve de concept d'un client Discord. Si vous voyez « poc » ou « pyoncord », cela signifie généralement bunnycord ou leur équipe. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |

#### Bundlers de plugins

| Nom | Fonctionnalités | Langage(s) | Statut de développement |
| :---: | :---: | :---: | :---: |
| [Ittai (fork de AAGaming)](https://git.catvibers.me/Ittai/ittai) | Fork de Ittai qui rassemble les plugins pour BetterDiscord, Powercord et Goosemod, rendant un plugin multi-plateforme. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [Ittai (original)](https://github.com/Kyza/ittai) | Bundleur pour BetterDiscord, Powercord et Goosemod, rendant un plugin multi-plateforme. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [BetterDiscordBuilder](https://github.com/BetterDiscordBuilder/bdbuilder) | Bundler simplifié pour BetterDiscord. Prend en charge JSX/TSX et TypeScript. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |

### Enveloppes/adaptateurs/lanceurs pour les clients officiels

| Nom | Fonctionnalités | Langage(s) | Statut de développement |
| :---: | :---: | :---: | :---: |
| [Datcord](https://github.com/gamingdoom/datcord) | Un client Discord open-source utilisant Firefox. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 En pause depuis février 2025 |
| [Dorion](https://github.com/SpikeHD/Dorion) | Alternative légère au client Discord avec une empreinte moindre et quelques fonctionnalités extensibles. | [![Rust][Rust-Badge]][Rust-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [GoofCord](https://github.com/Milkshiift/GoofCord) | Un client axé sur la vie privée avec chiffrage des messages, chargement de scripts, etc. Basé sur ArmCord. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [LegCord](https://github.com/legcord/legcord) | LegCord est un client personnalisé conçu pour améliorer votre expérience Discord tout en gardant tout léger. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Vesktop](https://github.com/Vencord/Vesktop) | Vesktop est une application desktop multiplateforme visant à donner une expérience Discord plus rapide avec Vencord préinstallé. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Equibop](https://github.com/Equicord/equibop) | Fork de Vesktop avec des plugins et fonctionnalités supplémentaires. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [WebCord](https://github.com/SpacingBat3/WebCord) | Un client Discord sans API, réalisé avec Electron. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔵 Actif *(variable[^2])* |
| [ChimeraCord](https://github.com/RoboChimera/ChimeraCord) | Un client Discord non officiel fonctionnel et élégant pour FreeBSD, visant une parité de fonctionnalités avec le client Discord officiel. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [Discord-PWA](https://github.com/NeverDecaf/discord-PWA) | Un wrapper pour le client web Discord sous forme d'application web progressive, pour navigateur basé sur Chromium. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [LemonCord](https://github.com/japandotorg/LemonCord) | Un client Discord rapide et léger réalisé avec amour en Rust. | [![Rust][Rust-Badge]][Rust-Url] | 🟠 En pause depuis mars 2026 |
| [Themecord](https://github.com/Theme-Cord/ThemeCord) | Une application légère qui permet aux utilisateurs de personnaliser l'apparence du client Discord avec des thèmes CSS personnalisés. | [![Python][Python-Badge]][Python-Url] | 🟢 Actif |
| [Discord-Sandbox](https://github.com/khlam/discord-sandboxed) | Client Discord open-source sandboxé pour les utilisateurs soucieux de leur vie privée. Dites NON à la collecte de données intrusive. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [NativeCord](https://github.com/andre4ik3/NativeCord) | SSB (site-specific browser) pour Discord. En gros, tout ce qu'il fait est de charger Discord comme site web dans une application. | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Actif |
| ~~[ArmCord](https://github.com/armcord/armcord)~~ | ArmCord est un client personnalisé conçu pour améliorer votre expérience Discord tout en gardant tout léger. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Sunroof](https://github.com/verticalsync/Sunroof) | Un fork de Vesktop. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Discord-Lite](https://web.archive.org/web/20221230055539/https://github.com/therealcyber71/Discord-Lite) | Un client Discord léger écrit en Python pour les développeurs, par des développeurs. | [![Python][Python-Badge]][Python-Url] | 🟢 Actif |
| [2018cord](https://github.com/OldCord-Client/2018Cord) | Un client destiné à reproduire l'apparence et l'expérience de Discord en 2018. | [![Python][Python-Badge]][Python-Url] | 🔴 Abandonné |
| [Discord Tauri](https://github.com/DiscordTauri/discord-tauri) | Un wrapper Discord léger réalisé en Tauri. | [![Rust][Rust-Badge]][Rust-Url] | 🔴 Abandonné |
| [FeatherCord](https://github.com/OfficiallySp/FeatherCord) | FeatherCord est une alternative légère au client Discord et utilise jusqu'à 25 % de ressources en moins que le client desktop par défaut. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [GTK3cord](https://github.com/diamondburned/gtkcord3) | Un client Discord Gtk3 en Golang. | [![Go][Go-Badge]][Go-Url] | 🔴 Abandonné. Le développement a migré vers GTK4cord |
| [Rikka](https://github.com/rikka-org/Rikka) | Rikka est une modification Discord rapide, puissante et extensible. Elle peut charger des plugins, gérer des plugins et propose une API riche. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [RyU](https://github.com/Muunatic/RyU) | Client Discord puissant écrit en JavaScript. Léger, efficace, riche en fonctionnalités. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Cassé |
| [Voidcord](https://web.archive.org/web/20230517194514/https://github.com/logoskosmos/voidcord) | Un client web Discord léger et extensible sur Neutralinojs. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |

### Réimplémentations tierces

| Nom | Fonctionnalités | Langage(s) | Statut de développement |
| :---: | :---: | :---: | :---: |
| [Maicord](https://github.com/maj113/MaiCord) | Client Discord natif léger pour Windows. C++23 et Direct3D 11, sans Electron, ~7 MB. Voix avec E2EE, plugins et thèmes. | [![C++][C++-Badge]][C++-Url] | 🟢🚽 Actif |
| [Acheron](https://github.com/ouwou/acheron) | Abaddon rewrite en Qt 6. | [![C++][C++-Badge]][C++-Url] | 🟢🧻 Actif |
| [Yapfast](https://github.com/yapfast/yapfast) | L'application de chat qui ne mange pas votre PC. Un client Discord léger et natif en Rust. | [![Rust][Rust-Badge]][Rust-Url] | 🟢🚽 Actif |
| [Serein](https://github.com/ViceVerse-cz/Serein) | Client Discord tiny, performant et 100 % natif, en Rust. IA utilisée pour le code. | [![Rust][Rust-Badge]][Rust-Url] | 🟢🚽 Actif |
| [IMDiscord](https://github.com/hiddenFSBuser/IMDiscord) | Client très fonctionnel écrit sans CRT et en ImGui, page GitHub en russe. | [![C++][C++-Badge]][C++-Url] | 🟢🚽 Actif |
| [Lampcord](https://github.com/l6t9/Lampcord) | Un client Discord multiplateforme Kotlin avec Material 3. | [![Kotlin][Kotlin-Badge]][Kotlin-Url] | 🔵🧻 Actif *(en bêta)* |
| [Abaddon](https://github.com/uowuo/abaddon) | Client Discord alternatif fait en C++ avec GTK. | [![C++][C++-Badge]][C++-Url] | 🔴 Abandonné au profit de Acheron |
| [AeroCord](https://github.com/VerityOfficial/AeroCord) | AeroCord est un client Discord conçu pour Windows 7 et versions plus anciennes, remontant jusqu'à Windows XP. | [![C++][C++-Badge]][C++-Url] | 🔴 ⛔ Travail en cours |
| [AeroChat](https://github.com/not-nullptr/Aerochat) | Un client Discord inspiré du look de WLM 09. | [![React][React-Badge]][React-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Concord](https://github.com/chojs23/concord) | Client Discord TUI riche en fonctionnalités, écrit en Rust. | [![Rust][Rust-Badge]][Rust-Url] | 🟢 🧻 Actif |
| [Discord Lite](https://github.com/dosdude1/discord-lite) | Un client Discord natif ultra léger pour macOS ancien et moderne. | [![Objective-C][Objective-C-Badge]][Objective-C-Url] | 🟢 Actif |
| [Discord Messenger-DM](https://github.com/DiscordMessenger/dm) | Discord Messenger est un client de messagerie compatible Discord, gratuit et ciblant Windows ancien et récent. | [![C++][C++-Badge]][C++-Url] | 🟢 Actif |
| [Discordo](https://github.com/ayntgl/discordo) | Un client terminal Discord léger, sécurisé et riche en fonctionnalités. | [![Go][Go-Badge]][Go-Url] | 🟢 Actif |
| [Oxicord](https://github.com/linuxmobile/oxicord) | Oxicord est un client Discord TUI haute performance et sûr, écrit en Rust. | [![Rust][Rust-Badge]][Rust-Url] | 🟢 Actif |
| [Endcord](https://github.com/mzivic7/endcord) | Client TUI Discord riche en fonctionnalités, avec serveur RPC, lecteur multimédia ASCII, recherche de messages et theming. | [![Python][Python-Badge]][Python-Url] | 🟢 Actif |
| [Fermi Chat](https://github.com/MathMan05/Fermi) | Un client SpaceBar en TS HTML/CSS. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [LibreDiscord](https://gitlab.com/zipdox/librediscord/-/tree/master?ref_type=heads) | LibreDiscord est un client vocal et vidéo Discord libre et open source, écrit en C avec GTK3 et GLib. | [![C][C-Badge]][C-Url] | 🟢 Actif |
| [QTCord](https://github.com/mak448a/QTCord/) | Un client Discord natif léger écrit en Python avec QT. | [![Python][Python-Badge]][Python-Url] | 🟢 Actif |
| [Unicord](https://github.com/UnicordDev/Unicord) | Client Discord pour Windows 10 et Windows 10 Mobile. | [![C#][C#-Badge]][C#-Url] | 🟢 Actif |
| [Dissent](https://github.com/diamondburned/dissent) | Dissent (auparavant gtkcord4) est un client Discord tiers conçu pour une expérience native et fluide sur Linux. | [![Go][Go-Badge]][Go-Url] | 🟢 Actif |
| [MiniCord](https://github.com/thehatkid/Minicord) | Une version minimale de Discord basée sur la version web. | [![C++][C++-Badge]][C++-Url] | 🔵 Travail en cours </br>🟠 En pause depuis février 2025 |
| [Paicord](https://github.com/llsc12/Paicord) | Client Discord écrit en SwiftUI, visant la parité fonctionnelle avec personnalisations et améliorations qualité de vie. | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Actif |
| [Sakuracord](https://github.com/SakuraCordApp/SakuraCord) | Client Discord créé avec Swift et SwiftUI, visant à être plus rapide et plus léger pour macOS avec un design natif et toutes les fonctionnalités. | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Actif |
| [EveryDiscord](https://github.com/gaouservbf/EveryDiscord) | EveryDiscord est un client Windows Win32 léger et FOSS ciblant les anciens Windows, en particulier NT5, tout en essayant de fonctionner sur les Windows basés MS-DOS. | [![C++][C++-Badge]][C++-Url] | 🟡 En pause |
| [Spacebar Chat Client](https://spacebar.chat/) | Client natif open-source, thémable et extensible compatible Spacebar. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟠 Inactif, ... |
| [Accord](https://github.com/evelyneee/accord) | Client pour Macs modernes. | [![Swift][Swift-Badge]][Swift-Url] | 🟠 En pause depuis décembre 2022 |
| [Unofficial-discord-client](https://github.com/Coding-Bunker/unofficial-discord-client) | Client non officiel pour Discord construit en C++ avec Qt. | [![C++][C++-Badge]][C++-Url] | 🟠 En pause depuis ... |
| [Ripcord](https://cancel.fm/ripcord/) | Client de discussion alternatif pour Slack (et Discord) conçu pour les utilisateurs avancés. | [Code fermé] | 🔴 Cassé *(patchs[^3])* <br/> ⛔ *(avertissement[^6])* |
| [MiniCord](https://github.com/OJddJO/MiniCord) | Une version minimale de Discord basée sur la version web. | [![C++][C++-Badge]][C++-Url] | 🟠 En pause depuis octobre 2022 |
| [Swiftcord](https://github.com/cryptoAlgorithm/Swiftcord) | Un client Discord entièrement natif pour macOS construit 100 % en Swift et SwiftUI. | [![Swift][Swift-Badge]][Swift-Url] | 🔴 Cassé |
| [6cord](https://gitlab.com/diamondburned/6cord) | Une interface terminal pour le service de chat Discord. | [![Go][Go-Badge]][Go-Url] | 🔴 Cassé |
| [concord](https://github.com/volatide/concord) | Client Discord fait en Qt5. | [![Python][Python-Badge]][Python-Url] | 🔴 Abandonné |
| [Cordless](https://github.com/Bios-Marcel/cordless) | Cordless est un client Discord personnalisé visant un faible usage mémoire et conçu pour les utilisateurs avancés. | [![Go][Go-Badge]][Go-Url] | 🔴 Cassé |
| [Discline](https://github.com/mitchweaver/Discline) | Un client Discord en terminal que vous pouvez réellement utiliser. | [![Python][Python-Badge]][Python-Url] | 🔴 Abandonné |
| [discord-curses](https://github.com/RX14/discord-curses) | Client Discord basé sur le terminal. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [DiscordFlex](https://github.com/ZenithRogue/DiscordFlex) | Un client Discord personnalisé construit de zéro. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![Vue.js][Vue.js-Badge]][Vue.js-Url] | 🟢 Actif |
| [DiscordQt](https://github.com/ruslang02/discord-qt) | Un client Discord desktop alimenté par Node.JS et NodeGui. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [discord-screenaudio](https://github.com/maltejur/discord-screenaudio) | Un client Discord personnalisé qui prend en charge le streaming avec audio sur Linux. | [![C++][C++-Badge]][C++-Url] [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟡 En pause |
| [Discord-Terminal](https://web.archive.org/web/20221120040653/https://github.com/atlx/discord-term) | Un client Discord terminal extensible. Peut être utilisé avec des tokens de bot ou utilisateur. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [Disorder](https://github.com/lexffe/discorder) | Client Discord en ligne de commande. | [![Go][Go-Badge]][Go-Url] | 🔴 Abandonné |
| [Disrust](https://github.com/DvorakDwarf/disrust) | Un client Discord TUI entièrement écrit en Rust. | [![Rust][Rust-Badge]][Rust-Url] | 🔴 Abandonné |
| [Fast-Discord](https://github.com/EnyoYoen/Fast-Discord) | Client écrit en C++ et Qt. | [![C++][C++-Badge]][C++-Url] | 🔴 Abandonné |
| [Harmony](https://github.com/hlafaille/Harmony) | Un client Discord basé sur Java. | [![Java][Java-Badge]][Java-Url] | 🔴 Abandonné |
| [micro-discord](https://github.com/soukouki/micro-discord) | Client Discord simple qui n'utilise pas JavaScript. | [![Ruby][Ruby-Badge]][Ruby-Url] | 🔴 Abandonné |
| [Mirdorph](https://gitlab.gnome.org/ranchester/mirdorph) | Un client Discord pauvre en fonctionnalités utilisant libadwaita. | [![Python][Python-Badge]][Python-Url] | 🔴 Abandonné |
| [Pesterchum-Discord](https://github.com/henry232323/Pesterchum-Discord) | Un client Discord imitant le client de chat Pesterchum de Homestuck. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [protocord](https://github.com/diamondburned/protocord) | Un prototype CLI pour un petit client Discord. | [![Go][Go-Badge]][Go-Url] | 🔴 Abandonné |
| [Terminalcord](https://github.com/xynxynxyn/terminal-discord) | Client terminal simple pour Discord avec un look minimal. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [ToastCord](https://github.com/Traumatism/ToastCord) | Interface utilisateur terminal Discord en Python 3. | [![Python][Python-Badge]][Python-Url] | 🔴 Abandonné |
| [DiscordBSD](https://github.com/SrWither/DiscordBSD) | Une tentative de client Discord natif pour FreeBSD. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 Abandonné |
| [RustCord](https://github.com/ulughann/rustCord) | Petit client Discord (5 MiB) construit avec Pake/Tauri. *Attention : cela sert surtout de démonstration, pas pour une utilisation quotidienne.* | [![Rust][Rust-Badge]][Rust-Url] | 🟡 Démonstration |

## Clients pour consoles de jeu

| Nom | Fonctionnalités | Langage(s) | Statut de développement |
| :---: | :---: | :---: | :---: |
| [Tricord](https://github.com/2b-zipper/TriCord) | Un client Discord moderne pour Nintendo 3DS. | [![C++][C++-Badge]][C++-Url] | 🟢 Actif |
| [A-client-for-Discord-for-3DS](https://github.com/XeathJP/A-client-for-Discord-for-3DS) | Applications permettant d'utiliser Discord sur 3DS. | [![C++][C++-Badge]][C++-Url] | 🟠 En pause |
| [Quarrel](https://github.com/UWPCommunity/Quarrel) | Quarrel est un client Discord pour Windows et Xbox visant à apporter le chat vocal à Xbox et un meilleur support des tailles d'écran sur les appareils. | [![C++][C++-Badge]][C++-Url] | 🟢 Actif |
| [NXCord](https://github.com/Grarak/NXCord) | Client Discord non officiel pour Nintendo Switch. | [![C++][C++-Badge]][C++-Url] | 🟠 En pause |
| [crcophony](https://github.com/freyamade/crcophony) | Client TUI Discord rapide et agréable, écrit en Crystal. | [![Crystal][Crystal-Badge]][Crystal-Url] | 🟠 En pause |
| [VitaCord](https://github.com/devingDev/VitaCord) | Client Discord pour PS Vita / PS TV. | [![C++][C++-Badge]][C++-Url] | 🟠 En pause |
| [Unofficial Discord 3DS Client](https://github.com/yourWaifu/Unofficial-Discord-3DS-Client) | Client Discord simple pour la 3DS utilisant la librairie `Sleepy Discord` et `Wslay`. | [![C++][C++-Badge]][C++-Url] | 🟢 Actif |
| [Switchcord](https://github.com/vbe0201/switchcord) | Un client Discord non officiel pour la console Nintendo Switch. | [![C++][C++-Badge]][C++-Url] | 🔴 Abandonné |
| [3DiScord](https://github.com/cheuble/3DiScord) | Un client Discord pour la Nintendo 3DS. | [![C++][C++-Badge]][C++-Url] | ⛔ Abandonné. Peut vous bannir |

## Autres clients

| Nom | Fonctionnalités | Langage(s) | Statut de développement |
| :---: | :---: | :---: | :---: |
| [Discross](http://discross.rc24.xyz/index.html) | Un pont webhook pour envoyer des messages Discord via une page web. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [purple-discord](https://github.com/EionRobb/purple-discord) | Un plugin libpurple/Pidgin pour Discord. | [![C][C-Badge]][C-Url] | 🟢 Actif |
| [Reliable Discord-client IRC Daemon (rdircd)](https://github.com/mk-fg/reliable-discord-client-irc-daemon) | Daemon de traduction Discord vers IRC. | [![Python][Python-Badge]][Python-Url] | 🟢 Actif |
| [Sailcord (anciennement SailDiscord)](https://github.com/roundedrectangle/SailDiscord) | Client Discord pour SailfishOS. | [![Python][Python-Badge]][Python-Url] [![Qt][Qt-Badge]][Qt-Url] | 🟢 Actif |
| [discord-j2me](https://github.com/gtrxAC/discord-j2me) | Client Discord pour appareils Java ME (MIDP 1.0 et 2.0). | [![Java][Java-Badge]][Java-Url] | 🟢 Actif |
| [Weechat Discord](https://github.com/terminal-discord/weechat-discord) | Plugin Weechat avec prise en charge Discord. | [![Rust][Rust-Badge]][Rust-Url] | 🟢 Actif |
| [DiskCord](https://github.com/maem0/diskcord) | Client Discord pour anciens navigateurs web (conçu pour BlackBerry10 OS). | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠🟢 Actif, ... |
| [DiscordBotClient](https://github.com/aiko-chan-ai/DiscordBotClient) | Le client de bot Discord permet d'utiliser votre bot comme n'importe quel compte utilisateur, sauf amis et groupes. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [DiscordBotClient (2022 - 2025)](https://github.com/ChrisEric1/ChrisEric1.GitHub.io) | Ancien client de bot Discord (plus léger, moins de fonctionnalités). | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [Kori](https://github.com/cyan-2048/Discord4KaiOS) | Client Discord non officiel pour KaiOS fait avec SolidJS. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Actif |
| [Discord WAP](https://github.com/gtrxAC/discord-wap) | Client pour anciens navigateurs web mobile prenant en charge WAP 1.x. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Actif |
| [Miranda NG](https://miranda-ng.org) | Programme multi-protocoles prenant en charge Discord. | [![C++][C++-Badge]][C++-Url] | 🟢 Actif |
| [bitlbee-discord](https://github.com/sm00th/bitlbee-discord) | Plugin Discord pour BitlBee. | [![C][C-Badge]][C-Url] | 🟠 En pause |
| [discord-aos](https://github.com/ruslang02/discord-aos) | Client Discord pour Sailfish OS. | [![Qt][Qt-Badge]][Qt-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟠 En pause |
| [crocodile](https://github.com/tbodt/crocodile) | Client Discord pour TempleOS. | [![Python][Python-Badge]][Python-Url] | 🟠 En pause |
| [discord-ppc](https://github.com/vistafan12/discord-ppc) | Version Discord pour architecture PowerPC. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟠 En pause |
| [Arcscord](https://github.com/Arcoz0308/arcscord) | Bibliothèque NodeJS écrite en TypeScript qui interagit avec l'API Discord. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🔴 Abandonné |
| [Scor](https://wiki.vencord.dev/article/Scor) | Client Discord dans l'application Paramètres/Système macOS avec support Vencord. Impossible de trouver GitHub pour l'instant. | [![Swift][Swift-Badge]][Swift-Url] | 🟢 Actif |
| [Nightcord](https://gist.github.com/Vendicated/bb30cb67878fa682bcee140f56af1531) | Client Discord contenant du code volé de plusieurs clients et mods, ainsi que du malware ; évitez de l'utiliser. | [Code fermé] | ⛔ Malware / code volé |
| [~~Naticord~~](https://github.com/Naticord/naticord) | Client Discord axé sur une expérience native. Naticord utilise DirectUI et Windows Forms. | [![C++][C++-Badge]][C++-Url] | 🟡 En pause |
| [~~Fshcord~~](https://github.com/fsh-org/Fshcord) | Alternative Discord légère et ouverte. WIP. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🔴 ⛔ Travail en cours, listé à titre informatif |

## Implémentations de serveurs tiers

Les éléments suivants sont des implémentations de serveurs qui réimplémentent l'API client-serveur de Discord :

| Nom | Fonctionnalités | Langage(s) | Auto-hébergeable | Statut de développement |
| :---: | :---: | :---: | :---: | :---: |
| [Polyphony](https://codeberg.org/polyphony) | Logiciel de communication fédéré libre et open source, compatible avec l'API Discord et construit avec [polyproto](https://polyproto.org/docs/intro/). | [![Rust][Rust-Badge]][Rust-Url] | 🟢 Oui | 🟢 Actif |
| [Spacebar Chat](https://spacebar.chat/) | Re-implémentation quasi complète de l'API server Discord, avec support expérimental de la fédération via ActivityPub. | [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Oui | 🟢 Actif |
| [Hummus](https://hummus.sys42.net/) | Réimplémentation du serveur Discord de 2017. | [Code fermé] | 🟠 Demander la permission au créateur | 🟢 Actif |
| [Miranda NG](https://miranda-ng.org) | Programme multi-protocoles prenant en charge Discord. | [![C++][C++-Badge]][C++-Url] | 🟢 Oui | 🟢 Actif |
| [Oldcord](https://github.com/oldcordapp/OldCordV3) | Réimplémentation open-source du backend Discord historique (2015-2018), avec patcher à la demande. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] | 🟢 Oui | 🟢 Actif |
| [Reflectcord](https://github.com/V3L0C1T13S/reflectcord) | Réimplémentation de l'API server Discord sur Revolt.chat. | [![JavaScript][JavaScript-Badge]][JavaScript-Url] [![TypeScript][TypeScript-Badge]][TypeScript-Url] | 🟢 Oui | 🟢 Actif |
| [Litecord](https://gitlab.com/litecord/litecord) | Réimplémentation partielle de l'API server Discord. | [![Python][Python-Badge]][Python-Url] | 🟠 Autorisé, mais pas prévu | 🟠 En pause |
| [Miranda NG](https://miranda-ng.org) | Programme multi-protocoles prenant en charge Discord. | [![C++][C++-Badge]][C++-Url] | 🟢 Oui | 🟢 Actif |

| IA | Description |
| :-: | :-----------------: |
| 🚽 | Code généré par IA |
| 💩 | Utilisation d'IA artistique |
| 🧻 | Assistance IA |
| 🪠 | Utilisation antérieure de l'IA |
| 😇 | Aucune IA artistique utilisée |
| ❔ | ND : nous ne savons pas |

[^1]: Aliucord est basé sur l'ancienne application Android Discord, remplacée par RNA en 2022. Malgré cela, les efforts de développement continuent de rétroporter des fonctionnalités à Aliucord.
[^2]: Des cassures occasionnelles peuvent survenir selon le temps libre des mainteneurs.
[^3]: Bien que le client principal soit toujours en pause, la communauté a créé des patchs pour prolonger son utilisation et corriger les bugs qui sont apparus avec le temps.
  - [Patcher](https://github.com/geniiii/patcher)
  - [Audio Hook](https://github.com/geniiii/ripcord-audio-hook)
[^4]: À l'heure actuelle, nous savons peu de choses sur ce mod, mais davantage d'informations seront ajoutées au fur et à mesure de leur découverte.
[^5]: Le client manque de fonctionnalités du serveur SpaceBar.
[^6]: Discord peut temporairement suspendre votre compte et vous demander de réinitialiser votre mot de passe à cause d'activités comme des connexions de tokens non autorisées.
[^7]: Dissent ne fait aucun effort pour usurper un client réel et omet intentionnellement `X-Super-Properties` ainsi que d'autres éléments qu'un client réel a. (source : [Hacker News](https://news.ycombinator.com/item?id=39763438)) Dissent peut faire flaguer votre compte comme spammeur ou provoquer son bannissement.
[^8]: Bien que le propriétaire prétende avoir ouvert le code source, une longue histoire d'arnaques et de vols de comptes a montré qu'on ne peut pas lui faire confiance ni croire à ses affirmations.

## Contribuer

Veuillez vous référer à [CONTRIBUTING.md](/.github/CONTRIBUTING.md) si vous souhaitez contribuer à ce projet.

## Commentaires complémentaires

Mise à jour selon les besoins !

Si vous voulez, n'hésitez pas à nous contacter sur [Nekopara#4266](https://discord.gg/qQQAnahBxZ) (chef d'équipe) sur le Discord officiel :
https://discord.gg/qQQAnahBxZ

## Avertissement

Nous (les contributeurs) ne sommes pas responsables si vous êtes banni pour l'utilisation d'un client tiers ou si vous êtes expulsé d'un serveur.

[C-Badge]: https://img.shields.io/badge/C-%2300599C.svg?style=flat&logo=c&logoColor=white
[C-Url]: https://en.wikipedia.org/wiki/C_(programming_language) "C"

[C++-Badge]: https://img.shields.io/badge/C++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white
[C++-Url]: https://en.wikipedia.org/wiki/C++ "C++"

[C#-Badge]: https://img.shields.io/badge/C%23-%23239120.svg?style=flat&logo=c-sharp&logoColor=white
[C#-Url]: https://en.wikipedia.org/wiki/C_Sharp_(programming_language) "C#"

[Crystal-Badge]: https://img.shields.io/badge/Crystal-%23000000.svg?style=flat&logo=crystal&logoColor=white
[Crystal-Url]: https://en.wikipedia.org/wiki/Crystal_(programming_language) "Crystal"

[Dart-Badge]: https://img.shields.io/badge/Dart-%230175C2.svg?style=flat&logo=dart&logoColor=white
[Dart-Url]: https://en.wikipedia.org/wiki/Dart_(programming_language) "Dart"

[Go-Badge]: https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat&logo=go&logoColor=white
[Go-Url]: https://en.wikipedia.org/wiki/Go_(programming_language) "Go"

[Java-Badge]: https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white
[Java-Url]: https://en.wikipedia.org/wiki/Java_(programming_language) "Java"

[JavaScript-Badge]: https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E
[JavaScript-Url]: https://en.wikipedia.org/wiki/JavaScript "JavaScript"

[Kotlin-Badge]: https://img.shields.io/badge/Kotlin-%230095D5.svg?style=flat&logo=kotlin&logoColor=white
[Kotlin-Url]: https://en.wikipedia.org/wiki/Kotlin_(programming_language) "Kotlin"

[Nim-Badge]: https://img.shields.io/badge/Nim-%23161820.svg?style=flat&logo=nim&logoColor=%23ffe953
[Nim-Url]: https://en.wikipedia.org/wiki/Nim_(programming_language) "Nim"

[Objective-C-Badge]: https://img.shields.io/badge/Objective%20C-000000.svg?&style=flat&logo=Apple&logoColor=white
[Objective-C-Url]: https://en.wikipedia.org/wiki/Objective-C "Objective-C"

[Python-Badge]: https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54
[Python-Url]: https://en.wikipedia.org/wiki/Python_(programming_language) "Python"

[Qt-Badge]: https://img.shields.io/badge/Qt-%23217346.svg?style=flat&logo=Qt&logoColor=white
[Qt-Url]: https://en.wikipedia.org/wiki/QML "Qt"

[Ruby-Badge]: https://img.shields.io/badge/ruby-%23CC342D.svg?style=flat&logo=ruby&logoColor=white
[Ruby-Url]: https://en.wikipedia.org/wiki/Ruby_(programming_language) "Ruby"

[Shell Script-Badge]: https://img.shields.io/badge/Shell_Script-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white
[Shell Script-Url]: https://en.wikipedia.org/wiki/Shell_script "Shell Script"

[Swift-Badge]: https://img.shields.io/badge/Swift-F54A2A?style=flat&logo=swift&logoColor=white
[Swift-Url]: https://en.wikipedia.org/wiki/Swift_(programming_language) "Swift"

[TypeScript-Badge]: https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white
[TypeScript-Url]: https://en.wikipedia.org/wiki/TypeScript "TypeScript"

[Vue.js-Badge]: https://img.shields.io/badge/Vue.js-%2335495e.svg?style=flat&logo=vuedotjs&logoColor=%234FC08D
[Vue.js-Url]: https://en.wikipedia.org/wiki/Vue.js "Vue.js"

[Zig-Badge]: https://img.shields.io/badge/Zig-%23F7A41D.svg?style=flat&logo=zig&logoColor=white
[Zig-Url]: https://en.wikipedia.org/wiki/Zig_(programming_language) "Zig"

[Rust-Badge]: https://img.shields.io/badge/Rust-%23000000.svg?&logo=Rust
[Rust-Url]: https://en.wikipedia.org/wiki/Rust "Rust"

[React-Badge]: https://img.shields.io/badge/React-%2361DAFB?style=flat&logo=react&labelColor=black&color=blue
[React-Url]: https://en.wikipedia.org/wiki/React_(software) "React"
