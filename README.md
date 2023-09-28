# -IWA1
created a tallycount program using Javascript , html and css.
## (-) button:

|User story in Gherkin|
| ------ |
 |Scenario: User can decrement a number using the "-" button|
 |Given the initial number is 0|
| When the user clicks the "-" button|
|Then the number should decrease by 5|


|User story in Gherkin|
| ------ |
 |Scenario:User cannot decrement the number below the minimum limit|
 |Given the number is at the minimum limit (-10)|
| When the user clicks the "-" button|
|Then the number should remain at the minimum limit|
|  And the "-" button should be disabled|