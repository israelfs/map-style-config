# Tileserver-gl Style Configuration

This guide will help you add custom styles to the tileserver-gl using South America tiles.

## Prerequisites

- Docker installed on your machine
- A clone of this repository

## Steps

1. **Prepare the Data:**

   - Create a new folder named `data` in the root directory of the cloned repository.
   - Add your tile data to this folder. If possible, name the file `south-america.mbtiles`.

2. **Run the Server:**

   - Navigate to the root directory of the cloned repository.
   - Run the following command to start the server:

   ```bash
   docker run --rm -it -v $(pwd):/data -p 8080:8080 maptiler/tileserver-gl
   ```

3. **Access the Server:**

   - Open your web browser and navigate to the following URL:

   ```bash
   http://localhost:8080
   ```

You should now be able to see your custom styles on the tileserver-gl.
