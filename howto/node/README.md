# node

A swarm's node given its container, the mrepo in it reached, and removed again.

The node is the bridgehead: a standard mrepo on the host, in service, its
`container` protocol open. Its replica runs in a container; from then on
`haicc container` at the node sends a command on into it, as to any
linked mrepo. Docker, its daemon running, is needed.

## Steps

The script, [steps.haicc](steps.haicc): each line as typed after `haicc`, what it answers under it; run with `howto/run`, shown here at info extraction.

## Notes

- **The haicc component's script `cluster`** does this for two nodes.
