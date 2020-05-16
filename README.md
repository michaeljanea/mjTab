# mjTab
A single content area with multiple panels, each associated with a header.

## How To Install
1. Extract the downloaded zip file (mjTab.zip)
2. Insert below codes to the <head> section of your page
`<link rel="stylesheet" type="text/css" href="mjTab.css" />`
3. Insert below codes before the </body> tag of your page
```JavaScript
<script type="text/javascript" src="jquery-1.9.1.min.js"></script>
<script type="text/javascript" src="mjTab.js"></script>
<script type="text/javascript">
$('#myTab').mjTab();
</script>
4. Add the below sample HTML to the BODY of your page
```html
<div class="mj_tab" id="myTab">
    <div class="mj_tab_items">
        <div data-tab="#tab1" class="active">Tab 1</div>
        <div data-tab="#tab2">Tab 2</div>
        <div data-tab="#tab3">Tab 3</div>
    </div>
    
    <div class="mj_tab_contents">
        <div id="tab1" class="active">
            Tab 1 content. Raw denim you probably haven't heard of them jean shorts Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro keffiyeh dreamcatcher synth. Cosby sweater eu banh mi, qui irure terry richardson ex squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan american apparel, butcher voluptate nisi qui.
        </div>
        <div id="tab2">
            Tab 2 content. Raw denim you probably haven't heard of them jean shorts Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro keffiyeh dreamcatcher synth. Cosby sweater eu banh mi, qui irure terry richardson ex squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan american apparel, butcher voluptate nisi qui.
        </div>
        <div id="tab3">
            Tab 3 content. Raw denim you probably haven't heard of them jean shorts Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro keffiyeh dreamcatcher synth. Cosby sweater eu banh mi, qui irure terry richardson ex squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan american apparel, butcher voluptate nisi qui.
        </div>
    </div>
</div>
```

## More Setup Information
|  Option | Description  |
| ------------ | ------------ |
|  duration | a string or number determining how long the animation will run. `Default Value: 400` |


## LOGS
##### Version 1.0
Initial release