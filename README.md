Ansible role: CMake
=========

![Build & Deploy](https://github.com/Provizanta/ansible-role-cmake/workflows/molecule/badge.svg?branch=master)

CMake is a cross-platform family of tools designed to build, test and package software.

Requirements
------------

None

Role Variables
--------------

These variables are defined in [defaults/main.yml](./defaults/main.yml):

    cmake_package_state: "present"

Dependencies
------------

None

Example Playbook
----------------

    - name: Converge
      hosts: all
      roles:
        - role: cmake
          vars:
            cmake_package_state: "latest"

License
-------

MIT

Author Information
------------------

Tibor Csóka
