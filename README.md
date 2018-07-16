# Redislab: Redis Open Source and Redis Enterprise
## Redislab Exercise: Step by step
### I. First - Install and configure Redis OSS on a Ubuntu instance running on AWS

Login to Ubuntu instance using SSH/Putty
Run Updates:
sudo apt update
sudo apt-get install build-essential tcl
Download and Install Redis OSS
cd /usr/local/src
sudo wget http://download.redis.io/releases/redis-3.2.12.tar.gz
sudo tar xzf redis-3.2.12.tar.gz
sudo Make
