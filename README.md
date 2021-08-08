# tasksToDo
## Run
* Add venv
```sh
python3 -m venv venv
```
* Activate venv
```sh
. venv/bin/activate
```
* Necessary facilities
```sh
pip3 install Flask mysql-connector-python Werkzeug
```
* Add neovim if used
```sh
pip3 install neovim pylint
```
* Export for development
```sh
export FLASK_APP=todo && export FLASK_ENV=development
```
* Flask run
```sh
flask run
```
