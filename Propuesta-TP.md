# Propuesta TP Desarrollo de Software -

## Grupo
### Integrantes 
* 55382 - Lombardi, Luca
* 53889 - Renzi, Agustín Gabriel
### Repositorios
 * 
 * 
## Tema
### Descripción
El sistema gestiona el ciclo de vida del cultivo mediante la administración de **Labores** (Siembra y Cosecha). Se garantiza la trazabilidad permitiendo registrar qué **Insumos** (Semillas y Fertilizantes) se aplicaron en cada **Lote**, manteniendo un historial de rendimientos por campaña. El objetivo principal es brindar una herramienta centralizada para el seguimiento técnico y la toma de decisiones basada en el histórico de producción.
### Modelo
![Diagrama del Modelo de Dominio](./MD_DSW.drawio.svg)
## Alcance Funcional

### Alcance Mínimo (Regularidad)
#### 1. CRUD Simple
* **Labor** 
* **Lote** 
#### 2. CRUD Dependiente
* **Datos_Campaña**
#### 3. Listado + Detalle
* **Listado de Cosechas Realizadas** 
#### 4. Caso de Uso de Usuario (CUU)
* **Registrar Labor**
#### Adicionales para Aprobacion:
#### CRUD:
 * **Productor**
 * **Labor**
 * **Fertilizante**
 * **Tipo_semilla**
 * **Lote**
 * **Cultivo**
#### CUU/Epic:
 * **Registrar labor**
 * **Registrar aplicacion de fertilizante**

