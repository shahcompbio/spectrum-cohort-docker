# Spectrum (Cohort)

This project contains the web-based **cohort-level** visualization dashboard for Spectrum.

The front-end is written using [React](https://reactjs.org/) and [Redux](https://redux.js.org/).

## Documentation

All documentation for Spectrum visualization can be found on [https://shahcompbio-spectrum.netlify.com](https://shahcompbio-spectrum.netlify.com).

## Installation instructions

To install a local instance of the dashboard, checkout this repository. Create a file called `.users` and add any user:password pairs you would like to use to authenticate the input function of the dashboard. To generate passwords I used:

```
openssl passwd -apr1
```

After you're done with `.users`, start docker compose:

```
docker-compose up
```

Then go to `localhost:5001` to see the dashboard
