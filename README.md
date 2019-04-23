# Spectrum (Cohort)

This project contains the web-based **cohort-level** visualization dashboard for Spectrum.

The front-end is written using [React](https://reactjs.org/) and [Redux](https://redux.js.org/).

## Documentation

All documentation for Spectrum visualization can be found on [https://shahcompbio-spectrum.netlify.com](https://shahcompbio-spectrum.netlify.com).

## Installation instructions

To install a local instance of the dashboard, checkout this repository. 

Users who want to input data for the visualization must be authenticated first. Create a file called `.users` and add any user:password pairs.

```
cd spectrum-cohort-docker
touch .users
```

Each password should be encrypted:

```
openssl passwd -apr1
```

Once created, start docker compose:

```
docker-compose up
```

Then go to `localhost:5001` to see the dashboard
