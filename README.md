If I call the html output produced by elm I get the buttons and functionality, if I use the js produced by elm, I don't see anything on screen...

[elm make as html](https://fabian20ro.github.io/elm-sample/out/main.html)

[elm make as js - not working](https://fabian20ro.github.io/elm-sample/out/main_js_not_working.html)

Does anyone have any idea what changes should I do main_js.html (or to the produced .js file) to make it work?

Use *gradlew build* to build.

Update:
[elm make as js - working](https://fabian20ro.github.io/elm-sample/out/main_js_working.html) as explained [here](https://groups.google.com/forum/#!topic/elm-discuss/KHga4wBxl68)
