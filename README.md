
# SmallExtensions

Small extensions for your day of developer .Net

[![CircleCI](https://circleci.com/gh/Lowpoc/SmallExtesions/tree/master.svg?style=svg)](https://circleci.com/gh/Lowpoc/SmallExtesions/tree/master)

## Release notes

- none

## Installation

Package Manager (Visual Studio):

```
Install-Package
```

.NET CLI:

```
dotnet add package 
```

## How use

```c#

# Strings
    string text = "asbcd 123";
    text.OnlyNumbers(); // 123
    text.OnlyAlphabet(); // asbcd
    text.RemoveAllWhiteSpaces(); // asbcd123
    text.Invert(); // 321 dcbsa
    text.IsNullOrEmpty(); // false
    text.Captalize(); // Asbcd 123
    text.In(caseSensitive: false, "asbcd");  // true
    text.In(caseSensitive: true, "AsbCd");  // false
    text.IsAlphaNumeric(); // true

# Dates

    var today = new Datetime(2019,11,14);
    var date = new DateTime(2018,11,14);

    datetime.Format(); // 14/11/2018
    datetime.LastDayOfTheMonth(); // new DateTime(2018,11,30)
    datetime.InTheSameMonthCurrent(); // true;
    datetime.Yesterday(); // new DateTime(2018,11,13)
    
```

## Contact us

If you have any questions, detect a bug or need a new feature, please, fell free to [open a new issue](https://github.com/Lowpoc/SmallExtesions/issues) on GitHub.