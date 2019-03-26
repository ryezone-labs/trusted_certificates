ryezone_labs.trusted_certificates
=========

Installs trusted wildcard certificates.

Requirements
------------

Certificate must be pregenerated and stored on ansible controler server at
`/opt/ansible/certificates/{{ top_level_domain }}.crt`

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
