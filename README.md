# php-composer-xdebug

Based on the composer docker image, install xdebug

Great for projects that need phpunit with coverage, able to run with multi-stage ci


# How to use this image

### Basic usage

Running the `videovisit/php-composer-xdebug` image is as simple as follows:

```console
$ docker run --rm --interactive --tty \
  --volume $PWD:/app \
  videovisit/php-composer-xdebug install
```
