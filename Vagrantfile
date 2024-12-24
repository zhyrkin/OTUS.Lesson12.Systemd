# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure(2) do |config|
    config.vm.box = "debian/bookworm64"
    config.vm.box_version = "12.20240905.1"
    # не проверять репозиторий на наличие обновлений
    config.vm.box_check_update = false
  
    config.vm.provider "virtualbox" do |vb|
      # имя виртуальной машины
      vb.name = "OTUS.Lesson12.Systemd"
      # объем оперативной памяти
      vb.memory = 2048
      # количество ядер процессора
      vb.cpus = 2
    end
    
    # hostname виртуальной машины
    config.vm.hostname = "OTUS.Lesson12.Systemd"
  end