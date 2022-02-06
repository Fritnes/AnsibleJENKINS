Role "Jenkins"
=========

https://www.jenkins.io/

Role Variables
--------------

docker_folder: "/opt"
version: "3.7"
jenkins_container_name: "jenkins"


Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: AnsibleJENKINS, when: ansible_system == 'Linux' }

Author Information
------------------

fritnes
https://github.com/Fritnes
