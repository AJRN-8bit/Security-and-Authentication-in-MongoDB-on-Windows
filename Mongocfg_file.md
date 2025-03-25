# Mongod.cfg file
In this document you will find the content of the mongod.cfg (file to configure MongoDB) used for this laboratory.


## Content

```bash
# mongod.conf

# for documentation of all options, see:
#   http://docs.mongodb.org/manual/reference/configuration-options/

# Where and how to store data.
storage:
  dbPath: C:\Program Files\MongoDB\Server\8.0\data

# where to write logging data.
systemLog:
  destination: file
  logAppend: true
  path:  C:\Program Files\MongoDB\Server\8.0\log\mongod.log

# network interfaces
net:
     port: 27017  # Port to use
     bindIp: 127.0.0.1  # Local IP address
#     ssl:
#       mode: requireSSL
#       PEMKeyFile: C:\mongodb.pem


# allowConnectionsWithoutCertificates: true

#processManagement:

# Enables the authentication of users.
security:
  authorization: "enabled"

#operationProfiling:

#replication:

#sharding:

## Enterprise-Only Options:

#auditLog:

```

***

Return to the [README file](README.md).