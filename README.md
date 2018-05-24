
<p align="center">
  <img alt="GoFortune Logo" src="https://avatars0.githubusercontent.com/u/29897061?v=3&s=200" height="140" />
  <h3 align="center">GoFortune</h3>
  <p align="center">Print a random, hopefully interesting, adage.</p>
  <p align="center">
    <a href="https://github.com/pcj/gofortune/releases/latest"><img alt="Release" src="https://img.shields.io/github/release/pcj/gofortune.svg?style=flat-square"></a>
    <a href="/LICENSE"><img alt="Software License" src="https://img.shields.io/badge/license-Apache%202-blue.svg?style=flat-square"></a>
    <a href="https://travis-ci.org/pcj/gofortune"><img alt="Travis" src="https://img.shields.io/travis/pcj/gofortune.svg?style=flat-square"></a>
    <a href="https://codecov.io/gh/pcj/gofortune"><img alt="Codecov branch" src="https://img.shields.io/codecov/c/github/pcj/gofortune/master.svg?style=flat-square"></a>
    <a href="https://goreportcard.com/report/github.com/pcj/gofortune"><img alt="Go Report Card" src="https://goreportcard.com/badge/github.com/pcj/gofortune?style=flat-square"></a>
    <a href="https://saythanks.io/to/vromero"><img alt="SayThanks.io" src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg?style=flat-square"></a>
    <a href="https://github.com/goreleaser"><img alt="Powered By: GoReleaser" src="https://img.shields.io/badge/powered%20by-goreleaser-green.svg?style=flat-square"></a>
  </p>
</p>

---
Forked from vromero/gofortune as the package name `github/gofortune/gofortune` did not resolve.

GoFortune is an implementation in the fortune unix tool set: `fortune` and `strfile`. Aiming storage format and 
command-line    compatibility with the `fortune-mod` version in 1.0.

This project adheres to the Contributor Covenant code of conduct. By participating, you are expected to uphold this code. We appreciate your contribution. Please refer to our contributing guidelines for further information.

## Usage

`gofortune fortune` will print a random, hopefully interesting, adage.
 
`gofortune strfile` will create a random access index file for storing strings.

## I18n

When any of the LANG variables are present in unix systems or language configuration is present in Windows systems;
if called without argument it will choose (if they exist) fortunes in the default fortunes directory appending
the language (i.e: `/usr/share/games/fortunes/es` and `/usr/share/games/fortunes/off/es` in unix with LC_ALL=es_ES)/.
