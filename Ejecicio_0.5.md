```mermaid
sequenceDiagram
    participant Navegador
    participant Servidor

    Navegador->>Servidor: GET / index.html
    Servidor->>Navegador: index.html
    Navegador->>Servidor: GET app. js, styles.css
    Servidor->>Navegador: JS y CSS 
    Navegador->>Servidor: GET datos desde la API
    Servidor->>Navegador: JSON com datos
    Navegador->>Servidor: Actualiza la vista sin recargar
```

