# memtech people

Let's plot a map showing where we call come from! [Check it Out](https://memtech.github.io/people/)!

## How can I contribute?

1. Fork this repo.
2. Edit the `js/locations.js` file, and add an object to the `locations` array.
   You can look up your hometown's geographic coordinates on [Google Maps](https://www.google.com/maps/).
3. Save your edits, and send us a Pull Request!

### The locations array, what?

The `js/locations.js` file shoudl look something like this:

    var locations = [
      { name: 'wayne bills', origin: 'northaven, tn', latitude: 35.26507, longitude: -90.04078 },
      { name: 'brad montgomery', origin: 'lepanto, ar', latitude: 35.61046, longitude: -90.33114 },
      { name: 'stephen bramlett', origin: 'memphis, tn', latitude: 35.61195, longitude: -90.33113 }
    ]

Add a new entry that looks something like this (just copy one of the existing
entries and edit the values accordingly).

      { name: 'your name', origin: 'your town, state', latitude: 35.1234, longitude: -90.1234 },

That's it!
