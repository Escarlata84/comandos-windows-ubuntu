# Usuarios y permisos en Windows

- `whoami` → Muestra el usuario actual.
- `net user` → Lista usuarios del sistema.
- `net user <usuario> <contraseña> /add` → Crea un usuario.
- `net localgroup` → Lista grupos locales.
- `net localgroup Administradores <usuario> /add` → Agrega usuario a administradores.
- `runas /user:<usuario> cmd` → Ejecuta consola como otro usuario.
- `query user` → Muestra usuarios conectados.
- `logoff` → Cierra sesión de usuario.
- `gpresult /r` → Muestra políticas aplicadas al usuario.
- `icacls` → Muestra o cambia permisos de archivos.
