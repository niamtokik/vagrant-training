# Networking

Every sessions will follow the adventures of Alice, Bob, Charly,
David, Eve and Fred. Each one required some features or network
interconnection facilities.

## Linux-Bridge (single)

A single virtual machines based on Debian10 to learn how to bridge
multiple interfaces. It uses:

 * `netns` feature
 * `veth` devices

```txt
cd linux-bridge
vagrant init
```

## Linux-Bond (single)

A single virtual machines based on Debian10 to learn how to create a
bonding with multiple interfaces. It uses:

 * `netns` feature
 * `veth` devices

```txt
cd linux-bond
vagrant init
```
