# memtech people

Let's plot a map showing where we call come from! [Check it Out](https://memtech.github.io/people/)!

## How can I contribute?

1. Fork this repo.
2. Edit the [`js/locations.js`](js/locations.js) file, and add an object to the `locations` array.
   You can look up your hometown's geographic coordinates on [Google Maps](https://www.google.com/maps/). (See below if you aren't sure how to do this)
3. Save your edits, and send us a Pull Request!

### Getting your coordinates

1. Find the location for on Google Maps. You can search for an adress but you can also click and drag to pinpoint an exact location.
2. The url will look something like `https://www.google.com/maps/place/Payne's+Bar-B-Q/@35.1182222,-90.0053115,17z/...`
3. Copy the two coordinates beginnig with the `@` symbol in the url; in the example above the coordinates would be `latitude: 35.1182222, longitude: -90.0053115`

### The locations array, what?

The [`js/locations.js`](js/locations.js) file should look something like this:

```js
    var locations = [
      { name: 'wayne bills', origin: 'northaven, tn', latitude: 35.26507, longitude: -90.04078 },
      { name: 'brad montgomery', origin: 'lepanto, ar', latitude: 35.61046, longitude: -90.33114 },
      { name: 'stephen bramlett', origin: 'memphis, tn', latitude: 35.61195, longitude: -90.33113 }
    ]
```

Add a new entry that looks something like this (just copy one of the existing
entries and edit the values accordingly).

```js
      { name: 'your name', origin: 'your town, state', latitude: 35.1234, longitude: -90.1234 },
```

That's it!
