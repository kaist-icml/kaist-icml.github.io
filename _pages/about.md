---
layout: about
title: About
permalink: /
subtitle:

profile:
  align:
  image:
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Welcome to the **KAIST @ ICML 2026**, a satellite event to meet KAIST faculty and students.

* 📅 **Date:** July 6 (Expo & Tutorial Day) 
* 📍 **Location:** [Within walking distance of COEX (the conference venue)](/venue/)
* 💬 **Program:** Half-day program with social lunch/networking, invited talks, panel discussions, student posters
* 👥 **Participants:** Invited non-KAIST researchers & pre-registered KAIST faculty and students

---

## **<span style="color: var(--global-theme-color);">Program</span>**

#### **Social lunch/networking**

TBA

#### **Invited Talks**

TBA

#### **Panel Discussions**

TBA

#### **Student Poster**

TBA

---

## **<span style="color: var(--global-theme-color);">Participants</span>**

#### **Tentative**

Been Kim (Google), Dongoh Park (Google), Gautam Kamath (U Waterloo/NYU), Kilian Weinberger (Cornell), Mateusz Malinowski (Moonvalley), Niloofar Mireshghallah (CMU), Pang Wei Koh (U Washington), Sanmi Koyejo (Stanford), Sharon Li (U Wisconsin), Sungmin Cha (Meta), Tristan Naumann (Microsoft)

---

## **<span style="color: var(--global-theme-color);">Organizers</span>**

#### **Faculty**

<div class="organizers_horizontal-grid">
  {% for organizer in site.data.faculty_organizers %}
    {% include organizer_horizontal.liquid organizer=organizer %}
  {% endfor %}
</div>

#### **Students**

<div class="organizers_horizontal-grid">
  {% for organizer in site.data.student_organizers %}
    {% include organizer_horizontal.liquid organizer=organizer %}
  {% endfor %}
</div>

---

## **<span style="color: var(--global-theme-color);">Sponsors</span>**

<div class="row projects pt-1 pb-1">
      <div class="col-sm-4" style="display:flex; align-items:center;">
          <img class="col-sm" src="/assets/img/kaist.png"/>
      </div>
      <div class="col-sm-4" style="display:flex; align-items:center;">
          <img class="col-sm" src="/assets/img/elice.png"/>
      </div>
</div>

We sincerely thank **[KAIST](https://www.kaist.ac.kr/en/)** for financial support and **[Elice](https://elice.io/en)** for providing the venue.