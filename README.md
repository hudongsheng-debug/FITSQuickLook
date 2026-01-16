# FITS QuickLook Version 2.1.20

FITS QuickLook is a lightweight macOS application designed for fast visualization and inspection of astronomical FITS images.  
It is especially tailored for large-scale spectroscopic survey data such as **LAMOST**.

## ✨ Features
## Version 1.0
- 🚀 **Fast FITS loading** for large astronomical images
- 🔍 **Quick inspection** of 2D FITS data without complex setup
- 📊 Optimized for **spectral image structures** commonly found in LAMOST data
- 🖥 Native macOS application with a simple and responsive interface
- 🧪 Ideal for **researchers, students, and engineers** working with astronomical data

## Version 1.2 New Features
- 🎨 Colormap support
Switch between Grayscale and Turbo colormaps for better contrast and feature visibility.
- Highlight clipping (vmax control)
Optionally clip high pixel values to a user-defined maximum to suppress bright outliers and enhance faint structures.
- 🔄 One-click view reset
Instantly reset zoom and pan to the original view for fast navigation during inspection.

## Version 1.3.0 New Features
- Fixed an issue where file status could incorrectly display as Idle
- Added on-image display of FITS image dimensions
- Updated the app icon with a refreshed design
- Added in-app display of the current app version
- Introduced collapsible control panels for a cleaner workspace
- Improved performance and reduced UI stuttering in some scenarios

## Version 1.3.1 New Features
- Added a warning dialog for invalid Clip Max values
- Fixed some performance stuttering issues

## Version 1.4.0 New Features
- Added user-defined range selection for zooming
- Improved axis display**

## Version 1.5.0 New Features
- Added a Profile Panel for inspecting image data along a single row or column.
- Users can select an individual row or column to view its intensity profile.
- The Profile Panel can be freely repositioned to avoid obscuring image content.

## Version 1.5.1 New Features
- Added a Lock feature to fix the currently selected row or column.
- Improved overall APP responsivene.

## Version 1.6.0 New Features
- The Profile Panel now displays basic statistics, including minimum, maximum, mean, and standard deviation.
- Added the ability to export the selected row or column profile as a CSV file.
- Improved interaction logic so that the selected row or column is determined directly from user selection, independent of control button positions.

## Version 1.7.0 New Features
- Added support for comparing multiple profile curves within the Profile Panel.
- Users can now remove individual profile curves or clear all pinned curves.
- Updated the Profile Panel toolbar layout:
- 1.Buttons are now con-only for a cleaner appearance.
- 2.Button functions are revealed on hove rfor improved usability.
- Added a Help button to explain the Profile Panel controls.
- Unified the Profile Panel size to remain consistent across different interaction states.

## Version 1.8.0 New Features
- Added show / hide toggle for each pinned profile.
- Profiles can now be temporarily hidden or displayed without removing them.
- Added support to export multiple profiles into a single CSV file.
- Improved internal file structure for better maintainability.

## Version 1.8.1 New Features
- Profile panel can now be resized to provide a larger viewing area for profile analysis.
- Added clear indication of the currently selected row or column.

## Version 1.9.0 New Features
This release marks the final update of our first-generation version.
- Added a crosshair overlay to improve spatial accuracy when inspecting pixels.
-  Added Profile view modes: Raw, Normalize, and Δ (adjacent difference), enabling enhanced edge detection and defect inspection.

## Version 2.1.20  New Features

**New Advanced Analysis Panel**

A powerful new workspace for quantitative analysis of FITS images.

**• Row Summation**

Sum pixel values across selected rows to generate 1D projections.

**• Column Summation**

Sum pixel values across selected columns for vertical projections.

**• Partial Range Support**

Define start and end positions to analyze only a specific region of interest.

**• Parametric Scan**

Automatically scan across a range using Start, End and Step to generate a full projection series.

**• Curve Color Picker**

Customize curve colors for clearer comparison and publication-ready plots.

**• Scrollable Axis**

When data exceeds the view width, drag to scroll along the axis while keeping global coordinates.

**• Export Projection to CSV**

Export row or column projections for use in Python, MATLAB or other analysis tools.

**• Crop & Export Raw Pixels**

Export raw pixel values from any user-defined rectangular region as CSV.

**• View Rotation**

Rotate the image by 90° steps for better orientation (display only — data remains unchanged).

**• New Logo**

Redesigned app logo for a cleaner and more modern look

• Added a new **Professional panel** with advanced FITS inspection tools

• Introduced optional distortion-correction features, including FITS export, keystone correction, and smile correction

• Added zoom support up to **200×** for detailed image inspection

• Improved compatibility with additional **FITS file formats**

• Reduced system requirements: iOS 15.0+, macOS 14.0+, visionOS 1.0+


## 🧠 Use Cases

- Rapid quality check of FITS images before pipeline processing
- Visual inspection of spectroscopic frames
- Educational demonstrations for astronomical data formats
- Lightweight alternative to full-featured analysis software


## 🛰 Supported Data

- Standard **FITS** image files (`.fits`, `.fit`)

## 🛠 Platform

- **macOS**
- Built with native macOS technologies
- No external dependencies required for basic usage


## 📦 Installation

FITS QuickLook is available on the Mac App Store.

## 🙌 Acknowledgements
	•	LAMOST project
	•   Weinmin Sun  &  Haiping Chen 

## Support

If you encounter issues or have suggestions, please open an issue on this repository or contact the developer.
