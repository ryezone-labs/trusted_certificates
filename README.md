ryezone_labs.trusted_certificates
=========

Installs trusted wildcard certificates.

Requirements
------------

Certificates must be pregenerated and stored on server at
`/opt/ansible/certificates/public`

Role Variables
--------------

### Global Variables

- `ryezone_labs_top_level_domain` (string)

   Sets the top level domain.

### Role Variables

- `top_level_domain` (string)

   Sets the top level domain.  Defaults to `{{ ryezone_labs_top_level_domain }}`.

License
-------

BSD
