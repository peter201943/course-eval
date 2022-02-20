Introduction

This is document outlines several possible choices for back-end frameworks that could be used for the CourseEval system. It offers a brief description and analysis of each of these technologies, resources to learn more about them, and a conclusion which offers a suggestion of which one to use.


Django

Architecture: MVT (Model-View-Template)
Language: Python
Open Source: Yes

Django is a web framework with many features built into it. Many have dubbed it a "batteries included" framework due to it's robustness. Django allows for rapid development by taking advantage of its multitude of built-in features like user authentication, messaging and admin abilities. It uses an MVT (Model-View-Template) structure which is similar to the MVC (Model-View-Controller) architecture. It also uses an ORM (Object Relational Mapping) layer to make the database much simpler by allowing for simple Python code to be written rather than directly defining tables and queries.

https://www.djangoproject.com/


Rails

Architecture: MVC (Model-View-Controller)
Language: Ruby
Open Source: Yes

Rails is a web framework also often dubbed "batteries included" for it's many built-in features which allow for rapid development. This robustness, like the ORM layer (Object Relational Mapping) and security features, also comes with a considerable learning curve, as many more advanced tasks require greater complexity. It uses the common MVC (Model-View-Controller) architecture. It is written in Ruby a language which somewhat rare, at least when compared to Python, Java, or JavaScript

https://rubyonrails.org/


Laravel

Architecture: MVC (Model-View-Controller)
Language: PHP
Open Source: Yes

Laravel is a web framework based around the idea of making upgrading as simple as possbile. It is a relatively simple framework which offers scalability and flexibility. It follows the MVC (Model-View-Controller) architecture, a structure that is common for it's ease of maintenance and reusability of code. While it is seen by many to be the best PHP framework, it is still base on PHP, a language in decline.

https://laravel.com/


Conclusion

While all of the frameworks listed in the document have merit, the best choice is most likely Django. It offers many powerful features which will allow for rapid development and offer scalability as the project continues and evolves. It will allow for easy and rapid development at all stages of the project. It has a helpful and insightful community, with many resources to help developers learn about it. Django, unlike Rails and Laravel, is based on Python, a very common language which all of our developers are familiar with, unlike Ruby and PHP. Also, unlike PHP, Python is not in decline as a language, is one of the most common languages for new projects, and will continue to be  for the foreseeable future. Django is a robust framework that could serve our project well.