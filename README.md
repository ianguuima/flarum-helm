<p align="center"><a href="https://github.com/crazy-max/docker-flarum" target="_blank"><img height="200" src="https://user-images.githubusercontent.com/26366802/233689057-f47dc3b7-236d-4416-b422-2b9df84a1542.png"></a></p>

## Flarum Helm Chart

A helm image using <a target="_blank" href="https://flarum.org/">Flarum</a> <a href="https://github.com/crazy-max/docker-flarum">docker image</a>. I've created a local server recently
and I wanted a way to deploy Flarum in a easy way in my kubernetes environment.


## Usage
The usage is pretty simple and are currently covering the essential properties. Just like the <a href="https://github.com/crazy-max/docker-flarum">docker image</a> requires.
```yaml
appProperties:
  volumeClaim: '' # Create a volume and a volume claim and pass the volume claim name here.
  database: 
    user: '' # database user
    name: '' # database name
    password: 
    host: ''
    port: 3306
  baseUrl: '' #FLARUM_BASE_URL
```



## Contribute

Feel free to open a pull request to include more functionality. The helm chart is simple and could be better when handling different use-cases.
