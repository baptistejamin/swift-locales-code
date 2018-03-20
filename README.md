# IsoLocales for Swift
![Platform](https://img.shields.io/cocoapods/p/Typist.svg?style=flat)
![Swift Version](https://img.shields.io/badge/swift-4.0-orange.svg?style=flat)

Iso Locale codes - that retrieves Locale names using an ISO 639 locale code.

### What?
This is a **iOS Swift** library/class  files that does a simple lookup depending on a ISO 693 [iso693](https://en.wikipedia.org/wiki/ISO_639 "iso693") locale code.

### Usage:

You can search via alpha-1, alpha-2 or alpha-3 format. 
Searching an ISO code returns a struct. 

```swift
print(IsoLocaleCodes.find(key: "FR").name) //French
print(IsoLocaleCodes.find(key: "NLD").name) //Dutch
print(IsoLocaleCodes.find(key: "NL").currency) //Dutch
```

You can also search by locale name
```swift
dump(IsoCountryCodes.searchByName(name: "Dutch")

dump(IsoCountryCodes.searchByLocal(name: "Français")
```
This returns a `IsoCountryInfo` struct:
```swift
▿ IsoCountryCodes.IsoCountryInfo
    - name: Dutch
    - local: Nederlands
    - alpha1: nl,
    - alpha2: nld
    - alpha2T: nld
    - alpha2B: dut
    - alpha3: nld
```

### Usage:

Copy/add files to your project

### Credits:

funky-monkey: https://github.com/funky-monkey/IsoCountryCodes
Jerryzhao-z: https://github.com/Jerryzhao-z/angular-language-code