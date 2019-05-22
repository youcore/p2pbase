# p2pbase
The basic p2p communication C# .net Standard

The final dll library must be simple to implement.

Example usage:
P2PBase p2p = new P2PBase();

Should only contain following publicly:
- FUNCTION: Server.Start()
- FUNCTION: Server.Stop()
- FUNCTION: Connect(Uri host)
- FUNCTION: Disconnect(Uri host)
- FUNCTION: Send(Uri host, string data)
- EVENT: Receive(Uri sender, string data)
