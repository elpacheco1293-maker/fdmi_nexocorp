# NEXOCORP-FDMI · Generador de Transfer Orders

Web estática (sin build): genera el ZIP con `DosSupplyLinesInt.csv` + `DosDistributionDetailsInt.csv` para el ERP.

## Subir a GitHub (sin instalar nada)
1. Entra a github.com e inicia sesión. Clic en **+** > **New repository**.
2. Nombre: `nexocorp-transfer-orders`. Privado o público. Crear.
3. Clic en **uploading an existing file**.
4. Arrastra `index.html` y `logo.jpg` (descomprime antes el ZIP; sube los archivos, no la carpeta ni el .zip).
5. Clic en **Commit changes**.

## Publicar en Vercel
1. Entra a vercel.com > **Continue with GitHub**.
2. **Add New** > **Project** > en la lista elige `nexocorp-transfer-orders` > **Import**.
3. Framework Preset: **Other**. No toques Build Command ni Output Directory.
4. **Deploy**. En 1 minuto tendrás una URL tipo `nexocorp-transfer-orders.vercel.app`.

Para actualizar: en GitHub abre `index.html` > lápiz > pega el nuevo > Commit. Vercel publica solo.

Los datos (líneas y catálogo) quedan solo en el navegador de cada usuario.
