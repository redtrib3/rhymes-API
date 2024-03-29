[![Deploy](https://button.deta.dev/1/svg)](https://deta.space/)

# Rhymes API
API to GET rhymes for a specific word.

## Documentation [/docs](https://rhymesapi-1-a5530429.deta.app/docs) :

![Screenshot at 2022-09-24 15-09-57](https://user-images.githubusercontent.com/68897241/192091283-b74faa97-8d31-48ee-b2d9-ffb8f59b35a8.png)

## Endpoints:
```
    |_. /rhyme/{word}
      [parameters: count= return count]
```
### Example:
  URL: ` https://rhymesapi-1-a5530429.deta.app/example?count=4 `

### Output:
```
{
    "example": [
        "ampal", 
        "ample", 
        "hampel", 
        "hample"
    ], 
    "COUNT": 4, 
    "maxCount": 8
}
```

# Made with [FastAPI](https://fastapi.tiangolo.com/) :
![FastAPI_logo](https://user-images.githubusercontent.com/68897241/192091105-9411e961-6e57-484a-951d-865224450fbe.png)


Old URLs:  ~~https://rhymes.herokuapp.com/docs/~~
        :  ~~https://zgzert.deta.dev/docs~~
