# 🔐 Cifrado App - Aplicación de Cifrado Seguro Personal

**Cifrado App** es una aplicación móvil desarrollada con **Apache Cordova**, diseñada para realizar operaciones de cifrado y descifrado de manera segura desde un dispositivo Android. Su objetivo principal es proteger la confidencialidad de textos, imágenes y videos directamente desde el teléfono, sin depender de servicios en la nube ni terceros.
![Screenshot_2025-06-16-13-41-51-001_com ejemplo cifradoapp](https://github.com/user-attachments/assets/b805e9f1-bb71-4394-970e-e23c7a5628ec)

---

## 📱 Funcionalidades principales

- 🔒 **Cifrado y descifrado de texto directo**
- 📷 **Captura y cifrado de imágenes desde la cámara**
- 🎥 **Cifrado y descifrado de archivos de video**
- 🛡️ **Módulo unificado para capturas multimedia cifradas**
- 🧩 Interfaz adaptable, intuitiva y enfocada en la simplicidad
- ✅ Compatibilidad completa con dispositivos Android modernos
![Screenshot_2025-06-16-13-41-54-979_com ejemplo cifradoapp](https://github.com/user-attachments/assets/d41b0c05-906a-4085-bf51-ff67e5ce24ac)

---

## 🛠️ Tecnologías utilizadas

- **Apache Cordova** (framework híbrido multiplataforma)
- **JavaScript** y HTML5
- **CryptoJS** y Web Crypto API para operaciones criptográficas
- **Cordova Plugins**:
  - `cordova-plugin-camera`
  - `cordova-plugin-file`
  - `cordova-plugin-android-permissions`
  - `cordova-plugin-media-capture`
  - `cordova-plugin-x-socialsharing`

---

## 🔐 Seguridad y privacidad

La aplicación fue diseñada desde el enfoque de **seguridad del lado del cliente**, implementando las siguientes buenas prácticas:

### ✔️ Buenas prácticas implementadas

- Las claves de cifrado son introducidas manualmente por el usuario y **no se almacenan en el dispositivo**.
- Se usan **algoritmos robustos** de cifrado (AES) con **salt**, **IV** y derivación de clave para reforzar la seguridad.
- Los datos cifrados quedan en control del usuario: se guardan localmente y pueden ser compartidos a través de medios seguros.
- El código fuente ha sido **minificado** para dificultar su ingeniería inversa.
- Se realiza validación dinámica de permisos y uso seguro del almacenamiento local.

---

## 🧪 Análisis de seguridad

Se realizó un análisis estático del APK con los siguientes resultados:

- ✅ No se detectaron claves embebidas ni fugas directas de información.
- ✅ Los archivos cifrados no pueden ser descifrados sin la clave correcta.
- ⚠️ Actualmente compilado en modo **debug**, solo para uso personal. En esta fase:
  - El APK no está firmado con clave de producción.
  - El código puede ser extraído y analizado con herramientas como jadx, apktool o mobSF.
- 🧩 No se permite actualmente la captura de pantalla en modo producción, pero puede añadirse como refuerzo adicional.

> 📌 **Nota:** Se recomienda compilar en modo `release` para distribución, firmar con clave privada, y aplicar técnicas de ofuscación avanzada si se desea distribuir públicamente.
![Screenshot_2025-06-11-16-21-13-636_com miui global packageinstaller](https://github.com/user-attachments/assets/1076f6ea-838a-4a49-a7d1-5a55009a431f)

---

## 👤 Autor

**Desarrollado por:** Andres Valdivieso P  
📍 Aplicación de uso personal y académico con fines de privacidad reforzada.  
🔒 Si deseas contribuir o aprender más sobre cifrado en aplicaciones móviles, puedes contactarme.

---

## ⚠️ Aviso legal

Esta aplicación fue desarrollada con fines educativos y personales. El uso de herramientas criptográficas debe estar en cumplimiento con las leyes locales e internacionales aplicables. El autor no se hace responsable del mal uso de la app.

