# test-challenge-mobile

Maythaphon Reanthong Omise's QA Challenge

## Section 1
The food develiry test plan available [here](section-1.xlsx)

### Estimation time to test your test scenaiors
  ~3 min * 48 cases = 144 min

### Explain how to test or technique you use to create the test   scenarios in brief
  I use Orthogonal Array Testing technique to genterate all possible 48 out comes that compute from number type of inputs
  * Price: 2 ( >=200, <200)
  * Vehicle: 2 (BIKE,CAR)
  * Distance: 4 (0,10,15,31)
  * Food: 3 (Meal, Dessert, Meal&Dessert)
  
  Total out comes = 2 * 2 * 4 * 3 = 48

### Propose the test cases from your test plan that should be covered by Automation Testing and why you selected those test cases
  I think all of my cases can be covered by Automation testing

## Section 2
Mobile test design available [here](section-2.xlsx)

## Section 3
[The test collection](section-3.json) require [Postman](https://www.postman.com/) to execute and this test collection is using https://reqres.in/ as an API endpoint.


### Test steps
![Alt text](img/step1.jpg?raw=true "Step 1")

![Alt text](img/step2.jpg?raw=true "Step 2")

![Alt text](img/step3.jpg?raw=true "Step 3")

![Alt text](img/step4.jpg?raw=true "Step 4")

![Alt text](img/step5.jpg?raw=true "Step 5")

![Alt text](img/result.jpg?raw=true "Result")