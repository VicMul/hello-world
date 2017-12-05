# hello-world
The proverbial "hello world" program in webspace

#!/bin/sh
while read i
do
   echo $i
done <<__EOT__
Hello World!
__EOT__
