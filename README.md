graph TD
    Start((Inicio de la<br>Infección)) --> A

    A[1. INGESTIÓN<br>Consumo de alimentos contaminados:<br>- Aves crudas/mal cocidas<br>- Leche no pasteurizada<br>- Agua contaminada]
    
    A --> B[2. ENTRADA AL ESTÓMAGO<br>La bacteria ingresa al sistema digestivo<br>y se enfrenta al ambiente ácido<br>pH muy bajo del estómago]
    
    B --> C[3. SOBREVIVENCIA ÁCIDO ESTOMACAL<br>La bacteria utiliza mecanismos de<br>resistencia para sobrevivir al<br>ambiente ácido del estómago]
    
    C --> D[4. LLEGADA AL INTESTINO<br>La bacteria alcanza el intestino donde<br>encuentra condiciones favorables<br>para la colonización]
    
    D --> E[5. MOVILIDAD Y DIRECCIONAMIENTO<br>Uso de estructuras especializadas<br>para moverse y localizar<br>células objetivo]
    E -->|Flagelo Polar| E1[Movimiento en moco intestinal:<br>- Permite atravesar la capa de moco<br>- Facilita el acceso al epitelio<br>- Proporciona movilidad dirigida]
    E -->|Quimiotaxis| E2[Detección de nutrientes:<br>- Proteínas Tlps detectan aminoácidos<br>- Guían hacia células epiteliales<br>- Optimizan la colonización]
    
    D --> F[6. ADHESIÓN EPITELIAL<br>Unión a las células del<br>epitelio intestinal]
    F -->|Proteínas CadF y FlpA| F1[Unión a fibronectina:<br>- Anclaje específico a células<br>- Adhesión firme al epitelio<br>- Inicio de colonización]
    F -->|Cápsula Polisacárida CPS| F2[Protección inmune:<br>- Barrera contra defensas<br>- Evasión del sistema inmune<br>- Supervivencia aumentada]
    F -->|Lipopolisacáridos LOS| F3[Interacción con huésped:<br>- Facilita adhesión<br>- Modula respuesta inmune<br>- Puede causar respuestas severas]
    
    F --> G[7. INVASIÓN CELULAR<br>Penetración en células<br>del huésped]
    G -->|Sistema T6SS| G1[Penetración celular:<br>- Adhesión avanzada<br>- Invasión efectiva<br>- Efectos citotóxicos]
    G -->|Proteínas CiaB/C/D| G2[Supervivencia intracelular:<br>- Secretadas por flagelo<br>- Facilitan entrada celular<br>- Apoyan supervivencia]
    G -->|Proteína FlaC| G3[Modulación inmune:<br>- Trabaja con CiaB<br>- Potencia invasión<br>- Modula respuesta inmune]
    
    G --> H[8. DAÑO CELULAR<br>Lesión a células del huésped]
    H -->|Toxina CDT| H1[Daño al ADN:<br>- Detiene ciclo celular<br>- Causa distensión<br>- Provoca muerte celular]
    H -->|Respuesta Inflamatoria| H2[Producción IL-8:<br>- Atrae leucocitos<br>- Causa inflamación<br>- Daño tisular]
    
    H --> I[9. MANIFESTACIONES CLÍNICAS<br>Desarrollo de síntomas y<br>posibles complicaciones]
    I --> I1[Síntomas Gastrointestinales]
    I --> I2[Complicaciones Sistémicas]
    
    I1 -->|Síntomas Agudos| J1[Manifestaciones GI:<br>- Diarrea sanguinolenta<br>- Dolor abdominal severo<br>- Fiebre alta<br>- Vómitos frecuentes<br>- Deshidratación]
    I2 -->|Complicaciones Post-infecciosas| J2[Secuelas graves:<br>- Síndrome Guillain-Barré<br>- Artritis reactiva<br>- Respuesta autoinmune<br>- Mimetismo molecular]
    
    style Start fill:#4CAF50,stroke:#333,stroke-width:2px
    style A fill:#E3F2FD,stroke:#333,stroke-width:2px
    style B fill:#E3F2FD,stroke:#333,stroke-width:2px
    style C fill:#E3F2FD,stroke:#333,stroke-width:2px
    style D fill:#E3F2FD,stroke:#333,stroke-width:2px
    style E fill:#E8EAF6,stroke:#333,stroke-width:2px
    style F fill:#E8EAF6,stroke:#333,stroke-width:2px
    style G fill:#E8EAF6,stroke:#333,stroke-width:2px
    style H fill:#FFF3E0,stroke:#333,stroke-width:2px
    style I fill:#FFEBEE,stroke:#333,stroke-width:2px
    
    style E1 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style E2 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style F1 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style F2 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style F3 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style G1 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style G2 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style G3 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style H1 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style H2 fill:#F5F5F5,stroke:#333,stroke-width:1px
    style J1 fill:#FFCDD2,stroke:#333,stroke-width:1px
    style J2 fill:#FFCDD2,stroke:#333,stroke-width:1px
