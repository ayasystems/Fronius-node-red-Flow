# Fronius-node-red-Flow
Lectura del modbus de Fronius para cargar datos en Domoticz

# Requisitos generales
Tener un broquer mqtt, node-red instalado y funcionando, domoticz y opcionalmente influxdb para envíar los datos de fronius

# Requisitos en node-red
Es necesario instalar los siguientes nodos de node-red

node-red-contrib-modbus
node-red-contrib-moment
node-red-contrib-buffer-parser
node-red-contrib-influxdb

# Requisitos domoticz
Necesitaremos tener 3 energy meter (counter + instant) creados en domoticz [dummy/virtual]

Producción
Importado
Exportado


