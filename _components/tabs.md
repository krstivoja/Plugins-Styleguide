---
layout: default
title: Tabs
---

<!-- <h2 class="nav-tab-wrapper">
	<a href="#" class="nav-tab nav-tab-active">Tab #1</a>
	<a href="#" class="nav-tab">Tab #2</a>
	<a href="#" class="nav-tab">Tab #3</a>
</h2> -->

<div class="dp__tabs">
	<div class="dp__tabs-navigation">
		<a href="#tab1" class="tab__trigger active">Tab 1</a>
		<a href="#tab2" class="tab__trigger">Tab 2</a>
		<a href="#tab3" class="tab__trigger">Tab 3</a>
	</div>	
	<div class="dp__tabs-content">
		<section id="tab1" class="tab__content">
			<!-- content goes here -->
			<h1>Content goes here</h1>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			<!-- content goes here -->
		</section>
		<section id="tab2" class="tab__content is-hidden">
			<!-- content goes here -->
			<h1>Content goes here</h1>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			<!-- content goes here -->
		</section>
		<section id="tab3" class="tab__content is-hidden">
			<!-- content goes here -->
			<h1>Content goes here</h1>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			<!-- content goes here -->
		</section>
	</div>	
</div>	


{% highlight html %}
<h2 class="nav-tab-wrapper">
	<a href="#" class="nav-tab nav-tab-active">Tab #1</a>
	<a href="#" class="nav-tab">Tab #2</a>
	<a href="#" class="nav-tab">Tab #3</a>
</h2>

<div class="dp__tabs">
	<div class="dp__tabs-navigation">
		<a href="#tab1" class="tab__trigger">Tab 1</a>
		<a href="#tab2" class="tab__trigger">Tab 2</a>
		<a href="#tab3" class="tab__trigger">Tab 3</a>
	</div>	
	<div class="dp__tabs-content">
		<section id="tab1" class="tab__content">
			<!-- content goes here -->
		</section>
		<section id="tab2" class="tab__content is-hidden">
			<!-- content goes here -->
		</section>
		<section id="tab3" class="tab__content is-hidden">
			<!-- content goes here -->
		</section>
	</div>	
</div>	
{% endhighlight %}