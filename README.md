# lector_biometrico
Plugin lector biometrico, el cual se puede integrar con cualquier API.

# GET  consultar huellas

{{ URL APP}} / ConsultaHuella?token=UVXXEe1670256547967&desde=0&hasta=10

Parametros enviados para la peticion de conusltar las huellas registradas:

    token:UVXXEe1670256547967
    desde:0
    hasta:10

# POST

{{ URL APP}} / AsociarHuella

# PUT

{{ URL APP}} / ActualizarHuella

# GET - habilitar lector

{{ URL APP}} / HabilitarSensor?token=u82UbV1672156050708&timestamp=1672949516&_=1672949518135

Parametros enviados para la peticion de habilitar el lector:

    token:     u82UbV1672156050708
    timestamp: 1672949516
    _:         1672949518135
