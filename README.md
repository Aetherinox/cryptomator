[![cryptomator](cryptomator.png)](https://cryptomator.org/)

<p align="center">

[![Build](https://github.com/cryptomator/cryptomator/workflows/Build/badge.svg)](https://github.com/cryptomator/cryptomator/actions?query=workflow%3ABuild)
[![Known Vulnerabilities](https://snyk.io/test/github/cryptomator/cryptomator/badge.svg)](https://snyk.io/test/github/cryptomator/cryptomator)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=cryptomator_cryptomator&metric=alert_status)](https://sonarcloud.io/dashboard?id=cryptomator_cryptomator)
[![Twitter](https://img.shields.io/badge/twitter-@Cryptomator-blue.svg?style=flat)](http://twitter.com/Cryptomator)
[![Crowdin](https://badges.crowdin.net/cryptomator/localized.svg)](https://translate.cryptomator.org/)
[![Latest Release](https://img.shields.io/github/release/cryptomator/cryptomator.svg)](https://github.com/cryptomator/cryptomator/releases/latest)
[![Community](https://img.shields.io/badge/help-Community-orange.svg)](https://community.cryptomator.org)

</p>

<br />

---

<br />

## About

Cryptomator offers multi-platform transparent client-side encryption of your files in the cloud.

Download native binaries of Cryptomator on [cryptomator.org](https://cryptomator.org/) or clone and build Cryptomator using Maven (instructions below).

<br />

---

<br />

## Features

- Works with Dropbox, Google Drive, OneDrive, MEGA, pCloud, ownCloud, Nextcloud and any other cloud storage service which synchronizes with a local directory
- Open Source means: No backdoors, control is better than trust
- Client-side: No accounts, no data shared with any online service
- Totally transparent: Just work on the virtual drive as if it were a USB flash drive
- AES encryption with 256-bit key length
- File names get encrypted
- Folder structure gets obfuscated
- Use as many vaults in your Dropbox as you want, each having individual passwords
- Four thousand commits for the security of your data!! :tada:

<br />

---

<br />

## Building
The following information explains how to build Cryptomator using Java JDK and Maven 3.

<br />

### Download Dependencies

* Java OpenJDK v21 <sup>( Pick Only One )</sup>
  * [Azul Zulu OpenJDK](https://www.azul.com/downloads/)
  * [Eclipse Temurin OpenJDK](https://adoptium.net/temurin/releases/)
* [Apache Maven 3]([text](https://maven.apache.org/download.cgi))

<br />

After installing the above dependencies, ensure you add the `PATHS` to your **Environment Variables**.

### Run Maven

```
mvn clean install
# or mvn clean install -Pwin
# or mvn clean install -Pmac
# or mvn clean install -Plinux
```

This will build all JARs and bundle them together with their OS-specific dependencies under the `target` folder. This can now be used to build native packages.

<br />

---

<br />

## License

This project is dual-licensed under the GPLv3 for FOSS projects as well as a commercial license for independent software vendors and resellers. If you want to modify this application under different conditions, feel free to contact our support team.
