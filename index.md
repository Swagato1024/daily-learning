# Jun 11

**async function testing**

- done
- contex

```js
const fun = context.mock.fn(); // fun is a mock function

//we can define our mock function
const fun = context.mock.fn((x, y) => {
  x();
  y();
});
```

**Handling input in mvc**

> input controller can be keyboard conroller or anything.

> input controller will recieve the input in raw form, parse it and emit event.

> some controller will be there who will register event based on events, set up necessary environment, then start input controller.

> our model will be independent from input controller
