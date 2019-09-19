Documntos Por Año Por Cliente
=============================

Conocer radicaciones de un cliente en un año especifico

Ruta::

   http://190.107.28.210:4000/codice/client_docs_in_year

Método::

   POST

Cabecera Requerida::

    Content-Type: application/json

Parámetros Requeridos::

    cc : int
    year: int

    {"cc" : 22817388, year: 2015}

Respuesta::

    array <number: int, date: string, state: string>
    
    [
        {
            "number": 10016, 
            "date": "2015-08-18", 
            "state": "PAGADO"
        }
    ]