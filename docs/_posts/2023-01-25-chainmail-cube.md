---
layout: post
title:  "Chainmail Cube"
date:   2023-01-25 11:00:00
families: Japanese
image_path: "/assets/images/posts/2023_01_25_chainmail_cube"
model_path: "/assets/models/posts/2023_01_25_chainmail_cube"
main_image: "/box_top_view.jpg"
tags: weave solid kinged
---

### Overview

Recently I found a wonderful [tutorial](https://www.mailleartisans.org/articles/articledisplay.php?key=145) by [Blaise](https://www.mailleartisans.org/members/memberdisplay.php?key=249) on [M.A.I.L.](https://www.mailleartisans.org/) that covers how to generalise the Japanese 8-in-2 sheet pattern into 3 dimmensions and create a cube. This takes a wonderful [Japanese]({{ site.baseurl }}{{ site.family_page }}#Japanese) weave and extends it into a third dimmension.

### Materials

The rings used for this peice are 14 {% include abbreviations/swg.html %} with a 5/16" {% include abbreviations/id.html %} for an {% include abbreviations/ar.html %} of 4.0 made of Bright Aluminum that I bought from the [Ring Lord](https://theringlord.com/).

### Notes

The first layer started out very loose; though once the first interstial layer was put in place the peice started taking shape.

Once the second layer was started some of the rings started being difficult to add. I found that trying to add them such you are guiding the new ring to be on top of any ring already in a position helped quite a lot. Additionally if you are using machine cut rings using the pointed edge also helped wedge the wire into postion as well.

Overall the final product maintains its shape fairly well, though there is still some slack.

This weave is known to serve very well for creating the sturucture of larger projects. Though as a small cube is also makes a good fidget toy/paperweight.

### Pictures

Below are some images of the completed cube:

#### Top View:

<img style="max-width: min(500px, 100%)" src="{{ site.baseurl }}{{ page.image_path }}/box_top_view.jpg">

#### Side View:

<img style="max-width: min(500px, 100%)" src="{{ site.baseurl }}{{ page.image_path }}/box_side_view.jpg">

#### Isometric View:

<img style="max-width: min(500px, 100%)" src="{{ site.baseurl }}{{ page.image_path }}/box_isometric_view.jpg">


### Interactive Model No Outline {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="baseline"></canvas>

### Interactive Model White Outline {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="white_outline"></canvas>


### Interactive Model Black Outline {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="black_outline"></canvas>


### Interactive Model Dark Grey White Outline {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="v3"></canvas>


### Interactive Model Dark Blue White Outline {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="v4"></canvas>


### Interactive Model Grey Red Outline {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="v5"></canvas>


### Interactive Model Grey Thick Black Outline {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="v6"></canvas>


### Interactive Model Grey Thick Black Outline 2 {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="v7"></canvas>


### Interactive Model Grey Black Outline 2 {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="v8"></canvas>


### Interactive Model Light Grey Thick Black Outline 2 {% include 3d_model_instructions.html %}

<canvas class="model_canvas" id="v9"></canvas>


{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_no_outline.glb" %}
{% include  3d_model.html model=path canvas_id="baseline" ignore_canvas="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_white_outline.glb" %}
{% include  3d_model.html model=path canvas_id="white_outline" ignore_canvas="Yes" is_secondary="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_black_outline.glb" %}
{% include  3d_model.html model=path canvas_id="black_outline" ignore_canvas="Yes" is_secondary="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_v_3.glb" %}
{% include  3d_model.html model=path canvas_id="v3" ignore_canvas="Yes" is_secondary="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_v_4.glb" %}
{% include  3d_model.html model=path canvas_id="v4" ignore_canvas="Yes" is_secondary="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_v_5.glb" %}
{% include  3d_model.html model=path canvas_id="v5" ignore_canvas="Yes" is_secondary="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_v_6.glb" %}
{% include  3d_model.html model=path canvas_id="v6" ignore_canvas="Yes" is_secondary="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_v_7.glb" %}
{% include  3d_model.html model=path canvas_id="v7" ignore_canvas="Yes" is_secondary="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_v_8.glb" %}
{% include  3d_model.html model=path canvas_id="v8" ignore_canvas="Yes" is_secondary="Yes" %}

{% assign path = site.baseurl | append: page.model_path | append: "/japanese_8_in_2_cube_v_9.glb" %}
{% include  3d_model.html model=path canvas_id="v9" ignore_canvas="Yes" is_secondary="Yes" %}
