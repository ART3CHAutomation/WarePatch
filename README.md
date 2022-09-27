# WarePatch
This repo contains the development code for the WarePatch...


## Schedule
```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Adding GANTT diagram functionality to mermaid
    
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section Inicio
    Configuración de horarios disponibles trabajo APM            :done,    des1, 2022-08-20, 7d
    Definición del nombre de la organización                     :done,    des2, 2022-08-20, 7d
    Discusión del funcionamiento de un warehouse típico          :done,    des3, 2022-08-20, 7d
    
    Definición de la EDT                                         :done, des4,   after des1, 7d
    Definición de los roles de cada integrante                   :crit, done, des5,   after des1, 7d
    
    Definición del grado de automatización final                  :done, des6, after des4, 14d
    Exploración inicial de los programas a utilizar en el proyecto    :crit, done, des7, after des4, 14d
    Elaboración de Layout inicial sin automatización               :crit, done, des8, after des4, 14d
    Establecimiento de etapas de un sistema de warehouse y logística    :crit, done, des9, after des4, 14d
    Elaboración de tarea de reflexión sobre robotizar o no         :done, des10, after des4, 14d
    
    Simulación de propuesta sin automatizar en Tecnomatix              :crit, done, des11, after des10, 14d
    Elaboración de Layout de propuesta automatizada              :crit, done, des12, after des10, 14d
    Diseño del Layout de la celda robotizada encargada del paletizado       :crit, done, des13, after des10, 14d
    Definición de de lista de elementos y parámetros de la celda robotizada  :done, des14, after des10, 14d
    Modelado CAD del Layout de la propuesta automatizada en NX            :crit, done, des15, after des6, 14d
    Evaluación OEE para caso base                                :done, des16, after des6, 14d
    Elaboración de informe de diseño de celda robotizada         :crit, done, des17, after des6, 14d
```

## References
[^current]: [Mercado Libre current system](https://www.youtube.com/watch?v=NIaEmq3eqvk&ab_channel=MercadoEnv%C3%ADos)
