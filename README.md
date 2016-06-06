# d3-scale-chromatic

Sequential, diverging and categorical color scales from Cynthia A. Brewer’s [ColorBrewer](http://colorbrewer2.org) color schemes.

## Installing

If you use NPM, `npm install d3-scale-chromatic`. Otherwise, download the [latest release](https://github.com/d3/d3-scale-chromatic/releases/latest). You can also load directly from [d3js.org](https://d3js.org), either as a [standalone library](https://d3js.org/d3-scale-chromatic.v0.1.min.js) or as part of [D3 4.0](https://github.com/d3/d3). AMD, CommonJS, and vanilla environments are supported. In vanilla, a `d3_scale_chromatic` global is exported:

```html
<script src="https://d3js.org/d3-array.v0.7.min.js"></script>
<script src="https://d3js.org/d3-collection.v0.2.min.js"></script>
<script src="https://d3js.org/d3-color.v0.4.min.js"></script>
<script src="https://d3js.org/d3-format.v0.5.min.js"></script>
<script src="https://d3js.org/d3-interpolate.v0.8.min.js"></script>
<script src="https://d3js.org/d3-time.v0.2.min.js"></script>
<script src="https://d3js.org/d3-time-format.v0.3.min.js"></script>
<script src="https://d3js.org/d3-scale.v0.7.min.js"></script>
<script src="https://d3js.org/d3-scale-chromatic.v0.1.min.js"></script>
<script>

var ylGn5 = d3_scale_chromatic.scaleYlGn();

</script>
```

[Try d3-scale-chromatic in your browser.](https://tonicdev.com/npm/d3-scale-chromatic)

## API Reference

### Categorical

<a href="#scaleAccent" name="scaleAccent">#</a> d3.<b>scaleAccent</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/accent.png" width="100%" height="40" alt="Accent">

Constructs a new [ordinal scale](https://github.com/d3/d3-scale#ordinal-scales) with a range of eight categorical colors.

<a href="#scaleDark2" name="scaleDark2">#</a> d3.<b>scaleDark2</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/dark2.png" width="100%" height="40" alt="Dark2">

Constructs a new [ordinal scale](https://github.com/d3/d3-scale#ordinal-scales) with a range of eight categorical colors.

<a href="#scalePaired" name="scalePaired">#</a> d3.<b>scalePaired</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/paired.png" width="100%" height="40" alt="Paired">

Constructs a new [ordinal scale](https://github.com/d3/d3-scale#ordinal-scales) with a range of twelve categorical colors.

<a href="#scalePastel1" name="scalePastel1">#</a> d3.<b>scalePastel1</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/pastel1.png" width="100%" height="40" alt="Pastel1">

Constructs a new [ordinal scale](https://github.com/d3/d3-scale#ordinal-scales) with a range of nine categorical colors.

<a href="#scalePastel2" name="scalePastel2">#</a> d3.<b>scalePastel2</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/pastel2.png" width="100%" height="40" alt="Pastel2">

Constructs a new [ordinal scale](https://github.com/d3/d3-scale#ordinal-scales) with a range of eight categorical colors.

<a href="#scaleSet1" name="scaleSet1">#</a> d3.<b>scaleSet1</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/set1.png" width="100%" height="40" alt="Set1">

Constructs a new [ordinal scale](https://github.com/d3/d3-scale#ordinal-scales) with a range of nine categorical colors.

<a href="#scaleSet2" name="scaleSet2">#</a> d3.<b>scaleSet2</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/set2.png" width="100%" height="40" alt="Set2">

Constructs a new [ordinal scale](https://github.com/d3/d3-scale#ordinal-scales) with a range of eight categorical colors.

<a href="#scaleSet3" name="scaleSet3">#</a> d3.<b>scaleSet3</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/set3.png" width="100%" height="40" alt="Set3">

Constructs a new [ordinal scale](https://github.com/d3/d3-scale#ordinal-scales) with a range of twelve categorical colors.

### Diverging

<a href="#scaleBrBG" name="scaleBrBG">#</a> d3.<b>scaleBrBG</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/br-b-g.png" width="100%" height="40" alt="BrBG">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “BrBG” diverging color scheme.

<a href="#scalePRGn" name="scalePRGn">#</a> d3.<b>scalePRGn</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/p-r-gn.png" width="100%" height="40" alt="PRGn">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “PRGn” diverging color scheme.

<a href="#scalePiYG" name="scalePiYG">#</a> d3.<b>scalePiYG</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/pi-y-g.png" width="100%" height="40" alt="PiYG">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “PiYG” diverging color scheme.

<a href="#scalePuOr" name="scalePuOr">#</a> d3.<b>scalePuOr</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/pu-or.png" width="100%" height="40" alt="PuOr">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “PuOr” diverging color scheme.

<a href="#scaleRdBu" name="scaleRdBu">#</a> d3.<b>scaleRdBu</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/rd-bu.png" width="100%" height="40" alt="RdBu">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “RdBu” diverging color scheme.

<a href="#scaleRdGy" name="scaleRdGy">#</a> d3.<b>scaleRdGy</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/rd-gy.png" width="100%" height="40" alt="RdGy">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “RdGy” diverging color scheme.

<a href="#scaleRdYlBu" name="scaleRdYlBu">#</a> d3.<b>scaleRdYlBu</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/rd-yl-bu.png" width="100%" height="40" alt="RdYlBu">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “RdYlBu” diverging color scheme.

<a href="#scaleRdYlGn" name="scaleRdYlGn">#</a> d3.<b>scaleRdYlGn</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/rd-yl-gn.png" width="100%" height="40" alt="RdYlGn">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “RdYlGn” diverging color scheme.

<a href="#scaleSpectral" name="scaleSpectral">#</a> d3.<b>scaleSpectral</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/spectral.png" width="100%" height="40" alt="Spectral">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “Spectral” diverging color scheme.

### Sequential (Single Hue)

<a href="#scaleBlues" name="scaleBlues">#</a> d3.<b>scaleBlues</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/blues.png" width="100%" height="40" alt="Blues">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “Blues” sequential color scheme.

<a href="#scaleGreens" name="scaleGreens">#</a> d3.<b>scaleGreens</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/greens.png" width="100%" height="40" alt="Greens">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “Greens” sequential color scheme.

<a href="#scaleGreys" name="scaleGreys">#</a> d3.<b>scaleGreys</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/greys.png" width="100%" height="40" alt="Greys">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “Greys” sequential color scheme.

<a href="#scaleOranges" name="scaleOranges">#</a> d3.<b>scaleOranges</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/oranges.png" width="100%" height="40" alt="Oranges">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “Oranges” sequential color scheme.

<a href="#scalePurples" name="scalePurples">#</a> d3.<b>scalePurples</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/purples.png" width="100%" height="40" alt="Purples">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “Purples” sequential color scheme.

<a href="#scaleReds" name="scaleReds">#</a> d3.<b>scaleReds</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/reds.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “Reds” sequential color scheme.

### Sequential (Multi-Hue)

<a href="#scaleBuGn" name="scaleBuGn">#</a> d3.<b>scaleBuGn</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/bu-gn.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “BuGn” sequential color scheme.

<a href="#scaleBuPu" name="scaleBuPu">#</a> d3.<b>scaleBuPu</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/bu-pu.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “BuPu” sequential color scheme.

<a href="#scaleGnBu" name="scaleGnBu">#</a> d3.<b>scaleGnBu</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/gn-bu.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “GnBu” sequential color scheme.

<a href="#scaleOrRd" name="scaleOrRd">#</a> d3.<b>scaleOrRd</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/or-rd.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “OrRd” sequential color scheme.

<a href="#scalePuBuGn" name="scalePuBuGn">#</a> d3.<b>scalePuBuGn</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/pu-bu-gn.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “PuBuGn” sequential color scheme.

<a href="#scalePuBu" name="scalePuBu">#</a> d3.<b>scalePuBu</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/pu-bu.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “PuBu” sequential color scheme.

<a href="#scalePuRd" name="scalePuRd">#</a> d3.<b>scalePuRd</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/pu-rd.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “PuRd” sequential color scheme.

<a href="#scaleRdPu" name="scaleRdPu">#</a> d3.<b>scaleRdPu</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/rd-pu.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “RdPu” sequential color scheme.

<a href="#scaleYlGnBu" name="scaleYlGnBu">#</a> d3.<b>scaleYlGnBu</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/yl-gn-bu.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “YlGnBu” sequential color scheme.

<a href="#scaleYlGn" name="scaleYlGn">#</a> d3.<b>scaleYlGn</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/yl-gn.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “YlGn” sequential color scheme.

<a href="#scaleYlOrBr" name="scaleYlOrBr">#</a> d3.<b>scaleYlOrBr</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/yl-or-br.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “YlOrBr” sequential color scheme.

<a href="#scaleYlOrRd" name="scaleYlOrRd">#</a> d3.<b>scaleYlOrRd</b>(<i>n</i>)

<img src="https://raw.githubusercontent.com/d3/d3-scale-chromatic/master/img/yl-or-rd.png" width="100%" height="40" alt="Reds">

Constructs a new [sequential scale](https://github.com/d3/d3-scale#sequential-scales) with the unit [domain](https://github.com/d3/d3-scale#continuous_domain) [0, 1] and the “YlOrRd” sequential color scheme.
