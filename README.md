# HowTo

Install Virtualbox and Hashicorp Vagrant. 
Run command vagrant up. 
Helm App Repo [here](https://github.com/CodyKurtz/argocd_demo/tree/master)

Continuous delivery implemented via ArgoCD, GitOps based approach. Still to do, is add GitHub Action to build image and push to registry. Ansible playbook builds on the fly. 

Still to DO:

DB Deploy
Secrets Management
Refactor Ansible Playbook
Make Ansible bootstrap more robust
Move Dockerfile and app to Git repo and automate Docker build and push to registry