# dnsmadeeasy

FORKED from the initial work by soniah as I wanted to extend the functionality for terraform
original caveats still apply, heance soniah's readme is still mostly intact.


[![Build
Status](https://travis-ci.org/sjones-sot/dnsmadeeasy.svg?branch=master)](https://travis-ci.org/sjones-sot/dnsmadeeasy)
[![Coverage](http://gocover.io/_badge/github.com/sjones-sot/dnsmadeeasy)](http://gocover.io/github.com/sjones-sot/dnsmadeeasy)
[![GoDoc](https://godoc.org/github.com/sjones-sot/dnsmadeeasy?status.png)](http://godoc.org/github.com/sjones-sot/dnsmadeeasy)
https://github.com/sjones-sot/dnsmadeeasy v1.1

This package provides the `dnsmadeeasy` package which offers an
interface to the [DNSMadeEasy](http://www.dnsmadeeasy.com/) API.

It doesn't have full API coverage, and only implements specific
endpoints, as it is designed for use with
[Terraform](https://github.com/hashicorp/terraform).

**For those reasons, I recommend looking elsewhere if you just need
a standard DNSMadeEasy API client.**

Sonia Hamilton, sonia@snowfrog.net, http://blog.snowfrog.net.

## Documentation

The full documentation is available on [Godoc](http://godoc.org/github.com/sjones-sot/dnsmadeeasy)

## Related Projects

* https://github.com/sjones-sot/terraform-provider-dme
* https://github.com/hashicorp/terraform
* https://github.com/pearkes/dnsimple

## License

See LICENSE. Copyright the DNSMadeEasy authors, see AUTHORS.md.
