---

layout: col-sidebar
title: OWASP Cork
site_side: true
tags: cork
level: 3
region: Europe
meetup-group: OWASP-Cork
country: Ireland
postal-code: 

---

<!-- rebuild -->
# OWASP Cork

Welcome to the Cork chapter landing page. 

The chapter board is:

* [Darren Fitzpatrick](mailto:darren.fitzpatrick@owasp.org)
* [Darragh Duffy](mailto:darragh.duffy@owasp.org)
* [John O'Riordan](mailto:john.oriordan@owasp.org)

Follow chapter news on [Twitter](https://twitter.com/owaspcork) | [Meetup.com](https://www.meetup.com/OWASP-Cork) | [Facebook](https://www.facebook.com/owaspcork) 

---

## Next Meeting

### Tuesday, 4th Febuary 2020

**Meetup Registration:**  Everyone is welcome to join us at our chapter meetings, [please RSVP via our Meetup Page](https://www.meetup.com/OWASP-Cork/events/268081403/)

**Location:** Dell Technologies, City Gate, Mahon, Cork.

**Time:** Doors Open at 6pm for registration, pizza, drinks and networking, the talks start at 6:30pm (we start on time).

**Talk:**
- Security at a Startup
  - Joe Lennon
  - CTO & Co-founder, Workvivo.
- Industrial Control System Simulation: How to build your own DIY ICS platform
  - Thomas Roccia
  - Security Researcher, McAfee Advanced Threat Research.

---

## Speaking at OWASP Cork Chapter Events

### Call For Speakers

Call For Speakers is always open, if you would like to present a talk on Application Security or Security in general we would be delighted to organise the event. Please review and agree with the [OWASP Speaker Agreement](Speaker_Agreement "wikilink") and send the proposed talk title, abstract and speaker bio to the Chapter Leaders via e-mail.

Check our Upcoming Meetup Events:
{% include chapter_events.html group=page.meetup-group %}

<script type='text/javascript'> $(function(){ $(".timeclass").hover(function() { utc_str = $(this).text(); ndx = utc_str.indexOf(':'); st_hour_str = utc_str.substring(0, ndx); st_min_str = utc_str.substring(ndx + 1, ndx + 3); utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0); start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName); ndx = utc_str.lastIndexOf(':'); end_hour_str = utc_str.substring(ndx - 2, ndx - 1); end_min_str = utc_str.substring(ndx + 1, ndx + 3); utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0); end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName); popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET); $(this).prop('title', popstr); }); }); </script>
