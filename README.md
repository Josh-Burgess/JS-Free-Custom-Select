# Scriptless Selects

Usually if you want to style a custom select, you need a
weighty plugin to either transliterate an existing select
into a listaffect a whole bunch of JavaScript originated styling
to that list, attach a bunch of custom event handlers to that
list and then force those handlers to update the original element.

It's cumbersome, heavy-handed, and ultimately unnecessary.

Scriptless Selects allows you to use native elements that
inherently allow styling to simulate a select experience without
all the overhead.

#How It Works

Scriptless selects use custom-styled radio button groups in
place of lists, and power all interactive features via CSS
as opposed to JavaScript.  This allows for faster load times
and solutions which work even when the client browser doesn't run
JS.

#Usage | Example

```
    
```