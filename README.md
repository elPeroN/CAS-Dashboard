## CAS - Dashboard

![license](https://img.shields.io/badge/license-MIT-blue.svg)

> Dashboard for CAS server made with React and material UI

## N.B. Ubuntu Server 20.04 is mandatory to run this environment's back end!

## Quick start

- [Download from Github](https://github.com/elPeroN/CAS-dashboard/archive/master.zip) or clone the repo: `git clone https://github.com/elPeroN/CAS-dashboard`

- Make sure your NodeJS and npm versions are up to date for `React 16.8.6`

- Install dependencies: `npm install` or `yarn`

- Start the Mongo-db:	`sudo service mongod start ` or `yarn db`

- Start the server CAS-BACKEND(if main directory of innometrics-backend is at same level of CAS-dash you can run `yarn server`)

- Start the server: `npm run start` or `yarn start`

- Views are on: `localhost:3000`

## Documentation

The documentation for the CAS-Dashboard is can be found [here]().

## File Structure

Within the download you'll find the following directories and files:

```
cas-dashboard

├── .eslintrc
├── .gitignore
├── .prettierrc
├── CHANGELOG.md
├── jsconfig.json
├── LICENSE.md
├── package.json
├── README.md
├── public
├── docs
└── src
	├── assets
	├── common
	├── components
	├── helpers
	├── icons
	├── layouts
	├── theme
	├── views
	│	├── Account
	│	├── Dashboard
	│	├── Icons
	│	├── NotFound
	│	├── ProductList
	│	├── Settings
	│	├── SignIn
	│	├── SignUp
	│	├── Typography
	│	└── UserList
	├── App.jsx
	├── index.jsx
	└── Routes.jsx
```

## Reporting Issues:

- [Github Issues Page](https://github.com/elPeroN/CAS-dashboard/issues)

## License

- Licensed under MIT ()

## Contact Us

- Email Us:
	- stefano.propato@gmail.com
	- perrisalvatore95@gmail.com

## TODO:
	-impostare un massimo di metriche visibile nei grafici?
