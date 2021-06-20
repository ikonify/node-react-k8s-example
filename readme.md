# Node React K8s example

A minimal example of a microservice architecture. Uses a very simple, custom eventbus. All data is stored in memory and wiped on restart.

## Startup

Requires docker images to be prebuilt. Image tags can be found in the deployment files in infra/k8s folder.

Run `skaffold dev` to create the Deployments and Services and start everything up.

The application requires you to add `127.0.0.1 posts.com` in to your hosts file.
