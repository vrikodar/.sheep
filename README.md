# .sheep

.sheep is a simple bash script to perform multithreaded ping sweep of a 24 bit masked subnet 


# Why .sheep

**nmap is widely tool but unfortunately is takes arround 24-25 seconds to perform a ping_sweep of a /24 subnet whereas .sheep can ping_sweep the same network in approximately 2 seconds and also save the alive hosts in a text file in order which you can directly give to nmap for port scanning**

# Compared

@Nmap


# Installing and Running


            $ git clone https://github.com/SxNade/.sheep
            $ cd .sheep
            $ chmod +x sheep
            
            $ ./sheep subnet/24


# More Info

**I am a bit busy right now but soon a feature to scan subnets of all types will be added**
