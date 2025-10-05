# Geo-Planeta Urbano

Proyecto MVP: aplicación web y móvil para planificación urbana basada en datos satelitales.

Resumen rápido:
- Frontend: React + Leaflet (mapas interactivos, capas, slider comparador, reportes ciudadanos).
- Backend: Node + Express (endpoints GeoJSON, almacenamiento simple de reportes, export CSV).
- Mobile: guía para app Expo (React Native) para reportes desde móvil.
- Datos: plantillas y documentación para integrar EarthData, Google Earth Engine y Microsoft Planetary Computer.

Cómo empezar (Windows PowerShell):

1) Backend

```powershell
cd "c:/Users/user/OneDrive/Escritorio/app,eco/geo-planeta-urbano/backend"
npm install
npm start
```

2) Frontend

```powershell
cd "c:/Users/user/OneDrive/Escritorio/app,eco/geo-planeta-urbano/frontend"
npm install
npm run dev
```

3) Mobile (opcional - Expo)

Sigue las instrucciones en `mobile/README-mobile.md`.

Notas:
- Este repositorio es un MVP con stubs para integración de datos satelitales y modelos ML. Los accesos a Earthdata, Planetary Computer y GEE requieren credenciales; ver `docs/data_integration.md`.
- Traducciones: se incluye un ejemplo con i18next.
