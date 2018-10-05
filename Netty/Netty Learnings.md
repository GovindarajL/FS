- From livingbook.manning.com
**ByteBuffer:-**
  - ByteBuff we are using instead of byte[] since byte buffer is used for faster read and writes and socket channel supports       bytebuff. 
  - Search google on advantages of byte buffer over 

**Encoders and Decoders in Netty:-** 
- Netty converts the incoming/inbound messages from bytes to java object. 
- Netty converts the outbound/outging messages to bytes
- This conversion is because network data is always a series of bytes. 
