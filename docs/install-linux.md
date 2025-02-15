### **Cómo instalar .NET 8 en Linux**

1. **Actualiza los repositorios**:
   Primero, asegúrate de tener la versión más reciente de los repositorios para instalar **.NET 8**.

   **Ubuntu/Debian**:
   ```bash
   sudo apt update
   sudo apt install -y dotnet-sdk-8.0
   ```

   **Fedora**:
   ```bash
   sudo dnf install dotnet-sdk-8.0
   ```

   **Arch Linux**:
   ```bash
   sudo pacman -S dotnet-sdk
   ```

2. **Verifica que .NET 8 esté instalado**:
   ```bash
   dotnet --version
   ```
   Si todo está correcto, debería mostrarte **8.x.x**.

