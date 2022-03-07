0-hello_world : echo "Hello, World"
1-confused_smiley : echo "\"(Ôo)'"
2-hellofile : cat /etc/passwd
3-twofiles : cat /etc/passwd /etc/hosts
4-lastlines : tail /etc/passwd
5-firstlines : head /etc/passwd
6-third_line : head -n 3 iacta | tail -n +3
7-file : use echo command
8-cwd_state : ls -la > ls_cwd_content \
9-duplicate_last_line : tail -1 < iacta >> iacta \
10-no_more_js : find -name "*.js" -type f -delete \
11-directories 
