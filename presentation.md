# Title

the title

## Slide 1
A paragraph with some text and a [link](https://hakim.se).

---
## Slide 2
```clojure
(def lazy-fib
  (concat
   [0 1]
   ((fn rfib [a b]
        (lazy-cons (+ a b) (rfib b (+ a b)))) 0 1)))
```

---
## Slide 3
<p class="fragment">Fade in</p>
<p class="fragment fade-out">Fade out</p>
<p class="fragment highlight-red">Highlight red</p>
<p class="fragment fade-in-then-out">Fade in, then out</p>
<p class="fragment fade-up">Slide up while fading in</p>

<br/><a href="#/0">Back to the first</a>

---
## Horizontal Slide
------
- top content
- use cursor down

SPEAKERNOTES: don't forget to say that ...

xxxxxx
## Vertical Slide 1
    one

xxxxxx
## Vertical Slide 2
two
