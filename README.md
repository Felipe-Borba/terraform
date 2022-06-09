# Observações
baixei o terraform no win msm pelo scoop

depois de criar o main.tf e especificar o provider e colocar o token roda

```bash
terraform init
```

ai depois define o recurso e dale um 

```bash
terraform apply
```

## Para apagar esses recursos da cloud 

*ps. não tenho certeza se eu sou obrigado a deletar o deploy antes*

> testei e a principio não precisou do `kubectl delete -f deployment.yaml`


```bash
terraform destroy
```