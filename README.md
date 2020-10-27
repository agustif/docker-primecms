![Logo][svg-notepad-logo]

# Docker Prime CMS
Get the [Prime CMS][github-primecms] application as a Docker service.

_This project is part of the [Astzweig][astzweig] social responsibility
program._

## License
* Licensed under the [EUPL][eupl].
* Logo: [Notepad by Made from the Noun Project][notepad-logo].


[svg-notepad-logo]: https://raw.githubusercontent.com/astzweig/docker-primecms/master/notepad-logo.svg?sanitize=true
[github-primecms]: https://github.com/birkir/prime
[astzweig]: https://astzweig.de/ges-ver
[eupl]: https://eupl.eu/1.2/en/
[notepad-logo]: https://thenounproject.com/term/notepad/1094631/

## How to build and run Docker Image
Guide from docker [External link](https://docs.docker.com/get-started/part2/)
git clone {repo}
docker build --tag primecms:1.0 .
docker run --publish 3000:3000 --detach --name primecms primecms:1.0
