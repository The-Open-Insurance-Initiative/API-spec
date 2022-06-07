# How to contribute

I'm really glad you're reading this, because we need volunteer developers to help this project come to fruition.

If you haven't already, come find us at ([Open Insurance Think Tank](https://openinsurance.io/)). We want you working on things you're excited about.

Here are some important resources:

  * [Online Forum for Developers](https://forum.openinsurance.io/) tells you where we are,
  * Mailing list: Join our [Open Insurance list](https://openinsurance.io/)

## Submitting changes

Please send a [GitHub Pull Request to Open Insurance](https://github.com/The-Open-Insurance-Initiative/API-spec) with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."

## Coding conventions

Start reading our code and you'll get the hang of it. We optimize for readability:

  * We ALWAYS put spaces after list items and method parameters (`[1, 2, 3]`, not `[1,2,3]`), around operators (`x += 1`, not `x+=1`), and around hash arrows.
  * This is open source software. Consider the people who will read your code, and make it look nice for them. It's sort of like driving a car: Perhaps you love doing donuts when you're alone, but with passengers the goal is to make the ride as smooth as possible.
  * So that we can consistently serve images from the CDN, always use image_path or image_tag when referring to images. Never prepend "/images/" when using image_path or image_tag.
  * Also for the CDN, always use cwd-relative paths rather than root-relative paths in image URLs in any CSS. So instead of url('/images/blah.gif'), use url('../images/blah.gif').

Thanks,
Fouad Husseini, Open Insurance Think Tank
