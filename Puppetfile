### Puppetfile for our site, largely based on versions that
### would comprise SIMP-6.1.0
## 
### site-specific manifests
##
### Forked modules
### TODO: change forked module refs to tags
##mod 'camptocamp-kmod',
##  :git => 'https://github.com/simp/puppet-kmod.git',
##  :ref => '0d69a96e8d0d3a08da0d5f476c733134df4fb9ee'
##
##mod 'elastic-elasticsearch',
##  :git => 'https://github.com/simp/puppet-elasticsearch',
##  :tag => '5.2.0'
##
##mod 'elastic-logstash',
##  :git => 'https://github.com/simp/puppet-logstash',
##  :tag => '5.2.1'
##
##mod 'herculesteam-augeasproviders',
##  :git => 'https://github.com/simp/augeasproviders',
##  :ref => 'bbfc6ff9fa9acfd39e1ae9aff6341dc07e86a8d4'
##
##mod 'herculesteam-augeasproviders_apache',
##  :git => 'https://github.com/simp/augeasproviders_apache',
##  :ref => '66f17fabef214dc830b1692123c99990d03d4b6b'
##
##mod 'herculesteam-augeasproviders_base',
##  :git => 'https://github.com/simp/augeasproviders_base',
##  :ref => 'de6152df502f2642003c439195acc438c6da69b3'
##
##mod 'herculesteam-augeasproviders_core',
##  :git => 'https://github.com/simp/augeasproviders_core',
##  :ref => '72fccf10b532f06fc81cf491614e7119c72ee981'
##
##mod 'herculesteam-augeasproviders_grub',
##  :git => 'https://github.com/simp/augeasproviders_grub',
##  :ref => 'b48597b56a48aa4cbae2f3866d32a67d6950c79b'
##
##mod 'herculesteam-augeasproviders_postgresql',
##  :git => 'https://github.com/simp/augeasproviders_postgresql',
##  :ref => '6b70535febce71e6d54c04e065deebd590491083'
##
##mod 'herculesteam-augeasproviders_puppet',
##  :git => 'https://github.com/simp/augeasproviders_puppet',
##  :ref => 'bb3310e60ddfeddc9ab2b45f05066e44ff2b942e'
##
##mod 'herculesteam-augeasproviders_shellvar',
##  :git => 'https://github.com/simp/augeasproviders_shellvar',
##  :ref => '455780660018a7f8bccfedb0ec2d6aad4c864caa'
##
##mod 'herculesteam-augeasproviders_ssh',
##  :git => 'https://github.com/simp/augeasproviders_ssh',
##  :ref => 'a8b72a482a37fe86827e41659a7d8753a309cb07'
##
##mod 'herculesteam-augeasproviders_sysctl',
##  :git => 'https://github.com/simp/augeasproviders_sysctl',
##  :ref => '4425603e3c95e086596c9e4ab41813b408f99785'
##
##mod 'onyxpoint-gpasswd',
##  :git => 'https://github.com/simp/puppet-gpasswd',
##  :ref => '04431f902da8b20527e1cb5eb98ec6f4fefd6429'
##
### FIXME:  This is a dependency of elastic-elasticsearch
### for which we do not have a fork
### TODO:  Test whether 'v2.0.0' works
##mod 'puppet-yum',
##  :git => 'https://github.com/voxpupuli/puppet-yum',
##  :tag => 'v1.0.0'
##
##mod 'puppetlabs-apache',
##  :git => 'https://github.com/simp/puppetlabs-apache',
##  :ref => 'e267d693abab94f68e3e6a9c1c445e9db83dc070'
##
### We have updated this module for Puppet 4, and submitted changes upstream. We
### will use the simp-master branch until it is accepted in master.
##mod 'puppetlabs-concat',
##  :git => 'https://github.com/simp/puppetlabs-concat',
##  :ref => '5eadf453a12a3df723380de1b80a2edc9ed10956'
##
##mod 'puppet-grafana',
##  :git => 'https://github.com/simp/puppet-grafana.git',
##  :tag => 'v3.0.0'
##
mod 'puppetlabs-inifile',
  :git => 'https://github.com/simp/puppetlabs-inifile',
  :ref => '252ab552f4bf57d1099c2c2f5578f602caa7b1a5'
