## What was New in 3.3.0

### Light Proxy Color Enhancements
This release of the 3.3.0 beta Proxy and Protocol Guide has been delivered to support the Light Proxy’s new color management functionality. This includes:

### Capabilities
[color\_correlated\_temperature\_max][1]

[color\_correlated\_temperature\_min][2]

[color\_rate\_behavior][3]

[color\_rate\_max][4]

[color\_rate\_min][5]

[color\_trace\_tolerance][6]

[supports\_color][7]

[supports\_color\_correlated\_temperature][8]


###  Commands

[SET\_COLOR\_TARGET][9]


###  Conversion Commands

This section lists the [Commands][10] used for converting to/from hue, saturation and lightness (HSV) and red, blue and green (RGB).


###  Conditionals
[IS\_COLOR][11]

###  Notifications
[LIGHT\_COLOR\_CHANGED][12]

[LIGHT\_COLOR\_CHANGING][13]


###  Events
[light\_color\_changed][14]

[light\_color\_changing][15]


###  Extras
New supporting [documentation][16].


### Advanced Lighting Scene Agent 
New supporting [documentation][17].


### Light Driver Development Best Practices
A new section has been added to the Light V2 proxy content including [best practice recommendations][18] for light driver developers.




[1]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-capabilities-color_correlated_temperature_max
[2]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-capabilities-color_correlated_temperature_min
[3]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-capabilities-color_rate_behavior
[4]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-capabilities-color_rate_max
[5]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-capabilities-color_rate_min
[6]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-capabilities-color_trace_tolerance
[7]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-capabilities-supports_color
[8]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-capabilities-supports_color_correlated_temperature
[9]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-commands-set_color_target
[10]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-conversion-commands
[11]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-conditionals
[12]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-protocol-notifications-light_color_changed
[13]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-protocol-notifications-light_color_changing
[14]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-events
[15]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-events
[16]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-v2-extras-interface-library
[17]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#advanced-lighting-scene-agent
[18]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#light-driver-development-best-practices