# Instrucciones
Sólo correr el notebook denominado "sub_mv_zLGBM_E_001.ipynb". Se generará el archivo de prediccion y el submit para enviar al bot de Zulip. 
No es mucho, pero es lo mejor que pude hacer. A continuación algunas consideraciones: 
- La definición de los tratamientos de datos a aplicar está basada en los experimentos realizados por mí y registrados en[este Google Sheet](https://docs.google.com/spreadsheets/d/1SKPrqZj2ic3VVf6-FS58k-dqeQm0LwmJCJECiaOF0Ns/edit?usp=sharing)
- El undersampling se fijó en 0.25 basándome en los resultados de Orsi y Gómez. Para las prubas utilicé 0.05 para correr más rápido.
- Los parámetros de zLGBM están basados en el trabajo de Gustavo D.
- Se hizo un ensable 3 - semillerío, aunque me inclinaba por hacer 5 pero se me acaba el tiempo y Google está empecinado en matarme las máquinas virtuales antes que termine de correr. 





