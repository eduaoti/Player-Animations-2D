# Player Animations 2D  

## 1. Crear un nuevo proyecto en Unity  

1. Abre **Unity Hub**.  
2. Selecciona la versión más reciente disponible.  
3. En el cuadro de diálogo, elige la opción **2D RPG**.  
4. Escribe un nombre para el proyecto (ejemplo: `RPG`) y selecciona la ruta de almacenamiento.  
5. Haz clic en **CREATE** y espera a que Unity inicialice el proyecto.  

![Crear proyecto](https://github.com/user-attachments/assets/a2608716-bd6f-4808-ba98-1a63e1270253)  
👉 Aquí se selecciona la plantilla **2D RPG**, se nombra el proyecto y se define la ruta.  

![Configurar proyecto](https://github.com/user-attachments/assets/b1095c3f-daf7-4bcc-b45d-88f82936c91c)  
👉 Pantalla de carga donde Unity **inicializa el proyecto**.  

---

## 2. Crear la estructura de directorios  

![Estructura de directorios](https://github.com/user-attachments/assets/60b7d081-d8e6-4de7-9132-a194dd4d10b1)  
👉 Se crean carpetas para mantener el proyecto organizado:  
- **Animations**  
- **Prefabs**  
- **Scenes**  
- **Scripts**  
- **Sprites**  

---

## 3. Crear objetos en la escena  

![Crear objetos vacíos](https://github.com/user-attachments/assets/5b9931b2-0fc8-4040-b3b7-1fba2be5c046)  
👉 En la **Hierarchy** se crean dos objetos vacíos y se renombran como:  
- `PlayerObject` → Representa al jugador.  
- `EnemyObject` → Representa a los enemigos.  

---

## 4. Guardar la escena  

![Guardar escena](https://github.com/user-attachments/assets/abd009f5-5e1c-46c4-9cce-fc43aad7f71d)  
![Guardar en Scenes](https://github.com/user-attachments/assets/6c577701-bf73-4335-ab16-ac07c2b8b337)  
👉 Se crea una carpeta llamada **Scenes** y dentro se guarda la escena principal con el nombre **LevelOne**.  

---

## 5. Configuración de jerarquía y propiedades  

![Ref 1](https://github.com/user-attachments/assets/bc4b44fe-ca34-499c-bcd3-ad69cae702b3)  
![Ref 2](https://github.com/user-attachments/assets/4fdf308b-bd10-42de-b599-07a96dd8d8d5)  
👉 Se muestra cómo en el **Inspector** se configuran las propiedades (posición, escala, etc.) y cómo queda la jerarquía en Unity.  

---

## 6. Creación de componentes y organización  

![Ref 3](https://github.com/user-attachments/assets/bcac015b-d5a5-4242-a0b3-50a1de54b2e4)  
![Ref 4](https://github.com/user-attachments/assets/2b8fff33-6755-4f5a-a424-551b41bb1990)  
👉 Se agregan **componentes** a los objetos (Sprite Renderer, Rigidbody2D, Animator).  

---

## 7. Ajustes de animaciones y sprites  

![Ref 5](https://github.com/user-attachments/assets/867ee5c8-c9c7-471e-8198-6b112bcd869d)  
![Ref 6](https://github.com/user-attachments/assets/b9fdb954-f8f3-4875-a357-71a0c51e0bd4)  
![Ref 7](https://github.com/user-attachments/assets/567bfa09-1acb-43fb-9fb9-bdc690614166)  
![Ref 8](https://github.com/user-attachments/assets/5fc7f764-745d-49c3-8534-3a83c525108c)  
👉 Se importan **sprites y spritesheets**, se cortan en frames y se asignan al **Animator** para crear animaciones (caminar, atacar, etc.).  

---

## 8. Organización y prueba en el editor  

![Ref 9](https://github.com/user-attachments/assets/44b529d6-494c-4594-a132-6dc23b8413b2)  
![Ref 10](https://github.com/user-attachments/assets/11e9232a-875f-47d0-80a2-a4669b547ac7)  
![Ref 11](https://github.com/user-attachments/assets/4b6a4efe-c419-4b3c-a04a-4687650a4fe5)  
👉 La jerarquía ya aparece **organizada** con los objetos y animaciones añadidas.  

---

## 9. Configuración de más animaciones y prefabs  

![Ref 12](https://github.com/user-attachments/assets/9059e285-1081-42c3-9cee-0c4175265aa1)  
![Ref 13](https://github.com/user-attachments/assets/1d7b8658-8565-477d-9a93-e3d14fdf2fec)  
![Ref 14](https://github.com/user-attachments/assets/0eb54615-c1cd-4326-8c84-fc44f2fc9c74)  
![Ref 15](https://github.com/user-attachments/assets/7bf87f23-468c-4119-9a2a-421f8c8c2b4a)  
![Ref 16](https://github.com/user-attachments/assets/cf8f8574-064a-4ea3-9e7d-fa52b7fe46a4)  
![Ref 17](https://github.com/user-attachments/assets/5bffc4d1-6449-4cd0-ab3a-61272802d9e4)  
👉 Se crean y prueban **animaciones adicionales**, además de convertir objetos en **prefabs reutilizables**.  

---

## 10. Vista final del proyecto configurado  

![Ref 18](https://github.com/user-attachments/assets/0525ff8a-8eb4-4ac3-9b4d-dc2824d61c41)  
![Ref 19](https://github.com/user-attachments/assets/e0b3f2ff-965a-4229-86d3-402b0168f5f9)  
![Ref 20](https://github.com/user-attachments/assets/a86ae548-3f17-41ed-acba-41fd655b28e2)  
👉 Proyecto final listo: carpetas ordenadas, objetos configurados, animaciones creadas y prefabs preparados para usar.  
