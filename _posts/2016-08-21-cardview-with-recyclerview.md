---
layout: post
title:  "CardView with RecyclerView"
date:   2016-08-20 17:15:19
categories: [tutorial]
comments: true
---
How to create a CardView with a RecyclerView

<!--more-->

One of the most common UI widgets that have increased in popularity on Android and are the art of Material Design are CardViews. CardViews can be put to good use when combined with RecyclerViews. Despite ListViews being CardViews extends the FrameLayout and is supported on Android 2.X. In this post I will demonstrate how you can create one for your app. 

Let’s begin! Start by creating a new android project with an empty activity. 

Add the following dependencies to your build.grade as we require these in order to use the widgets:

{% highlight ruby %}
dependencies {
	... 
	compile 'com.android.support:recyclerview-v7:24.1.1'
	compile ‘com.android.support:cardview-v7:24.1.1’
}
{% endhighlight %}
