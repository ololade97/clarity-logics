# clarity-logics

When you run the below:

```
(index-of (list 1 2 3 4 5 6 7) 0)
```
It returns "none". Note that it doesn't revert.

Samething goes for the below:

```
(element-at (list 1 3 5 7 9) u5)
```

-----
------

Note that there could be a mistake when you want to get a particular value in a tuple:

Here's the tuple:
```
{username: "Ololade", age: 37}
```
Here's a mistake in value passed to age when you want to get its value - This is because you have to rewrite the value to get it:
```
(get age {username: "Ololade", age: 36})
```

