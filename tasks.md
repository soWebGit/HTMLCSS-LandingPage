# Module 05 - Footer

## 5.1 - Footer

@footer The footer completes the landing page. It is divided into two sections - the footer links and a demonstration message. 

To style the footer open `main.css` and and create a rule that selects the `<footer>` element. Make it a flex container with `flex-wrap` enabled(`wrap`). Set `position` to `relative`, `z-index` to `0`, and minimum height to `330px`. Make the background color `black`. 

## 5.2 - Footer Sidebar

@footer-sidebar Dynamically set the content after the footer to `""`. **Hint: Use the `:after` pseudo-class.** This will create a sidebar. 

In the same rule(`footer:after`), Set the background color of the sidebar to `#a0a0a0` and set the width to `75%`.

Set the `position` of the sidebar to `absolute`. Now that the element is `absolute`, set top, bottom, left and right to `0`. Finally set `z-index` to `-1`.

## 5.3 - Lists

@lists All of the content contained in the footer is in unordered lists. To equally space these lists, create a `.lists` rule and set `flex` to `0 0 75%`. Add a gap between these columns that adds up to `30px`(left/right - `15px`). The top and bottom padding should be set to `40px`.

## 5.4 - Link Headers

@link-headers Each list has a header, so create a rule with a selector of `.link-header` and transform the text to `uppercase`. Set the font size to `16px` and font weight to `700`. Change the bottom margin to `15px`.

## 5.5 - Links
@links The anchor tags in the footer should receive the styling:
`white` text color, `uppercase`, font size of `12px`, and the padding should be set to `0 0 4px`. Whenever the link is hovered over set `text-decoration` to `underline`.

## 5.6 - Link Class Attributes

@link-class-attributes The first `<section>` in the 
`<footer>` should be given a class of `lists`. Add the `link-header` class to the following elements: 

- `<div>` in footer with contents `Customer Support`
- `<div>` in footer with contents `Company Info`
- `<div>` in footer with contents `Privacy &amp; Terms`
- `<div>` in footer with contents `Follow Us`

## 5.7 - Social Links

@social-links To help style the social links in the footer, create a rule that has a selector of `.social ul li` and sets the display to `inline-block`. 

The links in the social list (`.social ul li a`), should have the following styles: 

- `display` - `block`
- `width` and `height` - `23px`
- background size and position - `23px 23px` `center`

## 5.8 - Social Icons

@social-icons There are five anchor tags in the `<ul>` in the `Follow Us` list. These links will have icons for social media platforms. Create five classes `.twitter`, `.facebook`, `.instagram`, and `.pinterest`. Each rule should have a single declaration of `background-image`. Set this to the correct URL for each image. **Hint: Look in the `img` directory.**

## 5.9 - Social Class Attributes

@social-class-attributes Give the last `<div>` in the `<footer>` `<section>` the class `social`. Then, find the `<ul>` under the `Follow Us` `<div>`. To the first `<a>` apply the `twitter` class, second apply `facebook`, third apply `instagram`, and fourth apply `pinterest`.

## 5.10 - Newsletter Headers

@newsletter-headers Below the social icons there is a newsletter section. This block has two `<div>`'s that need styling. Create two rules, one that has the selector `.newsletter .link-header` and has the properties:

- `font-size` - `12px` 
- `font-weight` - `400`
- `margin-bottom` - `5px`

The second should have a selector of `.newsletter .link-subheader` and declarations that adjust the following: font style(`italic`), size(`12px`), weight(`400`), and a bottom margin(`15px`).

## 5.11 - Newsletter Form

@newsletter-form In this newsletter section there is also an `<input>` and a `<button>`. To select just this `<input>`create use the selector `.newsletter input`. The `<input>` should have a `border` of `1px solid #364147`,  `width` of `200px` and bottom margin of `10px`. 

Select just this `<button>` with `.newsletter button` and style it with these properties: 
- `width` - `150px`
- `min-width` - `auto`
- `text-transform` - `uppercase`
- `letter-spacing` - `1px`

## 5.12 - Newsletter Class Attributes

@newsletter-class-attributes In `index.html` find the `<div>` after the social icons `<ul>` and apply a class of `newsletter`. Give the nested `<div>` with the content `Email Updates` a class of `link-header`. In the `<div>` immediate below, apply a class of `link-subheader`.

## 5.13 - Pluralsight Demo Container

@pluralsight-demo-container The final section of the page is a notification that this site was made for demonstration purpose only. To style it, create a rule that has a selector of `.ps`, and add the following properties: 
 
- `flex` - `0 0 25%`
- `padding` - `40px 0`
- `color` - `#e5e5e5`
- `font-size` - `16px`

The Pluralsight logo in this section should have a `max-width` of `230px`.

## 5.14 - Pluralsight Demo Styles

@pluralsight-demo-styles Create a rule with the selector `.demo`  
and add a padding of `0 30px`. Before this `demo` section (`.demo:before`) add these properties: 

- `content` - `""`
- `display` - `block`
- `width` - `100%`
- `height` - `1px`
- `margin` - `30px 0`
- `background` - `linear-gradient(to right,#f05a28 0,#e80a89 100%)`

## 5.15 - Copyright

@copyright The final piece of the footer is the copyright. Create this one last rule, the selector `.copyright`, with the properties - flex(`0 0 75%`), padding(`10px 0`), font size(`12px`), and `center` align the text.

## 5.16 - Pluralsight Demo Class Attributes

@pluralsight-demo-class-attributes Locate the `<!-- PS DEMO -->` block in the `index.html` file. Give the `<section>` in this block the class `ps`. Give the nested `<div>` the class of `demo`. Give the copyright `<div>` the class of `copyright`.