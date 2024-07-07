# ClassicalChineseLiterature

- [Chibi Fu](./Chibi%20Fu.md)
- [Sending East Yang Ma Sheng](./Sending%20East%20Yang%20Ma%20Sheng.md)

> 2024-04-08 08:02:13 UTC -- Warning: Your gitlab.rb and gitlab-cd basecrets.json files contain sensitive data 
> and are not included in this backup. You will need these files to restore a backup.
> Please back them up manually.

> [!CAUTION]
>
> 2024-04-09 02:11:56 UTC -- Be sure to stop Puma, Sidekiq, and any other process that
> connects to the database before proceeding. For Omnibus
> installs, see the following link for more information:
> https://docs.gitlab.com/ee/raketasks/backup_restore.html#restore-for-omnibus-gitlab-installations
>
> Before restoring the database, we will remove all existing
> tables to avoid future upgrade problems. Be aware that if you have
> custom tables in the GitLab database these tables and all data will be
> removed.

> [!CAUTION]
>
> Restoring PostgreSQL database gitlabhq_production ... ERROR:  must be owner of extension pg_trgm
> ERROR:  must be owner of extension btree_gist
> ERROR:  must be owner of extension btree_gist
> ERROR:  must be owner of extension pg_trgm

> [!WARNING]
>
> 2024-04-09 02:25:20 UTC -- Warning: Your gitlab.rb and gitlab-secrets.json files contain sensitive data 
> and are not included in this backup. You will need to restore these files manually.
