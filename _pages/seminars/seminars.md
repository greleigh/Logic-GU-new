---
layout: seminars
permalink: /seminars/
title: Seminars
description: >
  Seminars, etc.
contact: graham # person in _profiles/

nav: true
nav_order: 2

show_categories:
  - seminars
  - nol
  - lindstrom-lectures
  - events

# debug: true

pagination:
  enabled: true
  collection: posts
  # permalink: /:num/
  per_page: 10
  sort_field: date
  sort_reverse: true
  trail:
    before: 1 # The number of links before the current page
    after: 3  # The number of links after the current page
---

{% include snippets/get_person_from_id.liquid 
  id = page.contact
%}

The Logic Group runs a bi-weekly _Research Seminar in Logic_, monthly _Nordic Online Logic Seminar_ and the annual _Lindström Lecture series_, as well as other events.

The research seminar in Logic meets on alternate Fridays at 10.15.
Unless otherwise stated, seminars are held at the department building (Humanisten). 
Details of online talks are distributed in the [GU Logic mailing list]({{ site.data.links['gu-mailing-list'].url }}). Alternatively, contact [{{ person.name }}]({{ person.homepage }}) directly.
