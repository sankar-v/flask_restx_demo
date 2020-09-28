"# flask_restx_demo" 


Known issues:

1) Flask_restx does not appear to install flask_restful though it says so. We need to install flask_restful to avoid the import reference issues
2) On importing "from flask_restplus import Api, Resource" api getting cannot import name 'cached_property' from 'werkzeug'. This can be overcome by downgrading werkzeug.utils to Werkzeug==0.16.1 like pip install Werkzeug==0.16.1

The swagger URL is http://localhost:8888/api/, which will list all the endpoints of the REST APIs in the defined namespace.

The application can be set up in virtual environment and pycharm IDE and run by invoking app.py.  




