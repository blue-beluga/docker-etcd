
# [<img src=".bluebeluga.png" height="100" width="200" style="border-radius: 50%;" alt="@fancyremarker" />](https://github.com/blue-beluga/docker-etcd) bluebeluga/etcd

[etcd](https://github.com/coreos/etcd) is a distributed, consistent key-value store for shared configuration and service discovery, with a focus on being:

* *Simple*: well-defined, user-facing API (gRPC)
* *Secure*: automatic TLS with optional client cert authentication
* *Fast*: benchmarked 10,000 writes/sec
* *Reliable*: properly distributed using Raft

etcd is written in Go and uses the [Raft](https://raft.github.io) consensus algorithm to manage a highly-available replicated log.

See [etcdctl](https://github.com/coreos/etcd/tree/master/etcdctl) for a simple command line client.
