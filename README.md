# Hytale Plugin Template
A minimal template for creating Hytale server plugins and the quickest way to get started today.<br> 
API documentation is still in progress as the game is also in early access, so looking through decompiled code will be necessary for now.

## Prerequisites
- Java 25 JDK (Hypixel Studios recommends [Adoptium](https://adoptium.net/temurin/releases))
- Gradle 9.x or higher
- **Hytale Server Jar** 
  - As of the date of this commit, Hypixel Studios has not published the Hytale server jar to maven central.<br>
  So, **you will need to manually copy(HytaleServer.jar) from your launcher installation and place it in the `libs` folder**.<br>
  Steps for finding the server jar can be found in the official [Hytale Support Site](https://support.hytale.com/hc/en-us/articles/45326769420827-Hytale-Server-Manual#server-setup)

## Building the Template
```bash
git clone https://github.com/leonesoj/hytale-plugin-template.git
cd hytale-plugin-template/
./gradlew build
```

## Helpful Resources
- [Hytale Server Manual](https://support.hytale.com/hc/en-us/articles/45326769420827-Hytale-Server-Manual)