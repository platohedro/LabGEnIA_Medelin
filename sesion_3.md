
## Animación con AI

[Deforum](https://deforum.github.io/)

[Google Colab](https://colab.research.google.com/github/deforum-art/deforum-stable-diffusion/blob/main/Deforum_Stable_Diffusion.ipynb)

[Documentación Deforum](https://docs.google.com/document/d/1RrQv7FntzOuLg4ohjRZPVL7iptIyBhwwbcEYEW2OfcI/edit#heading=h.s2ihhcctvtj1)

[Parametros de Animación](https://deforum.github.io/animation.html)


### Sintaxis Deforum

~~~
translation_x: "0:(0.5), 40:(1.5), 60:(0), 80:(-0.6), 120:(-0.9)"


0 Es el frame

: Prepara el valor que le vamos a pasar al parametro

(0.5) Es la cantidad que se le da a este parametro en determinado frame

, La coma separa los frames 

~~~


## ANIMATION 

~~~
animation_mode: 2D 3D VIDEO INPUT

max_frames: cantidad de frames del vídeo
~~~

## Motion Parameters

~~~
zoom: 0:(1.04)
translation_x: 0:(10*sin(2*3.14*t/10))
translation_y: 0:(0)
translation_z: 0:(10)
rotation_3d_x: 0:(0)
rotation_3d_y: 0:(0)
rotation_3d_z: 0:(0)
~~~

## PARA VIDEO INPUT 

~~~
Video Input: RUTA DEL VIDEO EN EL DRIVE
~~~


## PROPMT 

~~~
# prompts
prompts = {
    0: "a beautiful lake by Asher Brown Durand, trending on Artstation",
    10: "a beautiful portrait of a woman by Artgerm, trending on Artstation",
}
~~~



## LOAD SETTINGS 

~~~
PARA VIDEO INPUT

SEED BEHAVOR → FIXED 

STRENG IMAGEN Y VIDEO 

STRENG   0 ES MAS VIDEO O IMAGEN 1 ES MAS PROMPT
~~~

# Noticias y Refeencias

[Informe de AI en latinoamerica](https://web.karisma.org.co/informe-sobre-politicas-de-inteligencia-artificial-y-derechos-de-autor-en-america-latina/)

[Mixo](https://app.mixo.io/)

[invideo](https://ai.invideo.io/)

[Lexica](https://lexica.art/)

[Video Inpating](https://shangchenzhou.com/projects/ProPainter/)

[idomoo](https://www.idomoo.ai/)

[kapwing](https://www.kapwing.com/)
