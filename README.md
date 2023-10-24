# documents

### system token
```curl
curl -X POST --location "{{host}}/api/client/user/login" \
    -H "Content-Type: application/json" \
    -d "{
          \"username\": \"someuser\",
          \"password\": \"suerpasswd\"
        }"
```

### rocket chat token
```
curl -X POST --location "{{host}}//api/client/user/login-chat" \
    -H "Authorization: Bearer {{financial system token}}"
```
