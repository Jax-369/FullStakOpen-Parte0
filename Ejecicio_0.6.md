```mermaid 
sequenceDiagram
    participant Usuario
    participant Navegador
    participant Servidor 

    Usuario->>Navegador:Escribe nota y hace clic
    Navegador->>Servidor: POST /api/notes
    Servidor->>Navegador: 201 Created
    Navegador->>Usuario: Muestra nueva nota sin recargaraaaa6