##
##mod 'puppetlabs-java',
##  :git => 'https://github.com/simp/puppetlabs-java',
##  :ref => 'e36f6ce7603d2c14d391d368de171b0828437617'
##
##mod 'puppetlabs-java_ks',
##  :git => 'https://github.com/simp/puppetlabs-java_ks',
##  :ref => 'ef5ac6157f6ee90917af606b25010f31c906ed92'
##
##mod 'puppetlabs-motd',
##  :git => 'https://github.com/simp/puppetlabs-motd',
##  :ref => 'ac521566a31a5ba6aca9c6fe3f30c57dd5cf7449'
##
##mod 'puppetlabs-postgresql',
##  :git => 'https://github.com/simp/puppetlabs-postgresql',
##  :ref => 'd022a56b28b2174456fc0f6adc51a4b54493afad'
##
###FIXME Need to tag this module
##mod 'puppetlabs-puppet_authorization',
##  :git => 'https://github.com/simp/puppetlabs-puppet_authorization',
##  :ref => 'master'
##
mod 'puppetlabs-stdlib',
  :git => 'https://github.com/simp/puppetlabs-stdlib',
  :ref => '7507af555361b2dcba8ed6189dc54c21e64ea031'
##
##mod 'richardc-datacat',
##  :git => 'https://github.com/simp/puppet-datacat',
##  :ref => '93b88b78364ee35f2bf39ca98ad08b78f423c1d2'
##
### SIMP has made changes to this module that don't exist upstream
##mod 'saz-timezone',
##  :git => 'https://github.com/simp/puppet-timezone',
##  :ref => '9344a1d094313b7d94e1ee4da4be9bda441c2708'
##
### SIMP has made changes to this module that don't exist upstream
##mod 'trlinkin-nsswitch',
##  :git => 'https://github.com/simp/puppet-nsswitch',
##  :ref => '6a2fee0947932dbde3c96ff75f5e461931366c78'
##
##mod 'vhsn-gitlab',
##  :git => 'https://github.com/simp/puppet-gitlab',
##  :tag => 'v1.13.3'
##
### SIMP modules
##mod 'simp-acpid',
##  :git => 'https://github.com/simp/pupmod-simp-acpid',
##  :tag => '1.0.2'
##
##mod 'simp-activemq',
##  :git => 'https://github.com/simp/pupmod-simp-activemq',
##  :tag => '4.0.1'
##
##mod 'simp-aide',
##  :git => 'https://github.com/simp/pupmod-simp-aide',
##  :tag => '6.0.1'
##
##mod 'simp-at',
##  :git => 'https://github.com/simp/pupmod-simp-at',
##  :tag => '0.0.3'
##
##mod 'simp-auditd',
##  :git => 'https://github.com/simp/pupmod-simp-auditd',
##  :tag => '7.0.2'
##
##mod 'simp-autofs',
##  :git => 'https://github.com/simp/pupmod-simp-autofs',
##  :tag => '6.0.1'
##
##mod 'simp-chkrootkit',
##  :git => 'https://github.com/simp/pupmod-simp-chkrootkit',
##  :tag => '0.0.2'
##
##mod 'simp-clamav',
##  :git => 'https://github.com/simp/pupmod-simp-clamav',
##  :tag => '6.0.1'
##
##mod 'simp-compliance_markup',
##  :git => 'https://github.com/simp/pupmod-simp-compliance_markup',
##  :tag => '2.2.0'
##
##mod 'simp-cron',
##  :git => 'https://github.com/simp/pupmod-simp-cron',
##  :tag => '0.0.2'
##
##mod 'simp-dhcp',
##  :git => 'https://github.com/simp/pupmod-simp-dhcp',
##  :tag => '6.0.1'
##
##mod 'simp-fips',
##  :git => 'https://github.com/simp/pupmod-simp-fips',
##  :tag => '0.1.2'
##
##mod 'simp-freeradius',
##  :git => 'https://github.com/simp/pupmod-simp-freeradius',
##  :tag => '7.0.1'
##
##mod 'simp-gdm',
##  :git => 'https://github.com/simp/pupmod-simp-gdm',
##  :tag => '7.0.2'
##
##mod 'simp-gnome',
##  :git => 'https://github.com/simp/pupmod-simp-gnome',
##  :tag => '6.0.3'
##
### SIMP has made changes to this module that don't exist upstream
### and we have assumed ownership of the module
##mod 'simp-haveged',
##  :git => 'https://github.com/simp/puppet-haveged',
##  :tag => 'simp-0.4.1'
##
##mod 'simp-incron',
##  :git => 'https://github.com/simp/pupmod-simp-incron',
##  :tag => '0.0.2'
##
##mod 'simp-iptables',
##  :git => 'https://github.com/simp/pupmod-simp-iptables',
##  :tag => '6.0.2'
##
##mod 'simp-issue',
##  :git => 'https://github.com/simp/pupmod-simp-issue',
##  :tag => '0.0.2'
##
### SIMP has made changes to this module that don't exist upstream
### TODO needs tag
##mod 'simp-journald',
##  :git => 'https://github.com/simp/pupmod-simp-journald.git',
##  :ref => '0a6df1389b58ac787f3339a7f6ac3d1cdf56b9b9'
##
##mod 'simp-krb5',
##  :git => 'https://github.com/simp/pupmod-simp-krb5',
##  :tag => '7.0.2'
##
##mod 'simp-libvirt',
##  :git => 'https://github.com/simp/pupmod-simp-libvirt',
##  :tag => '5.0.3'
##
##mod 'simp-logrotate',
##  :git => 'https://github.com/simp/pupmod-simp-logrotate',
##  :tag => '6.1.0'
##
##mod 'simp-mozilla',
##  :git => 'https://github.com/simp/pupmod-simp-mozilla',
##  :tag => '5.0.1'
##
##mod 'simp-named',
##  :git => 'https://github.com/simp/pupmod-simp-named',
##  :tag => '6.0.2'
##
##mod 'simp-network',
##  :git => 'https://github.com/simp/pupmod-simp-network',
##  :tag => '6.0.2'
##
##mod 'simp-nfs',
##  :git => 'https://github.com/simp/pupmod-simp-nfs',
##  :tag => '6.0.3'
##
##mod 'simp-ntpd',
##  :git => 'https://github.com/simp/pupmod-simp-ntpd',
##  :tag => '6.0.2'
##
##mod 'simp-oddjob',
##  :git => 'https://github.com/simp/pupmod-simp-oddjob',
##  :tag => '2.0.1'
##
##mod 'simp-pam',
##  :git => 'https://github.com/simp/pupmod-simp-pam',
##  :tag => '6.0.3'
##
##mod 'simp-pki',
##  :git => 'https://github.com/simp/pupmod-simp-pki',
##  :tag => '6.0.1'
##
##mod 'simp-polkit',
##  :git => 'https://github.com/simp/pupmod-simp-polkit',
##  :tag => '6.1.0'
##
##mod 'simp-postfix',
##  :git => 'https://github.com/simp/pupmod-simp-postfix',
##  :tag => '5.0.2'
##
mod 'simp-pupmod',
  :git => 'https://github.com/simp/pupmod-simp-pupmod',
  :tag => '7.3.1'
