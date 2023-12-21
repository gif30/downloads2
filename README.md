# downloads2



docker pull fluent/fluent-bit:2.1.10
docker save fluent/fluent-bit:2.1.10 -o fluentbit-2-1-10.tar



cat fluentbit-2-2-0-debug.* | tar xzvf -
tar cvzf - fluentbit-2-2-0-debug.tar | split --bytes=100MB - split/fluentbit-2-2-0-debug.tar.gz.
