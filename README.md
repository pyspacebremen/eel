# pySpaceBremen



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


## Python Web (Electron) App

mit dem Python Modul ist es einfach möglich Desktop Web Applikationen zu erstellen.


``` python
import eel

eel.init('.')
eel.start('index.html')

```