##
### FIXME SIMP changes?
### TODO needs tag
mod 'simp-puppetdb',
  :git => 'https://github.com/simp/puppetlabs-puppetdb',
  :ref => '3718c588cf4e40c450dfaae16afc1aac6ad6cb88'
##
##mod 'simp-resolv',
##  :git => 'https://github.com/simp/pupmod-simp-resolv',
##  :tag => '0.0.2'
##
##mod 'simp-rsync',
##  :git => 'https://github.com/simp/pupmod-simp-rsync',
##  :tag => '6.0.3'
##
##mod 'simp-rsyslog',
##  :git => 'https://github.com/simp/pupmod-simp-rsyslog',
##  :tag => '7.1.0'
##
##mod 'simp-selinux',
##  :git => 'https://github.com/simp/pupmod-simp-selinux',
##  :tag => '2.1.0'
##
mod 'simp-simp',
  :git => 'https://github.com/simp/pupmod-simp-simp',
  :tag => '4.1.0'
##
##mod 'simp-simpcat',
##  :git => 'https://github.com/simp/pupmod-simp-simpcat',
##  :tag => '6.0.1'
##
mod 'simp-simplib',
  :git => 'https://github.com/simp/pupmod-simp-simplib',
  :tag => '3.4.0'
##
##mod 'simp-simp_apache',
##  :git => 'https://github.com/simp/pupmod-simp-simp_apache',
##  :tag => '6.0.1'
##
##mod 'simp-simp_elasticsearch',
##  :git => 'https://github.com/simp/pupmod-simp-simp_elasticsearch',
##  :tag => '5.0.0'
##
##mod 'simp-simp_gitlab',
##  :git => 'https://github.com/simp/pupmod-simp-simp_gitlab',
##  # NOT released in SIMP 6.0.0
##  :tag => 'master'
##
##mod 'simp-simp_grafana',
##  :git => 'https://github.com/simp/pupmod-simp-simp_grafana',
##  :tag => '1.0.4'
##
##mod 'simp-simp_logstash',
##  :git => 'https://github.com/simp/pupmod-simp-simp_logstash',
##  :tag => '5.0.0'
##
##mod 'simp-simp_nfs',
##  :git => 'https://github.com/simp/pupmod-simp-simp_nfs',
##  :tag => '0.0.3'
##
##mod 'simp-simp_openldap',
##  :git => 'https://github.com/simp/pupmod-simp-simp_openldap',
##  :tag => '6.0.4'
##
mod 'simp-simp_options',
  :git => 'https://github.com/simp/pupmod-simp-simp_options',
  :tag => '1.0.3'
