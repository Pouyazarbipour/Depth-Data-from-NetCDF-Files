# Extract Underwater Depth Data from NetCDF Files

This script processes **NetCDF (.nc)** files to extract longitude, latitude, and elevation data and saves the information about underwater points (where elevation is below sea level) into a plain text file.

## Features
- Reads geospatial data (latitude, longitude, elevation) from a NetCDF file.
- Identifies underwater points (negative elevation).
- Outputs results to a formatted text file (`depth.txt`).

---

## Requirements

### Libraries
The script uses the following Python libraries:
- **`numpy`**: For numerical operations and efficient array handling.
- **`netCDF4`**: For reading NetCDF file data.

---

## License  
This project is licensed under the MIT License. See the `LICENSE` file for details.  

---

## Contact  
For questions or feedback, please reach out to pouyazarbipour@gmail.com.
