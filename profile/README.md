[![Discord](https://img.shields.io/discord/272499714048524288.svg?logo=discord)](https://discord.bentobox.world)
[![Build Status](https://ci.codemc.org/buildStatus/icon?job=BentoBoxWorld/BentoBox)](https://ci.codemc.org/job/BentoBoxWorld/job/BentoBox/)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=security_rating)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=BentoBoxWorld_BentoBox&metric=bugs)](https://sonarcloud.io/dashboard?id=BentoBoxWorld_BentoBox)


## Hi there 👋
Welcome to BentoBox, the exciting open-source project that brings the captivating world of island-style game plugins to Minecraft! Whether you're a seasoned server administrator or an aspiring Minecraft enthusiast, BentoBox offers a treasure trove of features and possibilities that will elevate your gameplay experience to new heights. In this ReadMe.md file, we'll walk you through what BentoBox is, who should use it, and how you can contribute to this vibrant community.

At its core, BentoBox is a powerful toolkit designed to create island-style game modes for Minecraft servers. Built on the robust Bukkit API and compatible with PaperMC, BentoBox provides an open API that allows you to unleash your creativity and develop immersive game modes. From beloved classics like BSkyBlock and AcidIsland to innovative creations like AOneBlock and Boxed, BentoBox empowers you to build and customize captivating experiences for your players. 

BentoBox is named after Japanese lunch boxes that have a number of compartments holding different foods. The foods come together to form a meal. BentoBox has the same idea where different addons can be used to make a whole.

<img src="https://github.com/BentoBoxWorld/.github/assets/4407265/2e953053-e76f-46a5-b869-de6813c28f67" width="600">

### Who would use BentoBox? How?

Admins, if you're looking to enhance your Minecraft server with thrilling island-style game modes, BentoBox is the perfect solution for you. With its fully featured game play, [documentation](https://docs.bentobox.world), and [videos](https://www.youtube.com/@bentoboxworld7447/featured) setting up and managing these game modes becomes a breeze. You'll have access to a wide range of addons that seamlessly integrate with BentoBox, allowing you to offer exciting and unique gameplay experiences to your players. Visit our download site at https://download.bentobox.world to get started and discover the full potential of BentoBox for your server.

Developers, BentoBox provides you with a powerful and flexible API to create your own custom island-style game modes. Whether you're an experienced plugin developer or just starting out, BentoBox's open API and comprehensive documentation make it easy for you to dive in and start building your dream game modes. By harnessing the limitless possibilities of BentoBox's API, you can craft innovative gameplay mechanics, introduce new challenges, and bring your imaginative ideas to life. Join our thriving community of developers and contribute your creativity to the ever-growing world of BentoBox.

Thank you for joining us on this thrilling adventure with BentoBox. We can't wait to see the incredible game modes you create and the magical worlds you build. Together, we'll unlock new possibilities and make Minecraft an even more captivating universe. Happy gaming!

### Contributions

Contributions are the lifeblood of any thriving open-source project, and BentoBox is no exception. We warmly welcome contributions from developers, designers, and Minecraft enthusiasts who want to make their mark on this ever-growing ecosystem. Whether you want to fix a bug, add a new feature, or enhance the existing functionality, your contributions will help shape the future of BentoBox.

To get started, explore the repositories in this organization. You'll find a wealth of resources, including the source code, issue trackers, and documentation. If you have a specific feature or bug fix in mind, we recommend checking the existing issues to see if it's already being discussed. If not, feel free to open a new issue and start a conversation with the community.

If you do contribute code it **must be in agreement** with:
* our [license](https://github.com/BentoBoxWorld/BentoBox/blob/develop/LICENSE)
* and our [code of conduct](https://github.com/BentoBoxWorld/.github/blob/master/CODE_OF_CONDUCT.md)

### Support and Sponsorship

We would like to extend our heartfelt thanks to the generous sponsors who support BentoBox. Your sponsorships play a crucial role in covering the project's costs, including server hosting, infrastructure, and development resources. If you or your organization are passionate about the Minecraft community and would like to contribute to BentoBox's success, we invite you to consider becoming a sponsor. Your support not only ensures the project's sustainability but also demonstrates your commitment to fostering innovation within the BentoBox ecosystem. To learn more about sponsorship opportunities, [click here](https://github.com/sponsors/tastybento). We deeply appreciate your support in making BentoBox even better for the Minecraft community.

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
* [**Poseidon**](https://github.com/BentoBoxWorld/poseidon): Survive underwater!
* [**SkyGrid**](https://github.com/BentoBoxWorld/SkyGrid): Survive in world made up of scattered blocks - what an adventure!
* [**Parkour**](https://github.com/BentoBoxWorld/Parkour): Give your players a world to make Parkour courses and run them against the clock!

All official Addons are listed here:
* [**Addons**](https://github.com/BentoBoxWorld/BentoBox/blob/develop/ADDON.md)

There are also plenty of other official or community-made Addons you can try and use for your server!

## BentoBox API

BentoBox uses Maven, and its Maven repository is kindly provided by [CodeMC](https://codemc.org).

### Maven
```xml
<repositories>
  <repository>
    <id>bentoboxworld</id>
    <url>https://repo.codemc.org/repository/bentoboxworld/</url>
  </repository>
  <repository>
    <id>codemc-snapshots</id>
    <url>https://repo.codemc.org/repository/maven-snapshots/</url>
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
    mavenCentral()
    maven {
        name = "codemc-public"
        url = uri("https://repo.codemc.io/repository/maven-public/")
    }

    maven {
        name = "bentoboxworld"
        url = uri("https://repo.codemc.org/repository/bentoboxworld/")
    }
}

dependencies {
  compileOnly 'world.bentobox:bentobox:PUT-VERSION-HERE-SNAPSHOT'
}
```
**Note:** Due to a Gradle issue with versions for Maven, you need to use -SNAPSHOT at the end.

### History

[tastybento](https://github.com/tastybento) created ASkyBlock and AcidIsland that shared the same codebase. These plugins became very popular but became hard to maintain.
[Poslovitch](https://github.com/Poslovitch) was running a Skyblock server before starting to contribute regularly to ASkyBlock's codebase. He proposed the idea of completely rewriting ASkyBlock
to make it easier to maintain and richer in features. In May 2017, this became the *BSkyBlock* project. As development progressed it became clear that a lot of the new core features could be used by other
island-style games and so that core functionality was split off and renamed *BentoBox* and the addon system was created. The addons for BSkyBlock and AcidIsland became very simple to develop and much smaller. In December 2019, Poslovitch launched the BentoBox collection on SpigotMC and the story continues! 
The community continues to grow and we added new game modes like SkyGrid and CaveBlock by BONNe. BONNe also took over maintenance of Challenges and Biomes and contributes to other addons.  
tastybento added more game modes, including AOneBlock, Boxed, Parkor, and Poseidon. BentoBox also moved from Spigot to focus on Paper API compatibility in 2025.


