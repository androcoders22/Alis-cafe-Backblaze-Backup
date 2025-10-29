# pcmc-mongo-to-backblaze-backup

Restore command, with the fooking mongo URI.
```shell
mongorestore --gzip --archive=mongodb-backup-2025-10-24.gz --uri="here" --drop
```

replace correct uri with write permissions in the command in the location of `here` 

URI avalible in mongodb `atlassdashboad > clusters > connect > drivers`
