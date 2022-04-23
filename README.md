# PDCP

![](/photos/pdcp.png)

The functions of pdcp are as follows:-

1. Header Compression

2. Ciphering and Integrity Security

3. Routing and Duplicating of Split-Bearer

4. In-Sequence Delivery

#### Header Compression

The length of header will increase according to the data packets such as if it was IPv4 their size will be 40 bytes and if IPv6 their size will be 60 bytes. So as to decrease/reduce of header **PDCP** is used.

Therefore PDCP compresses the length of header upto couple of bytes before wireless trasmission and decompresses the header at receiving sides before transmitting to the IP-Protocol in wired network.

This compression is based on scheme known as ROHC.

#### Ciphering and Integrity Security

There are two types of security that PDCP looks for :-

1. Prevent Eavesdropping - TO counter this we use PDCP Ciphering.

2. Data Origin - To verify data is originated from right source for this purpose it performs Integrity Protection.

#### Routing and Duplicating of Split-Bearer

Suppose multiple cell are connected to the User-Equipment then in this case we use split and duplicate the data so as to maintain the performance of services.

#### In-Sequence Delivery
In this , we provide the sequence number to each packets and also stores the PDU's in the buffer until all the previous PDU's is recieved.

