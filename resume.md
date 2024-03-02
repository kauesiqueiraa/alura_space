Configuration Django

Após instalar python e pip

instalar o virtualenv

```
python -m virtualenv .venv
```

após isso, abrir ele:
`.venv\Scritps\activate`

caso queira sair do venv: `deactivate`

dentro do .venv instalar o django: `pip install django`

agora as dependencias caso já saiba alguma que vai utilizar: ``````

atualizar o arquivo requiriments.txt com as libs: `pip freeze > requiriments.txt`

criar o arquivo Django: `django-admin startprojetct setup .`

para rodar o python: `python manage.py runserver`

caso queira trocar hora e idioma: `Abrir o arquivo setings.py e alterar para: LANGUAGE_CODE = 'pt-br' - TIME_ZONE = 'America/Sao_Paulo'`

antes de subir o projeto para o github: `Instalar  a lib: pip install dotenv  depois disso acessar o site: gitignore.io e pegar o .gitigore do django para copiar e colar no projeto`
