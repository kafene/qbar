# Q bar - portable omnibar

- you can use [!bangs](https://duckduckgo.com/bang.html) from DuckDuckGo,
  for example, this will search videos on YouTube:

        homer's life !yt

- you can define your own bangs by editing source code
- your custom bangs can be used as keyword, so `mybang something` is same as `!mybang something`
- without bangs, it searches on Google
- first Google result is opened, if searched phrase ends with a `!` or `.`
- it process `?q=` parameter, so it can be set as default search engine
- it is only one html file with javascript, so it is pretty portable
