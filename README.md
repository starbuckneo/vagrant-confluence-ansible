# vagrant-ansible-confluence

Modify Confluence version on play.yml and confluence.service (change 7.4.5 for the version we want)

Once saved, execute `vagrant up`. When finish, access to http://192.168.33.11:8090/ to proceed with Confluence Setup.

When asking for the DATABASE POSTGRES information:

`host`: `localhost`

`port`: `5432`

`user`: `confluence`

`password`: `confluence`

`database`: `confluence`
