Vagrant.configure("2") do |config|
  # Specify the base box to use
  config.vm.box = "ubuntu/bionic64"  # Replace with your desired box

  # I expose the port 5001 of my vm to the port 5001 on my computer
  config.vm.network :forwarded_port, guest: 5001, host: 5001

  # Forward other ports if necessary
  # config.vm.network :forwarded_port, guest: 8080, host: 8080
  # config.vm.network :forwarded_port, guest: 3306, host: 3306
end
