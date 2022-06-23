## Steps @qavajs/steps-wdio

### I open {memory} url &#9989;

Opens provided url

| param |  type  |   description   |
|:-----:|:------:|:---------------:|
|  url  | string | url to navigate |
example:
```gherkin
   When I open 'https://google.com' url
```


---
### I type {string} to {element} &#9989;

Type text to element

|  param  |  type   |   description   |
|:-------:|:-------:|:---------------:|
| element | Element | element to type |
|  value  | string  |  value to type  |
example:
```gherkin
   When I type 'wikipedia' to 'Google Input'
```


---
### I click {element} &#9989;

Click element

|  param  |  type   |   description    |
|:-------:|:-------:|:----------------:|
| element | Element | element to click |
example:
```gherkin
   When I click 'Google Button'
```


---
### I clear {element} &#9989;

Clear element

|  param  |  type   |   description    |
|:-------:|:-------:|:----------------:|
| element | Element | element to clear |
example:
```gherkin
   When I clear 'Google Button'
```


---
### I expect text of {element} element {validation} {memory} &#9989;

Verify that text of element satisfies condition

|   param    |  type   |    description     |
|:----------:|:-------:|:------------------:|
|  element   | Element |  element to clear  |
| validation | string  |  validation type   |
|   value    | string  |  expected result   |

example:
```gherkin
   Then I expect text of '#1 of Search Results' equals 'uno'
   Then I expect text of '#1 of Search Results' does not equal 'dos'
```


---
### template &#9989;&#10060;

Description

| param | type |    description    |
|:-----:|:----:|:-----------------:|
| param | type | param description |
example:
```gherkin
   When example
```
