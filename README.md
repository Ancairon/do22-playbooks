# do22-playbooks

To run the app with k8s you need another vm running Jenkins.  

Change the hosts in the ingress .`yml`s to your desired URL. (This is a university assignment project, if you want to run it, fork it and change these URLs.)

For Jenkins to work in the target VM, you need to have a `jenkins` user with `sudo` access.  

Then follow these instructions to have `sudo` not ask for a password 👉 https://www.cyberciti.biz/faq/linux-unix-running-sudo-command-without-a-password/

Then you would point your node to Jenkins, make a pipeline job from the `jenkinsfile` in this repo, and finally build.