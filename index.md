# jaan.janesmae.com

<div>
	<h2>Blog Posts</h2>
	<ul>
	{% for post in site.posts %}
    	<li>{{ post.date | date_to_string }} &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
	</ul>
</div>
