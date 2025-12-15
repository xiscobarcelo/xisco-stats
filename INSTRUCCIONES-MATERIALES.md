# 📝 Guía de Personalización - Materiales de Xisco

## 🎯 Materiales por defecto actuales

Los materiales por defecto de Xisco son sus tacos de billar:
- **Velasco+Revo12.9** - Taco Velasco con flecha Revo 12.9
- **Lucasi+Revo12.9** - Taco Lucasi con flecha Revo 12.9
- **Bear+Centro** - Taco Bear con flecha Centro

## 🎯 Cómo cambiar los materiales por defecto

### Ubicación del código:
**Archivo:** `registro-partidos.html`
**Líneas:** 213-220 aproximadamente

### Código a modificar:

```javascript
let materials = [
    'Velasco+Revo12.9',  // ← Cambia esto
    'Lucasi+Revo12.9',   // ← Cambia esto
    'Bear+Centro'        // ← Cambia esto
];
```

---

## 💡 Ejemplos de personalización

### Ejemplo 1: Otros tacos de billar
```javascript
let materials = [
    'Predator+314-3',
    'McDermott G-Core',
    'Mezz WX700',
    'OB Cues Classic',
    'Cuetec Cynergy'
];
```

### Ejemplo 2: Diferentes flechas
```javascript
let materials = [
    'Velasco+Revo12.9',
    'Velasco+Z3',
    'Velasco+314-3',
    'Lucasi+Revo12.9',
    'Bear+Centro'
];
```

### Ejemplo 3: Tenis de mesa
```javascript
let materials = [
    'Pala Butterfly',
    'Pala Stiga',
    'Pala DHS',
    'Pelotas 3★',
    'Pelotas Entrenamiento'
];
```

### Ejemplo 4: Tenis
```javascript
let materials = [
    'Raqueta Wilson Pro',
    'Raqueta Babolat',
    'Raqueta Head',
    'Pelotas Wilson',
    'Pelotas Penn'
];
```

---

## ⚙️ Características adicionales

### 1. Añadir más materiales
Puedes añadir tantos como quieras:
```javascript
let materials = [
    'Material 1',
    'Material 2',
    'Material 3',
    'Material 4',
    'Material 5',
    'Material 6',
    'Material 7'
];
```

### 2. Añadir materiales desde la interfaz
También puedes añadir materiales directamente desde la página:
- Escribe el nombre en el campo "Añadir nuevo material"
- Click en "+ Añadir"
- Se guardará automáticamente

### 3. Los materiales se guardan
Una vez que cambies los materiales o añadas nuevos desde la interfaz:
- Se guardan en el navegador (localStorage)
- Se incluyen en el archivo data.json al descargar
- Permanecen disponibles en futuras sesiones

---

## 🔧 Pasos para modificar

1. Abre `registro-partidos.html` con un editor de texto
2. Busca la línea que dice: `// 🎯 MATERIALES POR DEFECTO`
3. Modifica los valores dentro del array `materials`
4. Guarda el archivo
5. Recarga la página en el navegador

---

## ⚠️ Notas importantes

- Los nombres pueden contener espacios y caracteres especiales
- No olvides las comas entre elementos
- Mantén las comillas simples `'` o dobles `"`
- El último elemento NO lleva coma al final

---

## 📞 ¿Necesitas ayuda?

Si tienes dudas o quieres personalizar algo más específico, 
solo pregunta y te ayudaré a modificarlo.
