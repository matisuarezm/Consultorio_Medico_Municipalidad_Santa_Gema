# 📘 Proyecto: Consultorio Médico Municipalidad Santa Gema - Semana 6

## 📝 Descripción general del sistema

El modelo relacional implementa el sistema de gestión de un consultorio médico municipal, cubriendo desde la identificación de pacientes y médicos hasta la emisión de recetas, registro de medicamentos, pagos y ubicación geográfica.
Incluye entidades para regiones, ciudades y comunas, pacientes, médicos y sus especialidades, diagnósticos, recetas médicas, medicamentos (con stock y precio unitario), dosis prescritas, métodos y medios de pago, bancos y digitadores encargados del registro.
Las relaciones y restricciones (PK, FK, UNIQUE, CHECK e IDENTITY) garantizan la integridad referencial, la validez de datos clave (como RUT y teléfonos únicos) y el cumplimiento de reglas de negocio del consultorio

### Objetivo general

- Representar de forma estructurada y consistente la información clínica y administrativa del consultorio.
- Permitir registrar para cada paciente sus datos personales y de contacto, su comuna y la relación con médicos y diagnósticos recibidos.
- Soportar la emisión de recetas con un diagnóstico asociado y uno o más medicamentos, controlando dosis, días de tratamiento, stock disponible y precio unitario.
- Gestionar los pagos asociados a las recetas, registrando el método de pago y el banco correspondiente, asegurando que cada pago se vincule a una receta específica.
- Facilitar consultas posteriores (informes, estadísticas, control de stock, trazabilidad de atención) mediante un diseño normalizado y fácilmente explotable por aplicaciones o reportes.

---
## 👤 Autores del proyecto
- **Nombre completo:** Matias Suarez M. / Sebastian Rodriguez R.
- **Ramo:** Modelamiento de Bases de Datos
- **Grupo:** Grupo N°10
- **Sección:** 001A
- **Profesor:** Armando Romero M.
- **Carrera:** Analista Programador Computacional
- **Sede:** Carrera 100% Online
