# Conversion Form

Form that converts equivalent values from one unit to another.

For starters, lets make a form that converts *Celcius* temperature
to *Fahrenheit*.

## Input

* A input field to capture Celcius temperature.
* A button to perform the calculation.

## Output

* use an appropriate HTML element to display the conversion results
  such as `<p>`, `<span>` or `<output>`

## Behaviour

The user will

1. enter the Fahrenheit value
1. press the "calculate" button
1. see the results displayed in the contents of output element

The output number format should be fixed to two decimal places.

The `<form>` should not submit so it should not have `action` or `method`
attributes. Rather, the button will have a JavaScript click event call the calculation function.
