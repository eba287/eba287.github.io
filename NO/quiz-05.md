## Quiz 05 responses:

1.  Script solution:

```JavaScript
  console.log(hiCraters.features[2].properties.elevation_ft);
```

2.  `byElev()` is a method, which is a function associated with a particular object.

3.  Script solution:

```JavaScript
  var result = hiCraters.byElev(100);
  console.log(result);
```

4.  Script solution:

```JavaScript
  var newCrater =
  {
      "properties": {
          "name": "Chain of Craters",
          "class": "Crater",
          "elevation_ft": 3110
      },
      "geometry": {
          "type": "Point",
          "coordinates": [-155.185318, 19.3709116]
      }
    }

  hiCraters.features.push(newCrater);
  console.log(hiCraters.features);
```

5. Bonus question: See code in quiz.html file for partial solution
