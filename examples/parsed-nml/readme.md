# Parsed NML

> this is still very outdated

NML is parsed using the [NML parser](https://github.com/nml-lang/parser)

Its parsed with c# bit the examples here show it in json.
This is just for readability

Basic example

```json
//Root Object
{
    "styles": null,
    "title": "Basic example",

    // uiObject
    "rootUiObject": {
        "width": 250,
        "height": 200,
        "x": 0,
        "y": 0,
        "z": 0,
        "id": "canvas",
        "type": "Rectagle",
        "class": null,
        "textcolour": "colour.white",
        "background": "colour.black",
        "children": [
            //imgObject
            {
                //uiObject
                "base": {
                    "width": null,
                    "height": null,
                    "x": 100,
                    "y": 0,
                    "z": 0,
                    "id": null,
                    "type": "Image",
                    "class": null,
                    "textcolour": null,
                    "background": null,
                },
                "source": "pics/smallblue.png"
            },
            //imgObject
            {
                //uiObject
                "base": {
                    "width": null,
                    "height": null,
                    "x": 0,
                    "y": 0,
                    "z": 0,
                    "id": null,
                    "type": "Image",
                    "class": null,
                    "textcolour": null,
                    "background": null,
                },
                "source": "pics/logo.png"
            }
        ]
    }
}
```