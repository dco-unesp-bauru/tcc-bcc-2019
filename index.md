# Mostra de TCC do BCC 2019



# Trabalhos

<ul>
	{% for post in site.posts %}
	<li>
	<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
	<p>Autor: {{ post.autor }} <br />
	Orientador: {{ post.orientador }}</p>
	</li>
	{% endfor %}
</ul>
