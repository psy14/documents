# documents

## test server 
http://107.22.14.140/

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
