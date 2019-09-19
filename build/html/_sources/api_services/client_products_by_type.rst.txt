Productos Por Tipo Por Cliente
==============================

Conocer productos vigentes de un seguro de Deuda o Familia protegida

Ruta::

   http://190.107.28.210:4000/codice/client_products_by_type

Método::

   POST

Cabecera Requerida::

    Content-Type: application/json

Parámetros Requeridos::

    cc : int
    type: enum('D', 'F')

    {"cc" : 1123326302, type: "F"}

Respuesta::

    array <number: int, date: string, state: string>
    
    [
        {
            "number": 99812, 
            "start": "2018-06-16", 
            "end": "2019-10-16", 
            "value": 0.0
        }
    ]