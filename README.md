# Django Docker Hello World

A example of Django start project.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

- [Docker](https://docs.docker.com/engine/installation/)

### Installing

```
# go to workspace
git clone https://github.com/eduardokanema/django-docker-hello-world.git
cd django-docker-hello-world
docker-compose up -d

# go to http://localhost:8000
```

To check logs type:

```

docker-compose logs -f --tail=50 web
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
