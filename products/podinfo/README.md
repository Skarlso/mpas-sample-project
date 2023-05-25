# Configuration instructions for backend

<h2>Configuration Instructions</h2>
<p>This is the api service of the podinfo microservices application.</p>
<p>The following parameters are available for configuration:</p>
<p>| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| replicas | integer | 2 | Number of replicas for the application |
| cacheAddr | string | tcp://redis:6379 | Address of the cache server |</p>
# Configuration instructions for frontend

<h2>Configuration Instructions</h2>
<p>This is the web frontend for the podinfo microservices application.</p>
<p>The following parameters are available for configuration:</p>
<p>| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| color | string | red | The background color of the website |
| message | string | Hello, world! | The message to display |
| replicas | integer | 1 | The number of replicas for the application |</p>
# Configuration instructions for cache

<h2>Configuration Instructions</h2>
<p>This is the cache for the podinfo microservices application.</p>
<p>The following parameters are available for configuration:</p>
<p>| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| replicas | int | 1 | The number of replicas for the cache |</p>
