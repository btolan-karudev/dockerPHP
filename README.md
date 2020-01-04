# dockerPHP
-- Build a PHP Image --

We built a php Docker image. We also learned about the importance of the `EXPOSE 80` line in the Dockerfile. Although this doesn’t actually publish the container’s port, it’s still a very useful line. It allows developers to look at the Dockerfile as documentation and understand exactly what ports need to be exposed to work properly.

Here’s the completed project:
https://github.com/btolan-karudev/dockerPHP

After cloning the project, build and run the container:
- `docker build . -t docker/php`
- `docker run --name=php -p=3003:80 docker/php`
- Visit http://localhost:3003
