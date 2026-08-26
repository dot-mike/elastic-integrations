# TODO

## Sample Data Coverage

Current sample data covers 20 of 145 typeids. The following event categories have no sample log data and are untested in the pipeline and dashboards:

- [ ] User Portal events (50000-50008): login, logout, password change/reset, certificate self-enrollment
- [ ] Guest Portal events (20601-20611): guest auth, MAC-only auth, SmartConnect
- [ ] OAuth Portal events (20701-20702): OAuth authentication
- [ ] SAML events (20500-20503): SAML IdP auth, SP requests
- [ ] RADIUS Accounting events (25000-25002): session start/stop/usage
- [ ] MAC Authentication events (20400-20404): MAC-based auth success/failure
- [ ] Certificate Management events (10121-10132): import, signing, revocation, expiration
- [ ] Hardware Monitor events (60000-60001): power supply status, disk capacity warning
- [ ] License events (10610-10616, 30020-30023): license import/expiration/status
- [ ] User contact field changes (10050-10058): email/mobile set/change/delete
- [ ] FortiToken management events (10101-10114): seed activation, import, transfer, revoke
- [ ] FIDO key events (10139-10142): registration, revocation, reset
- [ ] Guest user management (10154-10158): print/view/export/reset credentials
- [ ] SSO events (10205-10209): group mapping, user logoff/update, SAML/LDAP import
- [ ] Server restart events (30000-30003, 30100, 30150): LDAP, FSSO, Web, TACACS+, RADIUS
- [ ] Backup/restore events (10500-10502, 30300-30307): data backup, log backup, config backup
- [ ] KV-only log format (`date= time= devname= logid=...`) not supported in pipeline
