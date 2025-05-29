const miPlayList=[
    {
        titulo:"CODEANDO en silencio",
        url:"https://www.youtube.com/watch?v=pr2OHWcQgKM",
        resumen:"Vemos un poco el diagrama de flujo de datos de Lisa, y trataremos de ampliar sus funciones",
        tags:["apx","Lisa","programacion","diagramas de flujo"
        ],
        visto: true,
        dificultad:2,
    },
    {
        titulo:"El mejor lenguaje de programacion para empezar",
        url:"https://www.youtube.com/watch?v=bo3AnDcRY3o",
        resumen:"Vemos caracteristicas de javaScript como uno de los mejores lenguajes para comenzar a programar",
        tags:["apx","Lisa","programacion","java","lenguajes"
        ],
        visto: true,
        dificultad:1,
    },
    {
        titulo:"What is software architecture for?",
        url:"https://www.youtube.com/watch?v=KwQZfqX1LWs",
        resumen:"REvisamos los principios de la arquitectura de software y su desarrollo, a medida que nuestros soft se van haciendo mas grande",
        tags:["apx","estrucutura de datos","programacion","java","lenguajes"
        ],
        visto: true,
        dificultad:4,
    },
    {
        titulo:"Ruta de Aprendizaje para ser Arquitecto de Software",
        url:"https://www.youtube.com/watch?v=4La3bojn-W8",
        resumen:"Se habla de los puntos principales que debe ver cualquier futuro arquitecto de software",
        tags:["apx","estrucutura de datos","programacion","java","lenguajes"
        ],
        visto: true,
        dificultad:4,
    },
    {
        titulo:"Ruta de Aprendizaje para ser Arquitecto de Software",
        url:"https://www.youtube.com/watch?v=M4d3FXu9-3I",
        resumen:"En este video se cuenta toda la historia tecnologica durante la historia humana, hasta llegar a la era actual, y las super computadoras y tecnologias",
        tags:["apx","estrucutura de datos","programacion","java","lenguajes","historia","tecnologias"
        ],
        visto: true,
        dificultad:3,
    },
    {
        titulo:"TRUST YOURSELF AND NEW WAYS WILL BE OPENED [SELF-ESTEEM] [MOTIVATION] [PERSONAL GROWTH]",
        url:"https://www.youtube.com/watch?v=EMKZXF8J3FA",
        resumen:"Es un video de autosuperación, donde se ven las claves para poder mejorar la confianza en uno mismo y ver de otra manera los problemas que se presentan dia a dia",
        tags:["autosuperacion","crecimiento personal","espiritualidad"
        ],
        visto: true,
        dificultad:3,
    }
];
console.log("REPORTE");
console.log("Total de videos en la Play List:",miPlayList.length);
console.log("Primer video - Titulo:",miPlayList[0].titulo);
console.log("Primer video - URL:",miPlayList[0].url);
let cantidadvideos=miPlayList.length;
console.log(cantidadvideos);
console.log("Ultimo video - Titulo:",miPlayList[cantidadvideos-1].titulo);
console.log("Ultimo video - URL:",miPlayList[cantidadvideos-1].url);
