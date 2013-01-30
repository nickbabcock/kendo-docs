---
title: EditorImageBrowserSchemaModelFieldsName
slug: php-EditorImageBrowserSchemaModelFieldsName
tags: api, php
publish: true
---

# \Kendo\UI\EditorImageBrowserSchemaModelFieldsName

A PHP class representing the name setting of EditorImageBrowserSchemaModelFields.


## Methods

### field
The name of the field.
#### Parameters

##### $value `string`



#### Example 
    $name = new \Kendo\UI\EditorImageBrowserSchemaModelFieldsName();
    $name->field('value');

### parse
Specifies the function which will parse the field value. If not set default parsers will be used.
#### Parameters

##### $value `\Kendo\JavaScriptFunction`



#### Example 
    $name = new \Kendo\UI\EditorImageBrowserSchemaModelFieldsName();
    $name->parse(new \Kendo\JavaScriptFunction('function() { }'));
