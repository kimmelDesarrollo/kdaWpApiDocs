Clientes Por Tipo
=================

Conocer beneficiarios de un seguro de Deuda o Familia protegida

Ruta::

   http://190.107.28.210:4000/codice/clients_by_type

Método::

   POST

Cabecera Requerida::

    Content-Type: application/json

Parámetros Requeridos::

    cc : int
    type: enum('D', 'F')
    num: int

    {"cc": 37000726, "type": "F", "num": 1}

Respuesta::

    array <name: string, relationship: int, percent: float>
    
    [
        {
            "name": "JHON ALEXANDER PIEDRAHITA",
            "relationship": "Hijo (a)",
            "percent": 50.0
        },
        {
            "name": "NELSON CAMILO MENESES",
            "relationship": "Hijo (a)",
            "percent": 50.0
        }
    ]