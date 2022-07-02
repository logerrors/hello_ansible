Vagrant.configure("2") do |config|

  config.vm.define "nginx" do |nginx|
    nginx.vm.box = "bento/centos-7.9"
    nginx.vm.hostname = "nginx"
  end

  config.vm.define "php" do |php|
    php.vm.box = "bento/centos-7.9"
    php.vm.hostname = "php"
  end

  config.vm.define "mysql" do |mysql|
    mysql.vm.box = "bento/centos-7.9"
    mysql.vm.hostname = "mysql"
  end

  config.vm.provider "virtualbox" do |vb|
    vb.gui = false
    vb.memory = "2048"
  end

end
