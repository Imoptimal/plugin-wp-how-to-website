# plugin-wp-how-to-website

# Instructions:
- Install wordpress locally, using Local by Flywheel - PHP version must be > 7.4 (Simply Static plugin requires it).
- Adjust settings in admin dashboard:
  - General - set title to "'WP How to - WordPress Tutorial Videos'"; set tagline to "WordPress Plugin"
  - Writing - set static page as a Homepage (homepage created as instructed below)
  - Discussion - check off "Allow people to submit comments on new posts"
- Add pages:
  - Homepage (slug: homepage) with hardcoded content (set template to homepage template)
  - Buy Premium License page (slug: buy-premium) with hardcoded content (set template to buy-premium template)
  - FAQ page (slug: faq) with hardcoded content (set template to faq template)
  - Privacy Policy page (slug: privacy-policy) with hardcoded content
  - WordPress Plugin Json (slug: wordpress-plugin-json) with hardcoded content (set template to wordpress-plugin-json template)
  - WordPress Topic Json (slug: wordpress-topic-json) with hardcoded content (set template to wordpress-topic-json template)
- Download the latest official wordpress theme (parent) and activate the customized child theme:
  - Open full site editor and edit header:
    - Add site logo to header (resize uploaded logo to width of 150px) - to the left position
    - Add navigation ('Buy Premium', 'Go to Video Tutorials' - homepage of main domain - open in the new tab, 'FAQ' and 'Privacy Policy' page) - to the right position
  - Edit footer:
    - Add columns block ('Buy Premium', 'FAQ' and 'Privacy Policy' page - open all in the new tab) - to the center position (alignment)
    - Add navigation with 'WordPress Plugin Json' and 'WordPress Topic Json' pages (to generate static pages) - will be hidden by javascript.
- Install plugins:
  - Simply Static
- Convert webiste to static using Simply static plugin (Set relative paths - avoiding issue with website resources).
- Upload here.
- Create 404.html file here on GitHub website, and populate it with needed elements. <br>
<b>NOTE!</br>
- When updating repository, delete all static files except 404.html, CNAME, LICENSE, README.md and wp-how-to-black.png, and the upload all of the static files generated by Simply Static!</br>
- When updating theme template files - they maybe need to be renamed and reset to desired pages in order for it to work! (idk why)</b>
