## Openshift Laravel Quickstart
Quickstart Laravel para a plataforma Getup Cloud OpenShift.

Para criar sua aplicação Laravel, primeiro vcê precisa registrar-se na Getup. Acesse http://getupcloud.com/#/sign-up e faça seu cadastro. Você recebe gratuitamente 750hs para testar a plataforma.

Usando o comando rhc, execute:

```shell
rhc app create laravel php-5.4 mysql-5.5 --from-code git://github.com/caruccio/openshift-laravel4-quickstart-app.git
```

Se preferir, crie sua aplicação Laravel a partir do [Instant App do dashboard](https://broker.getupcloud.com/console/application_types/quickstart!10)

Após a criação, acesse seu app em http://laravel-[namespace].getup.io
