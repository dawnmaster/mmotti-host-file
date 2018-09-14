## MMotti Host File (Samsung Knox Firewall)

The aim of this host file is to provide additional host file from different provider.

This host file has been created specifically for use with Samsung Knox Firewall; It is based on the following sources:

* [adblock.mahakala.is (clean.list)](https://github.com/Ultimate-Hosts-Blacklist/adblock.mahakala.is)

#### Blacklist recommendations
These domains are annoyances that cannot be included in the main host-file due to issues that may arise as a result of blocking them.
* **com.android.chrome|*|53** (Chrome async DNS can make ads pass through, so this is blocked)
* **graph.facebook.com** (Facebook Ad Choices; can break Facebook login etc.)

#### Whitelist recommendations
These domains may need to be whitelisted for certain sites to function correctly.
* **analytics.twitter.com** (reports of broken twitter links)
* **track.aliexpress.com** (reports of broken aliexpress package tracking)
* **click.emails.purch.com** (reports of broken newsletter links, notably Tom'sHardware)
* **jp.naver.line.android|www.google-analytics.com** (reports of broken Line Today feature in Line messaging app)
