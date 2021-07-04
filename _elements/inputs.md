---
layout: default
title: Input
---

<div class="dp__input">
    <input type="text" placeholder="text"> <br><br>
    <input type="date"> <br><br>
    <input type="datetime-local">  <br><br>
    <input type="email" placeholder="email">  <br><br>
    <input type="number" placeholder="number">  <br><br>
    <input type="password" placeholder="password">  <br><br>

    <input type="url" placeholder="url">  <br><br>
    
    <input type="file">  <br><br>

    <textarea
        cols="10"
        rows="3"
        placeholder="textarea">
    </textarea>    
    <br><br>
    <p>
        Add button classes to input types (button, reset, submit)
    </p>
    <br>
    <input type="button" value="Button" class="dp__btn dp__btn-pri"> 
    <input type="reset" class="dp__btn dp__btn-pri"> 
    <input type="submit" class="dp__btn dp__btn-pri">    
    <br><br>
</div>    



{% highlight html %}
<div class="dp__input">
    <input type="text" placeholder="text">
    <input type="date">
    <input type="datetime-local"> 
    <input type="email" placeholder="email"> 
    <input type="number" placeholder="number"> 
    <input type="password" placeholder="password"> 

    <input type="url" placeholder="url"> 
    
    <input type="file"> 

    <textarea
        cols="10"
        rows="3"
        placeholder="textarea">
    </textarea>    

    <input type="button" value="Button" class="dp__btn dp__btn-pri">  <br><br>
    <input type="reset" class="dp__btn dp__btn-pri">  <br><br>
    <input type="submit" class="dp__btn dp__btn-pri">    
</div>   
{% endhighlight %}