# YouTube course learning django 4 by selfedu

## [#4. Маршрутизация и функции представления | Уроки по Django 4](https://www.youtube.com/watch?v=Kys3IrP2Uhc&list=PLA0M1Bcd0w8yU5h2vwZ4LO7h1xt8COUXl&index=5)

1. wrote routing urls in core/urls.py
2. created routing urls in app/urls.py
3. included app urls in core/urls.py with include
4. created basic views in app/views.py

```python
def index(request):
    return HttpResponse('IMDb clone main page')
```

### Keynotes:

- writing '/' at the end of a url is a general practice in django
- HttpResponse automatically generated headers, you provide the content
- include receives importlib-like string (app.urls, not app.urls.py or app/urls.py) 
- when using function views, you do not call them, just passing

