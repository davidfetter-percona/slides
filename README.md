= Slide deck template =

== Tips ==

- The main file to change is index.html, i.e. the slide deck itself.
- One way to get immediate feedback on write is with a spell that looks like this:
```
nohup npx browser-sync start -s -f $PWD --no-notify --port 9000 2>&1 > /dev/null &
```
