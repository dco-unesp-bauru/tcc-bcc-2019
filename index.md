# Mostra de TCC do BCC 2019 2º semestre

Realizada anualmente, a Motra de TCCs de BCC tem por objetivo inspirar e
apresentar aos alunos, professores, funcionários e a comunidade (em especial as
empresas e desenvolvedores de software locais) as invoações e realizações
acadamicas consquistas e contruidas pelos alunos graduandos desta universidade.

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
