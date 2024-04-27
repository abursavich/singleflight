# Singleflight

[![License][license-img]][license]
[![GoDev Reference][godev-img]][godev]
[![Go Report Card][goreportcard-img]][goreportcard]

Package singleflight provides a duplicate function call suppression mechanism.

This is a fork of Tailscale's fork of Go's singleflight package which has had several
homes in the past:

  - <https:pkg.go.dev/tailscale.com/util/singleflight>
  - <https:github.com/golang/go/commit/61d3b2db6292581fc07a3767ec23ec94ad6100d1>
  - <https:github.com/golang/groupcache/tree/master/singleflight>
  - <https:pkg.go.dev/golang.org/x/sync/singleflight>

The tailscale fork adds generics.

This fork adds contexts.


[license]: https://raw.githubusercontent.com/abursavich/singleflight/main/LICENSE
[license-img]: https://img.shields.io/badge/license-mit-blue.svg?style=for-the-badge

[godev]: https://pkg.go.dev/bursavich.dev/singleflight
[godev-img]: https://img.shields.io/static/v1?logo=go&logoColor=white&color=00ADD8&label=dev&message=reference&style=for-the-badge

[goreportcard]: https://goreportcard.com/report/bursavich.dev/singleflight
[goreportcard-img]: https://goreportcard.com/badge/bursavich.dev/singleflight?style=for-the-badge
