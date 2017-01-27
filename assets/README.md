# Assets

This folder contains local asset folders which are mapped 
into running containers for cases where you want to store
the assets on the host.

The only important example is the Backups folders, the
others should not really be used.

## Backup

This folder is used to hold any backups that may be created
in local operation. It is mapped into the project at path
/app/backup, in all containers.
