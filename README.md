# 🛡️ Area Calculator Plugin - QGIS Extension

This project is a **QGIS plugin** that provides a fast and accurate way to calculate the area of selected geometries. Designed for GIS professionals and analysts, it offers an intuitive interface and efficient computation.

## 🚀 Features

- Calculate the area of selected geometries in different units.
- Supports multiple geometry types (polygons, multipolygons).
- Provides real-time area calculations.
- Compatible with various QGIS versions.
- Simple and efficient user interface.

## 🔧 Technologies Used

- **Programming Language:** Python
- **GIS Framework:** QGIS API
- **Dependencies:** PyQGIS, GDAL, Shapely

## 🛠️ Installation

1. Open QGIS and navigate to **Plugins > Manage and Install Plugins**.
2. Click on the **Install from ZIP** option.
3. Select the `area_calculator.zip` file and install.
4. Activate the plugin from **Plugins > Installed**.
5. The plugin is now available in the QGIS interface.

## 🛠️ Usage

1. Select the desired polygons from your layer.
2. Open the **Area Calculator** plugin from the QGIS toolbar.
3. Choose the desired area unit (square meters, hectares, etc.).
4. Click **Calculate** to view the results.
5. Export the calculated values if needed.

## 📁 File Structure
```
├── area_calculator       # Plugin directory
│   ├── __init__.py       # Plugin initializer
│   ├── area_calculator.py  # Main functionality
│   ├── metadata.txt      # Plugin metadata
│   ├── resources.qrc     # UI resources
│   ├── ui_area_dialog.py # UI dialog file
```

## 📜 License

This project is distributed under the **MIT license** and is open for public use.


# 🛡️ Corner Viewer Plugin - QGIS Extension

This project is a **QGIS plugin** designed to display and analyze the corner coordinates of selected geometries. It is specifically developed for GIS analysts who require precise corner data for spatial analysis and mapping.

## 🚀 Features

- Extracts corner coordinates of selected polygons.
- Supports multiple geometry types, including polygons, multipolygons, and rectangles.
- Displays real-time coordinate values.
- Provides an option to export results.
- User-friendly and efficient interface.

## 🔧 Technologies Used

- **Programming Language:** Python
- **GIS Framework:** QGIS API
- **Dependencies:** PyQGIS, GDAL, Shapely

## 🛠️ Installation

1. Open QGIS and navigate to **Plugins > Manage and Install Plugins**.
2. Click on **Install from ZIP**.
3. Select the `corner_viewer.zip` file and install it.
4. Activate the plugin from **Plugins > Installed**.
5. The plugin is now available in the QGIS interface.

## 🛠️ Usage

1. Select the desired polygons from your layer.
2. Open the **Corner Viewer** plugin from the QGIS toolbar.
3. The plugin will automatically display the corner coordinates.
4. Export the coordinate values if needed.

## 📁 File Structure

```
├── corner_viewer        # Plugin directory
│   ├── __init__.py       # Plugin initializer
│   ├── corner_viewer.py  # Main functionality
│   ├── metadata.txt      # Plugin metadata
│   ├── resources.qrc     # UI resources
│   ├── ui_corner_dialog.py # UI dialog file
```

## 📜 License

This project is distributed under the **MIT license** and is open for public use.
