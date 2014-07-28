# Sentinel

[![Build Status](http://ci.cartalyst.com/build-status/svg/6)](http://ci.cartalyst.com/build-status/view/6)

Sentinel is a PHP 5.4+ fully-featured authentication & authorization system. It also provides additional features such as user groups and additional security features.

Sentinel is a framework agnostic set of interfaces with default implementations, though you can substitute any implementations you see fit.

## Package Story

It also provides additional features such as user groups and additional security features:

- Configurable authentication (can use any type of authentication required, such as username or email)
- Authorization
- Activation of user *(optional)*
- Groups and group permissions
- "Remember me"
- User suspension
- Login throttling *(optional)*
- User banning
- Password resetting
- User data
- Interface driven - switch out your own implementations at will

## Requirements

- PHP >=5.4

## Installation

Sentinel is installable with Composer. Read further information on how to install.

[Installation Guide](http://cartalyst.com/manual/sentinel/introduction/installation)

## Documentation

Refer to the following guide on how to use the Sentinel package.

[Documentation](http://cartalyst.com/manual/sentinel)

## Versioning

We version under the [Semantic Versioning](http://semver.org/) guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

## Support

If you like Sentinel, consider [subscribing](http://www.cartalyst.com/pricing) to our [Arsenal](http://www.cartalyst.com/arsenal). It allows us to keep creating awesome software and afford to eat at night. Subscribers also get **priority support** with all of our packages, both free and subscriber-only.

Have a bug? Please create an issue here on GitHub that conforms with [necolas's guidelines](https://github.com/necolas/issue-guidelines).

https://github.com/cartalyst/sentinel/issues

Follow us on Twitter, [@cartalyst](http://twitter.com/cartalyst).

Join us for a chat on IRC.

Server: irc.freenode.net
Channel: #cartalyst
