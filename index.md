# Política de Privacidad - Sunly Reminder

**Última actualización:** 28 de abril de 2026

Esta política describe qué datos recoge la aplicación **Sunly Reminder** ("la app"), cómo se utilizan y los derechos del usuario.

## 1. Información que recogemos

### 1.1 Cuando inicias sesión con Google (opcional)
Si decides iniciar sesión con tu cuenta de Google para sincronizar tus datos entre dispositivos, recibimos:
- Tu correo electrónico
- Tu nombre público de Google
- Tu foto de perfil de Google
- Un identificador único de usuario (UID)

Estos datos los proporciona Google a través del servicio Google Sign-In y se utilizan únicamente para identificarte y vincular tus tareas/recordatorios a tu cuenta.

### 1.2 Datos generados por ti dentro de la app
Cuando creas tareas, recordatorios o ajustes, almacenamos:
- Título y descripción de la tarea
- Hora y fecha del recordatorio
- Emoji asociado (si lo agregaste)
- Estado (completado / pendiente)
- Configuraciones de la app (idioma, tema, modo de sonido)

Si **no** has iniciado sesión, estos datos se guardan únicamente en tu dispositivo y no salen de él.

Si **sí** has iniciado sesión con Google, estos datos se sincronizan con Google Cloud Firestore (servicio de Firebase, propiedad de Google) para que estén disponibles en tus otros dispositivos donde uses la misma cuenta.

### 1.3 Datos que **no** recogemos
- No recogemos tu ubicación.
- No recogemos información sobre tu uso de otras apps.
- No recogemos datos de tu agenda telefónica ni mensajes.
- No usamos rastreadores publicitarios ni analíticas de terceros.

## 2. Permisos del dispositivo

La app solicita los siguientes permisos solo para las funciones indicadas:

- **Notificaciones**: para mostrarte recordatorios a la hora programada.
- **Micrófono**: solo cuando uses el asistente de voz para crear tareas. El audio se procesa por el servicio de reconocimiento de voz del sistema operativo y **no se sube a nuestros servidores ni se almacena**.
- **Biometría / huella digital**: opcional, solo si activas el bloqueo de la app. No se transmite ni se almacena ningún dato biométrico — la verificación la hace tu propio dispositivo.
- **Internet**: necesario para iniciar sesión con Google y sincronizar datos.

## 3. Almacenamiento y seguridad

- Los datos sincronizados se almacenan en servidores de Google Cloud Firestore (Firebase) bajo las medidas de seguridad de Google.
- Si configuras un PIN de bloqueo, este se almacena cifrado (hash SHA-256 con sal) localmente en tu dispositivo. Nunca enviamos tu PIN.
- La comunicación con Firebase usa HTTPS/TLS.

## 4. Compartir datos con terceros

**No vendemos, alquilamos ni compartimos tu información con terceros con fines publicitarios.**

Los únicos terceros que procesan datos en nombre del servicio son:
- **Google Firebase / Firestore** — almacenamiento sincronizado (solo si inicias sesión).
- **Google Sign-In** — autenticación.

Estos servicios están sujetos a la [Política de Privacidad de Google](https://policies.google.com/privacy).

## 5. Tus derechos

Puedes en cualquier momento:
- **Cerrar sesión**: tus datos quedan solo en el dispositivo.
- **Borrar tu cuenta y datos**: solicita la eliminación enviando un correo a la dirección de contacto al final de esta política. Eliminaremos todos tus datos asociados en un plazo máximo de 30 días.
- **Exportar tus datos**: puedes compartir tareas como archivos `.ics` desde la propia app.

## 6. Niños

La app no está dirigida a menores de 13 años. No recogemos a sabiendas datos de menores. Si crees que un menor nos ha proporcionado información, contáctanos para eliminarla.

## 7. Cambios en esta política

Si hacemos cambios sustanciales, actualizaremos la fecha al inicio de este documento y, cuando sea relevante, notificaremos en la app.

## 8. Contacto

Para cualquier pregunta o solicitud relacionada con tus datos:

**Correo electrónico:** stremeros69@gmail.com
**Responsable:** Sunly Reminder

---

# Privacy Policy - Sunly Reminder (English)

**Last updated:** April 28, 2026

This policy describes what data the **Sunly Reminder** application ("the app") collects, how it is used, and the user's rights.

## 1. Information we collect

### 1.1 When you sign in with Google (optional)
If you sign in with your Google account to sync your data across devices, we receive:
- Your email address
- Your public Google name
- Your Google profile picture
- A unique user identifier (UID)

This data is provided by Google through the Google Sign-In service and is used solely to identify you and link your tasks/reminders to your account.

### 1.2 Data you create within the app
When you create tasks, reminders, or settings, we store:
- Task title and description
- Reminder time and date
- Associated emoji (if any)
- Status (completed / pending)
- App settings (language, theme, sound mode)

If you are **not** signed in, this data is saved locally on your device only.

If you **are** signed in with Google, this data is synced to Google Cloud Firestore (Firebase, owned by Google) so it is available on other devices using the same account.

### 1.3 What we do **not** collect
- We do not collect your location.
- We do not track your use of other apps.
- We do not access your contacts or messages.
- We do not use advertising trackers or third-party analytics.

## 2. Device permissions

- **Notifications**: to show reminders at the scheduled time.
- **Microphone**: only when using the voice assistant. Audio is processed by the OS speech-recognition service and **is never uploaded to our servers or stored**.
- **Biometrics / fingerprint**: optional, only if you enable app lock. No biometric data is transmitted — verification happens on your device.
- **Internet**: required for Google Sign-In and data sync.

## 3. Storage and security

- Synced data is stored on Google Cloud Firestore servers under Google's security measures.
- If you set a PIN, it is stored hashed (SHA-256 with salt) locally on your device. We never transmit your PIN.
- All Firebase communication uses HTTPS/TLS.

## 4. Sharing with third parties

**We do not sell, rent, or share your information with third parties for advertising purposes.**

The only third parties that process data on behalf of the service are:
- **Google Firebase / Firestore** — synced storage (only if you sign in).
- **Google Sign-In** — authentication.

These services are subject to [Google's Privacy Policy](https://policies.google.com/privacy).

## 5. Your rights

You can at any time:
- **Sign out**: your data remains only on the device.
- **Delete your account and data**: request deletion by emailing the address at the bottom. We will remove all associated data within 30 days.
- **Export your data**: you can share tasks as `.ics` files from the app.

## 6. Children

The app is not directed at children under 13. We do not knowingly collect data from minors.

## 7. Changes

If we make significant changes, we will update the date at the top of this document.

## 8. Contact

**Email:** stremeros69@gmail.com
**Provider:** Sunly Reminder
