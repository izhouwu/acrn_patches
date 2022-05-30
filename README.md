# acrn_patches

label: Virtio vsock Context ID (CID)
tooltip:
Specify the post-launched VM's unique Context ID (CID) used by vsock (integer greater than 2). vsock provides a way for the host system and applications running in a user VM to communicate with each other using the standard socket interface. vsock uses a (context id, port) pair of integers for identifying processes. The host system CID is always 2. The port is hardcoded in our implementation.
