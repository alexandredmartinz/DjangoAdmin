Criamos o template base.html que vai conter todoo HTML comum a todas a páginas.

E criamos os blocos: 

 {% block 'title '%}
 {% endblock 'title '%}

Nos perfis 

Temos no body uma navbar
e 3 links para as listagens de Carros, Motos e todos.

Temos uma outra nav bar com um {%block content}%

