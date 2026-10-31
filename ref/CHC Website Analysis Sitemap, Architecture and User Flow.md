# CHC Website Analysis: Sitemap, Architecture and User Flow

Oct 28, 2026 · @GRACE

chc.org.sg organizes its site by what a visitor wants to do, not by department, and its Plan A Visit page is the strongest flow to borrow. This analysis covers the [homepage](https://www.chc.org.sg/) navigation tree and four pages opened on 28 Oct 2026: [Plan A Visit](https://www.chc.org.sg/be-connected/plan-a-visit), [Join a Cell Group](https://www.chc.org.sg/be-connected/join-our-family/join-a-group), [Questions About Life](https://www.chc.org.sg/be-connected/questions-about-life) and [Prayer Request](https://www.chc.org.sg/get-in-touch/prayer-request), plus the [Serve in a Ministry](https://www.chc.org.sg/be-connected/get-involved/ministry) page. The Give page sits on a separate subdomain and was not reviewed.

## 1. Sitemap

The site has 7 top-level items and about 3 levels of depth.

| Top-level | Second level | Third level |
| --- | --- | --- |
| About Us | The City Harvest Story, Mission & Beliefs, Service Timings, Latest Announcements, Governance | Our Founders (2 pages); Service Information (English, Chinese, Kids, Youth, JAMs, Dialect, Indonesian); Our Policies (Whistle-Blowing, PDPA) |
| Be Connected | Questions About Life, Plan A Visit, Upcoming Events, Bible Study Classes, CityFamilies, Young Adults, EMERGE Youth | Join Our Family (Become a Member, Join a Cell Group, Now Hiring); Get Involved (Mission Trip, Serve in a Ministry, Church Without Walls) |
| Media | The CHC App, CityWorship, City News, CityRadio, Media Downloads, The Harvest Festival | Podcast (Kong Hee Podcast, Weekend Sermons) |
| CHC In Culture | CHCSA, School of Theology, Harvest Network, Bookstore, Marketplace | None |
| Get In Touch | Accept Jesus, Contact Us, Prayer Request, Share a Testimony, Useful Downloads | Care & Help (Getting Married, Funeral Care, Church Without Walls, Financial Assistance) |
| Give | External link (separate subdomain) | None |
| 简体 | Language switch to a Chinese version | None |

The footer repeats a Quick Links set: Special Notices, Service Timings, Service Info, Events, Announcements, Contact and Bookstore. It also carries social links, the app download prompt, and Privacy and Terms.

## 2. Architecture

CHC groups content by visitor intent, but pushes key actions (giving, forms, media) onto separate subdomains.

| Aspect | What CHC does | Takeaway for you |
| --- | --- | --- |
| IA model | Organized by visitor intent ("Be Connected", "Get In Touch") rather than by org chart | Name sections by what the visitor wants to do |
| Homepage | 8-slide hero carousel mixing weekend services, social services, financial assistance, missions and baby dedication; a countdown to the next live webcast sits beside it | Keep one primary message; put the next service or livestream at the top |
| Navigation | Mega-dropdown menu, 3 levels deep; parent items are not clickable (`#` links) | Fine on desktop, harder on mobile |
| Multilingual | Separate Simplified Chinese version at `/chinese`, not an in-page toggle | Relevant if you serve both Traditional Chinese and English |
| Subsites | Giving, forms, the app, School of Theology, news and the Harvest Festival live on other subdomains or domains | Cheaper to run, but brand and navigation break when users cross over |
| Forms | Native forms with a PDPA consent block (Cell Group, Prayer Request) | The consent wording is worth copying |
| Media hub | Sermons and podcasts are pushed to the CHC App, YouTube and Facebook | The site mostly redirects instead of hosting the content |

## 3. User flows

Every flow follows one pattern: Learn, Visit, Connect (group), Serve, with Prayer and Give as always-available side entries.

| Visitor type | Flow | Observations |
| --- | --- | --- |
| First-time visitor | Homepage → Be Connected → Plan A Visit → service time and location | The best-built flow: service times, venues per service, a greeter tip and contact info. Times are shown for the current weekend. |
| Seeker / new believer | Get In Touch → Accept Jesus, or Be Connected → Questions About Life | A long evangelistic page with a prayer and a "connect with us" form at the end |
| Newcomer wanting community | Be Connected → Join a Cell Group → form | The form asks for service, age group, demographic, location and language so groups can be matched |
| Member serving | Be Connected → Get Involved → Serve in a Ministry | A list of about 45 ministries with a sign-up link |
| Needs prayer or help | Get In Touch → Prayer Request, or Care & Help (marriage, funeral, financial assistance) | Care services are grouped in one place |
| Remote attendee | Homepage countdown → Watch Online Now, or View Past Sermons | Both lead out to the CHC App |
| Giver | Header → Give | One click, but it leaves the main site |

## 4. Strengths and gaps

CHC is strong on the first-visit path and weak where users are sent off-site.

### Worth borrowing

- Plan A Visit gives all the practical details on one page.
- Navigation is by intent, not by department.
- The next-service countdown and watch-online button are prominent.
- Forms are short and carry consent text.
- Care & Help is grouped in one place, which is good pastoral design.

### Weaknesses to avoid

- Forms and Give leave the main site, which breaks the experience.
- The hero carousel has 8 slides, which dilutes the message.
- Church Without Walls appears under two menus.
- Parent menu items are not clickable, so there are no overview pages.
- The Questions About Life page is a very long block of text.
- The country dropdown in the group form is long and mostly unnecessary.

## 5. Suggested structure for your church

A smaller church can flatten CHC's structure to 6 top-level items and 2 levels.

| Item | Contents |
| --- | --- |
| New Here | Plan a Visit, What to expect, Our beliefs, FAQ |
| Worship | Service times, Livestream, Past sermons, Events calendar |
| Connect | Cell groups, Ministries and serving, Classes |
| About | Story, Leadership, Mission, Announcements |
| Care & Prayer | Prayer request, Pastoral care, Testimonies, Contact |
| Give | Embedded inside the site |

Build these first: a visit page with times and a map, a group sign-up form, a prayer request form and a giving page. A homepage with a single hero and the next service time covers the rest.

## Sources

- [CHC homepage and navigation](https://www.chc.org.sg/)
- [Plan A Visit](https://www.chc.org.sg/be-connected/plan-a-visit)
- [Join a Cell Group](https://www.chc.org.sg/be-connected/join-our-family/join-a-group)
- [Questions About Life](https://www.chc.org.sg/be-connected/questions-about-life)
- [Prayer Request](https://www.chc.org.sg/get-in-touch/prayer-request)
- [Serve in a Ministry](https://www.chc.org.sg/be-connected/get-involved/ministry)
