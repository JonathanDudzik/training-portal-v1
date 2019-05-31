# TODO
* fix high severity vulnerability found with npm audit
* side menu has hamburger on mobile

# Development notes
* The order of your styles in the stylesheet are important. To change sass variables that Bulma uses (changes default Bulma behavior), define the rules BEFORE Bulma's Import. To overwrite sass variables that Bulma uses (keep Bulma's default behavior), define the rules AFTER Bulma's Import.