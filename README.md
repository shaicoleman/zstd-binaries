# zstd-binaries
Binaries for zstd

## Example in Ansible

```
- name: Download binary
  get_url:
    url: https://github.com/shaicoleman/zstd-binaries/raw/master/zstd-1.3.3-xenial-amd64
    dest: /usr/local/bin/zstd
    mode: 0755
    owner: root
    group: root
    checksum: sha256:780100b18300567e38856d405d8a8ce5080ce4d4972f3a72cbdfb2fe5e202223
```
