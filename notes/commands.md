# Seeding Movies

```js
meteor shell
// inside shell
import { seedMovies } from 'meteor/getting-started'

seedMovies()
```

# Meteor Database Access
```
meteor mongo
// find/print all movies in terminal
db.movies.find()
// remove all movies
db.movies.remove({})
```