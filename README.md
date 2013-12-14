LolSpark
========

LolSpark is a web application providing a interface for the League of Legends API (https://developer.riotgames.com/).

It is still in early development and might not have all the necessary fonctionnalities yet.

I'll gladly accept every kind of help. Please report issues you find and/or propose pull requests.

Usage
-----

Just open index.html in any web browser.

There is currently a problem with Google Chrome as it forbids AJAX requests on "file://". You can just use a web server to distribute data (or launch one with "python -m SimpleHTTPServer" (it listens on http://localhost:8000/)).

This asks for your API Key for security reasons, I can't put my own on GitHub.


Using this code in another project
----------------------------------

This code is released under the MIT License, which means you are free to reuse it in any other project.

Everything related to the API is located in the 'spark' folder, you can contact me if you have any question.

Todo
-------

* Local caching
* I18N for league names, runes, masteries, ...
* More directives
* More filters
* Pretty interface, but I'm not really into CSS
* Python server for proxying/caching
* Minification task (Grunt ?)
* Web hosting
* Register the application to get a better API Key
* Profit... wait...



This product is not endorsed, certified or otherwise approved in any way by Riot Games, Inc. or any of its affiliates.