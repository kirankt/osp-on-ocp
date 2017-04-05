# osp-on-ocp

This project aims to run Kolla containers under Red Hat OpenShift Platform. Kolla build customizations are provided on a per-OpenStack service basis. 

Building Kolla Containers
kolla-build --template-override /path/to/osp-on-ocp/services/horizon/template-overrides.j2 --base-image registry.access.redhat.com/rhel7/rhel  --base rhel  horizon
