# OpenStack-Fast-Forward-Upgrade
This project is to automate the process of fast forward upgrade of OpenStack from OSP10 to OSP13

## Pre-requisites:
1. OSP10 is deployed and has passed the minor update
2. Use RHEL 7.5

## Steps:
1. Launch an instance in OSP10 and on a separate terminal, ping the instance
2. Enable collectd
3. Set all the variables in vars/main.yml
4. Run the playbook ffu.yaml
5. Check if the instance is ACTIVE after the upgrade 
