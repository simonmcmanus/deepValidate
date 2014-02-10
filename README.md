#Deep Validate

Given two objects, check that the data given in the first object is present in the second object.

Also checks that the types of the two values are the same.


##Usage:
```
  validate('objects', obj1, obj2, function(name, failure, key, obj1, obj2) {
    console.log(obj1[key]);
  })
```
