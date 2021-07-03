---
layout: default
title: Copy to clipboard
---
<!-- <style>
.dp__copy-to-clip{
    background: red;
}
</style> -->

<div class="dp__copy-to-clip dp__input"> 
    <input type="text" name="script_name[]" value="testsss" /> 
    <div class="reg-shortcode"> 
        <button href="#" class="dp__btn dp__btn-icon">
            <svg xmlns="http://www.w3.org/2000/svg" height="18px" viewBox="0 0 24 24" width="18px" fill="currentColor"><path d="M0 0h24v24H0z" fill="none"/><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg>
        </button>
    </div> 
</div> 

<script>
   // copy scripts manager enqueue code
   function copyToClipboardDplugins(element) {
       var sel, range;
       var el = jQuery(element)[0];
       if (window.getSelection && document.createRange) { //Browser compatibility
         sel = window.getSelection();
         if(sel.toString() == ''){ //no text selection
            window.setTimeout(function(){
               range = document.createRange(); //range object
               range.selectNodeContents(el); //sets Range
               sel.removeAllRanges(); //remove all ranges from selection
               sel.addRange(range);//add Range to a Selection.
           },1);
         }
       }else if (document.selection) { //older ie
           sel = document.selection.createRange();
           if(sel.text == ''){ //no text selection
               range = document.body.createTextRange();//Creates TextRange object
               range.moveToElementText(el);//sets Range
               range.select(); //make selection.
           }
       }
       var $temp = jQuery("<input>");
       jQuery("body").append($temp);
       $temp.val(jQuery(element).text()).select();
       document.execCommand("copy");
       $temp.remove();
   }
   jQuery(document).ready(function(){
      jQuery(document).on("click", ".reg-shortcode", function(){
        var currObj = jQuery(this);
        copyToClipboardDplugins(jQuery(currObj).find('input'));
        jQuery(currObj).find("span").html("Copied");
        setTimeout(function(){
            jQuery(currObj).find("span").html("Click to copy");
        }, 3000);
      });
   });
</script>


{% highlight html %}

<div class="script-row__edit"> 
   <div class="font-field swk-field"> 
    <label>Script name</label> 
    <input type="text" name="script_name[]" value="test" /> 
   </div> 
   <div class="swk-field reg-shortcode"> 
    <div class="reg-enq">
     wp_enqueue_script('test'); 
    </div> 
    <span>Click to copy</span> 
   </div> 
</div>

<script>
   // copy scripts manager enqueue code
   function copyToClipboardDplugins(element) {
       var sel, range;
       var el = jQuery(element)[0];
       if (window.getSelection && document.createRange) { //Browser compatibility
         sel = window.getSelection();
         if(sel.toString() == ''){ //no text selection
            window.setTimeout(function(){
               range = document.createRange(); //range object
               range.selectNodeContents(el); //sets Range
               sel.removeAllRanges(); //remove all ranges from selection
               sel.addRange(range);//add Range to a Selection.
           },1);
         }
       }else if (document.selection) { //older ie
           sel = document.selection.createRange();
           if(sel.text == ''){ //no text selection
               range = document.body.createTextRange();//Creates TextRange object
               range.moveToElementText(el);//sets Range
               range.select(); //make selection.
           }
       }
       var $temp = jQuery("<input>");
       jQuery("body").append($temp);
       $temp.val(jQuery(element).text()).select();
       document.execCommand("copy");
       $temp.remove();
   }
   jQuery(document).ready(function(){
      jQuery(document).on("click", ".reg-shortcode", function(){
        var currObj = jQuery(this);
        copyToClipboardDplugins(jQuery(currObj).find('.reg-enq'));
        jQuery(currObj).find("span").html("Copied");
        setTimeout(function(){
            jQuery(currObj).find("span").html("Click to copy");
        }, 3000);
      });
   });
</script>
{% endhighlight %}