---
layout: page
permalink: /teaching/
title: teaching
description: You can find below a list of courses I have taught or supported, along with selected syllabi and teaching materials. Please feel free to contact me for additional course materials.
nav: true
nav_order: 5
---
<img src="/assets/img/Sevgi_teaching.png"
     style="max-width: 360px; width: 100%; height: auto; border-radius: 8px; margin-bottom: 20px;">
<br>
Teaching has been an important part of my academic life. At Harvard, I received a teaching certificate through the Bok Center for Teaching and Learning after participating in seminars and workshops on pedagogy, course design, inclusive teaching, feedback, and student learning. I also worked as a Pedagogy Fellow, collaborating with peers and the Bok Center to support teaching development across the graduate-student community. My teaching has been recognized with Derek Bok teaching awards and student recognition for excellence in instruction.
<br>
<br>
{% include courses.liquid %}
<br>
<br>

<style>
.teaching-list {
  display: flex;
  flex-direction: column;
  gap: 0.85rem;
  margin-top: 1.5rem;
}
.teaching-item {
  border: 1px solid #eadfd8;
  border-left: 6px solid #8b5e4a;
  border-radius: 14px;
  padding: 1rem 1.15rem;
  background: #fff;
  box-shadow: 0 2px 8px rgba(80, 45, 25, 0.06);
}
.teaching-item.harvard {
  border-left-color: #7a1f2b;
}
.teaching-item.bogazici {
  border-left-color: #2f6f73;
}
.teaching-item.language-program {
  border-left-color: #8b6f2f;
}
.teaching-top {
  display: flex;
  justify-content: space-between;
  gap: 1rem;
  align-items: baseline;
  flex-wrap: wrap;
}
.teaching-course {
  font-size: 1.05rem;
  font-weight: 600;
  color: #3f2a23;
}
.teaching-term {
  font-size: 0.9rem;
  color: #7a6a61;
  white-space: nowrap;
}
.teaching-details {
  margin-top: 0.35rem;
  font-size: 0.92rem;
  color: #5f514b;
}
.teaching-tag {
  display: inline-block;
  font-size: 0.75rem;
  padding: 0.18rem 0.55rem;
  border-radius: 999px;
  background: #f1e5dd;
  color: #4a332b;
  margin: 0.45rem 0.2rem 0 0;
}
.teaching-item.harvard .teaching-tag {
  background: #f4e1e4;
  color: #6d1c27;
}
.teaching-item.bogazici .teaching-tag {
  background: #dff0ef;
  color: #235b5f;
}
.teaching-item.language-program .teaching-tag {
  background: #f4ecd6;
  color: #6f5720;
}
.teaching-award {
  display: inline-block;
  font-size: 0.75rem;
  padding: 0.18rem 0.55rem;
  border-radius: 999px;
  background: #fff0b8;
  color: #7a5a00;
  margin: 0.45rem 0.2rem 0 0;
}
.teaching-level {
  display: inline-block;
  font-size: 0.75rem;
  padding: 0.18rem 0.55rem;
  border-radius: 999px;
  margin: 0.45rem 0.2rem 0 0;
}
.teaching-level.undergrad {
  background: #e9f3df;
  color: #3d6429;
}
.teaching-level.grad {
  background: #e4ebff;
  color: #263f82;
}
/* Dark mode fixes */
html[data-theme="dark"] .teaching-item,
body[data-theme="dark"] .teaching-item,
[data-theme="dark"] .teaching-item {
  background: #1f1f1f;
  border-color: #3a3a3a;
  color: #f2f2f2;
  box-shadow: 0 2px 8px rgba(0,0,0,0.35);
}
html[data-theme="dark"] .teaching-course,
body[data-theme="dark"] .teaching-course,
[data-theme="dark"] .teaching-course {
  color: #f4f4f4;
}
html[data-theme="dark"] .teaching-term,
body[data-theme="dark"] .teaching-term,
[data-theme="dark"] .teaching-term,
html[data-theme="dark"] .teaching-details,
body[data-theme="dark"] .teaching-details,
[data-theme="dark"] .teaching-details {
  color: #cfcfcf;
}
html[data-theme="dark"] .teaching-tag,
body[data-theme="dark"] .teaching-tag,
[data-theme="dark"] .teaching-tag {
  background: #343434;
  color: #f0f0f0;
}
html[data-theme="dark"] .teaching-award,
body[data-theme="dark"] .teaching-award,
[data-theme="dark"] .teaching-award {
  background: #4a3b12;
  color: #ffe9a6;
}
html[data-theme="dark"] .teaching-level.undergrad,
body[data-theme="dark"] .teaching-level.undergrad,
[data-theme="dark"] .teaching-level.undergrad {
  background: #26351f;
  color: #c9efb2;
}
html[data-theme="dark"] .teaching-level.grad,
body[data-theme="dark"] .teaching-level.grad,
[data-theme="dark"] .teaching-level.grad {
  background: #1f2d4a;
  color: #c7d8ff;
}
html[data-theme="dark"] .teaching-item.harvard,
body[data-theme="dark"] .teaching-item.harvard,
[data-theme="dark"] .teaching-item.harvard {
  border-left-color: #d56a7b;
}
html[data-theme="dark"] .teaching-item.bogazici,
body[data-theme="dark"] .teaching-item.bogazici,
[data-theme="dark"] .teaching-item.bogazici {
  border-left-color: #62b7b0;
}
html[data-theme="dark"] .teaching-item.language-program,
body[data-theme="dark"] .teaching-item.language-program,
[data-theme="dark"] .teaching-item.language-program {
  border-left-color: #d6b65f;
}
</style>
