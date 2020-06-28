# microservices-basic

## Required Installs
1. Docker
2. Kubernetes
3. NPM
4. Skaffold

## Prerequisite
We use the `posts.com` domain name to point to the Kubernetes cluster.

Go to:
```
Windows:
C:\Windows\System32\drivers\etc\hosts

Mac/Linux:
/etc/hosts
```
Paste `127.0.0.1 posts.com` at the bottom of the `hosts` file.

## Start Application

Run this project using `skaffold dev` (may need to run 2 times)
