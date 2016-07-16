# vagrant
fix error provider virtualbox 5.1

open file "/opt/vagrant/embedded/gems/gems/vagrant-1.8.4/plugins/providers/virtualbox/driver/meta.rb
"

Go to line 63 and change "" 5.0 "=> Version_5_0",  for "" 5.1 "=> Version_5_0," and problem solved.
