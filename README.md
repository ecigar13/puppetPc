
# puppetPc

Used to create another Ubuntu machines with the exact same configuration as mine

  

# Steps:
1. How to do this
2. Use hierra?
3. Write code
4. Done

  

Keep it simple, why go overboard for a personal PC?

  

# Actions:

1. Enable puppet repo on Apt: puppet 6.16 18.04 (bionic)

```
wget https://apt.puppet.com/puppet6-release-bionic.deb
sudo dpkg -i puppet6-release-bionic.deb
sudo apt-get update
```
2. Install puppet
```
sudo apt-get install puppetserver -y
sudo systemctl start puppetserver
```
