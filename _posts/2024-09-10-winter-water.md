---
layout: post
title:  "What causes winter water warming in the Southern Ocean?"
date:   2024-09-10 
categories: 
        - research
---

{% newthought 'Winter Water' %} is a mode water that forms during austral summer in the Southern Ocean south of the subpolar front.

{% marginfigure 'mf-id-ww' 'assets/img/winter_water/spira_2024.png' 'Spira et al. 2024, “Winter Water in the austral summer” *Spira et al. (2024). The observed spatiotemporal variability of Antarctic Winter Water. Journal of Geophysical Research: Oceans.*'%}

In the winter it is the water that makes up the mixed layer and it thus cold from heat loss and salty from brine rejection. In the summer time, when sea ice melts, a fresh layer is formed above the winter water. This layer warms quickly and traps winter water beneath. Below the winter water is the warm (2°C) and salty Circumpolar Deep Water. 

During summer, this winter water layer warms and erodes, changes its density class and mixes with the waters above and below. It is thus a key mediator of water mass transformation and is thought to to be intermediary water in the pathway of water transformation from Circumpolar Deep Water to Antarctic Intermediate Water. 

{% marginfigure 'mf-id-mr' 'assets/img/winter_water/slocum_mr.png' '“A slocum with a microrider”, *Sarah Nicholson*'%}

The question addressed with this study is what physical process drives the warming of winter water in the summer time. We used exciting and novel observations of microstructure shear. 

## Turbulent processes

The intensity of turbulent mixing mediates the turbulent flux of a water property (like momentum, heat). By measuring the rate of dissipation of turbulent kinetic energy together with the background gradient of, for example, temperature, we can approximate the turbulent flux of heat. 

$$
F_H = K\frac{dT}{dz},
$$ where $$K = 0.2\frac{\varepsilon}{N^2}$$.  

<br><br>

