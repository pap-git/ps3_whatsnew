idk how should i make this
<h1>WIPPY WIP!!!!!</h1>

# sorta "What's New" information writeup to markdown from info.xml

> [!IMPORTANT]
> The document is absolutely messed up with my poor english so maybe it could be better with looking at og info.xml from files/info.xml

> [!TIP]
> todo: make fuckingly clear

# Banners
## Images
Working Image formats: `PNG/JPG, 485x405 resolution (to fill the space)`
## SWFs
Working SWF formats: `SWF, Adobe Flash ≦9/Flash Script (Maybe ActionScript?) ≦1.5`
## Videos
Working Video formats: `FLV/MOV/MP4`

> [!TIP]
> <img width="228" height="138" alt="image" src="https://github.com/user-attachments/assets/aa9c4012-6725-4f85-9c48-1cf21a80b20b" />
> <img width="303" height="212" alt="image" src="https://github.com/user-attachments/assets/b79d1c43-1e75-42f5-a3c7-4bea62736d01" />
> 
> There's no mention about resolutions and codec about this things, so i looked up the mov files which is available in "Function Examples" of info.xml:
> and also the media folder stuff, so about the MP4 **resolutions and codecs are should be okay with**
> `1280x720 or less, H.264 codec`

## idk
GIF

# URL Types
For define what types of media are used in per item

PNG: `<url type="1">`

JPG: `<url type="2">`

GIF: `<url type="3">`

SWF: `<url type="72">`

MP4/FLV/MOV: `<target type="u">`

# Languages/Regions

These tags can be used to display the item in specific language and regions.

### Languages
```xml
<lang>0</lang>  Japanese
<lang>1</lang>  English
<lang>2</lang>  French
<lang>3</lang>  Espanish 
<lang>4</lang>  German
<lang>5</lang>  Italian
<lang>6</lang>  Dutch
<lang>7</lang>  Porguese 
<lang>7</lang>  Russian
<lang>9</lang>  Korean
<lang>10</lang> Chinese T
<lang>11</lang> Chinese S
<lang>12</lang> Finish
<lang>13</lang> Swedish
<lang>14</lang> Danish
<lang>15</lang> Norweigan
<lang>16</lang> Polish
<lang>17</lang> Portuguese BR
<lang>18</lang> English GB
<lang>19</lang> Turkish
```

### Regions
```xml
<cntry agelmt="0">ae</cntry>	<cntry agelmt="0">ar</cntry>	<cntry agelmt="0">at</cntry>	<cntry agelmt="0">au</cntry>	<cntry agelmt="0">be</cntry>
<cntry agelmt="0">bg</cntry>	<cntry agelmt="0">bh</cntry>	<cntry agelmt="0">bo</cntry>	<cntry agelmt="0">br</cntry>	<cntry agelmt="0">ca</cntry>
<cntry agelmt="0">ch</cntry>	<cntry agelmt="0">cl</cntry>	<cntry agelmt="0">cn</cntry>	<cntry agelmt="0">co</cntry>	<cntry agelmt="0">cr</cntry>
<cntry agelmt="0">cy</cntry>	<cntry agelmt="0">cz</cntry>	<cntry agelmt="0">de</cntry>	<cntry agelmt="0">dk</cntry>	<cntry agelmt="0">ec</cntry>
<cntry agelmt="0">es</cntry>	<cntry agelmt="0">fi</cntry>	<cntry agelmt="0">fr</cntry>	<cntry agelmt="0">gb</cntry>	<cntry agelmt="0">gr</cntry>
<cntry agelmt="0">gt</cntry>	<cntry agelmt="0">hk</cntry>	<cntry agelmt="0">hn</cntry>	<cntry agelmt="0">hr</cntry>	<cntry agelmt="0">hu</cntry>
<cntry agelmt="0">id</cntry>	<cntry agelmt="0">ie</cntry>	<cntry agelmt="0">il</cntry>	<cntry agelmt="0">in</cntry>	<cntry agelmt="0">is</cntry>
<cntry agelmt="0">it</cntry>	<cntry agelmt="0">jp</cntry>	<cntry agelmt="0">kr</cntry>	<cntry agelmt="0">kw</cntry>	<cntry agelmt="0">lb</cntry>
<cntry agelmt="0">lu</cntry>	<cntry agelmt="0">mt</cntry>	<cntry agelmt="0">mx</cntry>	<cntry agelmt="0">my</cntry>	<cntry agelmt="0">ni</cntry>
<cntry agelmt="0">nl</cntry>	<cntry agelmt="0">no</cntry>	<cntry agelmt="0">nz</cntry>	<cntry agelmt="0">om</cntry>	<cntry agelmt="0">pa</cntry>
<cntry agelmt="0">pe</cntry>	<cntry agelmt="0">ph</cntry>	<cntry agelmt="0">pl</cntry>	<cntry agelmt="0">pt</cntry>	<cntry agelmt="0">py</cntry>
<cntry agelmt="0">qa</cntry>	<cntry agelmt="0">ro</cntry>	<cntry agelmt="0">rs</cntry>	<cntry agelmt="0">ru</cntry>	<cntry agelmt="0">sa</cntry>
<cntry agelmt="0">se</cntry>	<cntry agelmt="0">sg</cntry>	<cntry agelmt="0">si</cntry>	<cntry agelmt="0">sk</cntry>	<cntry agelmt="0">sv</cntry>
<cntry agelmt="0">th</cntry>	<cntry agelmt="0">tr</cntry>	<cntry agelmt="0">tw</cntry>	<cntry agelmt="0">ua</cntry>	<cntry agelmt="0">um</cntry>
<cntry agelmt="0">us</cntry>	<cntry agelmt="0">uy</cntry>	<cntry agelmt="0">ve</cntry>	<cntry agelmt="0">za</cntry>	<cntry agelmt="0">pepe</cntry>
```

## Functions

> i still dont know how these works...

`psgm`, `psvp`, `psns`

### `psgm`


## Functions Example

```xml
<!-- Start multiMAN (psgm) -->
<target type="u">psgm:play?id=BLES80608</target>

```
