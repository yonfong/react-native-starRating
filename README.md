# react-native-starRating
react native starRatin component

# Installation

npm install react-native-starrating --save

# Usage

Install the package via npm install react-native-starrating --save. Then import it in your JavaScript file via import StarRating from 'react-native-starrating'. Check out an example usage below:

```js
import StarRating from 'react-native-starrating';

class ExampleComponent extends React.Component{
  onStarRatingPress(value) {
    console.log('Rated ' + value + ' stars!');
  }
  render() {
    return (
      <StarRating
        maxStars={5}
        rating={3}
        disabled={false}
        starSize={15}
        onStarChange={(value) => this.onStarRatingPress(value)}
      />
    );
  }
}
```
