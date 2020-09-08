# cwmp-management
This feeds contains some OpenWrt packages for CWMP managment. 

Usage

To enable this feed add the following line to your feeds.conf:

src-git cwmpmanagement https://github.com/topeqin/cwmp-management.git

To install all its package definitions, run:

./scripts/feeds update cwmpmanagement
./scripts/feeds install -p icwmp bbf

