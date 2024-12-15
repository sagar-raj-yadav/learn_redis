Redis is a NoSQL database.
Redis->remote directory server
# redis mostly tab use karte h jab humara application frequently read-write operation perform karta h.

# Redis is is in-memory datastructure that can be used as a database ,caching,message broker

# 1. Redis as a Database
Redis in-memory data ko store karta hai, matlab data ko RAM me rakhta hai, jo bahut fast read aur write operations ke liye helpful hota hai. 

# 2. Redis as a Cache
Jab kisi application me frequently accessed data (jaise user sessions ya API responses) ko fast access karna ho, to Redis ko use kiya jata hai.

# 3. Redis as a Message Broker
Redis publish-subscribe (Pub/Sub) aur streams ke through message brokering ka kaam karta hai. Yeh real-time messaging ke liye kaafi useful hota hai, jaise chat applications ya notifications ke liye.

# Pub/Sub Workflow:
Publisher ->ek channel par message send karta hai.
Subscribers ->usi topic channel subscribe karte hain aur messages receive karte hain.

# Redis supports various data structure such as string,hash,list,set,bitmap(for image)