Hello, We are pleased to confirm that your public key has been successfully deployed on your Jelastic Cloud.
Targeted environment: ${globals.env}
Targeted node : node${targetNodes[0].id}-${env.name}

You can ssh node : node${targetNodes[0].id}-${env.name}
**ssh -6 jelastic@${targetNodes.extipsv6}**

