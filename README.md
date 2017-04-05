# osp-on-ocp

This project aims to run Kolla containers under Red Hat OpenShift Platform. Kolla build customizations are provided on a per-OpenStack service basis. 

## Building Kolla Containers

kolla-build --template-override /path/to/osp-on-ocp/services/horizon/template-overrides.j2 --base-image registry.access.redhat.com/rhel7/rhel  --base rhel  horizon

## Upload Kolla Image into the local OCP Registry
oc whoami -t
5SvdoO6b9V9IDpEIy3cHalINL9qFj4CxvKgNgJusIUwc

docker login -u ocpuser -p 5SvdoO6b9V9IDpEIy3cHalINL9qFj4CxvKgNgJusIUwc https://172.30.202.25:5000

## Run the container
TODO
