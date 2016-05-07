# front_end_JS_framework_angular

## Demo

Create a `db.json` file in json-server folder

```json
{
  "dishes": [
    {
      "id": 0,
      "name": "Uthapizza",
      "image": "images/uthapizza.png",
      "category": "mains",
      "label": "Hot",
      "price": 4.99,
      "description": "A unique combination of Indian Uthappam (pancake) and Italian pizza, topped with Cerignola olives, ripe vine cherry tomatoes, Vidalia onion, Guntur chillies and Buffalo Paneer.",
      "comments": [
```

Start JSON Server

```bash
cd json-server
$ json-server --watch db.json
```

Use Gulp to watch live demo
```bash
in front_end_JS_framework_angular folder
gulp watch
```
