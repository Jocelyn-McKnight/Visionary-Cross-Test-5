<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3D Model Viewer</title>
    <!-- Include 3DHOP's JavaScript -->
    <script type="text/javascript" src="3dhop/3dhop.min.js"></script>
    <style>
        /* Style to ensure 3D viewer takes full page space */
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
        }
        #viewerDiv {
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <!-- Container for the 3D viewer -->
    <div id="viewerDiv"></div>

    <script type="text/javascript">
        // Initialize the 3DHOP viewer
        var viewer = new Viewer("viewerDiv");

        // Load the 3D model (replace with the actual file path of your model)
        viewer.addModel({
            file: 'models/your_model.nxs',  // Nexus format (.nxs) or PLY (.ply)
            mtl: null  // Optionally provide materials (if any)
        });

        // Configure the scene
        viewer.setScene({
            model: "your_model.nxs",  // Replace with the actual model file
            trackball_type: "turntable",  // Turntable navigation mode
            background_color: [1.0, 1.0, 1.0, 1.0]  // White background
        });
    </script>
</body>
</html>