##
##mod 'simp-simp_rsyslog',
##  :git => 'https://github.com/simp/pupmod-simp-simp_rsyslog',
##  :tag => '0.1.2'
##
##mod 'simp-ssh',
##  :git => 'https://github.com/simp/pupmod-simp-ssh',
##  :tag => '6.2.0'
##
##mod 'simp-sssd',
##  :git => 'https://github.com/simp/pupmod-simp-sssd',
##  :tag => '6.0.2'
##
##mod 'simp-stunnel',
##  :git => 'https://github.com/simp/pupmod-simp-stunnel',
##  :tag => '6.1.0'
##
##mod 'simp-sudo',
##  :git => 'https://github.com/simp/pupmod-simp-sudo',
##  :tag => '5.0.2'
##
##mod 'simp-sudosh',
##  :git => 'https://github.com/simp/pupmod-simp-sudosh',
##  :tag => '6.0.1'
##
##mod 'simp-svckill',
##  :git => 'https://github.com/simp/pupmod-simp-svckill',
##  :tag => '3.2.1'
##
##mod 'simp-swap',
##  :git => 'https://github.com/simp/pupmod-simp-swap',
##  :tag => '0.1.1'
##
##mod 'simp-tcpwrappers',
##  :git => 'https://github.com/simp/pupmod-simp-tcpwrappers',
##  :tag => '6.0.1'
##
##mod 'simp-tftpboot',
##  :git => 'https://github.com/simp/pupmod-simp-tftpboot',
##  :tag => '6.0.1'
##
##mod 'simp-tpm',
##  :git => 'https://github.com/simp/pupmod-simp-tpm',
##  :tag => '1.0.1'
##
##mod 'simp-tuned',
##  :git => 'https://github.com/simp/pupmod-simp-tuned',
##  :tag => '0.0.2'
##
##mod 'simp-upstart',
##  :git => 'https://github.com/simp/pupmod-simp-upstart',
##  :tag => '6.0.1'
##
##mod 'simp-useradd',
##  :git => 'https://github.com/simp/pupmod-simp-useradd',
##  :tag => '0.2.0'
##
##mod 'simp-vnc',
##  :git => 'https://github.com/simp/pupmod-simp-vnc',
##  :tag => '6.0.2'
##
##mod 'simp-xinetd',
##  :git => 'https://github.com/simp/pupmod-simp-xinetd',
##  :tag => '4.0.2'
##
### STANDARD SIMP modules we don't need at site so far, but we
### will install
##mod 'simp-dirtycow',
##  :git => 'https://github.com/simp/pupmod-simp-dirtycow.git',
##  :tag => '1.0.3'
## 
### EXTRA forked modules we don't need at site so far, but we
### will install
##mod 'herculesteam-augeasproviders_mounttab',
##  :git => 'https://github.com/simp/augeasproviders_mounttab',
##  :tag => '670e8eb3df1297735da50d1ff5ec10c547acf00c'
##
##mod 'herculesteam-augeasproviders_nagios',
##  :git => 'https://github.com/simp/augeasproviders_nagios',
##  :tag => '4af1337ecbedfd1f8e79084c919b25a25b3f7d62'
##
##mod 'herculesteam-augeasproviders_pam',
##  :git => 'https://github.com/simp/augeasproviders_pam',
##  :tag => 'a9481948712e2e2951162cbcf5dda7003d54cf16'
##
##mod 'puppetlabs-mysql',
##  :git => 'https://github.com/simp/puppetlabs-mysql',
##  :tag => '9442272f5654b10d1ce33559ebb73d45ff23a128'
##
### EXTRA SIMP modules we don't need at site so far, but we
### will install
##mod 'simp-jenkins',
##  :git => 'https://github.com/simp/pupmod-simp-jenkins',
##  :tag => '6.0.1'
##
##mod 'simp-libreswan',
##  :git => 'https://github.com/simp/pupmod-simp-libreswan',
##  :tag => '3.0.1'
##
##mod 'simp-mcafee',
##  :git => 'https://github.com/simp/pupmod-simp-mcafee',
##  :tag => '6.0.1'
##
##mod 'simp-openscap',
##  :git => 'https://github.com/simp/pupmod-simp-openscap',
##  :tag => '6.0.2'
##
##mod 'simp-vsftpd',
##  :git => 'https://github.com/simp/pupmod-simp-vsftpd',
##  :tag => '7.0.1'
##
### modules specific to our site that are not SIMP modules
### or forks
##mod 'stahnma-epel',
##  :git => 'https://github.com/stahnma/puppet-module-epel',
##  :tag => '1.2.2'
##
##mod 'puppet-virtualbox',
##  :git => 'https://github.com/voxpupuli/puppet-virtualbox',
##  :tag => 'v1.8.0'
##
##mod 'puppetlabs-git',
##  :git => 'https://github.com/puppetlabs/puppetlabs-git',
##  # work beyond 0.5.0 that has not been released
##  :ref => '4e4498e3db218cefc27e40b7eb4e442177ccab28'
##
### BROKEN SIMP modules
###mod 'simp-mcollective',
###  :git => 'https://github.com/simp/pupmod-simp-mcollective',
###  :ref => '90ceda13854da0501e17f15602634d293bf54205'
###
## 
### OBE EXTRA modules: still in extras section of simp.spec
###mod 'simp-foreman'  
## 
### OBE No longer needed?
###mod 'dalen-puppetdbquery' <-- don't know why it was pulled down
###mod 'electrical-file_concat',
###  :git => 'https://github.com/simp/puppet-lib-file_concat',
###  :ref => '813132b5d776204e1da169a93e4bc6a1e253f75c'
###
###mod 'puppetlabs-puppet_agent' <-- don't know why it was pulled down
###mod 'puppetlabs-transition'   <-- required by puppetlabs-puppet_agent
###mod 'zack-report'             <-- was pulled down for examination, not used
