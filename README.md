## PayPal REST API Java SDK [![Build Status](https://travis-ci.org/paypal/PayPal-Java-SDK.svg?branch=master)](https://travis-ci.org/paypal/PayPal-Java-SDK)

![Home Image](https://raw.githubusercontent.com/wiki/paypal/PayPal-Java-SDK/images/homepage.jpg)

This repository contains Java SDK and samples for REST API. For PayPal mobile(Android) SDK, please go to [PayPal Android SDK](https://github.com/paypal/PayPal-Android-SDK)

## Please Note
> **The Payment Card Industry (PCI) Council has [mandated](http://blog.pcisecuritystandards.org/migrating-from-ssl-and-early-tls) that early versions of TLS be retired from service.  All organizations that handle credit card information are required to comply with this standard. As part of this obligation, PayPal is updating its services to require TLS 1.2 for all HTTPS connections. At this time, PayPal will also require HTTP/1.1 for all connections. [Click here](https://github.com/paypal/tls-update) for more information. Connections to the sandbox environment use only TLS 1.2.**

## Direct Credit Card Support
> **Important: The PayPal REST API no longer supports new direct credit card integrations.**  Please instead consider [Braintree Direct](https://www.braintreepayments.com/products/braintree-direct); which is, PayPal's preferred integration solution for accepting direct credit card payments in your mobile app or website. Braintree, a PayPal service, is the easiest way to accept credit cards, PayPal, and many other payment methods.

## Prerequisites
* Java JDK 6 or higher
* An environment which supports TLS 1.2 (see the [TLS-update site](https://github.com/paypal/TLS-update#java) for more information)

## Integration

#### Gradle
```gradle
repositories {
	mavenCentral()
}
dependencies {
	compile 'com.paypal.sdk:rest-api-sdk:+'
}
```
#### Others
- For Maven and other options, follow [instructions here](https://github.com/paypal/PayPal-Java-SDK/wiki/Installation)

## Get Started
- [Make your first call](https://github.com/paypal/PayPal-Java-SDK/wiki/Making-First-Call).
- [Run Samples project](rest-api-sample).

License
--------------------
Code released under [SDK LICENSE](LICENSE)

Contributions
--------------------
Pull requests and new issues are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.
