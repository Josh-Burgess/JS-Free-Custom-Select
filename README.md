# Scriptless Selects

Usually if you want to style a custom select, you need a
weighty plugin to either translate an existing select
into a list, apply a whole bunch of JavaScript originated styling
to that list, attach a load of custom event handlers to that
list and then force those handlers to update the original element.

It's cumbersome, heavy-handed, and ultimately unnecessary.

Scriptless Selects allows you to use native elements that
inherently allow styling to simulate a select experience without
all the overhead.

## How It Works

Scriptless selects use custom-styled radio button groups in
place of lists, and power all interactive features via CSS
as opposed to JavaScript.  This allows for faster load times
and solutions which work even when the client browser doesn't run
JS.

## Usage | Example

```
<div class="custom-select">
  <input id="custom-selector" type="radio" name="option_list" />
  <label for="custom-selector">
    <div class="cover"></div>
    <ul class="options">
      <li class="placeholder">Select an Option</li>
      <li>
        <input id="option-selector-1-radio" type="radio" name="option_list" />
        <label for="option-selector-1-radio"><b>Option 1</b></label>
      </li>
      <li>
        <input id="option-selector-2-radio" type="radio" name="option_list" />
        <label for="option-selector-2-radio"><i>Option 2</i></label>
      </li>
      <li>
        <input id="option-selector-3-radio" type="radio" name="option_list" />
        <label for="option-selector-3-radio">Option 3</label>
      </li>
    </ul>
  </label>
</div>
```

**Rendered Output**

![closed select list](/../screenshots/screenshots/2015-08-25_21h45_16.png?raw=true "On initial load")

![open select list](/../screenshots/screenshots/2015-08-25_21h45_38.png?raw=true "After clicking on the select")
