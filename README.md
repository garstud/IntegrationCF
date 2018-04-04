# IntegrationCF
Joomla Use Case to explain how to add Custom Fields support in our owns components

We assume your component is well-developped with MVC and normal Joomla features (Model XML form mapping and loader, Table store, admin standard layout ...)

## 1st point : add Fields sub-menus

helper : 2 submenus ... (TODO)

Now the administration of you component supports Custom Fields !

## 2nd point : load Fields in you Backend edition

/models/forms/record.xml : add params fields with Fields fieldset (TODO)

/views/record/tmpl/edit.php : JLayoutHelper::render ... params ? (TODO)

/views/record/tmpl/edit_params.php (TODO)

## 3rd point : save Backend Fields input

/tables : store : params (TODO)


## Last point : Global Parameters for Integration
Optionnal. Like the Joomla Core components you can provide a paraméter to activate or deactivate the Ciustom Fields support

... config.xml : fieldset integration + field custom_fields_enable  (TODO)

... helper ... if ... 2 sub-menus  (TODO)



## Conclusion : what scripts to modify ?

 (TODO)
