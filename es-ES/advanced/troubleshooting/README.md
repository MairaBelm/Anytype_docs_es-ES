# Solución de problemas

1. Asegúrate de que tu ordenador tiene la hora correcta. Si la hora local difiere en más de 2 horas, quizá no se pueda establecer una conexión.
2. Comprueba si estás usando un proxy, una VPN, un cortafuegos o una red empresarial para conectarte. Si es así, intenta conectarte sin usarlo para ver si hay alguna diferencia.
3. Intenta realizar la conexión fuera de redes corporativas o configuraciones similares.
4. Usa tu dispositivo móvil como punto de acceso Wi-Fi para el ordenador de escritorio e intenta conectarte de esa manera.
5. Prueba a iniciar sesión desde otro dispositivo (y desde otra red).

Problemas más específicos:

<details>

<summary>¿Cómo puedo compartir el registro de StackGoroutines si no puedo pasar del inicio de sesión en el móvil?</summary>

1. Si se produce un bloqueo en StartAccount, puedes [pulsar 5 veces «Entrar en mi arca»](https://drive.google.com/file/d/1V4muGfFDNDb98ZVp213-YmbnVv3Vx_tX/view?usp=drive_link).
2. El comando Rpc.Debug.StackGoroutines generará un archivo de registro.
3. Puedes enviarlo por el método que prefieras.

</details>

<details>

<summary>¿Qué puedo hacer si la app no refleja correctamente el espacio de almacenamiento?</summary>

Ve a `Depurar > Conciliar archivos` en la barra de menú superior y reinicia la aplicación.

</details>

<details>

<summary>¿Qué puedo hacer si no se me pide que elija mi nombre ANY tras pagar mi suscripción?</summary>

Escribe [anytype://main/membership](anytype://main/membership) en tu navegador o en la búsqueda global de Anytype y reinicia la aplicación.

</details>

<details>

<summary>¿Qué hago si tengo problemas gráficos?</summary>

Prueba a eliminar la carpeta GPUCache que se encuentra en `~/.config/anytype`.

</details>

<details>

<summary>¿Qué debo hacer si no puedo conectarme a la red de Anytype?</summary>

Puedes descargar y ejecutar nuestra herramienta AnySync Netcheck, que encontrarás [aquí](https://github.com/anyproto/any-sync-tools/tree/main/any-sync-netcheck) junto con las instrucciones de uso.

</details>
