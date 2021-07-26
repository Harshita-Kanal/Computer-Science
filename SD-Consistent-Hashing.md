## Consistent Hashing
- **Server**: Serves requests
- Balance load on all servers, server has load on it
- **Load Balancing**: Taking N servers and balancing the load evenly
- Request ID -> Hash it -> m1 % N -> take it to the server with the value returned
- If there are x requests, each server has x/n load, load factor = 1/n
- Whenever a new request comes, serve it to the nearest server in a ring or clockwise manner
- Create multiple hash functions
- Used by web caches, databases, distrib
