


### UNDERSTANDING ANSIBLE USE CASES
The core of Ansible is configuration management. The
Ansible modules and plug-ins cover a wide range of
functions, which means that Ansible can be used for
configuration management and beyond. Here are some
common use cases.

<details><summary>Using Ansible for Configuration
Management</summary>
Many people know Ansible only as a configuration
management solution, and there’s a reason for that.
Ansible started as a solution for configuration
management, and that is what it still is used for in most
cases. In configuration management, Ansible is used to
manage configuration files, install software, create users,
and perform similar tasks to guarantee that the managed
systems all are in the desired state.
</details>

<details><summary>Using Ansible for Provisioning</summary>
Another common scenario for use of Ansible is for
deploying and installing systems (provisioning).
Provisioning is particularly common in virtual and cloud
environments, where in the end a new machine is just a
configuration file that needs to be pushed to the
managed machine and started from there. Ansible does
not offer the functionality to PXE-boot and kickstart a
bare-metal server but is used in combination with
solutions that can take care of that as well. While
exploring the different modules that are available, you’ll
notice that a wide range of modules is provided to work
with Ansible in different cloud environments.
</details>
<details><summary>Using Ansible for Provisioning</summary>
Another common scenario for use of Ansible is for
deploying and installing systems (provisioning).
Provisioning is particularly common in virtual and cloud
environments, where in the end a new machine is just a
configuration file that needs to be pushed to the
managed machine and started from there. Ansible does
not offer the functionality to PXE-boot and kickstart a
bare-metal server but is used in combination with
solutions that can take care of that as well. While
exploring the different modules that are available, you’ll
notice that a wide range of modules is provided to work
with Ansible in different cloud environments.
</details>

<details><summary>Using Ansible for Continuous Delivery</summary>
Continuous integration/continuous delivery (CI/CD)
makes sure that source code can easily be developed and
updated, and the results are easily provisioned as a new
version of an application. Ansible cannot take care of the
entire CI/CD procedure itself, but Ansible playbooks can
play an important role in the CD part of the CI/CD
pipeline.
</details>
