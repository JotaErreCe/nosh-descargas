# Nosh

Nosh escucha tus reuniones en tu Mac y te dice qué prometió cada quien y para cuándo. Los recordatorios son solo para ti.

## Descargar

**[Descargar Nosh para Mac](https://github.com/JotaErreCe/nosh-descargas/releases/latest/download/Nosh.dmg)** (versión de prueba)

## Qué necesitas

- Una Mac con chip de Apple (M1 o más nueva).
- macOS 14.4 o más nuevo.
- Unos 2 GB libres.

## Cómo instalarla

1. Abre `Nosh.dmg` y arrastra **Nosh** a **Aplicaciones**.
2. La primera vez, haz clic derecho sobre Nosh y elige **Abrir**. Si la Mac no te deja, ve a **Ajustes del Sistema > Privacidad y seguridad** y pulsa **Abrir de todos modos**. Esto pasa porque la app todavía no lleva la firma de Apple.
3. Sigue la bienvenida: escribe tu nombre y pulsa **Permitir** en cada aviso.

Si sale "Nosh está dañado y no se puede abrir": abre la app Terminal, pega `xattr -cr /Applications/Nosh.app`, presiona Enter y vuelve a abrir Nosh.

## Tu privacidad

El audio y la transcripción se quedan en tu Mac. Para el resumen y los pendientes, el texto de la reunión se envía a Claude (Anthropic). No se guarda ni se usa para entrenar. El audio se borra solo a los 30 días. Avisa siempre a los demás antes de grabar.
