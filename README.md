[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

# Upgrade Spring Boot to 3.1.x and compare on Cloud Foundry

## Prerequisites
- [SDKMan](https://sdkman.io/install)
  > i.e. `curl -s "https://get.sdkman.io" | bash`
- [Httpie](https://httpie.io/) needs to be in the path
  > i.e. `brew install httpie`
- bc, pv, zip, unzip, gcc, zlib1g-dev
  > i.e. `sudo apt install bc, pv, zip, unzip, gcc, zlib1g-dev -y`
- [Vendir](https://carvel.dev/vendir/)
  > i.e. `brew tap carvel-dev/carvel && brew install vendir`

## Quick Start
```bash
./demo.sh
```

## Attributions
- [Demo Magic](https://github.com/paxtonhare/demo-magic) is pulled via `vendir sync`

## Related Videos

- https://www.youtube.com/live/qQAXXwkaveM?si=4KunXZaretBrPZs3
- https://www.youtube.com/live/ck4AP7kRQkc?si=lDl203vbfZysrX5e
- https://www.youtube.com/live/VWPrYcyjG8Q?si=z7Q2Rm_XOlBwCiei

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[forks-shield]: https://img.shields.io/github/forks/dashaun/openrewrite-upgradespringboot_3_1-cloudfoundry.svg?style=for-the-badge
[forks-url]: https://github.com/dashaun/openrewrite-upgradespringboot_3_1-cloudfoundry/forks
[stars-shield]: https://img.shields.io/github/stars/dashaun/openrewrite-upgradespringboot_3_1-cloudfoundry.svg?style=for-the-badge
[stars-url]: https://github.com/dashaun/openrewrite-upgradespringboot_3_1-cloudfoundry/stargazers
[issues-shield]: https://img.shields.io/github/issues/dashaun/openrewrite-upgradespringboot_3_1-cloudfoundry.svg?style=for-the-badge
[issues-url]: https://github.com/dashaun/openrewrite-upgradespringboot_3_1-cloudfoundry/issues
