# TODO
* fix high severity vulnerability found with npm audit
* correct screen reader with menu open/closed alert
* make main content and quiz modal more readable by screen reader - either absolutely position off screen (issues of links being tabbed to), Add a "skip to main content" link, or change focus to the main content element with JS and tabindex
* Add note for non-javascript users

# Development notes
* The order of your styles in the stylesheet are important. To change sass variables that Bulma uses (changes default Bulma behavior), define the rules BEFORE Bulma's Import. To overwrite sass variables that Bulma uses (keep Bulma's default behavior), define the rules AFTER Bulma's Import.