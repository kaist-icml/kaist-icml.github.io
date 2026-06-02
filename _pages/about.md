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

* 📅 **Date:** July 6 (Expo & Tutorial Day), Half-day event
* 📍 **Location:** [Within walking distance of COEX (the conference venue)](/venue/)
* 💬 **Program:** Half-day program with social networking, student posters, and panel discussions
* 👥 **Participants:** Invited non-KAIST researchers & pre-registered KAIST faculty and students

---

## **<span style="color: var(--global-theme-color);">Afternoon Program</span>**

| **Time**    | **Event**                             | **Notes**  |
|-------------|---------------------------------------|------------|
| 12:30–13:00 | Registration                          |            |
| 13:00–13:10 | Opening remark & sponsor talk         |            |
| 13:10–13:55 | Panel discussion 1                    | Topic: TBA |
| 14:10–15:00 | Student posters & social networking 1 |            |
| 15:10–16:00 | Student posters & social networking 2 |            |
| 16:15–17:00 | Panel discussion 2                    | Topic: TBA |
| 17:05–17:50 | Panel discussion 3                    | Topic: TBA |
| 17:50–18:00 | Closing remark                        |            |
{: .table}
{: .table-light}
{: .table-striped}

---

## **<span style="color: var(--global-theme-color);">Confirmed Participants</span>**

**Adish Singla** (MPI-SWS),
**Dongkwan Kim** (Texas A&M),
**Emtiyaz Khan** (RIKEN AIP / TU Darmstadt / Hessian.AI),
**Gautam Kamath** (U Waterloo / NYU),
**Hsuan-Tien Lin** (NTU),
**Kalika Bali** (Microsoft Research India),
**Niloofar Mireshghallah** (CMU),
**Sarah Wiegreffe** (UMD),
**Sharon Li** (U Wisconsin-Madison),
**Shayne Longpre** (MIT),
**Sungmin Cha** (Meta Superintelligence Labs),
**Xiang Lorriane Li** (U Pittsburgh),
**Yoon Kim** (MIT),
**Young Kyun Jang** (Google Deepmind),
**Yuntian Deng** (U Waterloo)

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