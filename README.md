# Auto_Off

A Clone and Update of Mattias Fornander's Auto Off App for Hubitat, with acknowlegement of his original work.

This version converted Mattias Fornander's Auto Off to be a Parent/Child app instead of multiple instance. Once converted, features of Parent/child became possible, such as allowing a single "Debug" option to be distributed throughout the entire set of Children.

One major difference was that the original polls every minute looking for devices to turn off. This new version starts a timer when the switch turns On.
