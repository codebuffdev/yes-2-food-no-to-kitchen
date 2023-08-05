# `yes-2-food-no-to-kitchen` react mini project

The project i'm working on is called `yes-2-food-no-to-kitchen`. This project i'm building while learning `react`.

To create this project i'm not going with the conventional approach to create a react app i.e. `create-react-app yes-2-food-no-to-kitchen`. Instead i'm going with creating a the app from scratch.

Following process the approach i'm going with in creating the app.

1. A Folder name with `yes-2-food-no-to-kitchen`.
2. npm init
    - Pass the required input
3. Adding a bundler
    - Going with `parcel`
        - `create-react-app` uses webpack as a bundler.
    - npm install -D parcel
4. Need react packages as well
    - npm install react
    - npm install react-dom

We are done with the project structure & initial dependencies here.

index.html is the entrypoint for the project.

We can run this will multiple approaches. But we will take the help of the parcel. `npx parcel index.html`

npx parcel index.html will do these following things

1. It will bundle the project by minifying the code with various optimizations/algorithms.
2. It will create 2 directories .parcel-cache and .dist. pace-cache for the build caching & dist is the minified code distribution.
3. If everything went well, you can see a terminal message as `Server running at http://localhost:1234` . We can see out code by visiting the url.

**parcel is an absolute beast in web development, i would highly recommend using it.**
