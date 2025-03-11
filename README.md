To run this repo:

```sh
pip install -r requirements.txt
make html
```

Then start a server:

```sh
python -m http.server -d _build/html
```

Go to http://localhost:8000/notebook1.html

Observe that the the widgets (ipywidget and ipyleaflet) are NOT doubled on the page.
