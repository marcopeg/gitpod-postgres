# gitpod-postgres
One click to run Postgres (with Adminer) into GitPod

[![Open in GitPod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/marcopeg/gitpod-postgres)

## How does it work?

This custom workspace runs both Postgres and Apache with [Adminer](https://www.adminer.org/) already
downloaded and accessible on port 8008.

Once the workspace is up and running, just click on the available ports and open 8008 as preview or in a custom tab.

## How to login?

In order to login to the database select "postgres" and use:

| property |  value            |
| -------- | ----------------- |
| system   |  postgres         |
| server   |  *don't touch it* |
| username |  gitpod           |
| password |  gitpod           |
| database |  postgres         |

👉 Choose the **permanent login** option so next
time you run the workspace, you'll be able to login with just one click.
