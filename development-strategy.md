# Calculator-Refactor

[wireframe](https://wireframe.cc/e9wTvJ)

## DOM

| tag name | attributes | role |
| --- | --- | --- |
|Form | none | Calculator Container|
|input | id= "value1" | It will take the first value inserted by the user|
|input | id= "value2"  | It will take the second value inserted by the user|
|select | id= "operator" | To select the mathematical operation|
|h2 | id= "result" | Will show the result|

## Styling

| class name | description | role |
| --- | --- | --- |
| body  | Apply the general styles for the whole webpage | format styles |
| .Container | Apply  styles for the container | format styles |
| #calculate | Apply  styles for the button| format styles |

## Listeners

| type | attached to | callback |
| --- | --- | --- |
|Click event | To the button with the id = "calculate"| function calculateHandler(event)|

## Handlers

| syntax | parameters | return value | behavior |
| --- | --- | --- | --- |
| function calculateHandler(event)| a, b, op | boolean | Pass the data entered by the user to the logic and then show the results|

## Logic

| syntax | parameters | return value | behavior |
| --- | --- | --- | --- |
|const doMathTests |  a, b, operation| A number if the operation is valid, a string if the operation is invalid| Makes mathematical operations and controls|

