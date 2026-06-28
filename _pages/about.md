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
| 12:30–13:00 | Onsite registration                   |            |
| 13:00–13:20 | Opening remark & sponsor talk (Elice) |            |
| 13:30–14:20 | Panel discussion 1: Language model reliability & safety | Moderator: Prof. Se-Young Yun |
| 14:30–15:50 | Student posters & social networking   |            |
| 16:00–16:50 | Panel discussion 2: Vision, multimodal AI & agents | Moderator: Prof. Hyunwoo J Kim |
| 17:00–17:50 | Panel discussion 3: Career advice for junior researchers & students | Moderator: Prof. Hyunwoo Kim |
| 17:50–18:00 | Closing remark                        |            |
{: .table}
{: .table-light}
{: .table-striped}

---

## **<span style="color: var(--global-theme-color);">Confirmed Participants</span>**

**Adish Singla** (MPI-SWS),
**Amaya Gallagher-Syed** (Imperial College London)
**Ben Bogin** (Google),
**Dongkwan Kim** (Texas A&M),
**Doyup Lee** (DirectorLabs),
**Constantin Seibold** (University Clinic Heidelberg),
**Emtiyaz Khan** (RIKEN AIP / TU Darmstadt / Hessian.AI),
**Furong Huang** (UMD),
**Gautam Kamath** (U Waterloo / NYU),
**Haewon Jeong** (UCSB / Flatiron Institute),
**Hanshen Xiao** (Purdue/NVIDIA),
**Hsuan-Tien Lin** (NTU),
**Jaehong Yoon** (NTU Singapore),
**Kalika Bali** (Microsoft Research India),
**Kyunghyun Cho** (NYU),
**Niloofar Mireshghallah** (CMU),
**Sarah Wiegreffe** (UMD),
**Seonguk Seo** (Meta),
**Sharon Li** (U Wisconsin-Madison),
**Shayne Longpre** (MIT),
**Sungmin Cha** (Meta),
**Xiang Lorriane Li** (U Pittsburgh),
**Yoon Kim** (MIT),
**Young Jin Kim** (Microsoft AI),
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