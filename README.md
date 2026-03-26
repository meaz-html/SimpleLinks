<img width="300" height="300" alt="Screenshot 2026-03-21 132625" src="https://github.com/user-attachments/assets/2065bb81-1995-416e-890e-3c1d78c667a4" />

# Simple Links
<p>Simple Links is a Astro Template that contains just CSS and HTML, Its for people who dont know much programming but HTML (and maybe CSS), and If you acquire new skills from time to time, no worries!, just add what you know, and it will be better!</p>
<a href="https://simple-links-demo.vercel.app">You can view the demo here</a>

<p>In order to use this template, you must have:</p>
<ul>
<li>Astro (Any Version should work)</li>
<li>VS Code (Either 2026 Insider or Normal should just work fine, As long as you have the Astro Extension Installed)</li>
<li>Node.js (22.12.0 or higher, odd numbers like 23 are not supported)</li>
<li>Terminal (Powershell for windows etc, this is where you can control astro)</li>
<li>You will also need npm (this is bundled with node.js if you selected it), npm will be used to run the dev host and start up it</li>
</ul>

## Installation
<p>To install it:</p>

<pre><code># Run this command and follow instructions
npm create astro@latest -- --template meaz-html/SimpleLinks

# If you skipped installing dependencies, run
cd [YOUR_PATH] (This should be first)
And then
npm install

# Now start the dev server
npm run dev   
</code></pre>

<p>..and Congrats, you did it!</p>

## Important
Please Remember that when deploying it from a repo using a deployment service (eg, Vercel), you might encounter a error with npm, if so, please check your .gitignore file and then do:

<pre><code># Install git-filter-repo via Mac
brew install git-filter-repo

# Or via pip (with python)
pip3 install git-filter-repo

# After that, run
git filter-repo --invert-paths --path PATH-TO-YOUR-FILE-YOU-ADDED-TO-.GITIGNORE
</code></pre>

And then after redeploying (Remember to use the latest branch!), it should sucessfully work now.

## Credits

<ul>
  <li>Me (meaz-html, also known as Kazuno or Ahyan Z, Done the HTML Files only)</li>
  <li>Github Copliot (Helped with the CSS and refining)</li>
  <li>Brave AI (Helped me with troubleshooting a lot)</li>
</ul>

<p>and aswell I did this README.md all myself, so give some round of applause to me.</p>
