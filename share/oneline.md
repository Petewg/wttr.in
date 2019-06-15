
One line output format
--
example:\
`curl -s wttr.in/Athens?format="%10%l%11%20%t%20:%20%w%20:%20%p%20:%20%s%20:%20%h%20:%20%C%20:%20%M%20:%20%P"`\
output:\
`►Athens◄ +33°C : ↓19 km/h : 0.0mm : 2019-06-15 21:23:35+02:00 : 32% : Partly cloudy : 12 : 1011hPa`

|format specifier|expected return value|sample output   
|:--------------:|:--------------------|:------------
<b>%c</b> | weather condition (symbols) |  ☀ or ⛅️ 
<b>%C</b> | weather condition (textual)         | <samp>Partly cloudy</samp>
<b>%l</b> | location                          | <samp>Athens</samp>  
<b>%t</b> | temperature in Celsius or Fahrenheit (signed) | <samp>+32°C</samp> (or <samp>±NNN°F</samp> \*)
<b>%w</b> | wind direction (arrow) and speed in km/h | <samp>←22 km/h</samp>
<b>%p</b> | rain height in millimeters               | <samp>0.5mm</samp>
<b>%h</b> | humidity percentage                      |  <samp>57%</samp>
<b>%M</b> | Day number of Moon phase                 | <samp>12</samp>
<b>%m</b> | Moon phase (symbols)                      | 🌖 or 🌓
<b>%P</b> | atmospheric pressure in hectopascal   | <samp>1011hPa</samp>
<b>%s</b> | a timestamp related to location (or something ?)\*    | <samp>2019-06-15 21:23:35+02:00</samp>

<sup>\* verification and/or clarifications needed!</sup>

