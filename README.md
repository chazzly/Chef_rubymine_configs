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
#### Windows
    copy files from 'live_templates' to "C:\Users\USER\.RubyMine<version>\config\templates"
####mac
    copy file from 'live_templates' to "/Users/USER/Library/Preferences/RubyMine<version>/templates"
####Linux
    copy file from 'live_templates' to "~/.RubyMine<version number>/config/templates"

## Live Templates for Chef Resources
<table>
<tr><td>bash</td>
<td>batch></td>
<td>chef_gem</td>
</tr>
<tr><td>cookbook_file</td>
<td>cron</td>
<td>directory</td></tr>
<tr><td>execute</td>
<td>file</td>
<td>gem_package</td></tr>
<tr><td>git</td>
<td>group</td>
<td>http_request</td></tr>
<tr><td>ifconfig</td>
<td>link</td>
<td>log</td></tr>
<tr><td>mount</td>
<td>ohai</td>
<td>package</td></tr>
<tr><td>perl</td>
<td>python</td>
<td>reboot</td></tr>
<tr><td>remote_directory</td>
<td>remote_file</td>
<td>ruby_block</td></tr>
<tr><td>service</td>
<td>template</td>
<td>user</td></tr>
</table>

## Live Templates for LWRP's'
<table>
<tr><td>add_to_list  (line)</td>
<td>append_if_no_line (line)</td>
<td>chef_handler (chef_handler</td></tr>
<tr><td>delete_from_list (line)</td>
<td>delete_lines (line)</td>
<td>hostsfile_entry (hostsfile)</td></tr>
<tr><td>jenkins_command (jenkins)</td>
<td>jenkins_jnlp_slave (jenkins)</td>
<td>jenkins_job (jenkins)</td></tr>
<tr><td>jenkins_plugin (jenkins)</td>
<td>jenkins_ssh_slave (jenkins)</td>
<td>jenkins_user (jenkins)</td></tr>
<tr><td>logrotate_app (logrotate)</td>
<td>lvm_logical_volume (lvm)</td>
<td>lvm_physical_volume (lvm)</td></tr>
<tr><td>lvm_volume_group (lvm)</td>
<td>replace_or_add (line)</td>
<td>ssh_known_hosts (ssh)</td></tr>
<tr><td>yum_repository (yum)</td>
</tr></table>

## Live Templates for ChefSpec
<table>
<tr><td>describe</td>
<td>expect</td>
<td>it</td></tr>
<tr><td>let</td>
<td>shared_context</td>
</td>shared_examples</td></tr>
</table>

# Contribute
Submissions Welcome and encouraged.

- Fork Repo
- Submit Pull Request