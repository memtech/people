# memtech people

Let's plot a map showing where we call come from! [Check it Out](memtech_people.geojson)!

## How?

1. Fork this repo.
2. Edit the `memtech_people.geojson` file, copy one of the _Feature_ objects,
   and change the `coordinates` to your hometown (you can look these up on
   google maps or [geojson.io](http://geojson.io).
3. Save your copy, push back up to your fork and send us a Pull Request.

## The feature object

...will look something like this:

    {
      "type": "Feature",
      "properties": {
        "marker-color": "#ff2600",
        "marker-size": "medium",
        "marker-symbol": ""
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -90.33113479614258,
          35.611953036068876
        ]
      }
    }

The part you want to change is the `coordinates`:

        "coordinates": [
          -90.33113479614258,
          35.611953036068876
        ]

Just change those two numbers. Once you push taht back up to your repo,
click on the file and github should render a map. If you see a marker on
your hometown, it worked!
