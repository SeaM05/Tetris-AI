# Tetris-AI
Tetris game with AI in python

* `tetris_game.py` is the main application.
* `tetris_model.py` is the data model for this game.
* `tetris_ai.py` is the AI part.

Run `tetris_game.py` from command line and you start to play or watch the AI playing.

```shell
$ python3 tetris_game.py
```

### Play manually

If you want play by yourself, you should comment out these line in `tetris_game.py`:

```python
# TETRIS_AI = None

from tetris_ai import TETRIS_AI
```

### Gmae Controlles

-   You use *up* key to rotate a shape.
-   *left* key to move left.
-   *right* key to move right.
-   *space* key to drop down current shape immediately.
-   *P* key to pause.
-   *R* key to restart.
