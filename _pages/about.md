---
layout: about
title: about
permalink: /
subtitle: Doctoral Student at the Robotics Institute of Carnegie Mellon University <br> sunyuw@andrew.cmu.edu

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

selected_papers: false # selected publications are rendered manually below with a custom heading
social: true # render the social icons directly below the profile image

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: # leave blank to include all the blog posts
---

<style>
  .post {
    /* Adjust this value to control the gap below the profile/social row. */
    --profile-publications-gap: 0.75rem;
  }

  .about-hero {
    align-items: start;
    display: grid;
    gap: 1rem;
    grid-template-columns: minmax(0, 1fr) minmax(220px, 30%);
    margin-bottom: 0;
  }

  .about-summary {
    min-width: 0;
  }

  .education h2 {
    margin-bottom: 0;
    margin-top: 1.25rem;
  }

  .about-hero .post-header,
  .about-hero .post-title {
    margin-top: 0;
  }

  .about-hero .profile {
    float: none;
    margin: 0;
    width: 100%;
  }

  .about-profile-social {
    margin-top: 0.2rem;
  }

  .about-profile-social .contact-icons {
    font-size: 2.25rem;
  }

  .publications {
    clear: both;
    margin-top: 0;
  }

  .publication-heading {
    clear: both;
    margin-top: var(--profile-publications-gap);
  }

  .publications ol.bibliography > li {
    margin-bottom: 2rem;
    width: 100%;
  }

  .publication-entry {
    align-items: start;
    display: grid;
    gap: 1.5rem;
    grid-template-columns: minmax(180px, 24%) minmax(0, 1fr);
    width: 100%;
  }

  .publication-thumbnail img {
    aspect-ratio: 4 / 3;
    border-radius: 0.375rem;
    display: block;
    object-fit: cover;
    width: 100%;
  }

  .publication-title {
    font-weight: 700;
    line-height: 1.35;
  }

  .publication-authors,
  .publication-venue,
  .publication-links {
    margin-top: 0.45rem;
  }

  .publication-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }

  @media (max-width: 575px) {
    .about-hero {
      grid-template-columns: 1fr;
    }

    .publication-entry {
      grid-template-columns: 1fr;
    }

    .publication-thumbnail {
      max-width: 20rem;
      width: 100%;
    }
  }
</style>

<h2 class="publication-heading">Publications</h2>

{% include selected_papers.liquid %}
