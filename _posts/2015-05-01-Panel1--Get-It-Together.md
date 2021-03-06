---
#title: "Get It Together<span>&trade;</span>"
title: ""
subtitle: ""
tagline: "The Art of Doing More with Less"
description: "Do you feel like you are always running late, or losing things? Are you reluctant to ask people over because you are tired of shutting the door on an ever increasing amount of stuff? <br><br>
My three-step interior therapy program will cut through the clutter, get you organized, and transform your home or office. Leaving you free to do more of what is important to you, with less."
step1_title: "Motivation"
step1_text:  "A compelling set of questions to unlock the potential for your living/workspace"
step2_title: "Mindset"
step2_text: "Customized plan to ensure your surroundings relate intelligently to who you are"
step3_title: "Method"
step3_text:  "Sensitive when it comes to letting-go. No-nonsense getting you organized"
layout: post
published: true
---
<header id="header" class="intro container-fluid">
	<div class="intro-body row">
		<div class="col-sm-6 col-lg-5 col-lg-offset-1">
			{% if page.title != "" %}
			<div class="brand title"><h1>{{ page.title }}</h1></div>
			{% endif %}
			<div class="tagline"><h2>{{ page.tagline }}</h2></div>
			<div class="description">{{ page.description }}
				<img class="logo" src="{{ site.navigation.brand.logo }}">
			</div>
		</div>
		<div class="col-sm-4 col-sm-offset-2">
			<div class="row steps">
				{% if page.subtitle != "" %}
				<div class="col-md-11 col-md-offset-0 col-lg-6 col-lg-offset-2 subtitle"><h2>{{ page.subtitle }}</h2></div>
				{% endif %}
				<div class="row">
					<div class="col-sm-3 col-sm-offset-6 step1"><h2>{{ page.step1_title }}</h2><p>{{ page.step1_text }}</p></div>
				</div>
				<div class="row">
					<div class="col-sm-3 col-sm-offset-4 step2"><h2>{{ page.step2_title }}</h2><p>{{ page.step2_text }}</p></div>
				</div>
				<div class="row">
					<div class="col-sm-3 col-sm-offset-2 step3"><h2>{{ page.step3_title }}</h2><p>{{ page.step3_text }}</p></div>
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col-sm-2 col-sm-offset-5 text-center">
				<a href="#testamonials" class="btn btn-circle page-scroll">
				<i class="fa fa-angle-double-down animated"></i>
				</a>
			</div>
		</div>
	</div>
</header>
