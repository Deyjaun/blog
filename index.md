# **Blog Intro**

<p>Hello my name is Deyjaun Lawrence <br>I am Jamaican <br> I do Full Stack Developement and have a hard working personality <br>and most of all i make music and i am a gaming content creator

![My summer photo](/assets/family.jpg)


## Recent Posts
<ul>
{% for posts in sits.posts %}
<li>
<a href="/blog{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>