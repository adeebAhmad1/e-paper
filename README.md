# Local setup

- Clone the repository
- Then run command 'npm install'
- Then run command 'npm run dev'
- Right now it is redirected to public/ folder index.html file, so whatever you make change, make change into the public folder.
- Make changes, follow similar folder structure in public to add images, font, css, js etc
- After you add your design push to the github repository and you will be able to see the changes at live site https://dpsignadvertising.com/index.html or the html files that you pushed. If you pushed about.html then URL will be https://dpsignadvertising.com/about.html
- Optional: If you need to push your development work then you can push into the dev/ branch and your testing environment URL is https://ebookdesign-qno3sx9xo.vercel.app/index.html. First do "git checkout dev && git merge master", then start your development and push with "git push origin dev"

# ebookdesign

# Our ideas collection

- HTML5 document
- Let's make primary and secondary palettes, and gradients, stick to them so that we can generate multiple theme latter on.
- Use only one google font like Roboto or Realway etc (Stay with only one font, but we can use light, medium, condensed, bold as needed)
- Images alway use the licence free, pexels.com is one site.
- Color selection: Please select analogous color combinations and let us know why you choose it https://www.canva.com/learn/100-color-combinations/, there are Analogous color combinations, Triadic color combinations and Complementary color combinations.
- Don't use full black color (#000000) anywhere.
- Our CSS framework will be Bootstrap, if you can work on the scss then better to provide it.
- For icons better to stick with bootstrap icons, but we can decide if need to use fontawesome.
- Paragraph font size to be 16px (SEO purposes), then in other try to use corresponding needed ems (em)
- CSS should start with "\* {margin:0;padding:0;}"
- Use lowercase for class name and id name
- RTL and LTR both need to be supported.
- Use only one h1 in a page (For SEO purpose and w3 validation)
- Follow the hierarchical approach of html tags like div > h1, not like h1 > div (Important for w3 validation)

# Validate CSS and HTML

https://validator.w3.org/
http://jigsaw.w3.org/css-validator/
Pagespeed test https://developers.google.com/speed/pagespeed/insights/, score need to be more than 80 and try to reach 100 :) both in mobile and desktop.
