Ansible a powerful configuration management tool designed to simplify the management of hundreds of servers. 

It automates tasks such as configuration, deployment, and orchestration, making it easier to manage complex IT environments efficiently.

With its agentless architecture and simple YAML-based playbooks, Ansible helps streamline operations and reduce manual effort, ensuring consistent and error-free management across systems.

We can write the playbooks but you can also use Ansible modules to execute basic commands like moving files (mv), copying files (cp), and more, allowing for straightforward automation of routine operations called (ad-hoc commands)

example- 
-- ansible -i inventory all -m "shell" -a "cp file1.txt myfolder"
-- ansible -i inventory all -m "shell" -a "rm file1.txt"
