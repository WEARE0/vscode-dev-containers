# [java](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/java)

**Image version:** dev

**Source release/branch:** [main](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/java)

**Definition variations:**
- [16-jdk-bullseye](#variant-16-jdk-bullseye)
- [11-jdk-bullseye](#variant-11-jdk-bullseye)
- [16-jdk-buster](#variant-16-jdk-buster)
- [11-jdk-buster](#variant-11-jdk-buster)

## Variant: 16-jdk-bullseye

**Digest:** sha256:78568e9cd92c336414f9227e17826a2aac1f8a33c6ca31168ad58a702b2021cf

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/java:dev-16-jdk-bullseye
mcr.microsoft.com/vscode/devcontainers/java:dev-16-bullseye
mcr.microsoft.com/vscode/devcontainers/java:dev-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Java](https://adoptopenjdk.net/) | 16.0.2 | /usr/local/ |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 5b3d2b2f0c02ef059fcbcbdb619b22318b8cc13a | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Other tools and utilities**

| Tool | Version | Path |
|------|---------|------|
| [SDKMAN!](https://github.com/sdkman/sdkman-cli) | 5.12.4 | /usr/local/sdkman |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+b1 |
| dialog | 1.3-20201126-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13 |
| libgssapi-krb5-2 | 1.18.3-6 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1k-1+deb11u1 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| manpages-posix | 2017a-2 |
| manpages-posix-dev | 2017a-2 |
| nano | 5.4-2 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26 |
| vim-tiny | 2:8.2.2434-3 |
| wget | 1.21-1+b1 |
| yarn | 1.22.5-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2 |
| zsh | 5.8-6+b2 |

## Variant: 11-jdk-bullseye

**Digest:** sha256:d1b75f9bf0c57203ecbf794bc8f0001a364887e8623c0e61e8fa317e73624525

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/java:dev-11-jdk-bullseye
mcr.microsoft.com/vscode/devcontainers/java:dev-11-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Java](https://adoptopenjdk.net/) | 11.0.12 | /usr/local/ |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 5b3d2b2f0c02ef059fcbcbdb619b22318b8cc13a | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Other tools and utilities**

| Tool | Version | Path |
|------|---------|------|
| [SDKMAN!](https://github.com/sdkman/sdkman-cli) | 5.12.4 | /usr/local/sdkman |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+b1 |
| dialog | 1.3-20201126-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13 |
| libgssapi-krb5-2 | 1.18.3-6 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1k-1+deb11u1 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| manpages-posix | 2017a-2 |
| manpages-posix-dev | 2017a-2 |
| nano | 5.4-2 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26 |
| vim-tiny | 2:8.2.2434-3 |
| wget | 1.21-1+b1 |
| yarn | 1.22.5-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2 |
| zsh | 5.8-6+b2 |

## Variant: 16-jdk-buster

**Digest:** sha256:90ace5e29ee77102ee61e8a2e1852b15c94a55f668a3eddb0df0be84dd9d92ff

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/java:dev-16-jdk-buster
mcr.microsoft.com/vscode/devcontainers/java:dev-16
mcr.microsoft.com/vscode/devcontainers/java:dev-16-buster
mcr.microsoft.com/vscode/devcontainers/java:dev-buster
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 10 (buster)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Java](https://adoptopenjdk.net/) | 16.0.2 | /usr/local/ |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 5b3d2b2f0c02ef059fcbcbdb619b22318b8cc13a | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Other tools and utilities**

| Tool | Version | Path |
|------|---------|------|
| [SDKMAN!](https://github.com/sdkman/sdkman-cli) | 5.12.4 | /usr/local/sdkman |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 1.8.2.3 |
| apt-utils | 1.8.2.3 |
| ca-certificates | 20200601~deb10u2 |
| curl | 7.64.0-4+deb10u2 |
| dialog | 1.3-20190211-1 |
| git | 1:2.20.1-2+deb10u3 |
| gnupg2 | 2.2.12-1+deb10u1 |
| htop | 2.2.0-1+b1 |
| iproute2 | 4.20.0-2+deb10u1 |
| jq | 1.5+dfsg-2+b1 |
| less | 487-0.1+b1 |
| libc6 | 2.28-10 |
| libgcc1 | 1:8.3.0-6 |
| libgssapi-krb5-2 | 1.17-3+deb10u2 |
| libicu63 | 63.1-6+deb10u1 |
| libkrb5-3 | 1.17-3+deb10u2 |
| liblttng-ust0 | 2.10.3-1 |
| libssl1.1 | 1.1.1d-0+deb10u7 |
| libstdc++6 | 8.3.0-6 |
| locales | 2.28-10 |
| lsb-release | 10.2019051400 |
| lsof | 4.91+dfsg-1 |
| man-db | 2.8.5-2 |
| manpages | 4.16-2 |
| manpages-dev | 4.16-2 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| nano | 3.2-3 |
| ncdu | 1.13-1+b1 |
| net-tools | 1.60+git20180626.aebd88e-1 |
| openssh-client | 1:7.9p1-10+deb10u2 |
| procps | 2:3.3.15-2 |
| psmisc | 23.2-1 |
| rsync | 3.1.3-6 |
| strace | 4.26-0.2 |
| sudo | 1.8.27-1+deb10u3 |
| unzip | 6.0-23+deb10u2 |
| vim-tiny | 2:8.1.0875-5 |
| wget | 1.20.1-1.1 |
| yarn | 1.22.5-1 |
| zip | 3.0-11+b1 |
| zlib1g | 1:1.2.11.dfsg-1 |
| zsh | 5.7.1-1 |

## Variant: 11-jdk-buster

**Digest:** sha256:52a9755f075bf7f3cee31bc38aa20188f5efbdf2be142e1f4fe248767563ee96

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/java:dev-11-jdk-buster
mcr.microsoft.com/vscode/devcontainers/java:dev-11
mcr.microsoft.com/vscode/devcontainers/java:dev-11-buster
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 10 (buster)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Java](https://adoptopenjdk.net/) | 11.0.12 | /usr/local/ |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 5b3d2b2f0c02ef059fcbcbdb619b22318b8cc13a | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Other tools and utilities**

| Tool | Version | Path |
|------|---------|------|
| [SDKMAN!](https://github.com/sdkman/sdkman-cli) | 5.12.4 | /usr/local/sdkman |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 1.8.2.3 |
| apt-utils | 1.8.2.3 |
| ca-certificates | 20200601~deb10u2 |
| curl | 7.64.0-4+deb10u2 |
| dialog | 1.3-20190211-1 |
| git | 1:2.20.1-2+deb10u3 |
| gnupg2 | 2.2.12-1+deb10u1 |
| htop | 2.2.0-1+b1 |
| iproute2 | 4.20.0-2+deb10u1 |
| jq | 1.5+dfsg-2+b1 |
| less | 487-0.1+b1 |
| libc6 | 2.28-10 |
| libgcc1 | 1:8.3.0-6 |
| libgssapi-krb5-2 | 1.17-3+deb10u2 |
| libicu63 | 63.1-6+deb10u1 |
| libkrb5-3 | 1.17-3+deb10u2 |
| liblttng-ust0 | 2.10.3-1 |
| libssl1.1 | 1.1.1d-0+deb10u7 |
| libstdc++6 | 8.3.0-6 |
| locales | 2.28-10 |
| lsb-release | 10.2019051400 |
| lsof | 4.91+dfsg-1 |
| man-db | 2.8.5-2 |
| manpages | 4.16-2 |
| manpages-dev | 4.16-2 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| nano | 3.2-3 |
| ncdu | 1.13-1+b1 |
| net-tools | 1.60+git20180626.aebd88e-1 |
| openssh-client | 1:7.9p1-10+deb10u2 |
| procps | 2:3.3.15-2 |
| psmisc | 23.2-1 |
| rsync | 3.1.3-6 |
| strace | 4.26-0.2 |
| sudo | 1.8.27-1+deb10u3 |
| unzip | 6.0-23+deb10u2 |
| vim-tiny | 2:8.1.0875-5 |
| wget | 1.20.1-1.1 |
| yarn | 1.22.5-1 |
| zip | 3.0-11+b1 |
| zlib1g | 1:1.2.11.dfsg-1 |
| zsh | 5.7.1-1 |

