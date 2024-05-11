# MiniBolt Info

A bash script to monitor a [MiniBolt node](https://v2.minibolt.info) health and activity at a glance.

## Installation

  ```sh
  $ sudo apt install jq net-tools netcat
  $ cd /tmp/
  $ git clone https://github.com/minibolt-guide/minibolt_info
  $ cd minibolt_info
  $ sudo install -m 0755 -o root -g root -t /usr/local/bin *.sh
  $ minibolt.sh
  ```

## Disable admin password request (optional -caution!)

[how to disable admin password request](https://v2.minibolt.info/bonus-guides/system/ssh-keys#disable-admin-password-request-optional-caution)
