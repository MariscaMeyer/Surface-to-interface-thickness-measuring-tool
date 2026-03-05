# Surface-to-interface-thickness-measuring-tool
The standalone executable is currently available for review. The full source code is being prepared for public release and will be uploaded to this repository prior to final publication.

Overview
This automated software tool is designed for high-resolution thickness mapping of curved 3D biological structures. It uses a five-stage workflow to establish a stable measurement axis (longitudinal centerline) that follows the natural geometry of a model, ensuring all thickness measurements remain perpendicular to the local anatomical curvature.

Getting Started with the Demo
A sample model is provided to help users familiarize themselves with the tool's functionality.Navigate to the "Demo" folder in the repository.
Load the demo structure into the software interface (ensure your input files are in .obj format).

How to Use the Software Interface
1. Setting Measurement Precision
  Step Size: Use the "Step Size" button to define the longitudinal interval between virtual slices.
  Units: This value is measured in millimeters (mm). For example, entering 0.5 will generate a measurement slice every 0.5 mm along the length of the structure.

2. Visualization & Scene Settings
   The "Scene Settings" menu allows you to toggle the visibility of different components of the 3D workflow:
     Slice Lines: Displays the virtual 2D planes used for local thickness calculation.
     Center Lines: Displays the established longitudinal axis used to maintain perpendicularity.
     Original Models: View the raw input data for the inner and outer surfaces.
     Remeshed Model: View the watertight, interpolated version of the geometry created by the software.

3. Model Transparency
   Opacity Sliders: You can adjust the transparency of the outer and inner models independently using the drag-line sliders. This is particularly useful for   inspecting the internal root canal or endosteal boundaries within the larger structure.
   
4. Exporting Data
   CSV Export: Once measurements are complete, you can export all local thickness values as a .csv file for statistical analysis.

Validation
The tool has been validated using cylindrical and cuboidal computer-generated models, demonstrating measurement precision up to 0.0001 mm on curved surfaces.

Citation
If you use this tool in your research, please cite our paper:
Meyer, M., Potgieter, R., Jonker, C.H., Rajbaran-Singh, S. and Oettle, A.C. (2026). Surface-to-interface thickness measuring tool for curved biological structures. [Journal of Anatomy / Pending]
