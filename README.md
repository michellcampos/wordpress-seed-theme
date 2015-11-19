<h4>Template Files List</h4>
<p>Here is the list of the Theme files recognized by WordPress. Of course, your Theme can contain any other stylesheets, images, or files. Just keep in mind that the following have special meaning to WordPress -- see <a href="/Template_Hierarchy" title="Template Hierarchy">Template Hierarchy</a> for more information.
</p>

<dl>
<dt><i>style.css</i></dt>
<dd> The main stylesheet. This <b>must</b> be included with your Theme, and it must contain the information header for your Theme.
</dd>
<dt><i>rtl.css</i></dt>
<dd> The rtl stylesheet. This will be included <b>automatically</b> if the website's text direction is right-to-left. This can be generated using <a class="external text" href="http://wordpress.org/extend/plugins/rtler/">the RTLer</a> plugin.
</dd>
<dt><i>index.php</i></dt>
<dd> The main template. If your Theme provides its own templates, <i>index.php</i> must be present.
</dd>
<dt><i>comments.php</i></dt>
<dd> The comments template.
</dd>
<dt><i>front-page.php</i></dt>
<dd> The front page template.
</dd>
<dt><i>home.php</i></dt>
<dd> The home page template, which is the front page by default. If you use a <a href="/Creating_a_Static_Front_Page" title="Creating a Static Front Page">static front page</a> this is the template for the page with the latest posts.
</dd>
<dt><i>single.php</i></dt>
<dd> The single post template. Used when a single post is queried. For this and all other query templates, <i>index.php</i> is used if the query template is not present.
</dd>
<dt><i>single-{post-type}.php</i></dt>
<dd> The single post template used when a single post from a custom post type is queried. For example, <i>single-book.php</i> would be used for displaying single posts from the custom post type named "book". <i>index.php</i> is used if the query template for the custom post type is not present.
</dd>
<dt><i>page.php</i></dt>
<dd> The page template. Used when an individual <a href="/Pages" title="Pages">Page</a> is queried.
</dd>
<dt><i>category.php</i></dt>
<dd> The <a href="/Category_Templates" title="Category Templates">category template</a>. Used when a category is queried.
</dd>
<dt><i>tag.php</i></dt>
<dd> The <a href="/Tag_Templates" title="Tag Templates">tag template</a>. Used when a tag is queried.
</dd>
<dt><i>taxonomy.php</i></dt>
<dd> The <a href="/index.php?title=Taxonomy_Templates&amp;action=edit&amp;redlink=1" class="new" title="Taxonomy Templates (page does not exist)">term template</a>. Used when a term in a custom taxonomy is queried.
</dd>
<dt><i>author.php</i></dt>
<dd> The <a href="/Author_Templates" title="Author Templates">author template</a>. Used when an author is queried.
</dd>
<dt><i>date.php</i></dt>
<dd> The date/time template. Used when a date or time is queried. Year, month, day, hour, minute, second.
</dd>
<dt><i>archive.php</i></dt>
<dd> The archive template. Used when a category, author, or date is queried. Note that this template will be overridden by <i>category.php</i>, <i>author.php</i>, and <i>date.php</i> for their respective query types.
</dd>
<dt><i>search.php</i></dt>
<dd> The search results template. Used when a search is performed.
</dd>
<dt><i>attachment.php</i></dt>
<dd> Attachment template. Used when viewing a single attachment.
</dd>
<dt><i>image.php</i></dt>
<dd> Image attachment template. Used when viewing a single image attachment. If not present, attachment.php will be used.
</dd>
<dt><i>404.php</i></dt>
<dd> The <b><a href="/Creating_an_Error_404_Page" title="Creating an Error 404 Page">404 Not Found</a></b> template. Used when WordPress cannot find a post or page that matches the query.
</dd>
</dl>
