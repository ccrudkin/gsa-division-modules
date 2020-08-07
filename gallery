## Documentation

### Basics

The Gallery Module is a template for creating a gallery layout, with multiple rows of same-height elements.

Features:
* Mobile-first design; gallery items stack vertically on small screens.
* Customizable, full-height colored background for gallery items.
* Flexible layout; automatically fills a row with any number of gallery items.

### Use
The most basic form of the template is a simple series of nested containers with two content areas, main and footer:  
```
<!-- FUNDAMENTAL TEMPLATE -->  
<div class="dg-gallery-container">  
    <div class="dg-gallery-item">  
        <div class="dg-item-body">  
            <!-- main content -->  
        </div>  
        <div class="dg-item-footer">  
            <!-- footer content -->  
        </div>  
    </div>  
    <!-- Placeholder for incomplete rows; each row must have equal number of items for equal spacing -->  
    <div class="dg-gallery-item empty-item"></div>  
</div>  
```  
All blocks in a row will stretch to the same height, and the footer is pushed down to align with the bottom of the gallery item.  

For a gallery page, suggested use includes a full-width image followed by text copy in the main content area:  
```
<!-- TEMPLATE WITH LINKED IMAGE -->  
<div class="dg-gallery-container">  
    <div class="dg-gallery-item">  
        <div class="dg-item-body">  
            <div class="dg-img">  
                <a href="target-URL">  
                    <!-- img wrapped in a link -->   
                    <img class="img-responsive" src="img-URL" alt="description" />   
                </a>  
            </div>  
            <div>  
                <!-- text copy -->  
            </div>  
        </div>  
        <div class="dg-item-footer">  
            <!-- footer content -->  
        </div>  
    </div>  
    <!-- Placeholder for incomplete rows; each row must have equal number of items for equal spacing -->  
    <div class="dg-gallery-item empty-item"></div>  
</div>  
```

### Customization
To customize, include internal CSS rules with the `<style>` tag, somewhere on the page, ideally in its own, clearly identified HTML content block.  

The main target for customization is the block background color.
```
<style>  
    .dg-gallery-item {  
        background-color: #456123;  
    }  
</style>  
```
Fill each row (`.dg-gallery-container`) with the desired number of items, usually 3 to 4. If a row is incomplete, fill the empty slot(s) with an empty container:  
```
<div class="dg-gallery-item empty-item"></div>  
```
