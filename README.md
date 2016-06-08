# hobknob-client-php

> A php client to retrieve feature toggles stored in Etcd.

## Etcd

Feature toggles are stored in Etcd using the following convention:
`http://host:port/v2/keys/v1/toggles/applicationName/toggleName`
