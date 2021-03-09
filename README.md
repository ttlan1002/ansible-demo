# ansible-demo

### Please prepare the following environment variable:

```
[General]
katello_ca_url: ''
rhn_username: ''
rhn_password: ''
rhn_poolid: ''
foreman_pubkey_url: ''
ansible_pubkey: ''
httpd_port: ''
activationkey: ''
vietnam_ntp_pool:
  - ''
  - ''
```
```
[VCENTER]
vsphere_folder: ''
vsphere_port_group: ''
esxi_hostname: ''
vm_template: ''
vm_netmask: ''
vm_gateway: ''
vm_domain_name: ''
vm_dns_servers: ''
ansible_host: ''
guest_notes: ''
vcenter_datacenter: ''
vcenter_datastore: ''
  - ''
  - ''
local_ntp_server:
  - ''
  - ''
```
```
[AWS]
ec2_key_pair: ''
instance_type: ''
region: ''
ami_image: ''
vpc_subnet_id: ''
security_group: ''
activationkey: ''
local_ntp_server:
  - ''
```
