# Entrega 1 - Definición de lenguaje Ubicuo, dominios y contextos
## Grupo: Desacoplados
- MARIANA DIAZ ARENAS
- MANUEL GUILLERMO SANCHEZ BALLEN
- SERGIO ARTURO PEREZ RINCON
- JUAN NICOLAS MALAGON NAVARRO
## Documentación de dominios y sub-dominios
- Los dominios y sub-dominios fueron especificados en los siguientes documentos:
  -  [src/alpes-partners-as-is.cml](https://github.com/jmalagonn/MISW4406-Mapas-de-contexto/blob/main/src/main/cml/alpes-partners-as-is.cml)
  -  [src/alpes-partners-to-be.cml](https://github.com/jmalagonn/MISW4406-Mapas-de-contexto/blob/main/src/main/cml/alpes-partners-to-be.cml)
## Documentación del lenguaje ubicuo
### AS-IS
La documentación del lenguaje ubicuo AS-IS se puede consultar en el siguiente enlace [documentacion lenguaje ubicuo AS-IS](https://miro.com/app/board/uXjVJUhmRa0=/?share_link_id=48136594769)
<img alt="image" src="https://github.com/user-attachments/assets/7e9a686a-c44a-4c72-8a26-89289138a2a4" />
### TO-BE
La documentación del lenguaje ubicuo TO-BE se puede consultar en el siguiente enlace [documentacion lenguaje ubicuo TO-BE](#)

## Documentación de contextos acotados
La ejecución del proyecto se realizó utilizando los contenedores de desarrollo locales de VS Code, se recomienda que si se va a realizar una generación de gráficos, se haga de la misma forma.
### AS-IS
El mapa representa el sistema actual en forma de monolito, con cuatro contextos principales (Reportes, Marca, Pagos y Aliados). Las dependencias son simples y existe un único Shared Kernel entre Marca y Aliados. Refleja un modelo centralizado, con alto acoplamiento y poca flexibilidad para evolucionar.

El documento de definición se encuentra en la ruta ``src/main/images/alpes-partners_ContextMap-as-is.png``
<img width="2000" height="1400" alt="image" src="https://github.com/user-attachments/assets/e4899891-faff-4395-9503-62484efb6e86" />

### TO-BE
El mapa futuro describe la transición hacia una arquitectura distribuida con más contextos estratégicos (Marca, Influencers, Lealtad, Tracking, Afiliados, Aliados, Pagos y Compliance). Se incorporan dependencias bien definidas y varios Shared Kernels para mantener consistencia. Este diseño favorece la escalabilidad, la separación de responsabilidades y la evolución independiente de cada módulo.

El documento de definición se encuentra en la ruta ``src/main/images/alpes-partners_ContextMap-to-be.png``
<img width="2000" height="776" alt="alpes-partners_ContextMap-to-be" src="https://github.com/user-attachments/assets/ff81d1ef-52b3-4b7c-83eb-617316fb0b52" />


