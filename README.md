# ssl

When downgrading an TLS connection to a transport connection 
we're NOT sending close alert to peer before releasing the transport socket.
