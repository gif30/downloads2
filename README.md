# downloads2


# repo

docker pull fluent/fluent-bit:2.1.10
docker save fluent/fluent-bit:2.1.10 -o fluentbit-2-1-10.tar



tar cvzf - fluentbit-2-2-0-debug.tar | split --bytes=50MB - split/fluentbit-2-2-0-debug.tar.gz.



##LOAD
cat fluentbit-2-2-0-debug.* | tar xzvf -
docker load -i fluentbit-2-2-0-debug.tar
