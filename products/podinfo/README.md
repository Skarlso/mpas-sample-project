# Configuration instructions for backend

## Configuration Instructions

This is the api service of the podinfo microservices application.

The following parameters are available for configuration:

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| replicas | integer | 2 | Number of replicas for the application |
| cacheAddr | string | tcp://redis:6379 | Address of the cache server |

# Configuration instructions for frontend

## Configuration Instructions

This is the web frontend for the podinfo microservices application.

The following parameters are available for configuration:

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| color | string | red | The background color of the website |
| message | string | Hello, world! | The message to display |
| replicas | integer | 1 | The number of replicas for the application |

# Configuration instructions for cache

## Configuration Instructions

This is the cache for the podinfo microservices application.

The following parameters are available for configuration:

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| replicas | int | 1 | The number of replicas for the cache |
