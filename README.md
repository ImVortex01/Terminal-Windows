# Comandos útiles para el terminal de Windows

> [!WARNING]
> Algunos comandos pueden requerir permisos de administrador para ejecutarse correctamente.

## Navegación y Gestión de Archivos

- **cd**: Cambia el directorio actual.
  ```cmd
  cd [ruta_del_directorio]
  ```

- **dir**: Lista los archivos y directorios en el directorio actual.
  ```cmd
  dir
  ```

- **mkdir**: Crea un nuevo directorio.
  ```cmd
  mkdir [nombre_del_directorio]
  ```

  - **notepad**: Puedes abrir Notepad desde la terminal y crear un nuevo archivo
  ```cmd
  notepad archivo.txt
  ```

- **del**: Elimina un archivo.
  ```cmd
  del [nombre_del_archivo]
  ```

- **rd**: Elimina un directorio.
  ```cmd
  rd [nombre_del_directorio]
  ```

## Gestión de Procesos

- **tasklist**: Lista todos los procesos en ejecución.
  ```cmd
  tasklist
  ```

- **taskkill**: Termina un proceso mediante su ID.
  ```cmd
  taskkill /PID [ID_del_proceso] /F
  ```

## Redes

- **ping**: Envía paquetes de datos a una dirección IP para probar la conectividad.
  ```cmd
  ping [dirección_ip_o_nombre_de_host]
  ```

- **ipconfig**: Muestra la configuración de red del equipo.
  ```cmd
  ipconfig
  ```
  
- **netstat**: Muestra las estadísticas del protocolo y las conexiones TCP/IP
  ```cmd
  netstat
  ```

- **getmac**: Devuelve la dirección del control de acceso multimedia (MAC).
  ```cmd
  getmac
  ```

## Otros Comandos Útiles

- **cls**: Limpia la pantalla del terminal.
  ```cmd
  cls
  ```

- **echo**: Muestra mensajes en el terminal o redirige la salida a un archivo.
  ```cmd
  echo [mensaje]
  ```
  
- **winget list**: Lista todas las aplicaciones instaladas.
  ```cmd
  winget list
  ```

- **winget upgrade --all**: Actualiza todas las aplicaciones instaladas.
  ```cmd
  winget upgrade --all
  ```
