---
title: LinearGaugeScaleMinorTicks
slug: php-LinearGaugeScaleMinorTicks
tags: api, php
publish: true
---

# \Kendo\Dataviz\UI\LinearGaugeScaleMinorTicks

A PHP class representing the minorTicks setting of LinearGaugeScale.


## Methods

### color
The color of the minor ticks.
Any valid CSS color string will work here, including hex and rgb.
#### Parameters

##### $value `string`



#### Example 
    $minorTicks = new \Kendo\Dataviz\UI\LinearGaugeScaleMinorTicks();
    $minorTicks->color('value');

### size
The minor tick size.
This is the length of the line in pixels that is drawn to indicate the tick on the scale.
#### Parameters

##### $value `float`



#### Example 
    $minorTicks = new \Kendo\Dataviz\UI\LinearGaugeScaleMinorTicks();
    $minorTicks->size(1);

### visible
The visibility of the minor ticks.
#### Parameters

##### $value `boolean`



#### Example 
    $minorTicks = new \Kendo\Dataviz\UI\LinearGaugeScaleMinorTicks();
    $minorTicks->visible(true);

### width
The width of the minor ticks.
#### Parameters

##### $value `float`



#### Example 
    $minorTicks = new \Kendo\Dataviz\UI\LinearGaugeScaleMinorTicks();
    $minorTicks->width(1);
