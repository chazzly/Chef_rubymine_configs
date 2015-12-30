# Chef_rubymine_configs
Rubymine configurations for Chef

Currently this only includes live templates, but I may add file templates as well and other configs over time.

I've included many of the:
- Common (IMHO) base chef resources ('chef' Template Group)
- A number of resources from LWRP's and other cookbooks we've used ('chef_extras' Template Group).  The dependant cookbook is noted in the Description field.
- A few ChefSpec reources ('chef_spec' Template Group).  I expect to add more over time.

These will fill out the resource structure and fields for many common or required properties.
Tab / Shift+Tab to move between properties.  The properties for each reasource are rarely all inclusive, to avoid an exxesive amount of deleting.  I've tried to hit the required and/or useful ones.'

## Install
copy files from 'live_templates' to "C:\Users\USER\\.RubyMine80\config\templates"

## Live Templates for Chef Resources
bash
batch
chef_gem
cookbook_file
cron
directory
execute
file
gem_package
git
group
http_request
ifconfig
link
log
mount
ohai
package
perl
python
reboot
remote_directory
remote_file
ruby_block
service
template
user

## Live Templates for LWRP's'
add_to_list  (line)
append_if_no_line (line)
chef_handler (chef_handler
delete_from_list (line)
delete_lines (line)
hostsfile_entry (hostsfile)
jenkins_command (jenkins)
jenkins_jnlp_slave (jenkins)
jenkins_job (jenkins)
jenkins_plugin (jenkins)
jenkins_ssh_slave (jenkins)
jenkins_user (jenkins)
logrotate_app (logrotate)
lvm_logical_volume (lvm)
lvm_physical_volume (lvm)
lvm_volume_group (lvm)
replace_or_add (line)
ssh_known_hosts (ssh)
yum_repository (yum)

## Live Templates for ChefSpec
describe
it
let
shared_context
shared_examples

# Contribute
Submissions Welcome and encouraged.

- Fork Repo
- Submit Pull Request