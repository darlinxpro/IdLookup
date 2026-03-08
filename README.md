# ID Lookup

BNGO2 ID Lookup es una herramienta web diseñada para **buscar y copiar los ID de los ítems** del juego BNGO2. Permite **enviar ítems a los jugadores** en el chat del juego con el ID correcto y un Player ID específico.

🔗 **Sitio Web:**  
👉 [ID Lookup](https://darlinxpro.github.io/IdLookup/)

## 🚀 Funcionalidades
✔ **Búsqueda de IDs**: Filtra ítems usando un campo de búsqueda.  
✔ **Búsqueda por estrellas**: Escribe **R1-R9** para filtrar por número de estrellas (ej: R8 muestra todos los 8★).  
✔ **Búsqueda combinada**: Escribe **nombre + R + número** para buscar un personaje específico con cierta estrella (ej: "titan r8").  
✔ **Infinite Scroll**: Carga más ítems a medida que el usuario baja en la lista.  
✔ **Copia rápida**: Al hacer clic en "Copiar", el ID del ítem y el Player ID se copian al portapapeles en el formato correcto.  
✔ **Confirmación visual**: Un mensaje debajo de la fila muestra qué se copió, junto con una barra de progreso.  
✔ **Footer fijo**: Indica que la herramienta está *Powered by Darlinxpro*.  

## 🔧 Cómo usar
1. **Ingresa el Player ID** en el campo correspondiente.  
2. **Busca el ítem** por su ID o nombre en el campo de búsqueda.  
3. **Usa atajos de estrellas**:
   - Escribe **R8** para ver todos los items con 8★
   - Escribe **titan r8** para buscar "Titan 8★"
4. **Haz clic en "Copiar"** para copiar el ID y enviarlo en el chat del juego en el formato correcto.  
5. **El mensaje de confirmación aparecerá** debajo de la línea copiada y desaparecerá después de 3 segundos.  

## 📌 Formato de copia
Cuando copias un ítem, el portapapeles contendrá lo siguiente:
/giveuser PlayerID IdItem 1

Ejemplo:
/giveuser 2240 10 1

## ⚠ Problemas conocidos
🔹 Algunos bugs afectan la **precisión del scroll infinito**, por lo que ciertos ítems pueden no mostrarse.  
🔹 **Mejoras en el rendimiento** serán agregadas para optimizar la carga de datos.  
🔹 **Correcciones de filtrado** para asegurar que todos los ítems sean encontrados, aunque no estén visibles de inmediato.  

## 📂 Instalación y uso local
Si deseas usar la herramienta localmente:
1. Clona este repositorio:  https://github.com/darlinxpro/IdLookup.git
2. Abre `index.html` en tu navegador.
3. Y usa el archivo como desees.

## 👨‍💻 Contribuir
Si deseas ayudar a mejorar esta herramienta, ¡los pull requests son bienvenidos! 💡

---
✨ **Powered by Darlinxpro** ✨
