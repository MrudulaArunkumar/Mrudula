---
title: Binding and Retrieval in Action Control (BRAC)
subtitle: A framework to explain how one executes an action with the information available in the environment
author: Mrudula Arunkumar
categories:
- Learning
- Stimulus-Response Pairs
- Cognition
date: "2022-03-05"
draft: false
excerpt: This theme has a form-to-email feature built in, thanks to the simple Formspree
  integration. All you need to activate the form is a valid recipient email address
  saved in the form front matter.
#layout options are single or single-sidebar
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: https://www.brac-psy.de/
- icon: wikipedia-w
  icon_pack: fa-brands
  name: Wikipedia
  url: https://en.wikipedia.org/wiki/Binding_and_Retrieval_in_Action_Control
#subtitle: An R Package
tags:
- hugo-site
---

![Formspree Logo](formspree-logo.png)

## [Formspree](https://formspree.io) makes it easy to receive submissions from HTML forms on your static website.

---

### Functional Form

This theme has a **form-to-email** feature built in, thanks to the simple Formspree integration. All you need to activate the form is a valid recipient email address saved in the front matter of the form
(`/content/forms/contact.md`). Of course, the example shown below (`your@email.here`) must not be used. Please use your actual email address.

```toml
# please replace with a valid Formspree form id or email address
formspree_form_id: your@email.here
```

Update that file and you're ready to begin receiving submissions. Just submit
the active form for the first time, and complete the email address verification
step with Formspree, and your contact form is live. The next time someone
fills it out, the submission will land in your inbox.

### Multiple Layouts

The files included with the theme have a contact page ready for copy/paste, or
you can type `hugo new forms/contact.md` and you're off to the races. There are two
layouts for `forms` – `split-right`, and `split-left` – you guessed it, one puts
the form on the right and the other on the left. You just fill out the front
matter, and the rest is automatic.

```toml
# layout options: split-right or split-left
layout: split-right
```

![Contact Form Split Right Layout Screenshot](built-in-contact-form-screenshot.png)

Both layouts display the page title and description opposite the form, and you
can also choose to show your social icon links if you have those configured in
the `config.toml` file.
