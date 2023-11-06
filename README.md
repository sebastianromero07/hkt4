# HKT 4

### Para este trabajo hemos usado un framework llamado DevExtreme con React como frontend mientras que el lado del backend es SpringBoot.

Para empezar, hemos hecho uso del postman para verificar que se ejecuta correctamente el backend y se obtiene la información correctamente.
Empezamos con el primer request de get que nos trae la lista de grupos:
![image](https://github.com/sebastianromero07/hkt4/assets/112716144/df7a67cf-eff7-49b1-8a79-4dc9da56ca79)

Y haciendo uso del ID podemos hacer otra request de get en base a ello:
![image](https://github.com/sebastianromero07/hkt4/assets/112716144/b65d2fe6-5253-4316-bea4-70ef00537499)

Adicionalmente, agregamos los métodos de post, para agregar nuevo grupo con las personas involucras y delete para borrar el grupo:
![image](https://github.com/sebastianromero07/hkt4/assets/112716144/56910130-23ba-468f-bec6-15fbcb0c122e)
![image](https://github.com/sebastianromero07/hkt4/assets/112716144/86cce85f-faf2-422d-b71a-6187efdd9cf8)


Visualmente para la persona que lo verá desde la interfaz (frontend), se evidencia de la siguiente manera:
![image](https://github.com/sebastianromero07/hkt4/assets/112716144/df5428cf-ff88-4b89-95ef-154d30dda898)


## ¿Cómo conectar el frontend con el backend?

Hemos usado una clase llamada CorsConfig que implementa el uso de una clase llamada WebMvcConfigurer
![image](https://github.com/sebastianromero07/hkt4/assets/112716144/590de485-0a25-4acb-81f5-974ca365bce1)
Y por último, el uso de la librería Axios para extrar la data al servidor:
![image](https://github.com/sebastianromero07/hkt4/assets/112716144/e53dc7a9-279e-4dc0-a83f-7928a5a52875)
