# lichess-bot

This is a [lichess-bot](https://github.com/lichess-bot-devs/lichess-bot) fork, but adapted to support
[my engine](https://github.com/Guilherme-Vasconcelos/chessy).

I have adapted the project to use pyproject.toml instead of requirements.txt, so in order to run it:

1. Create and make available in your environment a lichess OAuth token as described [here](./wiki/How-to-create-a-Lichess-OAuth-token.md).
2. `python3 -m venv .venv`
3. `poetry install`
4. `poetry run lichessbot`

## License
lichess-bot is licensed under the AGPLv3 (or any later version at your option). Check out the LICENSE file for the full text.
