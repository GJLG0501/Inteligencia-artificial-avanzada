# Entorno virtual para este proyecto

He creado un entorno virtual llamado `venv` en la raíz del proyecto.

Instrucciones de uso (Windows PowerShell):

1. Activar el entorno:

```powershell
.\\venv\\Scripts\\Activate.ps1
```

Si PowerShell bloquea la ejecución de scripts, ejecutar (una vez):

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

Instrucciones (CMD):

```cmd
.\\venv\\Scripts\\activate.bat
```

Instalar dependencias desde `requirements.txt`:

```powershell
pip install -r requirements.txt
```

Agregar una librería y actualizar `requirements.txt`:

```powershell
pip install <paquete>
pip freeze > requirements.txt
```

Desactivar el entorno:

```powershell
deactivate
```

Si necesitas que yo instale paquetes concretos, dime cuáles y los añado.
