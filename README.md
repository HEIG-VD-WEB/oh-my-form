# Oh My Form

Oh My Form is a free and open source alternative to commercial form creators like Google Forms, Typeform, or Wufoo. It is a full-stack solution built with Laravel and Vue.js.

## Prerequisites

The following prerequisites must be filled to run this service:

- [Docker](https://docs.docker.com/get-docker/) must be installed.
- [Docker Compose](https://docs.docker.com/compose/install/) must be installed (it should be installed by default with Docker in most cases).

## Start the application

In a terminal, run the following commands:

```bash

# Copy the default environment variables file
cp .env.defaults .env

# Edit the .env file to your needs, especially the following variables:
# - OH_MY_FORM_FQDN
# - OH_MY_FORM_ADMIN_EMAIL
# - OH_MY_FORM_ADMIN_PASSWORD
# - TRAEFIK_IMAGE_VERSION
```

The application should start and be accessible at <http://localhost:3000>.