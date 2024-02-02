# Modifying content

Access the file browser here: [https://filebrowser.tetras-libre.fr/](https://filebrowser.tetras-libre.fr/).

You will need to have the administration username and password.

Add content to the `www` folder, and it will be accessible at `https://files.tetras-libre.fr/`.

## Modifying IIIF Manifest metadata

Find the manifest you want, the `metadata` field will be at the bottom.

Add a new metadata field as a dict (don't forget to add a comma as you're adding it to a list). Each metadata field must have the following structure:

```json
{
    "label": {
        "en": [
            "Title"
        ],
        "fr": [
            "Titre"
        ]
    },
    "value": {
        "en": [
            "Content"
        ],
        "fr": [
            "Contenu"
        ]
    }
}
```