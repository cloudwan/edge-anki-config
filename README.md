# edge-anki-config

This project is used to store the track information for the anki edge use case. The track config provides a mapping from the real tile id's to our internal tile id's. The format is as follows:

Example for an oval course:

```json
[
	{"id": 1, "real_tile_id": 18, "type": "CURVE"},    
	{"id": 2, "real_tile_id": 10, "type": "STRAIGHT"},
    ...
]
```

Possible tile types:

```json
"CURVE"
"STRAIGHT"
"START_1"
"START_2"
```



