---
title: FX Tile
slug: fx-tile
publish: true
---

# Tile

Slides the element to its original position in the specified direction, while sliding out the element specified in the `previous` parameter.
Supported directions are `left`, `right`, `up` and `down`.
For this effect to work as expected, the elements should be positioned on top of each other.

    <style>
        #container {
            position: relative;
            width: 200px;
            height: 200px;
        }

        #foo {
            position: absolute;
            width: 200px;
            height: 200px;
            background: blue;
        }

        #bar {
            position: absolute;
            width: 200px;
            height: 200px;
            background: red;
        }

    </style>

    <div id="container">
        <div id="bar"> Page 2</div>
        <div id="foo"> Page 1</div>
    </div>

    <script>
        kendo.fx($("#bar")).tile("left", $("#foo")).play();
        kendo.fx($("#bar")).tileLeft($("#foo")).play();
    </script>


## Constructor Parameters

### Direction

The direction to which the sliding will occur.

### Previous

The element to slide out of the view.
