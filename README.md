# Social Blog app - template

**IMPORTANT**
* [Demo App](https://social-blog-cs.netlify.app/)
* [API Documentation](https://documenter.getpostman.com/view/7621298/T1Dv8F6p?version=latest#a071427d-c177-49b5-b7be-50c3456b9aac)

### Project Structure

```
|- src\
    |- components\
        |- BlogCard.js
        |- ReviewBlog.js
        |- ReviewList.js
    |- containers\
        |- HomePage\
        |- LoginPage\
        |- DashboardPage\
        |- Routes\
            |- PrivateRoute.js
            |- index.js
    |- images\
    |- redux\
        |- actions\
        |- constants\
        |- reducers\
        |- api.js
        |- configureStore.js
    |- utils\
```

- `src/components/`: folder for simple stateless components
- `src/containers/`: folder for stateful components
- `src/redux/actions`: each file in this folder is related to a set of actions, e.g. `auth.actions.js`
- `src/redux/reducers`: set of reducers that are combined in `index.js`
- `src/redux/constants`: set of types of actions
- `src/redux/store.js`: configuration of the store


### How to run:
- Install dependencies
- Modify BACKEND_URL (right now it is localhost:5000)
- `npm start`