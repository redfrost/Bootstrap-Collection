Bootstrap 3
===========

#### Custom Setting:

1. Customise: http://getbootstrap.com/customize/
2. Uncheck Glyphicons (Use Font-awesome instead)
3. Change @grid-float-breakpoint > @screen-md-min
4. Change CSS `html { font-size: 62.5%; }` to `100%`
5. Add `container { width: 100% }`, then use `max-width` to control fluid width.
6. Use default grid `col-sm-x` in HTML markup.


#### Container width (30px gutter)
* 960 content width = 990px
* 994 content width = 1024px
* 1140 content width = 1170px
* 1170 content width = 1200px


#### Media Query Breakpoint

```
/*
768 × 1024 iPad
414 × 736 iPhone 6+
375 × 667 iPhone 6
320 × 568 iPhone 5
320 × 480 iPhone 4
*/



/* Bootstrap 3 Custom
—————————————————————————*/

/* Desktop */
@media (min-width: 1601px) { }

/* Laptops */
@media (min-width: 1200px) { }

/* Tablet Landscape */
@media (min-width: 992px) and (max-width: 1199px) { }

/* Tablet Portrait */
@media (min-width: 768px) and (max-width: 991px) { }

/* Mobile Landscape */
@media (max-width: 767px) { }

/* Mobile Portrait */
@media (max-width: 480px) { }

/* Mobile Legacy */
@media (max-width: 320px) { }

/* Print */
@media print { }
```





Bootstrap 2
===========

[1] Customised Bootstrap. 12 col / 960px content width.

- Number of columns: 12
- Column width: 58px
- Gutter width: 24px

[2] Uncheck All [Responsive] (*Uncheck Icons if using Font-Awesome)

[3] Download and rename to base.css(and ~.min.css)




## Optional
#### 978
- Content width: 978px (full width: 1002px)
- Number of columns: 12
- Column width: 54px
- Gutter width: 30px

#### 1170
- Content width: 1170px
- Number of columns: 12
- Column width: 70px
- Gutter width: 30px

#### iPad Portrait mode:
- Content width: 720px
- Number of columns: 12
- Column width: 38px
- Gutter width: 24px

#### iPad Landscape mode:
- Content width: 968px
- Number of columns: 12
- Column width: 55px
- Gutter width: 28px


