# Chess-Data
## Data from Chess.com
# Suggestions from Chess.com Folks

### @Nevfy
You should install "httr" and "jsonlite" modules and then it will be easy to manipulate with API data. Use install.packages() and library(). And then something like:

request = GET("https://api.chess.com/pub/player/davidjayjackson")
data = fromJSON(rawToChar(request$content))

### @CyberSensei
 R uses Python, so if you find any Python code/library interfacing with the API, you'll be set. Check Github here are some quick hits:

https://github.com/saradzhyanartur/chess.com

https://github.com/ytmimi/Chess.com-Public-Game-Data-API

Happy programming.
