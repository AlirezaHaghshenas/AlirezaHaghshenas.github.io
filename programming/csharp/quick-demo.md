# A microservice with c# and kubernetes
Misconceptions around c# language and .net echosystem are so common, that I frequently find myself explaining to people why using c# is not a crazy choice. It's impossible to convince people that it's actually a great choice for many use cases as long as their guards are up. I decided to follow Scott Hanselman's method of posting to blogs instead of explaining the same concept over and over.

This is a first post in a sries, to write a toy microservice with c# and deploy it to kubernetes. I have other subjects in mind, in particular: **Why c# is a good language** for many tasks, maybe with comparisons to a few of the common languages it can replace. It can be one large post, or serveral posts, considering one language or aspect of comparison at a time, and **A bare minimum CD/CD setup for our c# service on gitlab**

## Prerequisites
If you want to replicate this post you need:
- A linux, windows or mac with dotnet sdk installed, I use Ubuntu+kde
- An editor, I use vscode
- docker cli
- A kubernetes cluster (You can test one, free for a limited time on DigitalOcean)
- kubectl, configured to connect to your kubernetes cluster