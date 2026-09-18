---
layout: about
title: about
permalink: /
subtitle: <a href='#'>zhoual@sas.upenn.edu</a>. Philadelphia, PA.

profile:
  align: right
  image: prof_pic.png
  image_circular: false # crops the image to make it circular
  more_info:
    "asdf"
    #>
    #<p>Philadelphia, PA</p>
    #<p>Ithaca, NY</p>
    #<p>Parsippany, NJ</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi! My name is Albert.

I'm currently a 1st year PhD student at the University of Pennsylvania studying experimental particle physics. I did my undergrad at Cornell University in physics and philosophy.

Among other things, I like fat cats, bicycles, motorcycle touring, Oasis, and Fall Out Boy.

I'm using this website as a digital archive of cool things I've done, seen, and worked on.

<style>
  .home-collage {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-auto-rows: 180px;
    gap: 10px;
    margin-top: 2rem;
  }

  .home-collage img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 8px;
  }

  .home-collage .featured {
    grid-column: span 2;
    grid-row: span 2;
  }

  @media (max-width: 600px) {
    .home-collage {
      grid-template-columns: repeat(2, 1fr);
      grid-auto-rows: 140px;
    }
  }
</style>

<div class="home-collage">
  <img
    class="featured"
    src="/assets/img/collage/bike_background.JPG"
    alt="Description of the first photo"
  >
  <img src="/assets/img/collage/hutong.png" alt="Description of the second photo">
  <img src="/assets/img/collage/baozi.jpeg" alt="Description of the third photo">
</div>
