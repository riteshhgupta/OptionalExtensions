# OptionalExtensions

<a href="https://github.com/Carthage/Carthage"><img src="https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat"></a>
[![Swift 2.1](https://img.shields.io/badge/Swift-2.1-orange.svg?style=flat)](https://developer.apple.com/swift/)
[![License MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg?style=flat)](https://opensource.org/licenses/MIT)

#### Usage

* **filter**
```swift
let number: Int? = 3

let biggerThan2 = number.filter { $0 > 2 } // .Some(3)


let biggerThan3 = number.filter { $0 > 3 } // .None

```

#### Setup


Carthage:

```
github "RuiAAPeres/OptionalExtensions"
```


## License
OptionalExtensions is licensed under the MIT License, Version 2.0. [View the license file](LICENSE)

Copyright (c) 2015 Rui Peres