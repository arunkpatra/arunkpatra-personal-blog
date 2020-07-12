# arunkpatra-personal-blog
Arun's personal blog

## Clone the Repo

You can use this command to clone your repo with all the submodules:
``` 
git clone --recursive git@github.com:arunkpatra/arunkpatra-personal-blog.git
```

Or if you have already cloned the project, you can use:

``` 
git submodule init
git submodule update
```
## Running Locally
``` 
hugo server -D
```
## Build static pages

``` 
hugo -D
hugo --cleanDestinationDir --verbose
```
> Output will be in ./public/ directory by default (-d/--destination flag to change it, or set publishdir in the config file).

## Deploy to GCP

``` 
gsutil -m rsync -R public gs://www.arunkpatra.io
```

CI is setup, so on each push, the site should get updated.

## Hugo Help

Help - https://gohugo.io/getting-started/usage/
Docs - https://gohugo.io/documentation/
