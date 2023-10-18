# bbb-remove-instal-limit
this repository is for removing installation limits (memory and CPU) of Big Blue Button.
how to use:
instead of:
wget -qO- https://raw.githubusercontent.com/bigbluebutton/bbb-install/v2.7.x-release/bbb-install.sh | bash -s -- -w -v focal-270 -s bbb.example.com -e info@example.com
just download bbb-install.sh from this repo and run:
cat  bbb-install.sh | bash -s -- -w -v focal-270 -s bbb.example.com -e info@example.com
enjoy.
