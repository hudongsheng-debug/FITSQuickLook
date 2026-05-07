# FITS QuickLook X Version 5.1.1

FITS QuickLook X is a lightweight macOS application designed for fast visualization and inspection of astronomical FITS images.  
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

**- Row Summation**

Sum pixel values across selected rows to generate 1D projections.

**- Column Summation**

Sum pixel values across selected columns for vertical projections.

**- Partial Range Support**

Define start and end positions to analyze only a specific region of interest.

**- Parametric Scan**

Automatically scan across a range using Start, End and Step to generate a full projection series.

**- Curve Color Picker**

Customize curve colors for clearer comparison and publication-ready plots.

**- Scrollable Axis**

When data exceeds the view width, drag to scroll along the axis while keeping global coordinates.

**- Export Projection to CSV**

Export row or column projections for use in Python, MATLAB or other analysis tools.

**- Crop & Export Raw Pixels**

Export raw pixel values from any user-defined rectangular region as CSV.

**- View Rotation**

Rotate the image by 90° steps for better orientation (display only — data remains unchanged).

**- New Logo**

Redesigned app logo for a cleaner and more modern look

- Added a new **Professional panel** with advanced FITS inspection tools

- Introduced optional distortion-correction features, including FITS export, keystone correction, and smile correction

- Added zoom support up to **200×** for detailed image inspection

- Improved compatibility with additional **FITS file formats**

- Reduced system requirements: iOS 15.0+, macOS 14.0+, visionOS 1.0+

## Version 2.1.21  New Features
-  Added a button to check for version updates.

## Version 2.2.17 New Features
**Interactive Plot Enhancements**

- Added crosshair inspection with real-time X/Y value display.

- Crosshair can optionally snap to the nearest data point in line plots for more precise reading.

- Support for mouse wheel / trackpad zoom on the X-axis, centered at the cursor position.

- Rectangle (box) zoom for intuitive range selection.

**Refined Plot Controls**

- Streamlined toolbar with compact icon-based controls.

- Dedicated reset action to quickly restore full plot ranges.

- Improved color selection workflow for plot styling.

**Enhanced Data Parsing**

- Added support for 1D Table FITS files that cannot be plotted,

enabling inspection in a parsed (non-plot) data view.

**Better User Guidance**

- Added contextual help explaining crosshair, zoom, and interaction gestures.

- Update notifications are now shown non-intrusively in the main toolbar.


## Version 3.1.1 New Features
### Back with a new update.
We’ve rethought our design direction — iOS now leads the experience.

This update includes:
- Redesigned interface for iPad and iPhone
- New launch screen
-  Updated app icon
- Color-coded tabs for file types
- Minimum window size support
- Improved toolbar layout and spacing

## Version 3.2.5 New Features
Back after three months with a focused round of improvements.

- Added a launch screen
- Improved minimization and window behavior
- Fixed lag when dragging the Profile panel
- Added an exit control to the Range panel
- Reset now properly restores both Profile and Range
- Refined Range panel behavior



## Version 3.2.7 New Features
This version is the final minor update for UI unification.

- “Professional” is now green, and the steps inside are also highlighted in green when active.
- Expanding “Tools” will automatically hide the section below.
- Improved overall smoothness and performance.

## Version 4.1.1 New Features
Introduces the Noise Region Detection model (Beta 1) to macOS.

- Added a “Noise Scan” button to the toolbar
- Noise Scan panel now supports minimization
- Noise Region Detection (Beta 1) is now available

## Version 4.2.3 New Features
This update brings the Noise Pixel Detection model (Beta 1) from iOS to macOS.

- Added a “Noise Pixel Detection” button to the toolbar
- The Noise Pixel Detection panel now supports minimization
- Introduced the Noise Pixel Detection model (Beta 1)
- Users can scan and annotate noise pixels within regions using adjustable thresholds
- Supports setting detected noise pixels to zero and saving as a new FITS file


## Version 4.3.1 New Features
This update introduces a new Compare feature for the Mac version.

- Added a Compare button to the toolbar
- Compare panel now supports minimized management
- Compare any opened FITS files
- Comparison opens in a new window, with support for synchronized or independent zoom and reset

## Version 4.4.2 New Features
Added new window analysis to the Profile panel, with support for exporting selected rows/columns to a separate window.

More Profile features coming soon.

## Version 4.5.6 New Features
In this update, we’ve added more features to the Profile panel in the new analysis window:

- Reset Zoom  
- Cursor readout  
- Export data to CSV  
- Auto-fit window height based on Y values  
- Grid lines and zero baseline  
- Vertical panning support  
- Pinch to zoom at the cursor location

## Version 4.6.3 New Features 
In this update, we’ve added three useful features to the Profile panel in the new analysis window:

- Crosshair support  
- Rectangular zoom  
- Y-axis scale on the left


## Version 4.7.2 New Features 
This update brings the new window analysis features from the Profile panel to the Advance panel.

- The Advance panel now includes all features from the Profile panel’s new window analysis  
- Fixed incorrect help documentation in the Advance panel
- Added descriptions for the new window analysis button in the Advance panel help documentation
- Updated the default curve color in the Advance panel to purple
- Replaced all “FITS QuickLook” references with “FITS QuickLook X”, including window titles and app display names


## Version 5.1.1 New Features 
This update brings more powerful new-window analysis features to the Profile and Advanced panels, along with a redesigned main interface for the Mac version.

Features

- Imported curves now support independent show/hide control.
- Imported curves can now be individually removed.
- X-axis ticks have been added to the new analysis window, with improved adaptation for different row/column display ranges.
- Multi-curve workflows now support simultaneous crosshair inspection.
- The Profile panel now supports difference calculation between two selected curves, with results displayed in the upper-left difference panel.
- The CSV button has been updated to export all curves together, while individual CSV export is now supported for each curve separately.

Interface

- The Mac main interface has been significantly redesigned with a new scrollable card-based file-opening workflow.
- Import backgrounds now support astronomy-inspired starfield visuals.
- External button icons have been redesigned with improved visual depth and selection scaling effects.
- Fixed a bug where the Reopen button became unavailable after closing non-2D FITS tabs.


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

FITS QuickLook X is available on the Mac App Store.

## 🙌 Acknowledgements
	-	LAMOST project
	-   Weinmin Sun  &  Haiping Chen 

## Support

If you encounter issues or have suggestions, please open an issue on this repository or contact the developer.
