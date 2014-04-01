ansible-playbook-mt
===================

ansible playbook smple. for Movable Type (with PowerCMS)

- 実行前に MT の source を以下に配置して下さい
  - `roles/web/files/MTA*.*.*-PowerCMSEnterprise*.*.zip`

- 実行前に以下 vars を確認して下さい
  - `group_vars/all`
  - `roles/web/vars/main.yml`

```
$ ansible-playbook -i hosts site.yml
```

