## JeremyCollins.net web source

This is the source for jeremycollins.net. Tech stack relied upon for deployment:

Deployment stack, optional:
- Docker
- [Traefik](https://containo.us/traefik/)

Local server & client:
- NodeJS
- [Gatsby](https://www.gatsbyjs.org/) (includes React, [Theme UI](https://theme-ui.com/))


### Local Installation (with Docker)

Pull and run [docker repo](https://hub.docker.com/r/jdodsoncollins/jeremycollins.net/) `docker pull jdodsoncollins/jeremycollins.net && docker-compose up`

Docker container extends `nginx-alpine` container, so follow any appropriate nginx docker guide if you're curious what that does or have problems. 

##### Local Development

1. `cd site && npm install`
2. Use `npx gatsby develop` to build and run locally. This site is built with [Gatsby](https://www.gatsbyjs.org/) so basic familiarity is needed if you roll with this project.

Note: Anyone else using this build will likely need to remove or modify my [Fathom](https://usefathom.com) script in `analytics.tsx`