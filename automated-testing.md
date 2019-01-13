footer: Automated browser testing - David Darke | [atomicsmash.co.uk](https://www.atomicsmash.co.uk)
slidenumbers: true

# [fit] Automated
# [fit] browser testing 🤖

## By David Darke

---

![fill](assets/atomicsmash-logo.png)

---

# [fit] Automate
# [fit] EVERYTHING

---

# [fit] You may have heard
# [fit] of unit testing...


---

# [fit] With Unit Testing you can break down
# [fit] functions into small chucks to test

---

[.autoscale: true]


# For example...
# A subscription purchase

* User logs in
* User makes purchase
* Get subscription information from the order
* Assign subscription to user

---

[.autoscale: true]

* User logs in
    * Get current user
    * Validate
    * Log user into site
* User makes purchase
    * An order is created
    * Order emails are sent
* Get subscription information from the order
    * Check order for subscription product
    * Order emails are sent
* Assign subscription to user
    * Check subscription was purchased
    * Add subscription to user
    * Check the subscription is active

---

![fit](assets/php-fatal.png)

---

# [fit] Unit testing is great
# [fit] But simple browser testing is also great

---

## Sadly though it's:
- Time consuming
- Easy to forget to test something important
- New developers on projects might not know what to test

---


![ 200% ](assets/dusk.pdf)

---

# THANKS!

Follow me:
@david_darke

Follow my studio:
@atomicsmash

Get presentation here:
https://github.com/daviddarke/A-modern-WordPress-development-workflow

---
[.autoscale: true]

### Tool list

- Capistrano | Used to deploy code from GIT to servers.
- Composer | Used to pulling PHP dependancies like Wordpress.
- Forge | Used for provisioning servers
- GIT | A version control system for storing and sharing code.
- Logflume | Gets uploads onto S3 so they are sharable with other developers
- Logsmith | The development framework made by Atomic Smash
- Release belt | Used for storing premium plugins and making them privately accessible to composer.

[^1]: https://hackernoon.com/please-use-git-da3bea7d1234

[^2]: https://www.atomicsmash.co.uk/blog/using-composer-wordpress-development/

[^3]: https://www.atomicsmash.co.uk/blog/our-current-development-tools-and-workflows/
