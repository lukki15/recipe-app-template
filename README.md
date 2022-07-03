# recipe app

build with hugo + tailwindcss + daisyUI

## Development

```
$ npx tailwindcss -i ./assets/css/input.css -o ./assets/css/index.css --jit --watch
```
and
```
$ hugo -D serve
```


## Deployment

```
$ npx tailwindcss -i ./assets/css/input.css -o ./assets/css/index.css --jit --minify
$ hugo --gc --minify
```