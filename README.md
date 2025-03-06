## Favicon Games
A project that included classic games and the website favicon

Supports the following games:
- Pong
- Snake
- Breaker
- 2048
- Flappy bird

## How does it work?
Website favicons are typically referenced using a hyperlink to an icon file, either locally or from the web. Fortunately, the HTML canvas provides a method called `.toDataURL()`, which returns a data URL containing the image representation of the canvas in a specified format (defaulting to PNG). This data URL can then be used directly as the favicon.

The final process looks something like this (summarized):

Hidden HTML canvas -> .toDataURL -> encoded URL -> favicon