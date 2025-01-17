#### Table of Contents
- [What can We do?](#what-can-we-do)
- [Weap: an Alternative to WHMCS](#Weap-an-alternative-to-whmcs)
- [A Little Background About Me](#a-little-background-about-me)
- [Tell me more](#tell-me-more)
- [Notes](#notes)


# What can We do?

If you made it this far in the article, I definitely got your attention. You may ask what's my solution to this decaying software and its business model that sees clients as cows to milk. I am more than glad to respond.

WebPros owns WHMCS and among other things also Plesk and cPanel. More than once they proved they can acquire anything that is worth their money. It doesn't matter what the CEO of this or that panel promise you today. In this industry money can easily buy everything.

Moreover I don't see how the provider that keeps migrating from one panel to another of inferior value on every price hike can support the growth of his/her business. How can you do that by constantly downgrading your technology level? And I am not even mentioning the costs for migrations.

In my opinion the only true solution is relying on a software that is free & open source. A software of this kind can't be acquired and unlike other panels it can keep basing development on the needs of end-users (providers).

The bad news is that this softare doesn't exists yet that's where I come into play.

I spent my whole career working for providers and I've been a provider myself. I coded very complex modules for WHMCS and have the required skills to start this project. The name of the software will be Weap.

# Weap: an Alternative to WHMCS

Here is Weap in a nutshell in comparison with WHMCS.

|  | Weap | WHMCS |
| ------------- | ------------- | ------------- |
| Source code | :hatching_chick: Open | :guardsman: Closed |
| License | :+1: Free | :punch: Commercial |
| Focus | :blush: Providers | :smiling_imp: Definitely not providers |
| Revenue model | :heart: Sponsors | :cow2: Milking |

# A Little Background About Me

I starterd using WHMCS in 2007 to run my hosting company. I quickly realized the importance of automation envisioning how it would increase my productivity, boosting service quality and making my life easier. It was love at the first sight.

I spent the next 6 years coding like crazy on scripts that allowed me to run my business on autopilot. Everything was working automagically. More than once I managed to anticipate trends and technologies directly in my WHMCS. Here are some examples:

* Bill clients for the actual usage of server resources on a hourly basis before things like OnApp were invented
* Install any CMS in one click from client area a decade before Plesk and cPanel incorporated this feature
* Web panels to manage Teamspeak, Ventrilo and hundreds of game servers with dynamic batch scripts

Quick forward to 2014, I have drawn the attention of some big names (and also massive ddos attacks) so I decided to sell my company and move to software development. That's when I created [katamaze.com](https://katamaze.com) and released several modules for WHMCS based on my deep knowledge of this system and scripts I used to run my previous business.

Over the years I've worked for or have helped to build hundreds if not thousands of providers. I focused on completing the lacks of WHMCS (eg. billing, affiliates, CMS, SEO) and fixing its bugs. In retrospect, I wish I had actually worked on my own system instead of wasting my time with the obtusity of WHMCS team.

If you think that it is impossible for me to create Weap, please understand that over the years I managed to deliver more useful and tested features in my modules working alone than the entire staff of WHMCS combined. Let me give you an idea of what I'm talking about:

* [Turned WHMCS into a CMS](https://katamaze.com/whmcs/mercury/specifications) with blog, news, docs, feature requests, comments, bug reporting
* [SEO for WHMCS](https://katamaze.com/blog/45/whmcs-seo-increase-traffic) including SEO URLs, sitemap, GeoIP, OG Tags...
* Track sales with [Facebook Pixel](https://katamaze.com/docs/billing-extension/43/whmcs-facebook-pixel-tracking) and [LinkedIn Insight Tag](https://katamaze.com/docs/billing-extension/44/whmcs-linkedin-insight-tag-tracking)
* Reduce invoices by 80% and transactions fees by 18% with [monthly invoicing](https://katamaze.com/docs/billing-extension/4/whmcs-monthly-invoice)
* Provide support based on [Service Level Agreement](https://katamaze.com/docs/mercury/50/service-level-agreement)
* [Cash flow](https://katamaze.com/docs/billing-extension/51/whmcs-cash-flow) for tracking inflow and outflow of money
* [Customer Retention and Churn Rate](https://katamaze.com/docs/billing-extension/56/whmcs-customer-retention)
* [Advanced Invoice Data Snapshot](https://katamaze.com/docs/billing-extension/57/whmcs-editing-invoice-snapshot) that includes currency rates
* Perfect integration with [VIES](https://katamaze.com/docs/billing-extension/8/whmcs-vies), [Australian GST](https://katamaze.com/docs/billing-extension/46/australian-taxation-system), [Tax Stamp](https://katamaze.com/docs/billing-extension/32/tax-stamp-on-invoices)
* Issue [Credit notes](https://katamaze.com/docs/billing-extension/33/whmcs-issuing-credit-note)
* Stop issuing unnecessary invoices thanks to [invoice suppression](https://katamaze.com/docs/billing-extension/54/whmcs-invoice-suppression)
* [Automatic Batch Invoice Export](https://katamaze.com/docs/billing-extension/47/whmcs-automatic-batch-invoice-pdf-export). PDF files are sent via FTP and/or and email as attachments
* [Affiliation Network](https://katamaze.com/whmcs/commission-manager/specifications) with multiple [Attribution Models](https://katamaze.com/docs/commission-manager/40/whmcs-affiliates-attribution-model)
* [SorTable](https://katamaze.com/docs/general/3/whmcs-advanced-filtering), [HereLang](https://katamaze.com/docs/general/2/whmcs-translation-interface), [MagicInput](https://katamaze.com/docs/general/1/whmcs-improved-inputs)

The list goes on but I think you've got the idea. This is just a partial list of things I made during the last 2 years of work for WHMCS. I even maintain documentation in two languages this is [bigger](https://katamaze.com/statistics) than WHMCS one.

Sometimes I wonder what WHMCS would have done in my place when I added [electronic invoicing](https://katamaze.it/docs/billing-extension/34/fatturazione-elettronica-whmcs-trasmissione-xml-sdi-ade) to their software. I know this article is written in italian but it still gives an idea the its complexity. I completed such a huge project in about 3 months. On the other hand WHMCS with God knows how many employees is still trying to fix GDPR they broke in v8 (November 2020).

It is no secret that the average release of WHMCS contains (not counting bugs) microscopic features that no one asked for that I wouldn't even put in a changelog. For instance few years ago they delivered calendar picker as the main feature of a major release. It's a free jQuery library that any decent developer can implement it in a couple of hours.

They are slow and their commitment is non-impactful. We have bugs from years that would take minutes to fix. Similarly we are waiting for missing features that any skilled developer could complete in a couple of days. I find incredible that a company of the size of WHMCS can't match the features delivered by the now-small group of third-party developers and designers.

Today my commitment to WHMCS is limited to maintaining my modules and support a small group of selected providers. I replaced WHMCS with something that is more rewarding and satisfying. My main focus now is working on a software that manages marketplaces, logistic, warehouses, data mining etc. that is actively used by several big companies.

It's a system that is way more complex and sensitive than WHMCS. A problem could result in the loss of significant amounts of money in missing sales. In comparison registering domains, start/stop servers and invoice customers feels like petting a cat. That being said, I am pretty confident with Leap.

# Tell me more

At this stage I prefer to lay the foundation of Leap only counting on a small group of people and providers that I personally know. I don't want to involve too many people otherwise Leap will quickly turn into a bland and unachievable wish list and will never be released.

Initial funding is not a problem. I can count on a partnership 🙏, PNRR and some extra cash coming from crypto (ATOM 😜).

When we go live, Leap will sustain itself with Github sponsors and donations. I will not enable them till the software reaches an acceptable level. The reason for that is simple. I don't like asking money only based on my good intentions that still need to be proved.

Don't ask for ETA. Leap will take years to complete. Also do not expect frequent updates on this page.

If you want to help, watch and star this project.

# Notes

The content below is tentative. They are mostly internal notes. What you see may not reflect what eventually is included in Leap. Manage your expectations accordingly.

### How to read tables

|  | Icon | Description |
| ------------- | ------------- | ------------- |
| Importance | ⭐<br>⭐⭐<br>⭐⭐⭐ | Low<br>Medium<br>High |
| Difficulty | 💣<br>💣💣<br>💣💣💣 | Low<br>Medium<br>High |
| Time | ⏰<br>⏰⏰<br>⏰⏰⏰ | Low<br>Medium<br>High |
| Status | 🟢<br>🟠<br>🔵<br>🔴<br>⚪ | Completed<br>In progress<br>Stalled<br>Dropped<br>New |

## CMS

- Facilitator: [Mercury](https://katamaze.com/whmcs/mercury/specifications).
- ETA (very tentative): 50 FTE

|  | Importance | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| News | ⭐⭐⭐ | 💣💣 | ⏰⏰  | Replica  | ⚪ |
| Blog | ⭐⭐⭐ | 💣💣 | ⏰⏰  | Replica | ⚪ |
| Docs | ⭐⭐ | 💣💣 | ⏰⏰  | Single page API-style | ⚪ |
| Feature Requests | ⭐ | 💣💣💣 | ⏰⏰⏰  | Bad idea | 🔵 |
| FAQ | ⭐ | 💣 | ⏰  |   | ⚪ |
| Bug Reporting | ⭐ | 💣💣 | ⏰  |   | ⚪ |
| Comments | ⭐ | 💣💣 | ⏰  | reCAPTCHA but they can still spam | ⚪ |
| Downloads | ⭐ | 💣 | ⏰⏰  |   | ⚪ |
| Widgets | ⭐⭐ | 💣 | ⏰⏰  |   | ⚪ |
| Page builder | ⭐ | 💣💣 | ⏰⏰⏰  |   | ⚪ |
| Service status | ⭐ | 💣💣 | ⏰⏰  | Like Coinbase Pro Trading (footer) | ⚪ |

## SEO

- Facilitator: [Mercury](https://katamaze.com/whmcs/mercury/specifications).
- ETA (very tentative): 20 FTE

|  | Importance | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Meta tags | ⭐⭐⭐ | 💣 | ⏰  |   | ⚪ |
| JSON-LD | ⭐ | 💣 | ⏰  |   | ⚪ |
| Canonical URL | ⭐⭐ | 💣 | ⏰  |   | ⚪ |
| Sitemap generator | ⭐ | 💣💣 | ⏰  | Language/Country [XML nodes](https://katamaze.com/docs/mercury/31/whmcs-sitemap-generator#XML-Structure) | ⚪ |
| Multi-language stuff | ⭐⭐⭐ | 💣💣💣 | ⏰⏰⏰  | Fallback for missing translations | ⚪ |
| SEO URL | ⭐⭐⭐ | 💣💣💣 | ⏰⏰⏰  |   | ⚪ |
| Open Graph Protocol | ⭐⭐ | 💣💣 | ⏰⏰  |   | ⚪ |
| HTML Semantic Elements | ⭐ | 💣💣 | ⏰⏰⏰  |   | ⚪ |
| Prevent SEO-bs (keyword stuffing, length etc.) | ⭐⭐ | 💣💣 | ⏰⏰⏰  |   | ⚪ |
| SERP preview | ⭐⭐⭐ | 💣 | ⏰  | [Moz-like](https://moz.com/learn/seo/title-tag) | ⚪ |
| Blackhat SEO protection | ⭐⭐ | 💣💣 | ⏰  |   | ⚪ |
| Disavow tool | ⭐ | 💣 | ⏰  |   | ⚪ |
| Basic statistics (hits) | ⭐ | 💣💣💣 | ⏰⏰⏰  | Graphs | ⚪ |

## Billing

- Facilitator: [Billing Extension](https://katamaze.com/whmcs/billing-extension/specifications).
- ETA (very tentative): 80 FTE

|  | Importance | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Basic engine | ⭐⭐⭐ | 💣💣💣 | ⏰⏰⏰  |   | ⚪ |
| EU | ⭐⭐ | 💣💣 | ⏰  |   | ⚪ |
| UK | ⭐ | 💣 | ⏰  |   | ⚪ |
| AU | ⭐ | 💣 | ⏰  |   | ⚪ |
| DE | ⭐ | 💣 | ⏰  |   | ⚪ |
| IT | ⭐⭐⭐ | 💣💣💣 | ⏰⏰  |   | ⚪ |
| General-purpose e-invoicing | ⭐⭐⭐ | 💣 | ⏰ |   | ⚪ |
| Italian electronic invoicing | ⭐⭐⭐ | 💣 | ⏰⏰⏰  | Aruba. End of the story | ⚪ |
| User-based billing cycles | ⭐⭐⭐ | 💣💣 | ⏰⏰⏰  |   | ⚪ |
| User-based billing modes | ⭐⭐⭐ | 💣💣 | ⏰⏰⏰  |   | ⚪ |
| Credit notes | ⭐⭐⭐ | 💣💣 | ⏰  |   | ⚪ |
| Overpayments | ⭐⭐⭐ | 💣 | ⏰  |   | ⚪ |
| Credit balance | ⭐⭐⭐ | 💣💣 | ⏰⏰  |   | ⚪ |
| Cashflow | ⭐⭐⭐ | 💣💣 | ⏰⏰⏰  |   | ⚪ |

## Support tickets

- Have to be created from scratch.
- ETA (very tentative): 40 FTE

|  | Importance | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Standard suite | ⭐⭐⭐ | 💣 | ⏰⏰⏰  |   | ⚪ |
| Service level agreement | ⭐⭐ | 💣💣 | ⏰⏰  | Working hours, holidays etc. | ⚪ |
| Emergency | ⭐ | 💣 | ⏰  |   | ⚪ |
| Premium | ⭐⭐ | 💣 | ⏰  | Paid support tickets | ⚪ |

## Multi-domain

- Facilitator: [Mercury](https://katamaze.com/whmcs/mercury/specifications), [Payments Bundle](https://katamaze.com/whmcs/payments-bundle).
- ETA (very tentative): 60 FTE

|  | Importance | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Whitelabel support with master (own company) and child (resellers and wannabes) brands | ⭐⭐⭐ | 💣💣 | ⏰⏰⏰  | Template, logo, names, emails | ⚪ |
| Brand-based pricing | ⭐⭐ | 💣💣 | ⏰⏰  |   | ⚪ |
| Multiple merchants (eg. paypal accounts) | ⭐ | 💣💣💣 | ⏰⏰⏰  |   | ⚪ |
| Country-based payment gateways | ⭐ | 💣 | ⏰  |   | ⚪ |
| Geolocation: Auto-redirect (watch out EU regulations!) | ⭐ | 💣💣 | ⏰  |   | ⚪ |
| Geolocation: Auto-complete fields | ⭐⭐ | 💣💣 | ⏰  |   | ⚪ |

## OAuth-based API

- Facilitator: Can re-use the structure from another project.
- ETA (very tentative): 30 FTE
 
|  | Importance | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Basic engine | ⭐⭐⭐ | 💣💣💣 | ⏰⏰⏰  |   | ⚪ |
| Scopes implementation | ⭐⭐⭐ | 💣💣💣 | ⏰⏰⏰  | Owner, resellers, end-users | ⚪ |
| Keyword-based requests | ⭐ | 💣 | ⏰  |   | ⚪ |
| lazy-API for idiots | ⭐ | 💣 | ⏰  | Nope | 🔴 |

## Action hooks

- ETA (very tentative): 15 FTE

|  | Importance | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Basic engine | ⭐⭐⭐ | 💣💣 | ⏰⏰  |   | ⚪ |
| Entrypoints, NVP etc. | ⭐⭐⭐ | 💣💣💣 | ⏰⏰⏰  |   | ⚪ |

## Affiliate Marketing

- Facilitator: [Commission Manager](https://katamaze.com/whmcs/commission-manager).
- ETA (very tentative): 60 FTE

|  | Importance | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Basic engine | ⭐⭐⭐ | 💣💣💣 | ⏰⏰⏰  |   | ⚪ |
| Last-click attribution | ⭐⭐ | 💣 | ⏰  |   | ⚪ |
| Interactive attribution | ⭐ | 💣 | ⏰  |   | ⚪ |
| Manual attribution | ⭐⭐⭐ | 💣 | ⏰  |   | ⚪ |
| Prevent cross-affiliation & exploits | ⭐⭐⭐ | 💣💣 | ⏰  |   | ⚪ |
| Unlockable rewards | ⭐⭐ | 💣💣💣 | ⏰⏰⏰  |   | ⚪ |

## Miscellaneous

|  | Priority | Difficulty | Time | Thoughts | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Migration tool from WHMCS | ⭐⭐⭐ | 💣 | ⏰⏰⏰  |  | ⚪ |
| Snapshot order details | ⭐⭐⭐ | 💣 | ⏰⏰  |   | ⚪ |
| Facebook Pixel | ⭐⭐⭐ | 💣💣 | ⏰⏰  |   | ⚪ |
| LinkedIn Insight Tag | ⭐⭐ | 💣 | ⏰  |   | ⚪ |
| Google Ad | ⭐⭐ | 💣💣💣💣 | ⏰⏰  |   | ⚪ |
| Google AdSense | ⭐⭐ | 💣 | ⏰  |   | ⚪ |
| Selling physical products | ⭐⭐ | 💣💣💣💣 | ⏰⏰⏰  |   | ⚪ |
| Selling on Amazon, eBay, Zalando etc. | ⭐⭐ | 💣 | ⏰⏰⏰  |   | ⚪ |
| End-users can sell on Marketplaces | ⭐⭐ | 💣💣💣 | ⏰⏰⏰  |   | ⚪ |
| Admin roles | ⭐⭐⭐ | 💣💣💣 | ⏰⏰  |   | ⚪ |
| Logging | ⭐⭐⭐ | 💣💣💣 | ⏰⏰  |   | ⚪ |
| Lock Screen | ⭐ | 💣💣 | ⏰⏰  | For inactivity and via shortcut keys | ⚪ |
| To-do List | ⭐ | 💣💣 | ⏰⏰  | With reminders and snooze | ⚪ |
| Shout function | ⭐ | 💣💣 | ⏰⏰  | Broadcasting any message to everyone matching filters | ⚪ |
| Google Calendar | ⭐ | 💣💣💣 | ⏰⏰⏰  |  | ⚪ |
| Feeds | ⭐ | 💣 | ⏰⏰  | For admins, childs and end-users | ⚪ |
| File Manager | ⭐ | 💣 | ⏰⏰  | Internal use (eg. CSV transmissions) | ⚪ |
| Chat | ⭐ | 💣💣 | ⏰⏰⏰  | Boring and long | ⚪ |
| Service status | ⭐ | 💣💣 | ⏰⏰⏰  | Like "Partially degraded" feature of Coinbase Pro | ⚪ |
| Organization chart | ⭐ | 💣 | ⏰⏰  |  | ⚪ |
| Hover Img | ⭐ | 💣 | ⏰  | Zwift | ⚪ |

# Integrations

Avoid "exotic" solutions for now.

## Domains

|  | Priority | Hate-o-Meter | Notes | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Internetbs | 1️⃣ | 😊 |   | ⚪ |
| eNom | 4️⃣ | 😡 |   | ⚪ |
| ResellerClub | 3️⃣ | 😕 | It's LogicBoxes. Integrate one to integrate many | ⚪ |
| Hexonet | 2️⃣ | 😊 |   | ⚪ |

## Hosting

|  | Priority | Hate-o-Meter | Notes | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Plesk | 1️⃣ | 😡 | Most used | ⚪ |
| cPanel | 2️⃣ | 😡 |   | ⚪ |
| DirectAdmin | 3️⃣ | 😊 |   | ⚪ |

## Payment Gateways

|  | Priority | Hate-o-Meter | Notes | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| PayPal | 1️⃣ | 😡 |   | ⚪ |
| Stripe | 2️⃣ | 😕 |   | ⚪ |
| Other | 3️⃣ | 😊 |   | ⚪ |

# Framework

|  | Approved | Notes | Status |
| ------------- | ------------- | ------------- | ------------- |
| PHP OOP | ✔️ | >=7.2 | 🟠 |
| [PSR-1](https://www.php-fig.org/psr/psr-1/) | ✔️ | Coding standards | 🟢 |
| [PSR-4](https://www.php-fig.org/psr/psr-4/) | ✔️ | Autoloader | 🟢 |
| [PSR-11](https://www.php-fig.org/psr/psr-11/) | ❔ | DI-Container | ⚪ |
| Composer | ✔️ |   | 🟢 |
| Dependency Injection | ✔️ | Need multiple containers | 🟢 |
| Smarty ~~or Twig~~ | ❔ | VUE? Node.js overkill? | 🟠 |
| jQuery | ✔️ |   | ⚪ |
| Bootstrap | ✔️ |   | 🟠 |
| ionCube | 🚫 |   | ⚪ |
| MySQL | ✔️ |   | 🟠 |
| MSSQL | ❔ | `LIMIT` `OFFSET` `TOP` | 🔵 |
| Strict Mode | ✔️ | Avoidable? Yes but come on... | 🟠 |
| No js? GTFO | ✔️ | R301 | ⚪ |
| Laravel | ❔ | Raw PDO? v8? | ⚪ |
| FontAwesome | ✔️ |   | 🟠 |
| Sprite CSS | ✔️ |   | ⚪ |
| User authentication | ❔ | OAuth, ~~bcrypt (custom)~~ or framework | ⚪ |
| TCPDF | 🚫 | Find alternative. Dompdf or mPDF | ⚪ |
| [Highcharts](https://www.highcharts.com/demo) | ❔ | 449.55 € per developer | ⚪ |
| [Chart.js](https://www.chartjs.org/) | ❔ | Easy, free | ⚪ |
| [DataTables](https://datatables.net/) | ❔ | Must use Yajra  | 🔴 |
| [SorTables](https://katamaze.com/docs/general/3/whmcs-advanced-filtering) | ✔️ | Refactored in line with [Material Design](https://material.io/components/data-tables) by Google | 🟠 |
| Multi-stream support for browsers | ✔️ | Parallel downloads | ⚪ |
| [MagicInput](https://katamaze.com/docs/general/1/whmcs-improved-inputs) | ✔️ |   | ⚪ |
| [HereLang](https://katamaze.com/docs/general/2/whmcs-translation-interface) | ✔️ |   | ⚪ |
| Toolbar | ✔️ | Pre-toolbar and toolbar with Type to Search | ⚪ |
| Sidebar | ✔️ | With Type to Search | ⚪ |
| Footer | ✔️ | With CB service status | ⚪ |
| Modal Generator | ✔️ |   | ⚪ |
| Installer | ✔️ | Zip, upload, enjoy | ⚪ |
| Automatic Updates | ❔ | So and so | ⚪ |
| Versioning | ✔️ | PHP [version_compare](https://www.php.net/manual/en/function.version-compare.php) compliant x.x.x | 🟢 |
| Publicly advertised cycles | ✔️ | Alpha, Beta, RC | ⚪ |
| Logs | ⭐ | 💣 | ⏰⏰  | Live like Mano Mano and Amazon | ⚪ |

# Team

|  | Role | Effort | Notes | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| P1K | Backend | 6 hours | Overloaded | Active |
| P2K | Frontend | 6 hours | RA | Active |
| P3K | Frontend | 8 hours | RA | Active |
| PXG | Dev team | Lot of hours |   | Doesn't depend on us |
| V1W | Backend | Don't know |   | Nah |
| V2Z | Frontend | Don't know |   | Nah |
| V3M | Dev team | Lot of hours | Surely not willing to work on `app` but `modules` | Ask when there's enough code to show |
| V4S | Frontend | Don't know |   | Nah |
| C13 | Tech, employees | Unlimited |   | Active |
| P01 | Partner |  |  | Active |
| P02 | Partner |  |  | Active |
| C2F | Beta |   | Provider | Active |
| C3P | Beta |   | Provider | Active |
| C4R | Beta |   | Provider | Dropped |
| C5S | Beta |   | Provider | Active |
| C6Q | Beta |   | Provider | Abandoned |
| C7V | Beta |   | Provider | Active |

# Funding

Software is free but needs funds.

|  | Status | Notes | Status |
| ------------- | ------------- | ------------- | ------------- |
| P1K | ✔️ | 1 | Funding |
| C13 | ✔️ | 3 | Funding |
| P01 | ✔️ | 2 | Funding |
| P02 | ✔️ | 5 | Funding |
| VX |  ❔ |   |   |
| C1F | ✔️ |   | Ready |
| C7V | ✔️ |   | Ready |
| Github Sponsor | ✔️ | 7$ and 14$ a month (free choice) | Ready |
| % on revenue | 🚫 | Absolutely not |   |
| Donations | ✔️ |   |   |
| Partnership | ✔️ | Can only work with some registrars |   |
| Data Farm | ❔ | Data mining and tracking |   |
| Ads | ✔️ | On our website (not in the software) | Ready |
| Freemium | 🚫 |   |   |
| Donation/Tip Goal | ❔ | "Goal: Feature X - Still 1.000 $ to go"  |   |
| SLA | ❔ | I want to sleep at night |   |

Also have the following:

* vBulletin license if we need a forum
* 4x WHMCS licenses to start working on a migration script
* ionCube Pro & Special Edition GUI (2 seats) but I guess we don't need it 😆
* [FontAwesome Pro Standard](https://fontawesome.com/plans) license (5 seats)
* All servers we need
* Office
  * Italy PE 4 seats but will be closed before summer 2022 (P1K)
  * Italy CH old headquarter 4-6 seats but noisy (C13)
  * Italy CH new headquarter all seats you want (C13)
  * Italy MI all seats you want (P01, P02)
  * Spain & Australia but why? Pointless
* Lifetime Niel for SEO
* 2x approved Google Ads
* Approved Amazon SP-API & MWS developer accounts
* Tens of various developer accounts
* Lifetime [TCAdmin](https://www.tcadmin.com/pricing/) 1x Pro Master, 3x Pro Remote Server in case we need to integrate game service providers

# Localisation

|  | Team | Notes |
| ------------- | ------------- | ------------- |
| English | P1K, P2K, P3K |   |
| Italian | P1K, P2K, P3K |   |
| Spanish | C13-ES |   |

# Questions

### How to prove we won't roll over for clowns (cough WebPros) some day in the future

* Crypto-something with locked funds in tokens/wallets ❔
* Old school notarial deed ❔
* Reputation ❔
* We can't ❔
* Stop selling WHMCS modules ✔️
* Should we?

### Customer support

* Github ✔️
* Stack Overflow ❔
* Forum ✔️
* Ticket ❔
* Reddit

### Licensing

* MIT 🚫
* GPL v3 ✔️ copyleft
* BSD ✔️
* Custom ❔

Basic idea. Free for personal and commercial use but "All rights reserved". Derived work? The whole work must be free and open source.

# Conventions

* Avoid nested `if`, `return` instead
* Stick to `AND`, `OR` instead of `&&`, `||` logic operators. Many devs don't know anything about precedence
* Classes `StudlyCaps`. Methods & variables `camelCase`
* Same spacing for js and PHP
* Avoid `;` for last CSS rule
* Dataset `array` not `StdClass`
* Logging must be `::`

# P1K

* Downlolad application/octect
* User roles: pages & actions... sigh
* Multiple language pickers. Magento in-line translation
* Single-cron setup
* What if we handle things like multi-tenancy and overrides as I did with shipping/logistics overrides?
* I can reuse my existing oAuth API
* Laravel (and/or Node) is cool but our typical customer is going to hate it. They're not user-friendly

# P2K

* Modal generator/handler
* [This theme](https://coderthemes.com/hyper/saas/dashboard-projects.html) is a good source of ideas
* We should be using ajax + json + react-like page load that works offline (change URI via js)
* Depended form fields
* Sidebar and action menu should be populated by json object/array to avoid nested ifs in Smarty
