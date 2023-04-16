Website for [Fogg Consulting LLC](https://scalingstartups.ai/) - Infrasctructure Consultancy 

The website is built using the [Beautiful-Jekyll](https://beautifuljekyll.com/) template by [Dean Attali](https://deanattali.com/)

**For Local Testing:**
  1. Comment out line 8 in Gemfile, uncomment lines 2-7
  2. run "bundle install"
  3. run "bundle exec jekyll serve"
markdown should now be served at localhost:4000

**For Deployment:**
  1. Uncommment line 8 in Gemfile, comment out lines 2-7
  2. run "bundle install"
  3. push to origin 
deployment workflow should run with changes now visible at https://scalingstartups.ai/

**Setting Up Local Environment:**
  1. install ruby https://www.ruby-lang.org/en/downloads/
  2. install jekyll https://jekyllrb.com/docs/
  3. see "for local testing" above (remember to switch back before pushing to master!)
  4. index.md, contact.md, and /assets/css/index.css are the main styling files
note: any push to master will automatically deploy live
