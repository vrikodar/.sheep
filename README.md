# .sheep

.sheep is a simple bash script to perform multithreaded ping sweep of a 24 bit masked subnet 


# Why .sheep

**nmap is widely tool but unfortunately is takes arround 24-25 seconds to perform a ping_sweep of a /24 subnet whereas .sheep can ping_sweep the same network in approximately 2 seconds and it also saves the alive hosts in a text file in "order" which you can feed to nmap for port scanning**

# Compared

@Nmap {takes arround 24 seconds} {even parallelism options won't help}

![Capture](https://github.com/SxNade/.sheep/blob/main/2021-05-29_03-15.png)

@.sheep

![Capture](https://github.com/SxNade/.sheep/blob/main/sheep.gif)

# Installing and Running


            $ git clone https://github.com/SxNade/.sheep
            $ cd .sheep
            $ chmod +x sheep
            
            $ ./sheep subnet/24

# On the GO one Liner

`curl -s https://raw.githubusercontent.com/SxNade/.sheep/main/sheep -o sheep; chmod +x sheep; ./sheep`

# More Info

**I am a bit busy right now but soon a feature to scan subnets of all types will be added**
