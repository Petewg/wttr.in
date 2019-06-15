
One line output format
--
example:\
`curl -s wttr.in/Athens?format="%10%l%11%20%t%20:%20%w%20:%20%p%20:%20%s%20:%20%h%20:%20%C%20:%20%M%20:%20%P"`\
output:\
`►Athens◄ +33°C : ↓19 km/h : 0.0mm : 2019-06-15 21:23:35+02:00 : 32% : Partly cloudy : 12 : 1011hPa`

|format specifier|expected return value|sample output   
|:---:          |:---          |:---
%c | weather condition (one/two symbols) |  ☀ or ⛅️ 
%C | weather condition (textual)         | <samp>Partly cloudy</samp>
%l |   location                          | <samp>Athens</samp>  
%t |   temperature in C or F             | <samp>+32°C</samp> (or ±NNN°F) \*
%w |   wind direction (arrow) and speed in km/h | <samp>←22 km/h</samp>
%p |   rain height in millimeters               | <samp>0.5mm</samp>
%s |   a timestamp related to location (or something ?)\*    | <samp>2019-06-15 21:23:35+02:00</samp>
%h |   percentage humidity \*                   |  <samp>57%</samp>
%M |   prints an undetermined (yet) number \*     | <samp>12</samp>
%P |   atmospheric pressure in hectopascal   | <samp>1011hPa</samp>

<sup>\* verification and/or clarifications needed!</sup>

