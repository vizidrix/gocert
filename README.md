gocert
======

Cert management helper utils for Golang

## Getting Started ##

1\. Add the import to your project

````go
import (
	"github.com/vizidrix/gocert"
)
````

2\. Start using

````
cert, err := gocert.MakeCert("Acme Inc.", 1024, []string{}, time.Minute * 10, false)

----

Version
----
0.1.0 ish

Tech
----

* [Go] - Golang.org
* [GOCERT] - RSA Cert generation helper for Golang

License
----

https://github.com/Vizidrix/gocert/blob/master/LICENSE

----
## Edited
* 27-January-2014		initial release

----
## Credits
* Vizidrix <https://github.com/organizations/Vizidrix>
* Perry Birch <https://github.com/PerryBirch>