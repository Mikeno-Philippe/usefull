# usefull-package

Usefull triggers for date-time, bin/hex.dec conversions and strings with [Espanso](https://espanso.org/) package!

# Installation

Make sure you have already installed [Espanso](https://espanso.org/install/) first.

```
espanso install usefull-package
```

That's all. You can start using the package. Open your favorite editor and type triggers to test!

# Preview

You can choose between all of them from the Search-bar:
![Search-bar](images/search-bar.jpg)

# Global variables

Used variables with explanation

|  Variable         | Explanation                                                                       |
| ----------------- | --------------------------------------------------------------------------------- |
| `binPrefix`       | `Prefix for result of conversion with binary numbers (empty string for no symbol)`|
| `hexPrefix`       | `Prefix for result of conversion with hex numbers (empty string for no symbol)`   |
| `decimals`        | `Number of digits after the decimal point`                                        |
| `dateFormatShort` | `"%d/%m/%Y"  as described under https://espanso.org/docs/get-started/`            |
| `dateFormatLong`  | `"%A%e %B %Y"  as described under https://espanso.org/docs/get-started/`          |

# Triggers

Trigger list with explanation

| Trigger | Description.                                          | Result                                |
| ------- | ----------------------------------------------------- | ------------------------------------- |
| `:dln`  | `Today's date (long)`.                                | Tuesday 9 January 2024                |
| `:dsn`  | `Today's date (short)`.                               | 09/01/2024                            |
| `:dst`  | `Tomorrow's date (short)`                             | 10/01/2024                            |
| `:dsy`  | `Yesterday's date (short)`                            | 08/01/2024                            |
| `:tn`   | `Current local time (tine now)`                       | 14h44                                 |
| `:dow`  | `Day of week :dow[1999-12-31]`                        | The weeksday for 1999-12-31 is Friday |
| `:days` | `Number of days since given date :days[1999-12-31]`   | 8775 days since 1999-12-31            |
| `:ip`   | `Public IP-address`                                   | 79.124.138.95                         |
| `:cal`  | `Gives result of math expression (:cal[(12-34)*0.2])` | -4.4                                  |
| `:hd`   | `Convert Hex to Dec (:hd[FF])`                        | 255                                   |
| `:dh`   | `Convert Dec to Hex (:dh[255])`                       | 0xFF                                  |
| `:bd`   | `Convert Bin to Dec (:bd[11111111])`                  | 255                                   |
| `:db`   | `Convert Dec to Bin (:db[255])`                       | 0b11111111                            |
| `:rev`  | `Reverse string in clipboard`                         | draobpilc                             |
           
# Contributions
If you feel like there's any important tag/snippet missing, feel free to create a Pull Request or open an issue in GitHub
