### [2.0.3](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/2.0.2...2.0.3) (2022-02-02)


### 🦊 CI/CD

* Update installed packages. ([9cc9fd9](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/9cc9fd9be95bc98fbde2077f6790930bfe9cfc32))
* Check packages for updates and trigger pack release when new packages are available ([725021b](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/725021b8406f9c3f6f47459336d100e75130f53a))
* Correctly checkout repository ([fc9cdf6](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/fc9cdf6a60587d6b3acce13a4b1d3847731f0f16))
* Prevent regular jobs from running on schedule ([7942579](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/794257915354e146aef7b8dd3476fae1d87ca952))


### Other

* Add list of package versions. ([9ef0626](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/9ef062683b2aa4d1ef0fae008e6b643ca4b59f4c))

### [2.0.2](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/2.0.1...2.0.2) (2022-01-23)


### 👀 Reverts

* Build for armv7 again thanks to [@djmaze](https://git.griefed.de/djmaze) and their dind-image-with-armhf available at https://github.com/djmaze/dind-image-with-armhf ([1dff0d7](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/1dff0d7cae081e7c98db32b6b5a928bfeb4272ee))


### Other

* **deps:** update griefed/gitlab-ci-cd docker tag to v2 ([c83b6a7](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/c83b6a7eab0b9be280073e512c789abe6cad984e))

### [2.0.1](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/2.0.0...2.0.1) (2022-01-21)


### 🦊 CI/CD

* Update griefed/baseimage-ubuntu to 2.1.0 ([3550cfe](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/3550cfecfb58b5311dd93d4a185baf9157755271))
* Update griefed/gitlab-ci-cd to 1.1.0 ([155fbc2](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/155fbc280dd336daaddb2ca69b4a9eb77c1fae53))


### Other

* **deps:** update griefed/baseimage-ubuntu docker tag to v2 ([ce80cae](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/ce80cae1a4700987064e976e0514435d13773c25))

## [2.0.0](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/compare/1.0.5...2.0.0) (2021-11-16)


### 🦊 CI/CD

* Switch image to gitlab-ci-cd which provides for all jobs ([685dd8d](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/685dd8d1e754bdcaa264d69fd1666af8f745a7b0))


### Other

* Add GitLab issue templates ([16aebf6](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/16aebf64b0f739046d4f65ecf0930002c8471381))
* **deps:** update griefed/gitlab-ci-cd docker tag to v1.0.1 ([4e6c2b3](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/4e6c2b329a7baf5bf0d86f6fdf672bcf840549f2))
* **deps:** update griefed/gitlab-ci-cd docker tag to v1.0.3 ([3f0e162](https://git.griefed.de/prosper/docker-baseimage-ubuntu-jdk-8/commit/3f0e16289fbd738ac495ef5c1ca7cdefab9a4164))

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
