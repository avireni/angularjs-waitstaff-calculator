# AngularJS WaitStaff Calculator

A tool that helps wait staff at restaurants compute meal costs and track their tips over the course of a shift. Built with AngularJS, Bootstrap, HTMl5 and CSS3.

It has three routes and views, the index page, new meal to enter details of a meal, and earnings for wait staff's earnings in a shift.
The user enters details for a meal in the `New Meal` panel. The app validates that the value in each field is numeric when the user clicks on submit button. If the form is valid, the "Customer Charges" panel and data model for the My Earnings view is updated accordingly.

In the `Customer Charges` panel, Subtotal is the value of the base meal price plus tax. Tip is the dollar value of the tip, given the subtotal and tip percentage. Total is equal to subtotal plus tip.
The form resets to its initial state when the cancel button is clicked.

`Earnings view` tracks the tip and meal totals for the waiter on a given shift. The data presented in this view should changes as user adds new meals. If the user clicks the "Reset" button, the cumulative earnings data is zeroed out.

![Screenshot:](https://raw.githubusercontent.com/avireni/angularjs-waitstaff-calculator/gh-pages/app/assets/waitstaff.gif)
