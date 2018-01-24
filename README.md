# Ansible role: Jenkins with Pipeline

This is a fork of the [Ansible Jenkins with
Pipeline](https://github.com/wjoel/ansible-jenkins-pipeline) role by Joel Wilsson.
It removes the need to install Jenkins because we instead rely upon
[Jeff Geerling's Jenkins
Role](https://github.com/geerlingguy/ansible-role-jenkins), it also updates the
main task file to use the
[jenkins_job](http://docs.ansible.com/ansible/latest/jenkins_job_module.html)
module.


