## galaxy-role-default/default

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](http://img.shields.io/travis/csteel/ansible-rolegalaxy-role-default/default.svg?style=flat)](http://travis-ci.org/csteel/ansible-rolegalaxy-role-default/default)
[![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](#)


This is a drop in replacement role skeleton used to create ansible roles with the ansible-galaxy command.

List of internal variables used by the role:

    fact_controller_home
    fact_controller_user

### Detailed usage guide

You can replace the default ansble-galaxy role skeleton or point to this one using the ansible-galaxy ROLE_SKELETON option.

#### To use as an alternative role skeleton

```shell
ansible-galaxy init --role-skeleton=ALTERNATIVE_ROLE_SKELETON_PATH ansible-role-myrole
```

#### To as a replacment for the default role skeleton that ships with Ansible

If you want to completely replace the default ansible role skeleton directory provided by ansible then you could deleted the default role skeleton directory and replace it with this one.

Here is an example using a miniconda created python environment called ansible with a pip installed version of ansible.

```shell
# delete the default ansible-galaxy role skeleton
rm -R ~/miniconda2/envs/ansible/lib/python2.7/site-packages/ansible/galaxy/data/default
# replace is with this one
cd ~/miniconda2/envs/ansible/lib/python2.7/site-packages/ansible/galaxy/data/
git clone git@github.com:cjsteel/ansible-galaxy-template.git
```


### Authors and license

`galaxy-role-default/default` role was written by:

- [Christopher Steel](http://mcin-cnim.ca/) | [e-mail](mailto:christopher.steel@mcgill.ca)

License: [MIT](https://tldrlegal.com/license/mit-license)

***
### Open Science

The Neuro has adopted the principles of Open Science. We are inspired by the likes of the Allen Institute for Brain Science, the National Institutes of Health's Human Connectome project, and the Human Genome project. For additional information please see [open science at the neuro](https://www.mcgill.ca/neuro/open-science-0).

![MCIN](imgs/mcin-logo-brain-140x116.png)          ![neuro](imgs/neuro-logo-160x116.png)  
README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).

