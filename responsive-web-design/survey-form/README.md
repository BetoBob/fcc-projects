# Survey Form

* [freeCodeCamp example page](https://codepen.io/freeCodeCamp/full/VPaoNP)
* use `ALT + Shift + 5` to strikethrough completed User Stories
* limit amount of local files so code can be hosted on codepen.io

## User Stories

1. ~~I can see a title with `id="title"` in H1 sized text.~~

2. ~~I can see a short explanation with `id="description"` in P sized text.~~

### form

3. ~~I can see a `form` with `id="survey-form"`.~~

4. ~~Inside the form element, I am required to enter my name in a field with `id="name"`.~~

5. ~~Inside the form element, I am required to enter an email in a field with `id="email"`.~~

6. ~~If I enter an email that is not formatted correctly, I will see an HTML5 validation error.~~

7. ~~Inside the form, I can enter a number in a field with `id="number"`.~~

8. ~~If I enter non-numbers in the number input, I will see an HTML5 validation error.~~
9. ~~If I enter numbers outside the range of the number input, which are defined by the `min` and `max` attributes, I will see an HTML5 validation error.~~
10. ~~For the name, email, and number  input fields inside the form I can see corresponding labels that  describe the purpose of each field with the following ids: `id="name-label"`, `id="email-label"`, and `id="number-label"`.~~
11. ~~For the name, email, and number input fields, I can see placeholder text that gives me a description or instructions for each field.~~
12. ~~Inside the form element, I can select an option from a dropdown that has a corresponding `id="dropdown"`.~~
13. ~~Inside the form element, I can select a field from one or more groups of radio buttons. Each group should be grouped using the `name` attribute.~~
14. ~~Inside the form element, I can select several fields from a series of checkboxes, each of which must have a `value` attribute.~~
15. ~~Inside the form element, I am presented with a `textarea` at the end for additional comments.~~
16. ~~Inside the form element, I am presented with a button with `id="submit"` to submit all my inputs.~~

## concept

| Field                                    | Use                                                          |
| ---------------------------------------- | ------------------------------------------------------------ |
| name                                     | name                                                         |
| email                                    | email (required to enter raffle)                             |
| number (integer, min / max values)       | order number (required field; 4 digits)                      |
| dropdown (select one of several options) | store location (required)                                    |
| radio (select one of several options)    | rating (1 - 5) with a description of the rating next to it (required) |
| checkbox (multiple choice)               | compliments (friendly service, packaged with care, )         |
| textarea                                 | further suggestions                                          |

I am going to do a shipping survey. I will pretend this is for a local bakery with multiple locations in a metro area. This is a survey to rate their catering services.

## style

* Beto's Bakery lol
* get styling ideas from Panera Bread
  * background colors especially
* background image of a bakery
* content center justified
  * create class for form elements, space them out accordingly

## content

Description:

Thank you for ordering from Beto's Bakery! We'd appreciate if you filled out this survey so we can improve our delivery experience. Once this survey is completed, you will have the chance to win a $10 Beto's Bakery coupon! (Terms and Restrictions Apply)

