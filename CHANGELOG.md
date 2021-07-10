### [1.0.5](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/1.0.4...1.0.5) (2021-07-10)


### 🦊 CI/CD

* Explicitly state baseimage version ([8a22e01](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/8a22e01fc82ed2fb4c3695b9b057ac4448d27b1a))
* Fix "breaking" type ([41238c7](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/41238c711561dc54bf2f0e80717e5e53db9378e1))
* Move Docker build for GitHub container registry to GitLab ([6578739](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/6578739690bcc62141c44f4555b0eb3763f29e3d))

### [1.0.4](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/1.0.3...1.0.4) (2021-06-29)


### 🛠 Fixes

* Well that excuse wasn't needed, I actually had to fix something. GitHub workflow was broken due to github.ref outputting refs/tags/foobar ([b887725](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/b8877250cee99c19b9e49aecda3f9a583c31e771))

### [1.0.3](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/1.0.2...1.0.3) (2021-06-29)


### 🦊 CI/CD

* Fix wrong setting in GitHub CI ([82d9207](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/82d92075ddb20b8bdfbc3da4fb50a1692edcb83b))


### 🛠 Fixes

* Default ARGs for date and version (really I just needed a reason to trigger a new release to test the GitHub workflow) ([a06063a](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/a06063a6c5fa6d3a810ccc6677520b5055d7aeb0))

### [1.0.2](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/1.0.1...1.0.2) (2021-06-29)


### 🦊 CI/CD

* Make sure releases on GitHub are created as well. ([eda2e01](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/eda2e01a71884f9b81ac41e419ca2068af154971))


### 🛠 Fixes

* Setup JRE_HOME as well as PATH correctly. ([16097c7](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/16097c7e6be295cec6805061c6821ad162fd3a23))

### [1.0.1](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/1.0.0...1.0.1) (2021-06-28)


### 👀 Reverts

* Comment out update-alternatives. Will make use of it should it be needed. Needs tests ([6a63c17](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/6a63c172be83ee6b3451b5431abfd2d420d1b2c6))

## [1.0.0](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/...1.0.0) (2021-06-28)


### 📔 Docs

* Add license ([ce72137](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/ce7213712ad9dcb5bfbde7f881e4ae93aa90b49f))


### 🦊 CI/CD

* Initial Dockerfile ([dfb6b9d](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/dfb6b9dcd387a330093ecc2e7fe500dbb2dc0933))
* Initial environment config ([3156348](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/3156348b5b4c1038127d0ad1a5f3bac86512914b))
* Add GitLab CI config, Release config, RenovateBot config, gitignore ([36cdf87](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/36cdf878bf2a06ed1fd5f89d398a0c16f7533cac))
* Fix branch name ([abbf586](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/abbf58681fa4c9a84ae9de3a0c9ffc2810c21f7c))
* Set correct images for docker jobs ([73dfc66](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/73dfc66d2afa304654b651fdc750cc277a134382))


### 🛠 Fixes

* Add missing COPY instruction ([7761223](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/776122335145276fcf77867ad66973627d6590f8))


### Other

* README stuffs ([224bbd8](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/224bbd8d9257a8225fee43522d6b3b9858e1c794))
