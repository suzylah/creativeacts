---
categories: []
layout: book
title: Actions
created: 1372506463
---
Here you find a collection of action reports. You can find reports written by the collectives themselves or summarised by the editors of Masta collective. Here you find first hand narrations about how an idea for an action was born and put in practice, and what kind of effects it did have.
<!--more-->

This chapter will never be closed. We started it with a selection of actions and you are invited to join us expanding it by submitting actions. Rather than collecting an encyclopedic amount of data about creative acts around the globe, we wish to find a representative selection, inlcuding examples of creative activism from every corner of this lovely planet - from small rural villages to metropolises, from people of all ages and backgrounds.

<div class="card-columns">
    {%- for post in site.categories.action -%}
    <div class="card">
        <!--<img src="..." class="card-img-top" alt="...">-->
        <div class="card-body">
        <span>Action</span>
        <h5 class="card-title">
            <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
            </a>
        </h5>
        <p class="card-text">{{ post.excerpt }}</p>
        </div>
    </div>
    {%- endfor -%}
</div>
