# Directores_Educaci-n_Superior_Mex

Construye un archivo con datos de 2403 instituciones de educación superior en México. Las variables son nombre y sexo del funcionario, y entidad federativa de la institución.  Los datos (menos sexo) fueron tomados de http://www.anuies.mx/html/diries/index.php consultada en junio de 2019.  El autor incluyó directores de facultades y escuelas de la UNAM que no estaban en la base de datos, y asignó el sexo del funcionario con base al grado académico (e.g. Dra., Mtra., Profra....); en casos sin grado o con ambigüedad se buscó esta información en el sitio de internet de la institución.  Como parte del preproceso de datos, se eliminaron del archivo todas instituciones cuyo director aparecía en dos o más instituciones.

Los datos están en el archivo directores_datos.csv; el código en R para visualizarlos está en directores.R

MCB, Londres, 01.07.19
