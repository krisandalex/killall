 ## second and third params - filter
 ps -ef | grep 'cgi'  | grep abit | grep -v grep | awk '{print $2}' | xargs -r kill -9
