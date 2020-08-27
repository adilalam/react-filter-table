# filter react table with pagination

Features include:

- Flexible approach to data, with customisable functions
- Extensible styling API with
- Component Injection API for complete control over the UI behaviour
- Controllable state props and modular architecture
- Long-requested features like option groups, portal support, animation, and more

# Installation and usage

The easiest way to use react-select is to install it from npm and build it into your app with Webpack.

```
yarn add react-select
```

Then use it in your app:

```js
import React from "react";
import ReactFilterTable from "react-filter-and-pagination-table";

function App() {
  const createData = (name, calories, fat, carbs, protein) => {
    return { name, calories, fat, carbs, protein };
  };

  const rows = [
    createData("Cupcake", 305, 3.7, 67, 4.3),
    createData("Donut", 452, 25.0, 51, 4.9),
    createData("Eclair", 262, 16.0, 24, 6.0),
    createData("Frozen yoghurt", 159, 6.0, 24, 4.0),
    createData("Gingerbread", 356, 16.0, 49, 3.9),
    createData("Honeycomb", 408, 3.2, 87, 6.5),
    createData("Ice cream sandwich", 237, 9.0, 37, 4.3),
    createData("Jelly Bean", 375, 0.0, 94, 0.0),
    createData("KitKat", 518, 26.0, 65, 7.0),
    createData("Lollipop", 392, 0.2, 98, 0.0),
    createData("Marshmallow", 318, 0, 81, 2.0),
    createData("Nougat", 360, 19.0, 9, 37.0),
    createData("Oreo", 437, 18.0, 63, 4.0),
  ];

  return (
    <div className="App">
      <ReactFilterTable rows={rows} />
    </div>
  );
}

export default App;
```

## Props

Common props you may want to specify include:

- `rows` - rows as prosa(Array)

# Thanks

Thank you to everyone who has contributed to this project. It's been a wild ride.