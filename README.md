# learn-sql
how to install and run mysql/postgresql in eks

```bash
SELECT STATUS, NAME FROM PUBLIC.INSTANCE WHERE NAME = 'name';
SELECT STATUS, NAME FROM PUBLIC.INSTANCE WHERE NAME = 'name' AND STATUS = 'deleting';
```
```bash
UPDATE PUBLIC.INSTANCE SET STATUS = 'deleted' WHERE NAME = 'name';
```
