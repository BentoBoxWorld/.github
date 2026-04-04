[![Discord](https://img.shields.io/discord/272499714048524288.svg?logo=discord)](https://discord.bentobox.world)
[![Build Status](https://ci.codemc.io/job/BentoBoxWorld/job/BentoBox/badge/icon)](https://ci.codemc.io/job/BentoBoxWorld/job/BentoBox/)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=security_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=bugs)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![BentoBox Integration Tests](https://github.com/BentoBoxWorld/bbox-test-harness/actions/workflows/integration-test.yml/badge.svg)](https://github.com/BentoBoxWorld/bbox-test-harness/actions/workflows/integration-test.yml)

## BentoBox

BentoBox is the definitive island-style game framework for Minecraft. Built on the Paper API, it powers some of the most popular game modes in the community — BSkyBlock, AOneBlock, AcidIsland, Boxed, and more. If you're running island-style gameplay on your server, this is where you start.

<img src="https://github.com/BentoBoxWorld/.github/assets/4407265/2e953053-e76f-46a5-b869-de6813c28f67" width="600">

### For Server Administrators

BentoBox handles the hard parts — island management, player data, protection, permissions, economy integration, and cross-addon communication — so you can focus on running your server. Drop in a game mode addon, configure it to your liking, and you're up. Full documentation is at [docs.bentobox.world](https://docs.bentobox.world) and binaries are available at [download.bentobox.world](https://download.bentobox.world).

Popular game modes include:

- [**BSkyBlock**](https://github.com/BentoBoxWorld/BSkyBlock) — Classic skyblock, done properly.
- [**AOneBlock**](https://github.com/BentoBoxWorld/AOneBlock) — Start with a single magical block.
- [**AcidIsland**](https://github.com/BentoBoxWorld/AcidIsland) — Stranded in a sea of acid.
- [**Boxed**](https://github.com/BentoBoxWorld/Boxed) — Expand your world by completing advancements.
- [**CaveBlock**](https://github.com/BentoBoxWorld/CaveBlock) — Survival underground.
- [**SkyGrid**](https://github.com/BentoBoxWorld/SkyGrid) — A world of scattered blocks.
- [**Poseidon**](https://github.com/BentoBoxWorld/Poseidon) — Underwater survival.
- [**Parkour**](https://github.com/BentoBoxWorld/Parkour) — Player-built parkour courses with timers.

The full list of official addons is [here](https://github.com/BentoBoxWorld/BentoBox/blob/develop/ADDON.md).

### For Developers

BentoBox exposes a clean, well-documented API for building game modes and addons. Island creation, grid management, player data, events, flags, blueprints, panels — it's all there. You can build a fully featured game mode without touching BentoBox's internals.

**What can you build?**
- A new island-style game mode with custom world generation and mechanics
- Economy, challenge, or progression addons that work across any game mode
- Custom protection flags, island panels, or player rank systems
- Hooks into BentoBox's event system for fine-grained control

JavaDocs are available on the [CI server](https://ci.codemc.io/job/BentoBoxWorld/job/BentoBox/ws/target/apidocs/index.html). Development snapshots at [ci.bentobox.world](https://ci.bentobox.world).

Contributions to BentoBox itself are also welcome — see the [license](https://github.com/BentoBoxWorld/BentoBox/blob/develop/LICENSE) and [code of conduct](https://github.com/BentoBoxWorld/.github/blob/master/CODE_OF_CONDUCT.md) before submitting.

### Maven / Gradle

**Maven**
```xml
<repositories>
  <repository>
    <id>bentoboxworld</id>
    <url>https://repo.codemc.org/repository/bentoboxworld/</url>
  </repository>
  <repository>
    <id>codemc-repo</id>
    <url>https://repo.codemc.org/repository/maven-public/</url>
  </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>world.bentobox</groupId>
    <artifactId>bentobox</artifactId>
    <version>PUT-VERSION-HERE</version>
    <scope>provided</scope>
  </dependency>
</dependencies>
```

**Gradle**
```groovy
repositories {
    maven { url = uri("https://repo.codemc.io/repository/maven-public/") }
    maven { url = uri("https://repo.codemc.org/repository/bentoboxworld/") }
}

dependencies {
    compileOnly 'world.bentobox:bentobox:PUT-VERSION-HERE-SNAPSHOT'
}
```

### Support

Community support and discussion lives on [Discord](https://discord.bentobox.world).

### Sponsorship

BentoBox is free, open-source, and has been for years. Keeping it that way — maintaining infrastructure, funding CI builds, and continuing active development — takes real time and money. If BentoBox runs on your server or underpins something you've built, consider [sponsoring the project](https://github.com/sponsors/tastybento). Sponsors are credited and genuinely appreciated. Every bit helps.