{% maincolumn 'assets/img/winter_water/giddy_transects.png' 'Giddy et al. 2023, “Transects of temperature, stratification and dissipation at 60°S” *Giddy et al. (2023). Vertical Convergence of Turbulent and Double-Diffusive Heat Flux Drives Warming
and Erosion of Antarctic Winter Water in Summer. Journal of Physical Oceanography*'%}

### Drivers of turbulent mixing and heat flux into the winter water layer

By diagnosing the sources of shear production we attributed enhanced mixing at the base of the mixed layer to wind driven shear (using a first order Law of the wall approximation) and enhanced mixing at the base of the winter water layer to double diffusive convection (evidence of temperature steps). 

Following with a heat budget, we conclude that the warming trend is attributable to turbulent fluxes of heat.   
<br><br>


{% maincolumn 'assets/img/winter_water/giddy_timeseries.png' 'Giddy et al. 2023, “Timeseries of temperature tendency” *Giddy et al. (2023). Vertical Convergence of Turbulent and Double-Diffusive Heat Flux Drives Warming
and Erosion of Antarctic Winter Water in Summer. Journal of Physical Oceanography*'%}


Read the full article:  

 <cite>[Giddy et al., 2023. Vertical Convergence of Turbulent and Double-Diffusive Heat Flux Drives Warming
and Erosion of Antarctic Winter Water in Summer. Journal of Physical Oceanography
](http://www.doi.org/10.1175/JPO-D-22-0259.1)</cite>

<!-- ## Fundamentals

### Color

Although paper handouts obviously have a pure white background, the web is better served by the use of slightly off-white and off-black colors. I picked ```#fffff8``` and ```#111111``` because they are nearly indistinguishable from their 'pure' cousins, but dial down the harsh contrast. Tufte's books are a study in spare, minimalist design. In his book [The Visual Display of Quantitative Information](http://www.edwardtufte.com/tufte/books_vdqi), he uses a red ink to add some visual punctuation to the buff colored paper and dark ink. In that spirit, links are styled using a similar red color.

### Headings

Tufte CSS uses ```<h1>``` for the document title, ```<p>``` with class ```code``` for the document subtitle, ```<h2>``` for section headings, and ```<h3>``` for low-level headings. More specific headings are not encouraged. If you feel the urge to reach for a heading of level 4 or greater, consider redesigning your document:


> [It is] notable that the Feynman lectures (3 volumes) write about all of physics in 1800 pages, using only 2 levels of hierarchical headings: chapters and A-level heads in the text. It also uses the methodology of *sentences* which then cumulate sequentially into *paragraphs*, rather than the grunts of bullet points. Undergraduate Caltech physics is very complicated material, but it didn’t require an elaborate hierarchy to organize.

<cite>[http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0000hB](http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0000hB)</cite>


As a bonus, this excerpt regarding the use of headings provides an example of using block quotes. Markdown does not have a native ```<cite>``` shorthand, but real html can be sprinkled in with the Markdown text. In the previous example, the ```<cite>``` was preceded with a single return after the quotation itself. The previous blockquote was written in Markdown thusly:

```Liquid
[It is] notable that the Feynman lectures (3 volumes) write about all of physics in 1800 pages, using only 2 levels of hierarchical headings: chapters and A-level heads in the text. It also uses the methodology of *sentences* which then cumulate sequentially into *paragraphs*, rather than the grunts of bullet points. Undergraduate Caltech physics is very complicated material, but it didn’t require an elaborate hierarchy to organize.
<cite>[http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0000hB](http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0000hB)</cite>
```
{% sidenote 'two' '<cite>[http://www.edwardtufte.com/tufte/books_be](http://www.edwardtufte.com/tufte/books_be)<cite>'%},


{% newthought 'In his later books' %}{% sidenote 'two' '[http://www.edwardtufte.com/tufte/books_be](http://www.edwardtufte.com/tufte/books_be)'%}, Tufte starts each section with a bit of vertical space, a non-indented paragraph, and sets the first few words of the sentence in small caps. To accomplish this using this style, enclose the sentence fragment you want styled with small caps in a custom Liquid tag called 'newthought' like so:

```Liquid
{{ "{% newthought 'In his later books'" }} %}
```

### Text

In print, Tufte uses the proprietary Monotype Bembo{% sidenote 3 'See Tufte’s comment in the [Tufte book fonts](http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0000Vt) thread.' %} font. A similar effect is achieved in digital formats with the now open-source ETBembo, which Tufte-Jekyll supplies with a ```@font-face``` reference to a .ttf file. Thanks to [Linjie Ding](https://github.com/daveliepmann/tufte-css/commit/0a810a7d5f4707941c6f9fe99a53ec41f50a5c00), italicized text uses the ETBembo Italic font instead of mechanically skewing the characters. In case ETBembo somehow doesn’t work, Tufte CSS degrades gracefully to other serif fonts like Palatino and Georgia. Notice that Tufte CSS includes separate font files for **bold** (strong) and *italic* (emphasis), instead of relying on the browser to mechanically transform the text. This is typographic best practice. It’s also really important. Thus concludes my unnecessary use of em and strong for the purpose of example.

Code snippets ape GitHub's font selection using Microsoft's [*Consolas*](http://www.microsoft.com/typography/ClearTypeFonts.mspx) and the sans-serif font uses Tufte's choice of Gill Sans. Since this is not a free font, and some systems will not have it installed, the free google font [*Lato*](https://www.google.com/fonts/specimen/Lato) is designated as a fallback. -->

<!-- 

<h2 id="epigraphs">Epigraphs</h2>

{% epigraph 'The English language . . . becomes ugly and inaccurate because our thoughts are foolish, but the slovenliness of our language makes it easier for us to have foolish thoughts.' 'George Orwell' ' "Politics and the English Language" ' %}

{% epigraph 'For a successful technology, reality must take precedence over public relations, for Nature cannot be fooled.' 'Richard P. Feynman' ' “What Do You Care What Other People Think?” ' %}



If you’d like to introduce your page or a section of your page with some quotes, use epigraphs. The two examples above show how they are styled. Epigraph elements are modeled after chapter epigraphs in Tufte’s books (particularly *Beautiful Evidence*). The [Tufte-css](https://github.com/edwardtufte/tufte-css) gitub repository has detailed instructions on how to achieve this using HTML elements. As an easier alternative, the *Tufte-jekyll* theme uses custom *Liquid tag* pairs that allow the writer to embed elements such as epigraphs in the middle of the regular Markdown text being edited. 

In order to use an epigraph in a page or section, type this:

```{{ "{% epigraph 'text of citation' 'author of citation' 'citation source' "}} %}```

to produce this:

{% epigraph 'I do not paint things, I paint only the differences between things.' 'Henri Matisse' 'Henri Matisse Dessins: thèmes et variations, 1943' %}

{% epigraph  ' "How did you go bankrupt?" Two ways. Gradually, then suddenly.' 'Ernest Hemingway' ' "The Sun Also Rises" '%}

### Lists

Tufte points out that while lists have valid uses, they tend to promote ineffective writing habits due to their “lack of syntactic and intellectual discipline”. He is particularly critical of hierarchical and bullet-pointed lists. So before reaching for an HTML list element, ask yourself:

* Does this list actually have to be represented using an HTML ul or ol element?
* Would my idea be better expressed as sentences in paragraphs?
* Is my message causally complex enough to warrant a flow diagram instead?

This is but a small subset of a proper overview of the topic of lists in communication. A better way to understand Tufte’s thoughts on lists would be to read “The Cognitive Style of PowerPoint: Pitching Out Corrupts Within,” a chapter in Tufte’s book *Beautiful Evidence*, excerpted at some length by Tufte himself [on his website](http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0002QF). The whole piece is information-dense and therefore difficult to summarize. He speaks to web design specifically, but in terms of examples and principles rather than as a set of simple do-this, don’t-do-that prescriptions. It is well worth reading in full for that reason alone.

For these reasons, Tufte CSS encourages caution before reaching for a list element, and by default removes the bullet points from unordered lists.

## Figures

### Margin Figures

{% marginfigure 'mf-id-1' 'assets/img/rhino.png' 'F.J. Cole, “The History of Albrecht Dürer’s Rhinoceros in Zoological Literature,” *Science, Medicine, and History: Essays on the Evolution of Scientific Thought and Medical Practice* (London, 1953), ed. E. Ashworth Underwood, 337-356. From page 71 of Edward Tufte’s *Visual Explanations*.'  %}

Images and graphics play an integral role in Tufte’s work. To place figures in the margin, use the custom margin figure liquid tag included in the ```_plugins``` directory like so:

```{{ "{% marginfigure 'mf-id-whatever' 'assets/img/rhino.png' 'F.J. Cole, “The History of Albrecht Dürer’s Rhinoceros in Zoological Literature,” *Science, Medicine, and History: Essays on the Evolution of Scientific Thought and Medical Practice* (London, 1953), ed. E. Ashworth Underwood, 337-356. From page 71 of Edward Tufte’s *Visual Explanations*.' "}} %}```.

Note that this tag has *three* parameters. The first is an arbitrary id. This parameter can be named anything as long as it is unique to this post. The second parameter is the path to the image. And the final parameter is whatever caption you want to be displayed with the figure.  All parameters *must* be enclosed in quotes for this simple liquid tag to work! 

In this example, the *Liquid* marginfigure tag was inserted *before* the paragraph so that it aligns with the beginning of the paragraph. On small screens, the image will collapse into a small symbol: <span class="contrast ">&#8853;</span> at the location it has been inserted in the manuscript. Clicking on it will open the image.

```{{ "{% marginfigure 'mf-id-whatever' 'assets/img/rhino.png' 'F.J. Cole, “The History of Albrecht Dürer’s Rhinoceros in Zoological Literature,” *Science, Medicine, and History: Essays on the Evolution of Scientific Thought and Medical Practice* (London, 1953), ed. E. Ashworth Underwood, 337-356. From page 71 of Edward Tufte’s *Visual Explanations*.' "}} %}```.

### Full Width Figures

If you need a full-width image or figure, another custom liquid tag is available to use. Oddly enough, it is named 'fullwidth', and this markup:

```{{ "{% fullwidth 'assets/img/napoleons-march.png' 'Napoleon's March *(Edward Tufte’s English translation)*' "}} %}```

Yields this:

{% fullwidth 'assets/img/napoleons-march.png' "Napoleon's March *(Edward Tufte’s English translation)*" %}


### Main Column Figures

Besides margin and full width figures, you can of course also include figures constrained to the main column. Yes, you guessed it, a custom liquid tag rides to the rescue once again:

```{{ "{% maincolumn 'assets/img/export-imports.png' 'From Edward Tufte, *Visual Display of Quantitative Information*, page 92' "}} %}```

yields this:

{% maincolumn "assets/img/exports-imports.png" "From Edward Tufte, *Visual Display of Quantitative Information*, page 92" %}

## Sidenotes and Margin notes

One of the most prominent and distinctive features of Tufte's style is the extensive use of sidenotes and margin notes. Perhaps you have noticed their use in this document already. You are very astute.

There is a wide margin to provide ample room for sidenotes and small figures. There exists a slight semantic distinction between *sidenotes* and *marginnotes*.

### Sidenotes

Sidenotes{% sidenote 'sn-id-whatever' 'This is a sidenote and *displays a superscript*'%} display a superscript. The *sidenote* Liquid tag contains two components. The first is an identifier allowing the sidenote to be targeted by the twitchy index fingers of mobile device users so that all the yummy sidenote goodness is revealed when the superscript is tapped. The second components is the actual content of the sidenote. Both of these components should be enclosed in single quotes. Note that we are using the CSS 'counter' trick to automagically keep track of the number sequence on each page or post. On small screens, the sidenotes disappear and when the superscript is clicked, a side note will open below the content, which can then be closed with a similar click. Here is the markup for the sidenote at the beginning of this paragraph:

```{{ "{% sidenote 'sn-id-whatever' 'This is a sidenote and *displays a superscript*'" }}%}```

### Margin notes

Margin notes{% marginnote 'mn-id-whatever' 'This is a margin note *without* a superscript' %} are similar to sidenotes, but do not display a superscript. The *marginnnote* Liquid tags has the same two components as the *sidenote* tag. Anything can be placed in a margin note. Well, anything that is an inline element. Block level elements can make the Kramdown parser do strange things. On small screens, the margin notes disappear and this symbol: <span class="contrast ">&#8853;</span> pops up. When clicked, it will open the margin note below the content, which can then be closed with a similar click. The Markdown content has a similar sort of markup as a sidenote, but without a number involved:

```{{ "{% marginnote 'mn-id-whatever' 'This is a margin note *without* a superscript'" }} %}```

## Equations

The Markdown parser being used by this Jekyll theme is Kramdown, which contains some built-in [Mathjax](//www.mathjax.org) support. Both inline and block-level mathematical figures can be added to the content.

For instance, the following inline sequence:

*When $$ a \ne 0 $$, there are two solutions to $$ ax^2 + bx + c = 0 $$*

is written by enclosing a Mathjax expression within *a matching pair of double dollar signs: ```$$```*:

```When $$ a \ne 0 $$, there are two solutions to $$ ax^2 + bx + c = 0 $$```

Similarly, this block-level Mathjax expression:

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$ -->
<!-- 
is written by enclosing the expression within a pair of ```$$``` with an empty line above and below:

```$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$```


You can get pretty fancy, for instance, the wave equation's nabla is no big thing:

$$ \frac{\partial^2 y}{\partial t^2}= c^2\nabla^2u $$


All of the standard <span class="latex">L<sup>a</sup>T<sub>e</sub>X</span> equation markup is available to use inside these block tags.

Please note that the block-level Mathjax expressions *must* be on their own line, separated from content above and below the block by a blank line for the Kramdown parser and the Mathjax javascript to play nicely with one another.

The Mathjax integration is tricky, and some things such as the inline matrix notation simply do not work well unless allowances are made for using the notation for a small matrix. Bottom line: If you are using this to document mathematics, be super careful to isolate your <span class="latex">L<sup>a</sup>T<sub>e</sub>X</span> blocks by blank lines!  

## Tables

Tables are, frankly,  a pain in the ass to create. That said, they often are one of the best methods for presenting data. Tabular data are normally presented with right-aligned numbers, left-aligned text, and minimal grid lines.

Note that when writing Jekyll Markdown content, there will often be a need to get some dirt under your fingernails and stoop to writing a little honest-to-god html. Yes, all that hideous ```<table>..<thead>..<th>``` nonsense. *And* you must wrap the unholy mess in a ```<div class="table-wrapper">``` tag to ensure that the table stays centered in the main content column.

Tables are designed with an ```overflow:scroll``` property to create slider bars when the viewport is narrow. This is so that you do not collapse all your beautiful data into a jumble of letters and numbers when you view it on your smartphone.

{% marginnote 'table-1-id' '*Table 1*: A table with default style formatting' %}
<div class="table-wrapper">
  <table class="table-alpha" id="newspaper-tone">
    <thead>
      <tr>
        <th class="left">Content and tone of front-page articles in 94 U.S. newspapers, October and November, 1974</th>
        <th class="left">Number of articles</th>
        <th>Percent of articles with negative criticism of specific person or policy</th></tr>
    </thead>
    <tbody>
      <tr>
        <td class="text">Watergate: defendants and prosecutors, Ford’s pardon of Nixon</td>
        <td><div class="number">537</div></td>
        <td class="c"><div class="number">49%</div></td>
      </tr>
      <tr>
        <td class="text">Inflation, high cost of living</td>
        <td><div class="number">415</div></td>
        <td class="c"><div class="number">28%</div></td>
      </tr>
      <tr>
        <td class="text">Government competence: costs, quality, salaries of public employees</td>
        <td><div class="number">322</div></td>
        <td class="c"><div class="number">30%</div></td>
      </tr>
      <tr>
        <td class="text">Confidence in government: power of special interests, trust in political leaders, dishonesty in politics</td>
        <td><div class="number">266</div></td>
        <td class="c"><div class="number">52%</div></td>
      </tr>
      <tr>
        <td class="text">Government power: regulation of business, secrecy, control of CIA and FBI</td>
        <td><div class="number">154</div></td>
        <td class="c"><div class="number">42%</div></td>
      </tr>
      <tr>
        <td class="text">Crime</td>
        <td><div class="number">123</div></td>
        <td class="c"><div class="number r">30%</div></td>
      </tr>
      <tr>
        <td class="text">Race</td>
        <td><div class="number">103</div></td>
        <td class="c"><div class="number">25%</div></td>
      </tr>
      <tr>
        <td class="text">Unemployment</td>
        <td><div class="number">100</div></td>
        <td class="c"><div class="number">13%</div></td>
      </tr>
      <tr>
        <td class="text">Shortages: energy, food</td>
        <td><div class="number">68</div></td>
        <td class="c"><div class="number">16%</div></td>
      </tr>
    </tbody>
  </table>
</div>


This is not the One True Table. Such a style does not exist. One must craft each data table with custom care to the narrative one is telling with that specific data. So take this not as “the table style to use”, but rather as “a table style to start from”. From here, use principles to guide you: avoid chartjunk, optimize the data-ink ratio (“within reason”, as Tufte says), and “mobilize every graphical element, perhaps several times over, to show the data.{% sidenote 'table-id' 'Page 139, *The Visual Display of Quantitative Information*, Edward Tufte 2001.'%} Furthermore, one must know when to reach for more complex data presentation tools, like a custom graphic or a JavaScript charting library.

As an example of alternative table styles, academic publications written in <span class="latex">L<sup>a</sup>T<sub>e</sub>X</span> often rely on the ```booktabs``` package to produce clean, clear tables. Similar results can be achieved in Tufte CSS with the ```booktabs``` class, as demonstrated in this table:

{% marginnote 'table-2-id' '*Table 2*: A table with booktabs style formatting' %}
<div class="table-wrapper">
<table class="booktabs">
          <thead>
            <tr><th colspan="2" class="cmid">Items</th><th class="nocmid"></th></tr>
            <tr><th class="l">Animal</th><th>Description</th><th class="r">Price ($)</th></tr>
          </thead>
          <tbody>
            <tr><td>Gnat</td>     <td>per gram</td><td class="r">13.65</td></tr>
            <tr><td></td>         <td>each</td>    <td class="r">0.01</td></tr>
            <tr><td>Gnu</td>      <td>stuffed</td> <td class="r">92.50</td></tr>
            <tr><td>Emu</td>      <td>stuffed</td> <td class="r">33.33</td></tr>
            <tr><td>Armadillo</td><td>frozen</td>  <td class="r">8.99</td></tr>
          </tbody>
</table>
</div>

The table above was written in HTML as follows:

```
<div class="table-wrapper">
<table class="booktabs">
          <thead>
            <tr><th colspan="2" class="cmid">Items</th><th class="nocmid"></th></tr>
            <tr><th class="l">Animal</th><th>Description</th class="r"><th>Price ($)</th></tr>
          </thead>
          <tbody>
            <tr><td>Gnat</td>     <td>per gram</td><td class="r">13.65</td></tr>
            <tr><td></td>         <td>each</td>    <td class="r">0.01</td></tr>
            <tr><td>Gnu</td>      <td>stuffed</td> <td class="r">92.50</td></tr>
            <tr><td>Emu</td>      <td>stuffed</td> <td class="r">33.33</td></tr>
            <tr><td>Armadillo</td><td>frozen</td>  <td class="r">8.99</td></tr>
          </tbody>
</table>
</div> -->
<!-- ```


{% newthought 'I like this style of table,' %}  so I have made it the default for unstyled tables. This allows use of the [*Markdown Extra*](https://michelf.ca/projects/php-markdown/extra/) features built into the [*Kramdown*](http://kramdown.gettalong.org/parser/kramdown.html) parser. Here is a table created using the Markdown Extra table syntax to make a nice table which has the side benefit of being human readable in the raw Markdown file:

{% marginnote 'tableID-3' 'Table 3: a table created with *Markdown Extra* markup using only the default table styling' %}

|                 |mpg  | cyl  |  disp  |   hp   |  drat  | wt  |
|:----------------|----:|-----:|-------:|-------:|-------:|----:|
|Mazda RX4        |21   |6     |160     |110     |3.90    |2.62 |
|Mazda RX4 Wag    |21   |6     |160     |110     |3.90    |2.88 |
|Datsun 710       |22.8 |4     |108     |93      |3.85    |2.32 |
|Hornet 4 Drive   |21.4 |6     |258     |110     |3.08    |3.21 |
|Hornet Sportabout|18.7 |8     |360     |175     |3.15    |3.44 |
|Valiant          |18.1 |6     |160     |105     |2.76    |3.46 |


Using the following Markdown formatting:

```
|                 |mpg  | cyl  |  disp  |   hp   |  drat  | wt  |
|:----------------|----:|-----:|-------:|-------:|-------:|----:|
|Mazda RX4        |21   |6     |160     |110     |3.90    |2.62 |
|Mazda RX4 Wag    |21   |6     |160     |110     |3.90    |2.88 |
|Datsun 710       |22.8 |4     |108     |93      |3.85    |2.32 |
etc...
```

The following is a more simple table, showing the Markdown-style table markup. Remember to label the table with a *marginnote* Liquid tag, and you *must* separate the label from the table with a single blank line. This markup:

```
{{ "{% marginnote 'Table-ID4' 'Table 4: a simple table showing left, center, and right alignment of table headings and data' "}} %}

|**Left** |**Center**|**Right**|
|:--------|:--------:|--------:|
 Aardvarks|         1|$3.50
       Cat|   5      |$4.23
  Dogs    |3         |$5.29
```

Yields this table:

{% marginnote 'Table-ID4' 'Table 4: a simple table showing left, center, and right alignment of table headings and data' %}

|**Left** |**Center**|**Right**|
|:--------|:--------:|--------:|
 Aardvarks|         1|$3.50
       Cat|   5      |$4.23
  Dogs    |3         |$5.29


## Code

Code samples use a monospace font using the 'code' class. The Kramdown parser has the 'GFM' option enabled, which stands for 'Github Flavored Markdown', and this means that both inline code such as ```#include <stdio.h>``` and blocks of code can be delimited by surrounding them with 3 backticks:

```
(map tufte-style all-the-things)
```
is created by the following markup:
<pre><code>```(map tufte-style all-the-things)```</code></pre>

To get the code highlighted in the language of your choice like so:


``` ruby
module Jekyll
  class RenderFullWidthTag < Liquid::Tag
  require "shellwords"

    def initialize(tag_name, text, tokens)
      super
      @text = text.shellsplit
    end

    def render(context)
      "<div><img class='fullwidth' src='#{@text[0]}'/></div> " +
      "<p><span class='marginnote'>#{@text[1]}</span></p>"
    end
  end
end

Liquid::Template.register_tag('fullwidth', Jekyll::RenderFullWidthTag)
```

Enclose the code block in three backticks, followed by a space and then the language name, like this:

<pre> <code>``` ruby
    module Jekyll
    blah, blah...
   ```</code> </pre>
 -->

