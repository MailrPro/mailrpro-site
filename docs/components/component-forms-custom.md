## Custom form controls

Custom select menus can be easily created for browsers that support the styles.

## Example html
<select class="custom-select">
  <option>Default</option>
  <option>First option</option>
  <option>Another option</option>
  <option>Alternative</option>
  <option>Last one</option>
</select>

<select class="custom-select custom-select-sm">
  <option>Default</option>
  <option>First option</option>
  <option>Another option</option>
  <option>Alternative</option>
  <option>Last one</option>
</select>
## Endexample

Custom selects support the `disabled` attribute as well.

## Example html
<select class="custom-select" disabled>
  <option>Default</option>
  <option>First option</option>
  <option>Another option</option>
  <option>Alternative</option>
  <option>Last one</option>
</select>

<select class="custom-select custom-select-sm" disabled>
  <option>Default</option>
  <option>First option</option>
  <option>Another option</option>
  <option>Alternative</option>
  <option>Last one</option>
</select>
## Endexample

Custom checkboxes and radios are built on the default Bootstrap checkboxes and radios. Add a couple extra classes and the indicator and you should be all set.

## Example html
<div class="form-check custom-control custom-checkbox">
  <label class="form-check-label">
    <input class="form-check-input" type="checkbox">
    <span class="custom-control-indicator"></span>
    Check this custom checkbox
  </label>
</div>
## Endexample

They can be done inline, too.

## Example html
<div class="checkbox-inline custom-control custom-checkbox">
  <label>
    <input type="checkbox">
    <span class="custom-control-indicator"></span>
    Check this custom checkbox
  </label>
</div>
<div class="checkbox-inline custom-control custom-checkbox">
  <label>
    <input type="checkbox" checked>
    <span class="custom-control-indicator"></span>
    This custom checkbox is checked
  </label>
</div>
## Endexample

Same goes with radio inputs.

## Example html
<div class="radio custom-control custom-radio">
  <label>
    <input type="radio" id="radio1" name="radio">
    <span class="custom-control-indicator"></span>
    Toggle this custom radio
  </label>
</div>
<div class="radio custom-control custom-radio">
  <label>
    <input type="radio" id="radio2" name="radio">
    <span class="custom-control-indicator"></span>
    Or toggle this other custom radio
  </label>
</div>
## Endexample

And they can also be inline.

## Example html
<div class="radio-inline custom-control custom-radio">
  <label>
    <input type="radio" id="radio1" name="radio">
    <span class="custom-control-indicator"></span>
    Toggle this custom radio
  </label>
</div>
<div class="radio-inline custom-control custom-radio">
  <label>
    <input type="radio" id="radio2" name="radio">
    <span class="custom-control-indicator"></span>
    Or toggle this other custom radio
  </label>
</div>
## Endexample
