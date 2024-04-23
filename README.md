# tf-test-learning
tf-test-learning

1) Renombrar el fichero:
```filename = "${path.module}/user_source_of_truth.json"```

2) Cambiar la lista de array:

```json
locals {
  admins = {
    gary  = "gary@gmail.com"
    wendy = "wendy@gmail.com"
    bob   = "bob@gmail.com"
  }
```

3) Añadir en ambas listas:

```json
locals {
  admins = {
    gary  = "gary@gmail.com"
    wendy = "wendy@gmail.com"
  }
  users = {
    bill  = "bill@gmail.com"
    jenny = "jenny@gmail.com"
    wendy = "wendy@gmail.com"
  }
}
```