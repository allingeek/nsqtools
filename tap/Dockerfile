FROM nsqio/nsq:latest

VOLUME ["/data"]

ENTRYPOINT ["/gopath/bin/nsq_to_file", "-channel=wiretap", "-output-dir=/data"]
