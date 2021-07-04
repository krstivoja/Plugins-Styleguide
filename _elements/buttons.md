---
layout: default
title: Buttons
---

<style>
.inline-wrap > *{
    margin-right: 20px;
    margin-bottom: 20px;
}
</style>

<h3>Themes</h3>

<div class="inline-wrap">
    <button href="#" class="dp__btn">Button Default</button>
    <button href="#" class="dp__btn dp__btn-pri">Button Primary</button>
    <button href="#" class="dp__btn dp__btn-sec">Button Secondary</button>
    <button href="#" class="dp__btn dp__btn-text">Button Text</button>
    <button href="#" class="dp__btn dp__btn-delete">Button Delete</button>

</div>    


{% highlight html %}
<button href="#" class="dp__btn">Button Default</button>
<button href="#" class="dp__btn dp__btn-pri">Button Primary</button>
<button href="#" class="dp__btn dp__btn-sec">Button Secondary</button>
<button href="#" class="dp__btn dp__btn-text">Button Text</button>
<button href="#" class="dp__btn dp__btn-delete">Button Delete</button>
{% endhighlight %}



<h3>Sizes</h3>

<div class="inline-wrap">
    <button href="#" class="dp__btn dp__btn-pri dp__btn-sm">Button Small</button>
    <button href="#" class="dp__btn dp__btn-pri">Button Primary</button>
    <button href="#" class="dp__btn dp__btn-pri dp__btn-lg">Button Large</button>
</div>    


{% highlight html %}
<button href="#" class="dp__btn dp__btn-pri dp__btn-sm">Button Default</button>
<button href="#" class="dp__btn dp__btn-pri">Button Primary</button>
<button href="#" class="dp__btn dp__btn-pri dp__btn-lg">Button Inline</button>
{% endhighlight %}



<h3>With Icons</h3>

<div class="inline-wrap">
    <button href="#" class="dp__btn dp__btn-icon">
        <svg xmlns="http://www.w3.org/2000/svg" height="18px" viewBox="0 0 24 24" width="18px" fill="#000000"><path d="M0 0h24v24H0z" fill="none"/><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg>
        Button With Icon
    </button>   
    <button href="#" class="dp__btn dp__btn-icon dp__btn-pri">
        <svg xmlns="http://www.w3.org/2000/svg" height="18px" viewBox="0 0 24 24" width="18px" fill="#000000"><path d="M0 0h24v24H0z" fill="none"/><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg>
        Button With Icon
    </button>   
    <button href="#" class="dp__btn dp__btn-icon">
        <svg xmlns="http://www.w3.org/2000/svg" height="18px" viewBox="0 0 24 24" width="18px" fill="currentColor"><path d="M0 0h24v24H0z" fill="none"/><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg>
    </button>   
</div>    

{% highlight html %}
    <button href="#" class="dp__btn dp__btn-icon dp__btn-outline">
        <svg xmlns="http://www.w3.org/2000/svg" height="18px" viewBox="0 0 24 24" width="18px" fill="#000000"><path d="M0 0h24v24H0z" fill="none"/><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg>
        Button With Icon
    </button>   
    <button href="#" class="dp__btn dp__btn-icon dp__btn-pri">
        <svg xmlns="http://www.w3.org/2000/svg" height="18px" viewBox="0 0 24 24" width="18px" fill="#000000"><path d="M0 0h24v24H0z" fill="none"/><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg>
        Button With Icon
    </button>   
    <button href="#" class="dp__btn dp__btn-icon dp__btn-outline">
        <svg xmlns="http://www.w3.org/2000/svg" height="18px" viewBox="0 0 24 24" width="18px" fill="currentColor"><path d="M0 0h24v24H0z" fill="none"/><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg>
    </button>   
{% endhighlight %}
