# Static site generators 

<p>We believe that in the majority of cases with a marketing website, the application&rsquo;s backend logic can be handled once, at build time, to generate a static site. Any extra &lsquo;dynamic&rsquo; functionality can be layered on with JavaScript.</p>
<p>Rather than building and maintaining a server, <a href="https://www.netlify.com/">Netlify</a> and <a href="https://zeit.co/now">Zeit Now</a> allow us to deploy a static site and simple build process with a few clicks and set this to run on every push to a master branch on GitHub. We can then relax knowing that the site we&rsquo;ve deployed will be almost infinitely scalable and lightning fast. Other services are popping up more and more frequently.</p>
<p>That scenario is more common than you would think, and many Wordpress sites could probably be built this way, preventing Hackers from attacking the vulnerable PHP code it exposes (ever wondered why you need to update Wordpress every few days?)</p>
<p>Our favourite SSGs are:</p>
<ul>
<li><a href="https://middlemanapp.com/">Middleman</a>: a Ruby-based tool that we have battle-tested in a lot of projects, including our own website.</li>
<li><a href="https://github.com/gatsbyjs/gatsby">Gatsby</a>: the new kid on the block. This tool allows you to write your static sites in React and provides ultra-fast page-loading thanks to the React Router integration.</li>
<li><a href="http://www.metalsmith.io/">Metalsmith</a>: another node.js-based tool that we&rsquo;ve used and thanks to its strong plugin system allows for a very flexible and lean way of building static sites. Metalsmith powers this <em>Playbooks</em>&nbsp;website.</li>
</ul>

<hr />

_Last updated: Wed May 03 2017 18:47:22 GMT+0100 (British Summer Time)_