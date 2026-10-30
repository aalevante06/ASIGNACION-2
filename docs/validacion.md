# Validación — Asignación #2

## Direccionamiento

| Equipo | IP |
|---|---|
| R1 | `10.21.74.1/24` |
| SW-2174 | `10.21.74.2/24` |
| NPS / Windows Server | `10.21.74.10/24` |

## Pruebas realizadas

| Prueba | Resultado |
|---|---|
| R1 registrado en NPS | Correcto |
| SW-2174 registrado en NPS | Correcto |
| USER0 autenticado | Correcto |
| USER0 privilege | `2` |
| USER5 autenticado | Correcto |
| USER5 privilege | `5` |
| USER10 autenticado | Correcto |
| USER10 privilege | `10` |
| SSH R1 | Correcto |
| SSH SW-2174 | Correcto |
| AAA consola/AUX | Configurado |
| Accounting EXEC | Configurado |
| Login success/failure logging | Configurado |
