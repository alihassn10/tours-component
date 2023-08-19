# Tours Component

![Tours Component](https://github.com/alihassn10/tours-component/blob/main/demo.gif)

Tours Component is a reusable React component that allows you to display a list of tours or activities with descriptions, images, and toggleable details. This component is designed to be easily integrated into your projects, providing a user-friendly way to showcase various tours and their details.

## Table of Contents

- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Props](#props)
- [Example](#example)
- [License](#license)

## Demo

Check out the [Live Demo](https://temp-tours-site.netlify.app/) to see the Tours Component in action.

## Installation

You can install the Tours Component package using npm or yarn:

```bash
npm install tours-component
```

or

```bash
yarn add tours-component
```

## Usage

To use the Tours Component in your React application, follow these steps:

1. Import the `Tours` component into your file:

```jsx
import Tours from 'tours-component';
```

2. Create an array of tour objects, each containing the necessary information:

```jsx
const toursData = [
  {
    id: 1,
    name: 'City Explorer',
    image: 'city.jpg',
    description: 'Explore the bustling city streets and iconic landmarks with our guided city tour.',
  },
  // Add more tour objects...
];
```

3. Render the `Tours` component in your JSX, passing in the `toursData` array as a prop:

```jsx
function App() {
  return (
    <div>
      <h1>Our Tours</h1>
      <Tours tours={toursData} />
    </div>
  );
}

export default App;
```

## Props

The `Tours` component accepts the following props:

- `tours` (array, required): An array of tour objects, where each object should have the following properties:
  - `id` (number, required): Unique identifier for the tour.
  - `name` (string, required): Name of the tour.
  - `image` (string, required): URL or path to the tour's image.
  - `description` (string, required): Description of the tour.

## Example

Here's an example of how to use the `Tours` component with sample data:

```jsx
import React from 'react';
import Tours from 'tours-component';

const toursData = [
  {
    id: 1,
    name: 'City Explorer',
    image: 'city.jpg',
    description: 'Explore the bustling city streets and iconic landmarks with our guided city tour.',
  },
  // Add more tour objects...
];

function App() {
  return (
    <div>
      <h1>Our Tours</h1>
      <Tours tours={toursData} />
    </div>
  );
}

export default App;
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/alihassn10/tours-component/blob/main/LICENSE) file for details.

---

Feel free to contribute to this project by opening issues or pull requests. If you have any questions or suggestions, please contact the author at their [GitHub profile](https://github.com/alihassn10).
