# http_ducks.cr
Web-API for httpducks.com ducks for every HyperText Transfer Protocol response status code

## Example
```cr
require "./http_ducks"

http_ducks = HttpDucks.new
status = http_ducks.get_status(403)
puts status
```
