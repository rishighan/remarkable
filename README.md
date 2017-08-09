# Remarkable

This is a fork of the original [remarkable](https://jonschlinkert.github.io/remarkable/demo/) project, with some modifications to the footnote rules.
The intent is to generate footnote markup that looks like:

```html
<!-- Links -->
<p>
    <sup id="fnref:1">
        <a href="#fn:1" rel="footnote">1</a>
    </sup>
</p>

<!-- Footnote List -->
<div class="footnotes">
    <ol>
        <li class="footnote" id="fn:1">
            <p>footnote. <a href="#fnref:1" title="return to article"> ↩</a><p>
        </li>
    </ol>
</div>
```

With this, you can use the excellent [littlefoot](https://github.com/goblindegook/littlefoot) library to generate in-place, mobile-friendly footnotes.

You can install this using `bower install https://github.com/rishighan/remarkable`