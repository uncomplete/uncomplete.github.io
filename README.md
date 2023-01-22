# My resume

## Running locally

1. Clone repo locally
2. Use Docker. [This one](https://github.com/BretFisher/jekyll-serve) works well:
```
$> docker pull bretfisher/jekyll-serve
$> docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```
3. Open your browser to `localhost:4000`
