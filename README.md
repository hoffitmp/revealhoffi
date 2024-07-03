# revealhoffi

demo reveal.js (see [reveal.js](https://revealjs.com/))

# how this was created:

```bash
cd <root>
git clone https://github.com/hakimel/reveal.js.git
mkdir myslidesdemo
cd myslidesdemo
cp     ../reveal.js/index.html ./
cp -rf ../reveal.js/css        ./
cp -rf ../reveal.js/dist       ./
cp -rf ../reveal.js/js         ./
cp -rf ../reveal.js/plugin     ./
```
## trouble-shooting

referencing an external file only works when file is served via a web server, e.g.:

```bash
python -m http.server 8080
```
