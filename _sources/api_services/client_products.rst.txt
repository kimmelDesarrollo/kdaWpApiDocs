Productos Por Cliente
=====================

Conocer los productos de los cuales dispone un cliente

Ruta::

   http://190.107.28.210:4000/codice/client_products

Método::

   POST

Cabecera Requerida::

    Content-Type: application/json

Parámetros Requeridos::

    cc : int

    {"cc" : 37000726}

Respuesta::

    array <type: string, number: int, end: string, value: float>
    
    [
        {
            "type": "Deudores",
            "number": 4712709,
            "start": "2017-12-09",
            "end": "2020-12-11",
            "value": 0.0
        },
        {
            "type": "Familia ",
            "number": 3939790,
            "start": "2017-12-09",
            "end": "2020-12-09",
            "value": 10000000.0
        },
        {
            "type": "Familia ",
            "number": 3939790,
            "start": "2018-11-10",
            "end": "2020-11-10",
            "value": 4000000.0
        },
        {
            "type": "Deudores",
            "number": 5227486,
            "start": "2018-11-10",
            "end": "2020-07-09",
            "value": 0.0
        }
    ]