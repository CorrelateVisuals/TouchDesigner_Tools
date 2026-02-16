# SOP to Pointcloud

![SOP to Pointcloud Example](https://github.com/CorrelateVisuals/Touchdesigner_Tools/blob/main/SOP_To_Pointcloud/SOP_To_Pointcloud_Image.PNG?raw=true)

## Overview

In TouchDesigner, the SOP data type represents surface geometry. This tool transforms SOP data into the EXR file format, exporting point cloud data as an OpenEXR file. The resulting file stores 3D point positions, colors, and other attributes, making it suitable for high dynamic range (HDR) rendering and post-processing workflows.

## Features

- Convert SOP geometry to EXR pointcloud format
- Preserve point positions, colors, and custom attributes
- Export for use in external rendering and compositing software
- Maintain HDR color information

## Use Cases

- **Rendering Pipelines**: Export geometry for external renderers
- **VFX Workflows**: Integration with compositing software
- **Data Exchange**: Share 3D point data between applications
- **Archival**: Store geometry with high precision color data

## Technical Details

**OpenEXR** is an industry-standard high dynamic range image format developed by Industrial Light & Magic. It supports:
- High precision floating-point data
- Multiple channels and layers
- Arbitrary metadata
- Lossless or lossy compression

## Workflow

1. Create or import SOP geometry in TouchDesigner
2. Configure export parameters (attributes, compression, etc.)
3. Export to EXR format
4. Use the pointcloud in external software or re-import for further processing

## Supported Attributes

- Position (XYZ coordinates)
- Color (RGB/RGBA)
- Normals
- Custom point attributes
- Texture coordinates (UV)

## Applications

- Film and television VFX production
- Game development asset pipelines
- Scientific visualization
- Architectural visualization
