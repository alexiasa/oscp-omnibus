# Set up custom terminator configuration for single user

```bash
# if not installed, install terminator
sudo apt-get install terminator

# create terminator config directory
cd /home/<username>/.config
mkdir terminator
cd terminator
curl -o config https://raw.githubusercontent.com/alexiasa/oscp-omnibus/master/terminator_config

# launch terminator with new configuration
terminator

```
