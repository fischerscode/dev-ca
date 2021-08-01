# dev-ca
A certificate authority environment for development.

**ONLY USE THIS SETUP IN DEVELOPMENT. NEVER USE THIS IN PRODUCTION**

## Usage
Fist of all, you have to start you dev-ca environment. Here you have 2 options:
1. Use docker compose:

   Simply run `docker compose up` in your the root directory of this project.
2. Use docker [Development Environments (Preview)](https://docs.docker.com/desktop/dev-environments/):

    Open Docker Desktop, go to Dev Environments, paste `https://github.com/fischerscode/dev-ca` in url field and press create.

Once the dev-ca environment has started, you should be able to access the [PowerDNS-Admin UI](http://localhost:8989).
After creating a new account, you can edit the DNS settings, the certificate authority uses.

## Credits
This project has been inspired by [pschiffe/docker-pdns](https://github.com/pschiffe/docker-pdns)!