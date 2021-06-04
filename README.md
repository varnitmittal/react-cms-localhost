# Netlify CMS + React Starter

A starter project for creating lightning-fast, offline-first websites with [Netlify CMS](https://netlifycms.org) and React.

- **[Create React App](https://github.com/facebookincubator/create-react-app)**
- **[React Router](https://github.com/ReactTraining/react-router)** for routing
- **[React Helmet](https://github.com/nfl/react-helmet)** for document titles, descriptions, meta
- **[React Snapshot](https://github.com/geelen/react-snapshot)** for pre-rendering to static html so it works without Javascript ⭐️
- **[Netlify CMS](https://github.com/netlify/netlify-cms)** for content management



## Developing

1.  Clone your repo to your local machine

1.  Install dependencies

`yarn` or `npm install`

1.  Run the development server

`yarn start` or `npm run start`

If you are adding or editing content locally in the CMS, a couple of things to note:

1.  Changes will be pushed to the remote repo.

1.  You will be prompted to enter your site's url, this is necessary for Netlify Identity to manage user login. This is stored in `localStorage`, so you might have to empty your browser cache if you are switching projects but remaining on `localhost:3000`.
