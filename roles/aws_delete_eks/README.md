AWS Delete EKS 
==============

A brief description of the role goes here.

Requirements
------------

The boto3 and botocore packages are required.

```
pip3 install boto3 botocore
```


Role Variables
--------------

We need to export `AWS_ACCESS_KEY` and `AWS_SECRET_KEY` before executing.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: ansible-kubernetes.aws_delete_eks }

License
-------

BSD
