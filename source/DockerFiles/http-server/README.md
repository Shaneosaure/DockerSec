# How to build this docker image
This docker file is largely based on [OWASP Juice-Shop](https://github.com/juice-shop/juice-shop), but we have adapted it to fit properly and securely in our environnement.
One of the main difference is the fact that the container can now have a shell, and the website is hosted on port 80 instead of 3000.

# Build Instructions
1. Clone the repository of [OWASP Juice-Shop](https://github.com/juice-shop/juice-shop)
2. Move in this directory
3. Copy our `DOCKERFILE` in the directory
4. Change  `safetyOverride: true` in config/default.yml from `false` to `true`
4. Build the docker Image from there
