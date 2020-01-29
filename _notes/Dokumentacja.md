# Wszystko co jest związane z pisaniem dokumentacji


## Po co to wszystko

Jak to piszę jestem w trakcie tworzenia mojej pracy inżynierskiej i doszedłem do wniosku, że napisanie kodu oby napisać jest totalnie bez sensu i chciałbym to jeszcze dobrze udokumentować, żeby za pół roku wiedzieć co i jak. Drugą rzeczą, którą muszę brać pod uwage to fakt, że sam będę używał tego oprogramowania a co za tym utrzymywał kod co wiąże się z pierwszym będę musiał dobrze udokumentować nie tylko jak to działa ale także wszystkie elementy aplikacji. Kolejnym trzecim aspektem dlaczego właśnie chciałbym wspomnieć o dokumentacji jest fakt, że uwielbiam czytać dobrze napisaną dokumentację, gdzie nie muszę się wgryzać w kolejne jej elementy. Dobrze napisana dokumentacja sama się czyta.

Co powinienem wiedzieć przed napisaniem dokumentacji ?

Jako że praca dyplomowa rządzi się swoimi prawami więc zakres tego artykułu będzie troszeczkę inny. Pisanie tego wpisu zajęło mi trochę czasu z powodu takiego, że wiele aspektów chciałem sam przetestować i po krótce opisać tutaj. Co więc powinna zawierać taka dokumentacja? 
Poniżej zawarłem dla mnie najważniejesze punkty takiej dokumentacji.

[Świetny blog o tym, że powinno się pisać dobrą dokumentację](https://www.writethedocs.org/)

## Co powinna zawierać dokumentacja

1. Description
2. Link to a demo
3. Getting Started
        How to add any required JS/CSS
        Required markup structure
        Instantiation steps, if required
4. Working with source files (for people who want to use the uncompiled code)
5. Options and Settings (since my plugins are usually configurable)
6. Browser Compatibility
7. License

## Jak pisać dokumenty *.md MarkDown

[Ciekawy kurs jak pisać](https://www.markdowntutorial.com/)

_this_ -- italic

**this** -- bold

Naglówki -- 

#Header one
##Header two
###Header three
####Header four
#####Header five
#####Header six

Linki -- [Visit GitHub!](www.github.com)

Zdjęcia -- ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)

Cytat ---
> "In a few moments he was barefoot,<

Wypunktowania --
* one
* two
    * two one
    * two two
* three

[Synax MarkDown](https://daringfireball.net/projects/markdown/basics)
[Syntax MarkDown](https://www.markdownguide.org/basic-syntax/)

[Blog Jacob Kaplan-Moss](https://jacobian.org/)

[Producing Open Source Software](https://producingoss.com/)

[Read the Docs. Create, host and browse documentation](https://readthedocs.org/)

[Write The Docs](http://www.writethedocs.org) [GitHub](https://github.com/writethedocs/www)

[JSDoc](https://jsdoc.app/index.html)
Template do dokumentacji
https://github.com/nijikokun/minami
https://github.com/docstrap/docstrap
https://github.com/braintree/jsdoc-template
https://github.com/Surnet/swagger-jsdoc


[Documenting Javascript Projects](https://medium.com/4thought-studios/documenting-javascript-projects-f72429da2eea)

## Best practices for writing documentation:

1. Include A README file that contains
    * A brief description of the project
    * Installation instructions
    * A short example/tutorial
2. Allow issue tracker for others
3. Write an API documentation
    * What a function do
    * What the function's parameters or arguments are
    * What a function returns
4. Document your code
5. Apply coding conventions, such as file organization, comments, naming conventions, programming practices, etc.
6. Include information for contributors
7. Include citation information
8. Include licensing information
9. Link to your e-mail address at the end
10. List all the version of the files along with the major edits you did in each version

An important tip: Naming files should be descriptive and consistent!    