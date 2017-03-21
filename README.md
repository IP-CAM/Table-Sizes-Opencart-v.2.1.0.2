# Table Sizes

Módulo para Opencart (testando apenas na versão 2.1.0.2). Exibe uma tabela de medidas do produto em modal (página do produto). 

## Instalação

Na área administrativa da loja: Extensões -> Instalador -> Upload do arquivo (tableSizes.ocmod.zip),

Após fazer isso: Extensões -> Modificações -> Atualizar.

## Arquivos "modificados" (nada é removido, apenas adicionado)

- admin/controller/catalog/product.php
- admin/model/catalog/product.php
- admin/view/template/catalog/product_form.tpl
- catalog/model/catalog/product.php
- catalog/controller/product/product.php
- catalog/view/theme/*/template/product/product.tpl
- Tabela oc_product, adicionado mais um campo: imageTabela


## Screenshots

Na área administrativa:
![Print 1](http://i.imgur.com/XnoOvWD.png)

Na página do produto:

![Print 2](http://i.imgur.com/fdxtsdA.png)

Modal ao clicar no botão:
![Print 3](http://i.imgur.com/LwkXMYS.png)
