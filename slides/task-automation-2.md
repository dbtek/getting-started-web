##Grunt Usemin

>Replaces references from non-optimized scripts, stylesheets and other assets to their optimized version within a set of HTML files (or any templates/views).

>[github.com/yeoman/grunt-usemin](https://github.com/yeoman/grunt-usemin)


<pre>
src/index.html
<code>
&lt;!-- build:js js/app.js --&gt;
&lt;script src="js/app.js"&gt;&lt;/script&gt;
&lt;script src="js/controllers/thing-controller.js"&gt;&lt;/script&gt;
&lt;script src="js/models/thing-model.js"&gt;&lt;/script&gt;
&lt;script src="js/views/thing-view.js"&gt;&lt;/script&gt;
&lt;!-- endbuild --&gt;
</code>
</pre>
<pre>
dist/index.html
<code>
&lt;script src="scripts/95e0c01f.app.js"&gt;&lt;/script&gt;
</code>
</pre>