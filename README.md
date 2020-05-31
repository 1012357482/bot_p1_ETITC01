# bot_p1_ETITC01
Documentos para importar a DialogFlow

El chat

El proyecto "chatbot tornicasso", tiene como propósito implementar un agente inteligente, que atienda las solicitudes de los ciudadanos, solucinando dudas, preguntas y cuestiones correspondientes a la ETITC.

La arquitectura del proyecto se compone, básicamente de tres factores, los cuales son:

procesamiento del lenguaje natural: Dialogflow de google, proporciona este servicio, de momento en su capa gratuita.

Lógica de Negocio: Este servicio es llevado a cabo, por el webhook, un webhook es generalmente un script(node.js, java, python entre otros) ofreciendo funcionalidades al chatbot (Redireccionamiento de datos para almacenamiento y procesamiento). En dialogflow se interactua con el webhook, por medio de archivos json. No es exagerado decir, que en esencia, es el alma del chatbot.

Almacenamiento: Aunque el desarrollo en una base sql es el común por estos días, el servicio firebase de google provee almacenamiento en tiempo real tanto para base sql como bases no sql.

El sitio aún esta en construcción, por lo que no es responsive, si desea probar las funcionalidades del chatbot, en un dispositivo movíl, lo invitamos a conectarse al siguiente canal de telegram ""
