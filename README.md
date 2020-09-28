"# flask_restx_demo" 


Known issues:

1) Flask_restx does not appear to install flask_restful though it says so. We need to install flask_restful to avoid the import reference issues
2) On importing "from flask_restplus import Api, Resource" api getting cannot import name 'cached_property' from 'werkzeug'. This can be overcome by downgrading werkzeug.utils to Werkzeug==0.16.1 like pip install Werkzeug==0.16.1
