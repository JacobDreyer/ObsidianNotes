Make application development easier and faster

```ad-success
title: Advantages

- Free (often) code that provides a lot of common functionality
- Provides high quality specialized tools
- Provide a layer of abstraction among different browsers
```

```ad-failure
title: Disadvantages

- Adds another dependency
- Quality varies
- Adds maintenance issues
```

## Including JavaScript Libraries
#### Download a Local Copy
- Download a local copy and serve from your own site
- e.g. \<script src="jquery-3.4.1.min.js">\</script>
- You control where it comes from
#### Download from a [[Content Delivery Network]] ([[CDN]])
- e.g. \<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js">\</script>
- Take advantage of [[Edge Catching]]
- Caveat: if your site is serviced via [[HTTPS]], then you must use https protocol for any assets