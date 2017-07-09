# Consul

Starting point is [issue 1580](https://github.com/hashicorp/consul/issues/1580) also discussed in [Consul IP advertising problems when DHCP-assigned IP changes](https://groups.google.com/d/msg/consul-tool/XgG3yYJ1xIg/PzOfwDm6BwAJ).

- [issue 457](https://github.com/hashicorp/consul/issues/457)
- [issue 839](https://github.com/hashicorp/consul/issues/839)
- [PR 850](https://github.com/hashicorp/consul/pull/850)
- [github.com/hashicorp/consul/command/agent/local.go](https://github.com/hashicorp/consul/blob/60a6da213f49c4c5d5227eacc3447a047b872629/command/agent/local.go)
- [github.com/hashicorp/consul/agent/local.go](https://github.com/hashicorp/consul/blob/master/agent/local.go)
- [agent.localState](https://github.com/hashicorp/consul/blob/master/agent/local.go): `type localState struct`
