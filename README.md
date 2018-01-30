# LINUX ubuntu 
# [mengatasi eror pada get lock terminal](https://github.com/faishall/erorr-get-lock)

##[Appabila anda mengalami hal seperti ini] :
[sudo apt-get update && sudo apt-get upgrade]
 Could not get lock /var/lib/apt/lists/lock - open (11: Resource temporarily unavailable)
 
 ##[maka solusinya seperti ini]
 -> sudo rm /var/lib/apt/lists/* -vf 
 
 baru kamu update lagi
-> sudo apt-get update
