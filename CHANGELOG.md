v0.1.2 (2016-02-14)
-------------------
- Changed chef_server_basename to basename
- Changed chef_server_count to count
- Added variable `ssh_cidrs` to allow SSH access restrictions. Default: `0.0.0.0/0`
- Added ports 10000-10003 to security groups (push-jobs)
- Supporting documentation updates

v0.1.1 (2016-02-11)
-------------------
- Bump version
- Move some operations around
- Place PEM key files under `.chef/keys` now
- Remove hacks to support Delivery (not necessary anymore)
- Update variables, trim some characters
- Update `README.md`
- Update `CHANGELOG.md` prettier

v0.1.0 (2016-02-04)
-------------------
- Bump version
- Make CHANGELOG.md prettier

v0.0.2 (2016-02-04)
-------------------
- Removed cookbooks directory from repo

v0.0.1 (2016-02-04)
-------------------
- Implement version in `CHANGELOG.md`
- Create `CHANGELOG.md`
- Finalize module
- Updates to `outputs.tf`, added more information
- Updates to `variables.tf`, adding descriptions

33mb9e2aa0 (2016-02-04)
-------------------
- Fixed old chef exec command hanging around
- Fixed IPTables issues; flush then set complete rule set

33m14b29b9 (2016-02-04)
-------------------
- Fixing references to aws_instance provider items

33m5bc32bc (2016-02-04)
-------------------
- removed cookbooks directory file sync
- execute chef server creation directly at server
- create first user
- create first org
- associate user to org
- download user pem
- download org validator pem

33m954a88d (2016-02-04)
-------------------
- fix bulleted list

33ma4c360c (2016-02-04)
-------------------
- Supported OSes
- more assumptions

33m2879244 (2016-02-04)
-------------------
- Delete email linking

33me856561 (2016-02-04)
-------------------
- Correcting e-mail link for Brian Menges

33m8b5553f (2016-02-04)
-------------------
- Correcting linking syntax for users

33m1077c11 (2016-02-04)
-------------------
- Correcting linking syntax

33me261f30 (2016-02-04)
-------------------
- Updating README.md
- More explanation about how to use this module

33mb66e077 (2016-02-03)
-------------------
- moved connection outside of the provisioners per @afiune recommendation
- Added TODO to get rid of the provisioner file hack
- creative addition of git package supporting CentOS and Ubuntu

33m3015e80 (2016-02-03)
-------------------
- SPELLING!

33m4a9a5eb (2016-02-03)
-------------------
- Fixing org to chef_org

33m2440c7c (2016-02-03)
-------------------
- Mixed up region and vpc

33m5475d18 (2016-02-03)
-------------------
- Removing AMI magic
- Getting too complex, simplifying things

33m3a1a2b0 (2016-02-02)
-------------------
- Fixed ami reference, using lookup now

33m3f76ee1 (2016-02-02)
-------------------
- Initial commit

33mc5e5f07 (2016-02-02)
-------------------
- Create repo
