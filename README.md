# Carl: Advanced Refusal Generator

Randomly reproduces a frustrating refusal phrase (courtesy of @rumseyc) in under 100 lines of Python!

## Examples
```
$ carl
I think I'm going to pass

$ carl
I'll join you next time
```

You can also create your own phrase list (it's just a JSON file with a variable named 'phrases' which has an array of strings as its value) and load it instead with:

```
$ carl -p other_phrases.json
```

## Dependencies
The script uses Python 3, and the following dependencies (`pip3 install <...>`):
* `docopt`
* `json`
