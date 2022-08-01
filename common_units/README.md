Tutorial 5
----------

Reference: [How to Use Common Units in CSS](https://www.digitalocean.com/community/tutorials/how-to-use-common-units-in-css)

Figcaptions describe a figure, so naturally should be distinct and less prominent visually. This could include a slightly lighter font color, or smaller text size.

Sub-pixel rendering happens "when a computer encounters a pixel calculation involving a decimal point and blends the color between pixels to apply a value less than 1px, causing a blurry edge." This is more common now because screens have improved resolution, so the physical size of a pixel has gotten smaller. However, the "pixel" unit of measurement hasn't (perhaps?) changed, so instead there are weird calculations (like pixel doubling) to account for higher resolution screens. 

When using percentages, the formula size / context = result will get you exactly where you need to be (as long as you remember to move the decimal 2 places). You have to keep the context, or default styles, or explicitly stated properties in mind when trying to figure out percentages, otherwise you might be getting accurate proportions. Scaling text size proportionally helps keeps your designs and layouts better in tact. BEST USE: WIDTH

EMs are a font-size relational unit. Simply, the font-size property defines exactly what size 1em will be. Where you can use width or font-size to determine percentages, you can only use ems in relation to font-size or an element's inherited font-size. You can also use ems more reliably on more properties (like margin or padding). You can use the same size / context = result formula, without needing to move the decimal or mulitply by 100. If you decide to round decimals, just do them consistently, whatever the preference is. 

EMs and REMs are very similar, but REM adds the additional ROOT to your thought process. EMs can change based on where you are in the stylesheet, but rems cannot since they are derived from the root element (most likely html or body). By default, rems are based on 16px, unless you specify something different at the top of your stylesheet. You have to have planned out some of the relationships- what do you want more proportional to the entire HTML base, vs single/one-off parent containers? Try to use good judgment. 