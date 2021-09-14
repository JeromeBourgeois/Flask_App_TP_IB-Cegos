# Flask_ToDo_App
Simple Flask Todo Application

## Exemple start app with gunicorn
`gunicorn --workers 4 --bind 0.0.0.0:5000 wsgi:app`
> The option `--workers N` is the number of cores in the server !