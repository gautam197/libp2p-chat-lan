# libp2p-lan-chat
A simple LAN terminal chat with auto-discovery built on top of libp2p.

## Install

Simply run `npm install` or `yarn` and you are set!

## Run

Open at least two terminals on the same LAN network and start the chat by `node index.js`.

You should see something similar:

```
Discovered: QmRDfm4JGAg1HyMHbXco3SwBpXBtXLsuw9DBdmCFANFrBZ
Connection established to: QmRDfm4JGAg1HyMHbXco3SwBpXBtXLsuw9DBdmCFANFrBZ
nodeA dialed to nodeB on protocol: /chat/1.0.0
```

and on the second terminal, you should see similar output:

```
Connection established to: QmNuY3BNxQH1VvY4wzPv1p9JYSim1xYCJiqTkCpyXg13Nb
nodeA dialed to nodeB on protocol: /chat/1.0.0
Discovered: QmNuY3BNxQH1VvY4wzPv1p9JYSim1xYCJiqTkCpyXg13Nb
```

Congratulations! You have established a two-way chat. Try to write something from both terminals..

```
Discovered: QmRDfm4JGAg1HyMHbXco3SwBpXBtXLsuw9DBdmCFANFrBZ
Connection established to: QmRDfm4JGAg1HyMHbXco3SwBpXBtXLsuw9DBdmCFANFrBZ
nodeA dialed to nodeB on protocol: /chat/1.0.0
Hi, I'm Gautam
Hi, I'm Mr.Phuyal
```

Now go and start the program on more terminals or even or different computers!


