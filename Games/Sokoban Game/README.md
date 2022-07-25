# Basic Sokban HTML and JavaScript Game

This is a basic implementation of the game Sokoban, but it's missing a few things intentionally and they're left as further exploration for the reader.

<img width="300" height="337" alt="" src="https://user-images.githubusercontent.com/2433219/104414591-c449eb00-552d-11eb-8454-4a631f3f5be2.png">

## Further Exploration

- More levels
  - Add more levels and have the next level start once the last one is finished
- Show number of moves
  - Keep track of how many times the player moves and display it. Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the number of moves to the screen
- Mobile and touchscreen support
  - Allow the game to be scaled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Support run length encoding 
  - [Run length encoding](http://www.sokobano.de/wiki/index.php?title=Level_format#Run_length_encoding) is a different way to encode the level that collapses the level data to a single line
- Support the `.sok` file format
  - Currently the code understands the `.sok` file format level symbols, but a full `.sok` file format [can have a lot of additional metadata](http://sokobano.de/wiki/index.php?title=Sok_format), including having multiple levels in a single file

**Important note:** I will answer questions about the code but will not add more features or answer questions about adding more features. This series is meant to give a basic outline of the game but nothing more.
  
## License

(CC0 1.0 Universal) You're free to use this game and code in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but appreciated.

## Other Basic Games

- [Snake](https://gist.github.com/straker/ff00b4b49669ad3dec890306d348adc4)
- [Pong](https://gist.github.com/straker/81b59eecf70da93af396f963596dfdc5)
- [Breakout](https://gist.github.com/straker/98a2aed6a7686d26c04810f08bfaf66b)
- [Tetris](https://gist.github.com/straker/3c98304f8a6a9174efd8292800891ea1)
- [Bomberman](https://gist.github.com/straker/769fb461e066147ea16ac2cb9463beae)
- [Frogger](https://gist.github.com/straker/82a4368849cbd441b05bd6a044f2b2d3)
- [Missile Command](https://gist.github.com/straker/afc4e2a30b6df772a5f9f6ef01751d41)
- [Doodle Jump](https://gist.github.com/straker/b96a4a68bd6d79cf75a833d98a2b654f)
- [Puzzle Bobble](https://gist.github.com/straker/afc5bedc7f4b4bc65ba8b05c435f6d32)
- [Helicopter](https://gist.github.com/straker/0d25ae9d235f6a62f8287fd36a097043)

## Support

Basic HTML Games are made possible by users like you. When you become a [Patron](https://www.patreon.com/straker), you get access to behind the scenes development logs, the ability to vote on which games I work on next, and early access to the next Basic HTML Game.

### Top Patrons

- Karar Al-Remahy
- UnbrandedTech