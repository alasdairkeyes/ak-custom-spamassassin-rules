# ak-custom-spamassassin-rules

Custom Spamassassin rules

## Notes

These rules were added to combat spam on my personal mail system. Feel free to
use and adjust these as you see fit.

## Site

https://github.com/alasdairkeyes/ak-custom-spamassassin-rules

## Installation

* Place the `93_ak_custom_rules.cf` file into your spamassassin configuration
folder.
* Adjust the scores as necessary. YMMV.
* Lint check your installation
```
# spamassassin --lint
```
* Restart Spamassassin

## License

Apache License 2.0 - Same as SpamAssassin. See license file.

## Changelog

* 2016-11-26 :: 0.01 :: First release
* 2016-11-26 :: 0.02 :: Added rules and fixes
* 2016-11-27 :: 0.03 :: Add more rules

## Author

Alasdair Keyes https://akeyes.co.uk/
