The components are present inside features folder in app folder. it contains various components folder, each folder component contains the component name file, it's api file and slice file. e.g. productList component folder contains productList.js, productListAPI.js, productListSlice.js

The pages folder contains the whole page, e.g. login page, signup page, home page. It's an entire page consisting of various components.

we have an auth folder in features which is for authorization for signin, signup, forget password

we have set react router in app.js, it's like a amusement park map which tells about different swings path/location.
## have a look at app.js file

for interlink, i.e. moving from sign in to sign etc. we use link to="/path" instead of a href, ## checkout code in login.js