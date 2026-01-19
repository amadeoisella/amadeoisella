# Revisión de repositorio

## Estado del contenido recibido

- El directorio de trabajo solo contiene un `README.md` de perfil y **no** incluye el código del proyecto ecommerce solicitado.
- Se intentó acceder al repositorio remoto indicado (`https://github.com/Lucasauat/Backend-II.git`), pero la conexión fue bloqueada por el entorno con el error:
  - `fatal: unable to access 'https://github.com/Lucasauat/Backend-II.git/': CONNECT tunnel failed, response 403`

## Próximos pasos necesarios

Para completar la revisión y/o implementar el CRUD de usuarios, autenticación con JWT y estrategias de Passport, se requiere:

1. Que el repositorio correcto esté disponible en el entorno (clonado en este directorio), o
2. Que se proporcione acceso al repositorio remoto para poder clonarlo.

Una vez disponible el código, se podrá validar si cumple con:

- Modelo `User` con campos requeridos y contraseña en hash (bcrypt.hashSync).
- Estrategias de Passport (local + JWT).
- Login con JWT.
- Endpoint `/api/sessions/current` con validación por token.
