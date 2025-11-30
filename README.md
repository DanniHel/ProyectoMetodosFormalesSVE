# Especificación Formal de un Sistema de Votación Electrónica  

## Carátula

**Universidad:** Universidad La Salle Arequipa  
**Docente:** Maribel Molina Barriga  
**Proyecto:** Especificación Formal de un Sistema de Votación Electrónica para el Contexto Peruano  
**Curso:** Métodos Formales  

**Autores:**  
- Davis Yovanny Arapa Chua  
- Luis Gonzalo Basurco Monroy  
- Esther Mariana Chunga Pacheco  
- Danny Quispe Cjuiro  
- Carlos Adrian Vizarreta Checya  

---

## Descripción

El presente proyecto desarrolla una especificación formal del proceso de registro, validación y autenticación de votantes en un Sistema de Votación Electrónica, considerando las particularidades del contexto electoral peruano.  
Se emplea el lenguaje formal **VDM++** para la definición de estructuras, invariantes y operaciones que aseguran consistencia lógica, integridad de datos y ausencia de ambigüedades en el manejo del padrón electoral.  

Asimismo, se utiliza **NuSMV** para la verificación formal mediante *model checking*, validando propiedades esenciales como la prevención del doble voto y el cumplimiento de las reglas de transición de estados en el proceso de autenticación.  

Las pruebas dinámicas realizadas en VDM Toolbox alcanzaron **100% de cobertura**, lo que garantiza que todas las rutas operacionales del modelo han sido analizadas y verificadas, contribuyendo a la confiabilidad y robustez del sistema propuesto.
