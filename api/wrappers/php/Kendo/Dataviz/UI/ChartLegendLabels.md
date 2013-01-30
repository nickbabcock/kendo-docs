---
title: ChartLegendLabels
slug: php-ChartLegendLabels
tags: api, php
publish: true
---

# \Kendo\Dataviz\UI\ChartLegendLabels

A PHP class representing the labels setting of ChartLegend.


## Methods

### color
The color of the labels.
Any valid CSS color string will work here, including hex and rgb.
#### Parameters

##### $value `string`



#### Example 
    $labels = new \Kendo\Dataviz\UI\ChartLegendLabels();
    $labels->color('value');

### font
The font style of the labels.
#### Parameters

##### $value `string`



#### Example 
    $labels = new \Kendo\Dataviz\UI\ChartLegendLabels();
    $labels->font('value');

### template
The template of the labels.
Template variables:
#### Parameters

##### $value `string`



#### Example 
    $labels = new \Kendo\Dataviz\UI\ChartLegendLabels();
    $labels->template('value');
