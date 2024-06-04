
## What was New in O.S.3

### Proxies that were Modified\*\* 


**Light (V2) Proxy**
LightV2 Proxy has been significantly enhanced in this release. It is recommended that Light Driver writers thoroughly review the Proxy content in this release. The changes included not only impact drivers written against OS 3. Previously delivered Light Proxy elements have been modified or in some cases deprecated. 

In OS 3, the proxy has been conceptually split into two components. The first being a Wall Control/Keypad portion and the second is a redesigned Light portion.The Light portion has been developed as a Bulb Library. The ultimate goal of the Bulb Library is to support ,more versatility for drivers to interrogate, group, control and manage individual drivers and bulbs. Bulb color, target level, minimum and maximum levels, cold start timing and other features are implemented in the Bulb Library. Dynamic Capabilities have also been added to the Light Portion. Note that all changes maintain backwards compatibility for driver side interaction. However, Navigators will have functionality deprecated due to performance reasons or improved ways of communicating with the driver.





