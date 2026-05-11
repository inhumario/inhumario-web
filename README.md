# inhumario — landing

Landing pública de Inhumario (servicios de programación, automatización e IA a terceros).

## Stack
- HTML / CSS / JS estático.
- Nginx alpine vía Docker.
- Desplegada en EasyPanel (proyecto `travelia`).

## Desarrollo local
Abrir `index.html` en el navegador, o:

```bash
docker build -t inhumario-web .
docker run --rm -p 8080:80 inhumario-web
```

## Despliegue
Push a `main` y EasyPanel reconstruye desde Dockerfile.

## Contacto
cuadrado.mario@aromasdete.com
