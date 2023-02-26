[![Discord](https://img.shields.io/discord/272499714048524288.svg?logo=discord)](https://discord.bentobox.world)
[![Build Status](https://ci.codemc.org/buildStatus/icon?job=BentoBoxWorld/BentoBox)](https://ci.codemc.org/job/BentoBoxWorld/job/BentoBox/)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=ncloc)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=security_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=bugs)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)


## Hi there 👋

### 🙋‍♀️ What is BentoBox World about?

BentoBox World is where we develop BentoBox. BentoBox is a plugin for Minecraft servers running the Bukkit API, like Spigot, and Paper
with a unique addon system that enables it to be customized and configured how an admin likes. 
BentoBox focuses on island-based games like SkyBlock, OneBlock, AcidIsland, Boxed, SkyGrid, etc., and a whole suite of addons for
those games. You can download BentoBox and associated addons at [download.bentobox.world](https://download.bentobox.world).

### Who would use BentoBox? How?

BentoBox is for admins who want to run games like Skyblock, Oneblock or other island games on a Minecraft multiplayer server. BentoBox is a plugin for the server, i.e. some extra code that adds to the vanilla server code. If you want to find out about how to run your own Minecraft server for fun or profit, there are a lot of tutorials and videos on the Internet. Just google for it. Oracle provide a good blog on how to set up a free server on their cloud and there are many, many server hosting options out there. Bentobox enhances the  stock Minecraft game (also called vanilla) with new game modes that challenge new and experienced players alike. We hope you enjoy the "art" we have created and have fun with it!

### 🌈 Contribution guidelines - how can the community get involved?

BentoBox is supported by volunteers who code and test it. The best way for you to get involved is to clone the repos you are interested in, 
submit a PR, which might be Java code, or language translations, or config edits and that will start the ball rolling. We are always happy for
submissions. We also appreciate testers, who report bugs and recommend improvements. If you can't code, but want to support the work we do,
you can help by [sponsoring](https://github.com/sponsors/tastybento), which helps pay for servers, domain names, and other costs.

If you contribute code it **must be in agreement** with:
* our [license](https://github.com/BentoBoxWorld/BentoBox/blob/develop/LICENSE)
* our [code of conduct](https://github.com/BentoBoxWorld/.github/blob/master/CODE_OF_CONDUCT.md)
* our contribution guidelines

### 👩‍💻 Useful resources

- User and Admin Documentation can be found at [docs.bentobox.world](https://docs.bentobox.world)
- Downloads of binaries are at the main download site: [download.bentobox.world](https://download.bentobox.world)
- Snapshots of development builds are on the Continuous Integration build server: [ci.bentobox.world](https://ci.bentobox.world)
- JavaDocs can be found on the CI server under each project's build. The BentoBox API is [here](https://ci.codemc.io/job/BentoBoxWorld/job/BentoBox/ws/target/apidocs/index.html)

#### Addons
These are some popular Gamemodes:
* [**AcidIsland**](https://github.com/BentoBoxWorld/AcidIsland): You are marooned in a sea of acid!
* [**AOneBlock**](https://github.com/BentoBoxWorld/AOneBlock): Start to play with only 1 magical block.
* [**Boxed**](https://github.com/BentoBoxWorld/Boxed): A game mode where you are boxed into a tiny space that only expands by completing advancements.
* [**BSkyBlock**](https://github.com/BentoBoxWorld/BSkyBlock): The successor to the popular ASkyBlock.
* [**CaveBlock**](https://github.com/BentoBoxWorld/CaveBlock): Try to live underground!
* [**SkyGrid**](https://github.com/BentoBoxWorld/SkyGrid): Survive in world made up of scattered blocks - what an adventure!

All official Addons are listed here:
* [**Addons**](https://github.com/BentoBoxWorld/BentoBox/blob/develop/ADDON.md)

There are also plenty of other official or community-made Addons you can try and use for your server!

## BentoBox API

BentoBox uses Maven, and its Maven repository is kindly provided by [CodeMC](https://codemc.org).

### Maven
```xml
<repositories>
  <repository>
    <id>codemc-snapshots</id>
    <url>https://repo.codemc.org/repository/maven-snapshots</url>
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

### Gradle
```groovy
repositories {
  maven { url "https://repo.codemc.org/repository/maven-public/" }
}

dependencies {
  compileOnly 'world.bentobox:bentobox:PUT-VERSION-HERE'
}
```

### History

[tastybento](https://github.com/tastybento) created ASkyBlock and AcidIsland that shared the same codebase. These plugins became very popular but became hard to maintain.
[Poslovitch](https://github.com/Poslovitch) was running a Skyblock server before starting to contribute regularly to ASkyBlock's codebase. He proposed the idea of completely rewriting ASkyBlock
to make it easier to maintain and richer in features. In May 2017, this became the *BSkyBlock* project. As development progressed it became clear that a lot of the new core features could be used by other
island-style games and so that core functionality was split off and renamed *BentoBox* and the addon system was created. The addons for BSkyBlock and AcidIsland became very simple to develop and much smaller. 
The community started to grow and we added new game modes like SkyGrid and CaveBlock by BONNe. BONNe also took over maintenance of Challenges and Biomes and contributed to other addons.  

In December 2019, Poslovitch launched the BentoBox collection on SpigotMC and the story continues! 

