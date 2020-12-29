# example ansible role

 - [defaults](defaults/main.yml) Local variables.
 - [handlers](handlers/main.yml) Restaring of servies or reloading.
 - [meta](meta/main.yml) Maintainer info.
 - [molecule](molecule/) [Testing of ansible-playbook](https://www.jeffgeerling.com/blog/2018/testing-your-ansible-roles-molecule).
 - [tasks](tasks/) Here is ansible tasks and example how one can import other task in main.yml.
 - [templates](templates/) template files user by ansible tasks like jinja2 templates.
 - [vars](vars/) other variables no in use. 

# jinja2
Convert your ordinary config from example myconf.conf to myconf.conf.j2 so 
you can use the ansible vars with a config file.

https://docs.ansible.com/ansible/latest/collections/ansible/builtin/template_module.html#see-also 
