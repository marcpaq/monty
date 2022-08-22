# Blessed State

When you create a new account, your kingdom is in the _Unholy State_.
This state contains these knights and shrubberies:

```json
[
    {
        "id": "b8b71701-4811-46c3-a0d6-cc7827cef1fd",
        "name": "Sir Bors",
        "age": 18,
        "favoriteColor": "RED",
        "bestFriend": "",
        "shrubbery": [
            {
                "height": 0.5,
                "radius": 0.5,
                "volume": 0.3,
                "description": "nice and small",
                "price": 4
            }
        ]
    },
    {
        "id": "834b2f98-f5a9-4664-8ca9-562b8b8a1318",
        "name": "Sir Gawain",
        "age": 30,
        "favoriteColor": "GREEN",
        "bestFriend": "",
        "shrubbery": [
            {
                "height": 1.5,
                "radius": 2,
                "volume": 18.8,
                "description": "beautifully nice",
                "price": 300
            }
        ]
    },
    {
        "id": "1dae11c2-915a-43b8-9511-11036934728d",
        "name": "Sir Kay",
        "age": 32,
        "favoriteColor": "BLUE",
        "bestFriend": "",
        "shrubbery": [
            {
                "height": 0.2,
                "radius": 0.8,
                "volume": 0.4,
                "description": "nicer than Bors'",
                "price": 6
            }
        ]
    }
]
```

You can bring your kingdom to the _Blessed State_ by meeting these conditions:

- No new knight has been created from the _Unholy State_.
- Sir Bors' list of shrubberies contains four shrubberies.
- Sir Gawain and Sir Kay are dead.

To do this, make these calls to the service, in this order:

1. Update Sir Gawain's best friend to Sir Kay.
2. Update Sir Kay's best friend to be Sir Gawain.
3. Update Sir Bors' best friend to be Sir Kay.
4. Slay Sir Gawain.
5. Slay Sir Kay.

