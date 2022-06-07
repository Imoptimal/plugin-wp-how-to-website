# plugin-wp-how-to-website

# Instructions:
- Install wordpress locally, using Local by Flywheel - PHP version must be > 7.4 (Simply Static plugin requires it).
- Adjust settings in admin dashboard:
  - General - set tagline to 'WordPress Plugin'
  - Writing - set static page as a Homepage (homepage created as instructed below)
  - Discussion - check off "Allow people to submit comments on new posts"
- Add pages:
  - Homepage (slug: homepage) with hardcoded content (set template to homepage template)
  - Buy Premium page (slug: buy-premium) with hardcoded content (set template to buy-premium template)
  - FAQ page (slug: faq) with hardcoded content (set template to faq template)
  - Privacy Policy page (slug: privacy-policy) with hardcoded content
- Download the latest official wordpress theme (parent) and activate the customized child theme:
  - Open full site editor and edit header:
    - Add site logo to header (resize uploaded logo to width of 150px) - to the left position
    - Add navigation ('Buy Premium', 'FAQ' and 'Privacy Policy' page) - to the right position
  - Edit footer:
    - Add columns block (with 'Buy Premium', 'FAQ' and 'Privacy Policy' page links) - to the center position (alignment)
- Install plugins:
  - Simply Static
- Convert webiste to static using Simply static plugin (Set relative paths - avoiding issue with website resources).
- Upload here.
- Create 404.html file here on GitHub website, and populate it with needed elements. <br>
<b>NOTE! When updating repository, delete all static files except 404.html, CNAME, LICENSE, README.md and wp-how-to-black.png, and the upload all of the static files generated by Simply Static!</b>
