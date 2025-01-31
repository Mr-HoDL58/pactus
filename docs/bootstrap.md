# Bootstrap Nodes

As part of the network infrastructure, Bootstrap Nodes play an important role in starting
and keeping the network secure.

## What are the Bootstrap Nodes?

Bootstrap nodes act as the initial contact points for new nodes in the Pactus network.
When a new node starts, it tries to connect to bootstrap nodes.
Through these connections, it learns about the entire network and discovers other peers.

## Expectations

Bootstrap node operators are essential contributors to the stability and growth of the Pactus
blockchain. To ensure a seamless integration, operators are expected to adhere to the following
guidelines:

### IP Address and DNS Stability

Bootstrap node operators are expected to maintain the stability of their assigned IP
or DNS address. It is imperative that these addresses remain unchanged and are not sold or
transferred to third parties.

### Security

Bootstrap node operators are expected to adhere to best practices in host security and
maintain control over the relevant infrastructure.
Specifically, they should ensure the security of their "network key".
A network key is a private key used to encrypt messages in the P2P network.

### Reliability (Uptime)

Bootstrap node operators are expected to maintain a high level of reliability and uptime.
They should ensure that their nodes are consistently available with minimal downtime.

### Responsive

Bootstrap node operators are expected to be highly responsive, particularly in times of emergencies.

### Software Updates

Bootstrap node operators are expected to apply software updates and patches provided by the Pactus development team.

### Documentation

Bootstrap node operators are encouraged, but not required, to publicly document the details of their operating practices.

### Monitoring

Bootstrap node operators are encouraged, but not required, to implements monitoring tools to
track the performance and health of their nodes.

## Inclusion in the Pactus Project

Upon meeting the expectations outlined above, Bootstrap node operators can add their node as a Bootstrap node to the list of bootstrap addresses.
Each Bootstrap address includes the IP or DNS address and the network ID.
Once you have provided this information, you can open a pull request to add your node as a bootstrap node in the Pactus blockchain.
An example of this pull request can be found [here](link).
