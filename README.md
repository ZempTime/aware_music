# AWARE

`albums with autonomous resequencing experiences`

## Setup instructions for Joe

```ruby 
# open up terminal in alfred
# in terminal, type:

cd code/aware_overtone
lein repl

use 'overtone.live)

#now you're good to go, for ex, try out this command:

(demo 7 (lpf (mix (saw [50 (line 100 1600 5) 101 100.5]))
                  (lin-lin (lf-tri (line 2 20 5)) -1 1 400 4000)))
```
