```
# 文法チェック
ansible-playbook -i localhosts, -c local -K site.yml --syntax-check

# ドライラン
ansible-playbook -i localhosts, -c local -K -v site.yml --check

# 実行
ansible-playbook -i localhosts, -c local -K -v site.yml
```

