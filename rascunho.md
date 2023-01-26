# Estudo sobre Django

> app = resolve problemas especificos. "\home" 
> models = responsavel pelo banco de dados, criar tabelas etc.
> viwes = responsavel pela logica da aplicação.
> template = cama de interfase, aonde o usuário vai conseguir ver o sistema.

# Ambiente Linux:
## criando o app
python3 manegy.py startapp <<nome>>

# Start project:
django-admin startproject <<nome>> .

# Criando um ambiente virtual:
python -m venv venv

# Ativando o ambiente:
.\venv\Scripts\activate

### Style:
AONDE PROCURAR OS ARQUIVOS ESTATICOS
IMPORT OS

1) STATICFILES_DIR = [os.oath.join(BASE_DIR, 'templates/static')] #irar concatenar as urls 