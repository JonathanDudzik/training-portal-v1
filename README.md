# TODO
* fix high severity vulnerability found with npm audit
* Make side-menu completely accessible with aria expanded
* quiz more readable by screen reader - use element.textCotent to create an on-page scoreboard for each question (use aria-live-region for screen readers)

# Development notes
* The order of your styles in the stylesheet are important. To change sass variables that Bulma uses (changes default Bulma behavior), define the rules BEFORE Bulma's Import. To overwrite sass variables that Bulma uses (keep Bulma's default behavior), define the rules AFTER Bulma's Import.