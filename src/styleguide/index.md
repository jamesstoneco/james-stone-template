# The Grid

Please refer to the ZURB Foundation 6 documentation on the Flexbox grid.

#  Colors

The colors are shown below with their hex values for reference only. If using colors via CSS or Scss always default to the color variables shown.

## Brand Colors

The main colors used by the brand and design system.

<div class="row up-1 medium-up-3">
  <div class="column">
    <div class="color-block">
      <span style="background: #fa7252;"></span>
      $brand-primary: #fa7252;
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #ffffff;"></span>
      $brand-white: #ffffff;
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #000000;"></span>
      $brand-black: #000000;
    </div>
  </div>
</div>

## Text Colors

Colors of typography elements.


<div class="row up-1 medium-up-3">
  <div class="column">
    <div class="color-block">
      <span style="background: #828282;"></span>
      $text-body-copy: #828282;
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #565656;"></span>
      $text-headline: #565656;
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #aa9f9d;"></span>
      $text-subhead: #aa9f9d;
    </div>
  </div>
</div>

# UI Colors

Other colors used in the UI.

<div class="row up-1 medium-up-3">
  <div class="column">
    <div class="color-block">
      <span style="background: #f7f7f7;"></span>
      $ui-card-background-grey: #f7f7f7;
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #dcdcdc;"></span>
      $ui-outline-grey: #dcdcdc;
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #fbfbfd;"></span>
      $ui-section-grey: #fbfbfd;
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #d8d8d8;"></span>
      $ui-slider-bullet-grey: #d8d8d8;
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #acacac;"></span>
      $ui-shadow-color: #acacac;
    </div>
  </div>
</div>



# Scss Settings

```scss
// brand colors
$brand-primary: #fa7252;
$brand-white: #ffffff;
$brand-black: #000000;

// text colors
$text-body-copy: #828282;
$text-headline: #565656;
$text-subhead: #aa9f9d;

// ui colors
$ui-card-background-grey: #f7f7f7;
$ui-outline-grey: #dcdcdc;
$ui-section-grey: #fbfbfd;
$ui-slider-bullet-grey: #d8d8d8;
$ui-shadow-color: #acacac;

// ui shadow settings
$ui-shadow-opacity: 0.5;
$ui-shadow-blur: 24px;
$ui-shadow-offset-x: 6px;
$ui-shadow-offset-y: $ui-shadow-offset-x;

// fonts

$brand-font-body-copy: "proxima-nova", 'Helvetica Neue', Helvetica, Roboto, Arial, sans-serif;
$brand-font-headline: "brandon-grotesque", 'Helvetica Neue', Helvetica, Roboto, Arial, sans-serif;
$brand-font-button: $brand-font-headline;

// spacing vars

$brand-spacing-level-1: 50px;
$brand-spacing-level-2: $brand-spacing-level-1 * 2;
$brand-spacing-level-3: $brand-spacing-level-1 * 3;

$ui-radius: 4px;
$ui-radius-circle: 9999px;

```



# Typography

<h4>This design uses Brandon Grotesque for headings, subheads, and buttons.</h4>
<p>This design uses Proxima Nova for paragraph text.</p>

---

<h1>Heading Level 1</h1>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h2>Heading Level 2</h2>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h3>Heading Level 3</h3>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h4>Heading Level 4</h4>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h5>Heading Level 5</h5>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h6>Heading Level 6</h6>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.



# Coded Pair Example

This is some additional docs, to further explain the code example pair below. Maybe an `.additional-class` or `$variable` should be mentioned. Note the component below does not exist.

```html_example
<div class="row">
  <div class="column">
    <div class="callout secondary">
      <h3>James Stone Consulting</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Itaque soluta rem ipsam adipisci sequi, vitae reprehenderit velit est, iure et consequatur recusandae voluptates debitis assumenda facilis? Ut quisquam odio dolor.</p>
    </div>
  </div>
</div>
```
