# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: the barbershop owner. They decide, pay, and are the one the page must convince. They evaluate on a phone, often between clients, frequently from a WhatsApp link.

Secondary, confirmed by the user as audiences this page speaks to:

- The barber who works in the shop. They do not buy, but they decide whether the system survives: a tool the team refuses to open is a tool the owner cancels.
- The end client of the barbershop. They receive the automatic confirmation and reminder.

Undecided, must not be claimed until confirmed: whether CS Barber exposes any client-facing surface (app, public booking page, client login). The product today documents "Agendamento online" as a growth module and automatic reminders to the client, nothing more. A page that routes an end client somewhere must have somewhere to send them.

## Product Purpose

Put a barbershop's whole operation — appointments, clients, team, cash and commission — in one system, assembled to match how that specific shop already works, instead of making the shop adapt to off-the-shelf software. Success is the owner starting the assisted 7-day trial and the shop still running on it after the trial.

## Positioning

Technology built in-house by Conecta Soluções, assembled per shop as modules, with the implementation done alongside the team and support that reaches the people who built the system. A reseller of off-the-shelf software cannot truthfully claim the "we build the missing function" part.

## Operating Context

- Evaluation happens on a phone far more than on a desktop, often from a WhatsApp link, in a noisy shop between appointments.
- The lead path ends in WhatsApp: the form assembles a ready message and the contact is answered Monday to Saturday, commercial hours, by the Conecta team.
- Migration from an existing system (or from paper and WhatsApp) is a real step: clients, services and history are brought across with help, and both systems can run in parallel during the trial.
- Sibling products from the same company: the institutional site (conectasolucoes.ia.br) and CS Bella for salons and aesthetics, currently marked as coming soon.

## Capabilities and Constraints

Confirmed functionality named on the page today: appointments by barber and by service with automatic confirmation and reminder; single client record with contact, history and preferences; per-barber profile, individual agenda and own access; daily summary, top services and total appointments. Growth modules activated when the shop wants them: online payment (Pix and card), loyalty programme, Google reviews, coupons and promotions, referral programme, multi-unit in one panel.

Commercial facts: 7-day trial on the real operation, with no feature limits stated; assisted implementation; support Monday to Saturday.

Technical constraints that future work must respect:

- One hand-written `index.html`, no build step. Published by `publicar.sh`, which strips comments from the published copy and uploads to S3 behind CloudFront. The repository keeps the readable source; the published file is the stripped one.
- Third-party runtime dependencies are vendored under `assets/vendor` and served from the same origin. Fonts are self-hosted under `assets/fonts`. The page makes zero third-party requests, and should keep doing so.
- The WhatsApp number is the Conecta commercial line, 5527999073651. It appears in several links and in the message the form assembles.
- The submit button ships `disabled` in the HTML and is enabled by script, so that without JavaScript the native submit cannot put name, e-mail and WhatsApp into a URL.

Undecided, must not be invented: price. No pricing is published today and the user has not set one for the page.

## Brand Commitments

- Name: CS Barber, a product of Conecta Soluções.
- The trial is 7 days. Not 15, not 30.
- Code ships without comments; the reasoning lives in the commit message.
- Both the institutional site and CS Barber already carry a built visual world (dark navy and gold, a pinned WebGL film). The user has asked to replace the film with a conventional page; identity assets, palette ownership and copy remain the company's.
- Standing preference, set by the user on 2026-10-02: this landing page follows the category convention rather than an invented visual world. The craft bar is Booksy Biz, AppBarber and Trinks — the page should sit alongside them without looking cheaper. Convention here is the commitment, executed at full fidelity, not a compromise to be decorated.

## Evidence on Hand

- Real product screenshots in `assets`: the panel on desktop (`painel-desktop`), the panel on a phone (`painel-mobile`), and a photograph of a barbershop (`cs_barber_hero`), each in WebP and JPEG at 1x and 2x.
- Seven real FAQ answers covering migration, time to go live, trial cost and commitment, multi-unit, mobile, whether the shop's own way of working fits, and support hours. These are mirrored into FAQPage structured data and the two copies must stay identical.
- No customer count, no performance metric, no testimonial, no case study, no press. The user confirmed there is no number to cite yet. Future work must not fabricate any of these, and must not borrow the institutional site's "15 barbearias" without the user saying it applies here.

## Product Principles

1. The owner is deciding on a phone, in a hurry. Anything that costs a second before the argument lands is a cost, not a flourish.
2. Say only what is true. With no metrics and no testimonials, the page earns trust through specificity about the operation, not through claims.
3. The shop adapts nothing. Every promise is a variation of "it is assembled to fit how you already work".
4. The trial is the only ask. One action, repeated, qualified by the form and answered on WhatsApp.
5. Nothing leaves the origin. No third-party fetch on the critical path, and no visitor data handed to anyone before the visitor chooses to send it.

## Accessibility & Inclusion

Established in the current implementation and to be preserved: 11px floor for functional text, 44px minimum touch targets, 16px form inputs so iOS does not zoom on focus, visible focus states, safe-area insets honoured, and a page that still reads and still reaches WhatsApp with JavaScript disabled.
