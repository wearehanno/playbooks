# Web apps

<p>We usually build web or mobile apps with one of two frameworks, <a href="https://angular.io/">Angular</a> or <a href="https://facebook.github.io/react/">React</a>.</p>
<p>From our POV, both are battle-tested enough to last in a production environment for a while (at least the next 5 years).</p>
<p><em>Choosing between Angular and React is like choosing between buying an off-the-shelf computer and building your own with off-the-shelf parts. </em></p>
<p><em>Angular 2 continues to put &ldquo;JS&rdquo; into HTML. React puts &ldquo;HTML&rdquo; into JS. HTML and JavaScript need to be glued together somehow, and React&rsquo;s JavaScript-centric approach is fundamentally superior to Angular, Ember, and Knockout&rsquo;s HTML-centric approach.</em></p>
<p>Here&rsquo;s a brief comparison between the two, highlighting the pro and cons of each framework:</p>
<h3>React</h3>
<ul>
<li>Is a library: you typically pull a number of other libraries off the shelf to build a real app</li>
<li>It&rsquo;s just the View Layer, which makes it a lot slimmer</li>
<li>You write HTML in JS using JSX</li>
<li>It is Javascript-centric</li>
<li>It doesn&rsquo;t exactly line up 1:1 with HTML tags</li>
<li>For state management, we&rsquo;d use <a href="http://redux.js.org/">Redux</a> (for most large apps) or <a href="https://github.com/mobxjs/mobx">MobX</a> (for less complex apps that don&rsquo;t need transactional state).</li>
<li>For stuff that&rsquo;s not baked in, you rely a lot on community-supported plugins</li>
</ul>
<h3>Angular 2</h3>
<ul>
<li>Is a framework: provides significantly more opinions and functionality out of the box</li>
<li>It has significantly more boilerplate</li>
<li>It&rsquo;s HTML-centric</li>
<li>It depends on TypeScript</li>
<li>It relies a lot on dependency injection</li>
<li>Has core support for forms, validation etc&hellip;</li>
<li>Delivers performance gains with Ahead Of Time compiling (AOT) and tree-shaking</li>
<li>Templates are an enhanced form of HTML, but you need to learn Angular DSL</li>
</ul>

<hr />

_Last updated: Wed May 03 2017 18:51:21 GMT+0100 (British Summer Time)_