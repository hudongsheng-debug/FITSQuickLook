# FITS QuickLook Studio Version 8.1.6

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


## Version 5.1.6 New Features 
### More powerful than ever before
We strongly recommend all users update to this version.

With this update, we aimed to make the app feel even more like a native Mac application. Thank you for your continued support.

- Redesigned the app icon with reduced corner radius  
- Redesigned the Tools & AI menu using a sidebar-style layout  
- Redesigned the minimize button and its placement  
- Updated the HUD position  
- Redesigned the Profile panel, moved function buttons into the sidebar, and adjusted window sizing  
- Redesigned the Advance panel and moved functions into the sidebar  
- Added Zoom Range support to the Profile and Advance panels, allowing users to view images by entering a range  
- Updated the launch screen effects  
- Added a Help button and reorganized tools into functional groups


## Version 5.1.8 New Features

- Added keyboard shortcuts for Profile and Advanced panel actions.
- Removed duplicate buttons in the Profile panel.
- Improved overall stability and performance.

## Version 5.1.10 New Features

This update focuses on refining the design of the Mac interface.

- Fixed an issue where the version number was displayed incorrectly on the launch screen  
- Updated the launch screen and main window backgrounds to a darker appearance for better visual consistency  
- Removed the top toolbar buttons. Import, Tools, and Information are now available from the menu bar  
- Adjusted the size of the Tools & AI buttons and centered them with their labels  
- Reduced the saturation of the selected tab color  
- Added keyboard shortcuts for the Tools & AI buttons


## Version 5.1.15 New Features
- Fixed an issue in Open New Window Analysis where multiple curves could appear with the same color. Curves are now displayed with properly differentiated colors.
- Added direct Row / Column input support for New Window Analysis, allowing specific rows or columns to be opened instantly for faster spectral analysis.



## Version 5.2.6 New Features
- Added a new FFT analysis workspace for row/column frequency analysis
- Added Log Scale, FFT Shift, Peak Detection, and PSD modes for FFT visualization
- Added interactive FFT zooming and panning with trackpad/mouse gestures
- Added FFT CSV export support for external scientific analysis workflows
- Added ROI Image workspace support for localized image analysis
- Added Advanced multi-range curve analysis for simultaneous summed profile comparison
- Added Tools menu shortcuts for ROI and FFT panels
- Improved Advanced analysis workflow with clearer single-curve and multi-curve behaviors
- Fixed Open Window color synchronization issues between pinned and newly opened curves

## Version 5.3.9 New Features
- Added multi-row / multi-column selection support in Matrix Workspace
- Added Multi Select mode for plotting multiple Row / Column profiles simultaneously
- Added multi-row / multi-column sum analysis (Sum Plot)
- Added full row / full column highlight selection
- Added Sidebar-based Matrix control panel
- Added Matrix Plot / Sum / ROI operations from Sidebar
- Added Matrix Viewport controls (Row / Column range)
- Added Matrix editing mode toggle
- Added support for opening Edited Matrix in a new window
- Improved Matrix Workspace interaction and scientific analysis workflow

## Version 6.0.0  New Features
Version 6 introduces a major expansion of 2D matrix analysis and scientific processing features in FITS QuickLook X.

- Added the new Matrix Workspace for interactive 2D matrix inspection and editing
- Added Matrix Expression processing for ROI and full-image operations
- Supported functions now include log, log10, sqrt, abs, pow, gamma, and clip
- Added Expression CSV export for processed matrix results
- Added Matrix Heatmap, Surface, and Contour visualization tools
- Improved matrix editing workflow and multi-selection behavior
- Enhanced Matrix Window management and activation behavior
- Added safeguards for large full-image operations to improve stability
- Redesigned the startup experience with the new FITS QuickLook X 6 visual style
- Further refinements across the interface, animations, and scientific workflows

