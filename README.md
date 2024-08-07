# Decoder for items.dat by Yuhkil

Willing to decode the `items.dat` file yourself (for private servers or reverse engineering purposes)? Check out the release version of my decoder here: [Yuhkil's Items.dat Decoder](https://github.com/GrowHax/Items.dat/releases/download/growtopia/Yuhkil.s_Items_Decoder.exe).

This tool helps decode the `items.dat` file used in Growtopia. It extracts and converts the binary data into a readable JSON format, which can then be analyzed or modified as needed.

## Usage Instructions

1. **Download the Decoder:**
   - Visit the [Release Page](https://github.com/GrowHax/Items.dat/releases/download/growtopia/Yuhkil.s_Items_Decoder.exe) to download the decoder executable.

2. **Prepare `items.dat`:**
   - Ensure that the `items.dat` file is in the same directory as the decoder executable.

3. **Run the Decoder:**
   - Execute the decoder by running `Yuhkil.s_Items_Decoder.exe`. This will process the `items.dat` file and generate a JSON file named `items.json` containing the decoded data.

## Additional Information

The `items.dat` file format has evolved through various versions, with changes in data structure and additional fields being introduced over time. Below is a summary of the modifications made to the data structure for each version:

### `version 11`
- **New Field:** `punch_option`
  - **Description:** A new string field named `punch_option` was introduced.

### `version 12`
- **Data Skipping:** 
  - **Description:** An additional 13 bytes of data are skipped in this version.

### `version 13`
- **Data Skipping:** 
  - **Description:** An additional 4 bytes of data are skipped in this version.

### `version 14`
- **Data Skipping:** 
  - **Description:** An additional 4 bytes of data are skipped in this version.

### `version 15`
- **Data Handling:**
  - **Description:** An additional 25 bytes of data are skipped, followed by reading a new string.

### `version 16`
- **Data Handling:**
  - **Description:** A new string is read in this version.

### `version 17`
- **Data Skipping:**
  - **Description:** An additional 4 bytes of data are skipped in this version.

### `version 18`
- **Data Skipping:**
  - **Description:** An additional 4 bytes of data are skipped in this version.

## Notes

- Ensure that the `items.dat` file version is supported by the decoder.
- If you encounter issues or discrepancies, check the format changes documented above or refer to the decoder’s source code for further insights.

Feel free to reach out for support or contribute to improving the decoder!

