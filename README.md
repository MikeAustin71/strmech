# *stmech* - String Mechanics

[![GoDoc](https://godoc.org/github.com/MikeAustin71/strmech?status.svg)](https://godoc.org/github.com/MikeAustin71/strmech)

[**strmech**](https://github.com/MikeAustin71/stringopsgo), is a collection of string management utilities written in the [**Go**](https://golang.org/) Programming Language. 

***strmech*** provides simple string management routines which perform operations like string formatting, centering, justification trimming, numeric digit extraction and character manipulation. 

Version 0.1.0 represents the first release of ***strmech*** which incorporates code transferred from Version 3.0 of [stringsopsgo](https://github.com/MikeAustin71/stringopsgo). The [stringsopsgo](https://github.com/MikeAustin71/stringopsgo) project has been deprecated and all future development of the string management toolbox will focus on ***strmech***.

## Key Features  

- Developed with  [**Go**](https://golang.org/) Version 1.16.3.
- Thread Safety protocols added for improved concurrency support.
- Enhanced error management capabilities added including support for attaching error prefix text to error messages. 
- Full support for [Go Modules](https://golang.org/ref/mod).
- For feature details, see the [Source Code Documentation](http://godoc.org/github.com/MikeAustin71/strmech).    



# Table of Contents

+ [Supported Platforms](#supported-platforms)
+ [Getting Started](#getting-started)
    - [Installation](#installation)
    - [Source Code Import](#source-code-import)
+ [Source Code Documentation](#source-code-documentation)
+ [Tests](#tests)
+ [Version](#version)
+ [License](#license)
+ [Comments](#comments-and-questions) 



## Supported Platforms

This package was developed and tested on Windows, although the package
was designed to operate on multiple operating systems including 
Mac-OS, Linux and Windows.

While development testing has focused primarily on *Windows*, the unit
tests are now completing successfully on *Linux Mint 19.2* and *Ubuntu 18.04.3*.



## Getting Started

### Installation
Use this command to download and install the ***strmech*** package locally. Note: ***strmech*** supports [Go Modules](https://golang.org/ref/mod).

    go get github.com/MikeAustin71/strmech/@v0.1.0

-- or --

```go
go get github.com/MikeAustin71/strmech/@latest
```



To update the package run:  

```go
go get -u github.com/MikeAustin71/strmech
```


​    


### Source Code Import        
```go
import (

	sMech "github.com/MikeAustin71/strmech"
)

```

The import example above shows an alias of 'sMech' which is optional.



## Source Code Documentation

 [Source Code Documentation](http://godoc.org/github.com/MikeAustin71/strmech)   



## Tests

Currently, the ***strmech*** package has 344 unit tests with a code coverage of 91%. 

Test coverage and outcomes are documented in:

[github.com/MikeAustin71/strmech/zzzzz_tests.txt](./zzzzz_tests.txt)

[How To Run Tests Documentation](./wt_HowToRunTests.md)



## Version

Version 0.1.0 is the first release of ***strmech*** and is based on an earlier project, Version 3.0 of [stringsopsgo](https://github.com/MikeAustin71/stringopsgo). The [stringsopsgo](https://github.com/MikeAustin71/stringopsgo) repository has been deprecated and all future development of this string management toolbox will focus on ***strmech***. 

[Release Notes](./releasenotes.md)



## License

Use of this source code is governed by the (open-source) MIT-style license which can be found in the LICENSE file located in this directory.

[MIT License](./LICENSE)



## Comments And Questions

Send questions or comments to:

    mike.go@paladinacs.net