## Version 6.2.6  New Features
- New windows are now brought to the front automatically when opened.
- Added ROI and Full selection modes for Matrix analysis.
- Introduced Markup tools, including arrows, text, rectangles, and circles, with customizable colors.
- Added PNG export for annotations.
- Added Clear and Redo actions for markup editing.
-Improved overall usability and workflow efficiency.

## Version 6.4.0  New Features
- Fixed an issue that could create multiple Matrix windows when opening Matrix views repeatedly.
- Added Matrix Transpose support. Transposed matrices now support the same analysis and processing tools as standard Matrix views.
- Improved ROI workflow and behavior.
- Added dedicated Sum, Single Plot, and Edit tools for ROI mode.
- Various stability improvements and bug fixes.

## Version 7.0.0  New Features
Welcome to Version 7!
New in this release:
- Added a new curve fitting tool. Users can create an empty dataset and manually enter x and y values for analysis.
- Supported fitting models now include:
* Linear fitting
* Gaussian fitting
* 1st–5th order polynomial fitting
- Added export options for fitted plots and fitting parameters.


## Version 7.1.7 New Features

FITS QuickLook X is now officially renamed  FITS QuickLook Studio.
- Added curve width and color controls in the fitting panel
- Added sin, cos, tan, and exponential fitting functions
- Added new plot markers: circle, star, heart, triangle, and square
- Improved the layout of several controls
- Added a new Peak Detection Analysis tool

Thank you for using FITS QuickLook Studio!


## Version 7.2.2 New Features
In this version, the following new features have been added:

- Added support for exporting peak detection results in Range mode.
- Added a new feature for exporting peak detection results.
- Optimized the workflow and overall user interaction logic.

## Version 7.3.0 New Features

A new level of scientific data compatibility.

- Added MAT to FITS conversion for MATLAB numeric matrices.
- Added XLSX to FITS conversion with worksheet selection.
- Supports Float32 and Float64 FITS output.
- Added transpose options during conversion.
- Improved compatibility with compressed MAT files and modern XLSX workbooks.
- Various stability and usability improvements.

## Version 7.3.2 New Features

Minor update with improvements:

- Added new **XLSX** and **MAT** entry cards to the main interface.

- Added a **Convert** tab to the Tools toolbar for easier file conversion access.

- Improved performance when handling large matrices.

## Version 8.0.0 New Features
### A new intelligent FITS experience.

- Added Science Assistant powered by Apple Intelligence, providing intelligent assistance for FITS data analysis, header interpretation, and scientific workflows.
- Redesigned the user interface with a new Cover Flow experience, making it easier to explore FITS tools and workflows.
- Improved the overall user experience across Mac, iPad, and iPhone.
- Apple Intelligence features require supported devices and are currently unavailable in some regions, languages, or configurations.
  e.g.
<div align="center">
  <img src="https://github.com/user-attachments/assets/ba3b6494-3313-4605-b4fe-fedc7080cc9a" width="450" align="top">
  &nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/3e12f4a6-08e6-4907-b515-51d671498733" width="450" align="top">
</div>


## Version 8.1.1 New Features
- Refined the redesigned top navigation with a cleaner full-width tab experience.
- Added a new Favorites tab for faster access to commonly used features.
- Enhanced the visual appearance of the Tools and AI panels with improved transparency effects.
- General interface refinements and stability improvements.


## Version 8.1.4 New Features
- Redesigned the sidebar for a cleaner and more intuitive experience.
- Improved navigation fluidity and overall responsiveness.
- Performance improvements and bug fixes.

## Version 8.1.6 New Features
### This release marks the beginning of our AI enhancement journey.
- Significantly enhanced Apple Intelligence with expanded parameter understanding across the entire application.
- FFT, Plot, Peak Analysis, and Curve Fitting now support comprehensive parameterized workflows.
- Added parameterized control for image visualization, analysis, ROI, annotations, matrix editing, data conversion, and export.
- Matrix expressions now require explicit confirmation before execution, improving safety and reliability.
- Fixed an issue where the on-device language model context could become exhausted before processing a new request.
- Performance improvements and bug fixes.

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
