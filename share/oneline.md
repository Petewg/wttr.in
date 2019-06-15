
One line output format
--
example:\
`curl -s wttr.in/Athens?format="%10%l%11%20%t%20:%20%w%20:%20%p%20:%20%s%20:%20%h%20:%20%C%20:%20%M%20:%20%P"`\
output:\
`►Athens◄ +33°C : ↓19 km/h : 0.0mm : 2019-06-15 21:23:35+02:00 : 32% : Partly cloudy : 12 : 1011hPa`

|format specifier|expected return value|sample output   
|:---:          |:---          |:---
%c | weather condition (one/two symbols) |  ☀ or ⛅️ 
%C | weather condition (textual)         | Partly cloudy
%l |   location                          | Athens  
%t |   temperature in C or F             | +32°C (or ±NNN°F) \*
%w |   wind direction (arrow) and speed in km/h | ←22 km/h
%p |   rain height in millimeters               | 0.5mm
%s |   a timestamp (related to location or what ?)\*    | 2019-06-15 21:23:35+02:00
%h |   percentage humidity \*                   |  57%
%M |   prints an undetermined (yet) number \*     | 12
%P |   atmospheric pressure in hectopascal   | 1011hPa

<sup>\* verification and/or clarifications needed!</sup>

