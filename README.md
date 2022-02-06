If you followed [React Authentication Crash Course With Firebase And Routing](https://www.youtube.com/watch?v=PKwu15ldZ7k) from Web Dev Simplified in 2022 and found some errors, this is probably due to the new React Router v6 release. As of today, react-router-dom lastest release (6.2.1) has no backwards compatibility with v5 (used by Kyle in this tutorial).

This repo has upgraded the tutorial's code to React Router 6. These are some changes implemented:
 - Upgrade all <Switch> to <Routes>
 - Use <Route element> instead of <Route component>
 - Use useNavigate instead of useHistory
 - Use <Outlet> to render child routes in nested routes (for <PrivateRoute>)


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
