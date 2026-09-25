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

education:
  - institution: Carnegie Mellon University
    degrees:
      - name: Ph.D. in Robotics
        years: 2021–2027(expected)
        details:
          - "Advisors: Prof. Nancy Pollard, Prof. Jean Oh"
  - institution: University of Illinois Urbana-Champaign
    degrees:
      - name: M.S. in Mechanical Engineering
        years: 2019–2021
        details:
          - "Advisor: Prof. Joao Ramos"
          - 'Thesis: <a href="https://www.ideals.illinois.edu/items/121189">A whole-body human-machine interface for dynamic bilateral teleoperation of humanoid robots</a>'
      - name: B.S. in Mechanical Engineering, Minor in Electrical Engineering
        years: 2015–2019
        details:
          - "GPA: 3.92/4.00. Highest honors"

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
    /*
     * ADJUSTABLE VERTICAL SPACING:
     * Change this one value to control both the email-to-Education gap
     * and the Education/profile-row-to-Publications gap.
     */
    --about-section-vertical-gap: 1.0rem;
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
    margin-bottom: 0.65rem;
    margin-top: var(--about-section-vertical-gap);
  }

  .education-school + .education-school {
    margin-top: 1rem;
  }

  .education-institution {
    line-height: 1.3;
  }

  .education-degree {
    margin-top: 0.25rem;
  }

  .education-degree + .education-degree {
    margin-top: 0.6rem;
  }

  .education-degree-heading {
    align-items: baseline;
    display: grid;
    gap: 0.75rem;
    grid-template-columns: minmax(0, 1fr) auto;
  }

  .education-years {
    text-align: right;
    white-space: nowrap;
  }

  .education-details {
    margin-bottom: 0;
    margin-top: 0.2rem;
    padding-left: 1.25rem;
  }

  .education-details li {
    line-height: 1.35;
  }

  .about-hero .post-header,
  .about-hero .post-title {
    margin-top: 0;
  }

  .about-hero .post-header,
  .about-hero .desc {
    margin-bottom: 0;
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
    margin-top: var(--about-section-vertical-gap);
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
